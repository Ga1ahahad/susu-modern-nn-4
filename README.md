# Лабораторная работа 4

Датасет: Smoker Detection [Image] classification Dataset. Бинарная классификация есть на изображении курильщик или нет. Картинки 250x250 цветные.  
Ссылка: https://www.kaggle.com/datasets/sujaykapadnis/smoking

Структура преобразования:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/ea87dd54-509f-4a4f-8a18-b831e86035a5)  

Обучение на неаугментированных данных давало метрики:  
  Precision: 0.46  
  Recall: 0.21  
  Accuracy: 0.22  

Архитектура 1:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/c6baa03b-6f5a-4792-90f1-94590ed61871)  


После обучения на аугментированном датасете на тестовом получены следующие метрики:  
  Precision: 0.53  
  Recall: 0.77  
  Accuracy: 0.70  

Архитектура 2:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/01b4c023-ebbe-4979-9f72-1f0d5bd903f9)  


После обучения на аугментированном датасете на тестовом получены следующие метрики:  
  Precision: 0.50  
  Recall: 0.76  
  Accuracy: 0.76  



Очевидно увеличение эффективности модели.  

Матрицы ошибок:  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/af949a9a-1ab6-4458-b86d-d91b3d3d2941)  
![image](https://github.com/Ga1ahahad/susu-modern-nn-4/assets/90559631/880215e2-4ec9-49ae-945f-c216714d8b3a)  



