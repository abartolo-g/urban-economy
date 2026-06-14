# urban-economy
#### En este proyecto Se trabajó con dos datasets '/datasets/tomtom_traffic.csv' y /datasets/oecd_city_economy.csv. El objetivo fue analizar la relación entre Movilidad Urbana y la Productividad Económica (PIB Per cápita) con el año 2024 , se analizaron 15 ciudades con un total de 7 paises de Latinoamérica.
#### Para iniciar, se generó un duplicado de la data original en crudo. Después importé las librerias Pandas, Numpy, Seaborn y Matplotlib. y cargué los dos datasets.
#### Una vez cargados los Dataseats se hizó revisión de la estructura con .info() y se determinó  que hacia falta estandarizar los nombres de las columnas para evitar errores y facilitar la union de los datasets, se cambiaron los formatos de dos columnas a datetime y otros a númerico . también se renombraron las columnas a formato snak_case para facilitar la unión .Se filtró un año especifico del Dataset , trabajamos 2024 y se sacaron los promedios.
 
