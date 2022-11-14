# w4 - ETL Project
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/ETL_process.jpeg)


### PROJECT REQUIREMENTS
Extract, transform and load data.
Must extract data from 3 different sources using 2 different tools(Downloading a .csv,API, web scrapping...)


### PROJECT TOPIC
WORLD CUP QATAR 2022
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/qatar_big_data.jpeg)


### WORK PROCESS

#### 1. EXTRACCIÓN
- Extracción de Ranking Top 100 FIFA mediante scraping (Selenium) de la FIFA, incluyendo las banderas de cada país - link
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/web_FIFA_1.png)
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/web_FIFA_2.png)

- Extracción de ficheros .csv de Kaggle, con la información de los grupos y el calendario
- Extracción de datos clima de API Ambee.
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/API%20website.png)

- Extracción del nuevo modelo de datos por partido que habrá en el mundial (fuente personal).



#### 2. EXPLORACIÓN Y LIMPIEZA
- Importación en pandas de los datos extraidos
- Limpieza de los dfs.
- Exportación a csv para su posterior carga en SQL para creación de Db.
- Pendiente terminar de explorar el modelo de datos que habrá en cada partido.
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/grupos.png)
![Image text](https://github.com/Davidteje/-w4-ETL-Project/blob/main/img/FIFA_ranking_pandas.png)

#### 3 CARGA EN SQL - DATA BASE
- Importación de tablas a SQL.
- Pendiente crear relaciones en función del desarrollo del proyecto final.












