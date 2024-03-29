# Neurowood & Higher School of Economics Computer Vision Hackathon
Классификация изображений на 3 класса в рамках [NeurowoodHack хакатона](https://www.kaggle.com/competitions/woodhack-hackathon)
## Задача

Необходимо классифицировать сортность каждого бревна по его спилу. Дано 578 изображений высокого качества. Решение данной задачи с высокой точностью позволит лесопромышленным и строительным компаниям достоверно определять себестоимость произведенной продукции и оптимизировать свои расходы.

Метки:
- «1» - первый и второй сорта
- «3» - третий сорт
- «0» - класс дрова

## Решение

Использована нейросеть [ResNet50](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html) из библиотеки [PyTorch](https://pytorch.org)

В качестве предобработки использовалась аугментация изображений из библиотеки [albumentations](https://albumentations.ai), т.е. увеличение кол-ва данных за счет поворотов и т.д.

## Качество

Точность предсказаний итоговой модели: 96.5%
