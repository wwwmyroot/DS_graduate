------

## Курс “Data Science 2022 4.0”.
**Слушатель: Куринной А.В.**
------

## Прогнозирование конечных свойств композиционных материалов

Выпускная квалификационная работа на тему «Прогнозирование конечных свойств композиционных материалов».

### Цель работы:
- изучение способов прогнозирования конечных свойств новых композиционных материалов и разработка моделей для выполнения прогнозов.

### Для достижения поставленной цели осуществлено решение ряда задач:
   - разработка алгоритма машинного обучения для прогноза значений модуля упругости при растяжении и прочности при растяжении;
   - создание нейронной сеть для рекомендации соотношения «матрица-наполнитель»;
   - разработка приложения для прогнозирования соотношения «матрица–наполнитель».


#### Для выполнения исследования использованы производственные данные Центра НТИ «Цифровое материаловедение: новые материалы и вещества» (структурное подразделение МГТУ им. Н.Э. Баумана). 
#### Информация представлена в виде двух файлов формата excel: X_bp.xlsx (характеристики базальтопластика) и X_nup.xlsx (характеристики нашивки из углепластика). 

## В процессе работы:

### Применены следующие модели:
1.	Метод К-ближайших соседей;
2.	Метод опорных векторов;
3.	Линейная регрессия;
4.	Дерево решений;
5.	AdaBoost;
6.	Градиентный бустинг;
7.	XGBoost;
8.	Случайный лес;
9.	Стохастический градиентный спуск;
10.	Метод регрессии «Lasso».

### Разработа нейронная сеть с использованием класса Sequential.

### Создано два варианта приложения:
- веб-приложение в фреймворке Flask;
- консольное приложение;

------

## Содержание репозитория:

 - .
 - ├── application
 - │   ├── app_fin_KurinnoyAV.ipynb
 - │   ├── minmax_scl_x.pkl
 - │   ├── minmax_scl_y.pkl
 - │   └── model_matrix
 - │       ├── fingerprint.pb
 - │       ├── keras_metadata.pb
 - │       ├── saved_model.pb
 - │       └── variables
 - │           ├── variables.data-00000-of-00001
 - │           └── variables.index
 - ├── dataset
 - │   ├── in_1col_x_bp.csv
 - │   ├── in_1col_x_nup.csv
 - │   ├── in_x_bp.csv
 - │   ├── in_x_bp.xlsx
 - │   ├── in_x_bp.zip
 - │   ├── in_x_nup.csv
 - │   ├── in_x_nup.xlsx
 - │   ├── in_x_nup.zip
 - │   └── X_full.xlsx
 - ├── MainCode_KurinnoyAV.ipynb
 - ├── maincode_kurinnoyav.py
 - ├── README.md
 - ├── Пояснительная_записка_КуриннойАВ.docx
 - ├── Пояснительная_записка_КуриннойАВ.pdf
 - ├── Презентация_КуриннойАВ.pdf
 - └── Презентация_КуриннойАВ.pptx

5 directories, 24 files

------
## Direct links.

### Основной репозиторий (ноутбук, приложения, пояснительная записка, презентация):
- Github: https://github.com/wwwmyroot/DS_graduate

### GoogleDocs (резерв-1 и прямые ссылки):

- GoogleCollab: https://colab.research.google.com/drive/1Zpm8JWJS9ExsMitfmnS-qjBXK1FC2nOX?usp=sharing
- Презентация: https://docs.google.com/presentation/d/1L_qtTnn5YHcUQQVB0D5ZE7_qVNtMnLmv-LbV8LQp7IM/edit?usp=sharing
- Пояснительная записка: https://docs.google.com/document/d/1tiq-vYmhQi4v4T9AOYW4pAkXb-dZQzEG/edit?usp=sharing&ouid=115919505493649108196&rtpof=true&sd=true

### Резерв-2 (архив .zip):
- GoogleDrive: https://drive.google.com/file/d/1MbPIdTj5FGW2wc5W_oAmeV0Mdtwo2i6l/view?usp=sharing 
 
------
