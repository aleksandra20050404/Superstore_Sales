# Superstore Sales 

## Оглавление 
- [Обзор Проекта](#обзор-проекта)

### Обзор Проекта 
Этот проект по анализу данных направлен на предоставление информации о производительности супермаркета. Анализируя различные аспекты данных о продажах, мы стремимся выявить тенденции, дать рекомендации, основанные на данных, и получить более глубокое понимание эффективности работы компании.
### Используемые Инструменты
- Numpy
- Pandas
- Matplotlib
- Seaborn
### Файлы
- **superstore_sales.ipynb**:
- **Data_Visuaization.csv:**
- **README.md:** Этот файл предоставляет обзор репозитория и инструкции по использованию и доступ к Jupyter Notebook.
- **train.csv:** Путь к фалу (/dataset/train.csv)

### Источник Данных
Данные получены с Kaggle (извлечение в формате Excel), подробнее можно ознакомиться [здесь](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)

### Автор
[Aleksandra Vislova](www.linkedin.com/in/sasha-undefined-a51ba9297)

### Этап 1: Загрузка данных и необходимых библиотек 
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
```python
#сохранение файла train_csv в переменную df
 df = pd.read_csv("train.csv")
 df.head()
```



