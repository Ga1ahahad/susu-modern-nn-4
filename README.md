# Лабораторная работа 4

Датасет: Smoker Detection [Image] classification Dataset. Бинарная классификация есть на изображении курильщик или нет. Картинки 250x250 цветные.  
Ссылка: https://www.kaggle.com/datasets/sujaykapadnis/smoking

Структура преобразования:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/ea87dd54-509f-4a4f-8a18-b831e86035a5)  


После обучения на аугментированном датасете на тестовом получены следующие метрики:  
  Precision: 0.52
  Recall: 0.80
  Accuracy: 0.75

Обучение на неаугментированных данных давало метрики:  
  Precision: 0.46  
  Recall: 0.21  
  Accuracy: 0.22  

Очевидно увеличение эффективности модели.  

Матрица ошибок:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/d6be20dc-7eb7-40c1-b714-87e3dc17529d)

