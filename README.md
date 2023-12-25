# Курс по обработке и генерации изображений - домашнее задание 1

  Задача - бинарная сегментация опухолей на МРТ головного мозга https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation

  Цель эксперимента: сравнить две архитектуры (PSPNet и UNet), посмотреть, как быстро и насколько качественно будут достигаться метрики (IOU) по прошествии 50 эпох

## PSPnet:
  
![image](https://github.com/oldrzym/ig/assets/115554194/250284cc-eec9-4566-81cb-eab853e11966)

Итоговые значения метрик: loss: 0.2018 - iou: 0.7950 - val_loss: 0.3904 - val_iou: 0.6108
![image](https://github.com/oldrzym/ig/assets/115554194/a36dc0c9-6788-452d-991e-720789cf9ca7)
![image](https://github.com/oldrzym/ig/assets/115554194/b557a764-e7db-4592-af21-ea6612de2cf0)
![image](https://github.com/oldrzym/ig/assets/115554194/44b913a6-07ca-4755-add1-ecd78d17b83a)
![image](https://github.com/oldrzym/ig/assets/115554194/32a62c74-c4dd-4087-8542-dcb1f5747857)

## Unet:
![image](https://github.com/oldrzym/ig/assets/115554194/5f5a724f-d847-4708-8a88-57b1455da7ec)

loss: 0.1704 - iou: 0.8298 - val_loss: 0.4440 - val_iou: 0.5570

![image](https://github.com/oldrzym/ig/assets/115554194/6a831af1-20e0-4fab-bfb1-a1cc242d0252)
![image](https://github.com/oldrzym/ig/assets/115554194/7e2da1c6-6b0f-4f92-9fe1-a4af3a794640)
![image](https://github.com/oldrzym/ig/assets/115554194/ecf052f0-0066-4355-ba34-885d394d65a8)
![image](https://github.com/oldrzym/ig/assets/115554194/981b8974-0143-498a-b748-c1f90f338206)
