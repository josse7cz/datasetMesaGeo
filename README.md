# datasetMesaGeo
This dataset is downloaded and generated by https://cartographyvectors.com/map/1432-czech-republic-with-regions
Use in mesa-geo tutorial. 
You should change "NAME" to "name" in code
Mesa-geo rozšiřuje aplikaci MESA o možnosti využití geografického informačního systému GIS. Přidáním funkcionalit GeoSpace lze generovat prostředí na základě mapových podkladů. Mapování prostředí modelu je tak možné například na základě dat uložených ve formátu Gson. Tato data lze získat např. na URL: https://cartographyvectors.com/map/1432-czech-republic-with-regions. GIS používá rasterové a vektorové data a Mesageo pomocí balíčku Geopandas poskytuje možnost pracovat s těmito daty za běhu. Funkcionality, které nesouvisí s prácí s geografickými objekty a daty jsou děděny právě z MESA a jsou vhodným způsobem rozšířeny. Jedná se například o GeoAgents a Cell. Dále jsou použity třídy Data Collector, Scheduler, Model. Agent MESA je rozšířen o atribut geometrie, získal vlastnost Shapely a crs pro referenční systém CRS. Tyto agenty rozšířené o atributy lze použít stejně jako objekty třídy Agent a předat je následně plánovači pro modelování pohybu.
![image](https://user-images.githubusercontent.com/24356264/215283421-b03fd506-efef-4123-9f3c-48a0cd2cc93a.png)
Mesageo dále poskytuje možnost uložení dat běhu modelu pro další použití. V Mesa-Geo lze exportovat data jako pole NumPy, anebo GeoDataFrames. Tato data lze převést jako rasterové anebo vektorové soubory. Tato exportovaná data lze iterpretovat zpět do GIS. ![image](https://user-images.githubusercontent.com/24356264/215283871-1e4b4fad-cc60-4d25-8bb0-904510f2a8d8.png)
 
