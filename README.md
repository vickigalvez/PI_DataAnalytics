# PROYECTO INDIVIDUAL Nº2: Data Analitycs

# INTRODUCCIÓN
Los accidentes aéreos representan eventos críticos que involucran aeronaves y pueden tener un impacto significativo tanto en la seguridad como en la industria de la aviación.

Este proyecto tiene como objetivo principal analizar y comprender los datos relacionados con estos incidentes, con el fin de mejorar la seguridad de la aviación y prevenir futuros accidentes. La OACI cuenta con un conjunto de datos inicial sobre accidentes de aviones.

En este contexto, este repositorio presenta un análisis detallado de los accidentes aéreos, junto con un completo panel de visualización de datos que complementa los análisis con gráficos y representaciones visuales. A través de este proyecto, se busca proporcionar una visión más clara y consistente de los factores que contribuyen a los accidentes aéreos y, en última instancia, contribuir a la mejora de la seguridad y la prevención de futuras tragedias en la industria de la aviación.

Aquí encontrarás los recursos y resultados de este proyecto de análisis de accidentes aéreos, que tiene como objetivo brindar una comprensión más profunda de estos eventos críticos y sus implicaciones. ¡Bienvenido a esta investigación y análisis en pro de la seguridad de la aviación!

# EDA: Analísis Exploratorio de los Datos

En primer lugar se realizó la carga del dataset, se analizaron los datos y campos del mismo para una mejor comprensión y relación de los datos. 

Los analísis realizados fueron:

1. Limpieza y procesamiento de los datos:
   
   . Eliminar columnas que no aportaban al analísis.
   
   . Remplazar valores por nulos.
   
   . Eliminación de duplicados y valores faltantes.
   
   . Transformación y ajuste de los tipos de datos según sea necesario.
   
   . Normalización de columnas como fecha, hora declarada, entre otras.
    
   . Creación de nuevas columnas necesarias.
   
   . Visualización y manejo de outliers.
   
2. Análisis estadístico y visualización de los datos:
   
   . Creación de nube de palabras paraa dectectar principales causas de accidentes.
   
   . Creación de gráficos y visualizaciones para identificar patrones y relaciones entre las variables.
   
   . Identificación de países con mas accidentes.
   
   . Identificación de aerolíneas y tipos de avion con mayor cantidad de fallecidos y de sobrevivientes


# Dashboard
Para finalizar con el proyecto, se creó un dashboard interactivo en PowerBI para presentar el proyecto. El mismo se encuentra en este mismo repositorio y se puede descargar y utilizar.
Cuenta con 1 portada y 4 páginas navegables.

![image](https://github.com/vickigalvez/PI_DataAnalytics/assets/106280956/1511c539-caa0-4c84-b6a5-1615b4617461)

# Accidentaldiad
  . Filtrando por año, por mes, por país, por tipo de aeronave y tipo de avión.
  
  . La cantidad total de accidentes.
  
  . Un mapa y una tabla con los paises con mayores accidentes en los últimos años. 
  
  . Un gráfico de evolución de accidentes a lo largo de los años.
  
  . Un gráfico con el porcentaje de accidentes de tipo militar o civil.

![image](https://github.com/vickigalvez/PI_DataAnalytics/assets/106280956/b625b8d7-7588-4d46-bf3c-603ba68a0374)

# Mortalidad

  . Filtramos por año.
  
  . Observamos medidores de tasa de mortalidad y tasa de supervivencia.
  
  . Cantidad de fallecidos y de sobrevivimientes.
  
  . Un gráfico de líneas en el que podemos comparar a lo largo de los años la evolucion de fallecidos y sobrevivientes en cada accidente.
  
  . Un gráfico de barras donde observamos el top 10 de aerolíneas con mayor cantidad de accidentes diferenciando con color de más claro a más oscuro según la cantidad.

![image](https://github.com/vickigalvez/PI_DataAnalytics/assets/106280956/531bb3d2-07ea-4b10-bf77-bb9bed7fef96)

# KPI's

Utilizamos dos páginas para anilazar los KPI. 

En la primer página se evaluaron 2 objetivos:

1. Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior.
   
2. Evaluar la disminución de un 10% la tasa de fatalidad de los pasajeros en los últimos 10 años, comparado a la década anterior.
   
  . Se calculo la tasa de mortalidad respecto a la década anterior y se hizo un kpi medible donde muestra los valores en verde si hubo una reducción del 10% de la tasa de mortalidad respecto a la década anterior y en rojo si no la hubo. 

![image](https://github.com/vickigalvez/PI_DataAnalytics/assets/106280956/b6d2445f-42fc-4b94-ae8c-7aa2add629fa)

En la segunda se evalua el 3 KPI:

1. Evaluar el aumento del 10% de la tasa de supervivencia respecto al año anterior.
   
  . Se mutran las cantidades de personas a bordo, de accidetes, de fallecidos y de sobrevivientes.
  
   . Se muestra un gráfico de lineas con la evolución de la tasa de supervivencia a lo largo de los años y un gráfico de barras con los 10 operadores con mayor cantidad de sobrevivientes.
   
   . Se muestra el porcentaje de la tasa de supervivencia comparado con la tasa de mortalidad.
   
   . Se mide el kpi respecto al año anterior mostrando en verde si hubo un aumento del 10% o más de la tasa de supervivencia y en rojo si no lo hubo.

![image](https://github.com/vickigalvez/PI_DataAnalytics/assets/106280956/06133fb5-53bd-45da-b9cf-9ca2c69c3b33)

# Conclusiones

Luego de analizar los datos proporcionados por la Organización de Aviación Civil Internacional (OACI) podemos concluir que: 

  . Ha habido una gran disminución de la tasa de mortalidad de la tripulación en las distintas décadas, en cuanto a los pasajeros la disminución en su mayoría no llega al 10% respecto a décadas anteriores.
  
  . Se debería prestar atención a los vuelos de Estados Unidos, ya que es el país con mas accidentes aéreos.
  
  . Aeroflot es el operador/aerolínea con más sobrevivientes, pero también el que tiene más accidentes registrados.




   
