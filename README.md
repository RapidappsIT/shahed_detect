# Shahed detect - Yolov5 model

Модель shahed_detect для библиотеки [yolov5](https://github.com/ultralytics/yolov5)

> Read this in other language: [English](README.en.md), [Русский](README.md), [Український](README.ua.md)

# Требования
* python3
* yolov5
* [labelImg](https://github.com/heartexlabs/labelImg) 

# Установка
```shell
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip3 install -r requirements.txt
```

# Обучение
```shell
python3 yolov5/train.py --img 640 --batch -1 --epochs 300 --data ../data/data.yaml --weights yolov5s.pt --cache disk
```

# Пример
```shell
python3 yolov5/detect.py --weights models/shahed_detect.py --source ../doc/raw_1.mp4
```

# Примеры обнаружения
![example_1](https://github.com/RapidappsIT/shahed_detect/blob/master/doc/example_1.jpg?raw=true)
![example_2](https://github.com/RapidappsIT/shahed_detect/blob/master/doc/example_2.jpg?raw=true)
![example_3](https://github.com/RapidappsIT/shahed_detect/blob/master/doc/example_1.gif?raw=true)