# TP6-Temperatura-de-superficie
- Universidad de Costa Rica 
- GF-0618 FOTOGRAMETRÍA Y TELEDETECCIÓN
- MSc.María José Molina Montero
- Estudiantes: Steven Guillén-Ana López
## Objetivo

Utilizar el set de datos de MODIS LST(Land Surface Temperature).
Realizar análisis temporales de periodos largos y periodos cortos para entender la variabilidad de los datos.


## Introducción  

### **Transmitancia y radiancia**

La transmitancia es parte de la irradiancia que transmite la superficie receptora.
> La transmitancia se refiere al movimiento de energía a través de una superficie; es la relación entre la radiación reflejada, transmitida y  absorbida (Weng, 2012). 

La Radiancia es el flujo radiante que abandona un cuerpo, esta guarda relación con la temperatura y emisividad, y a partir de esta se puede inferir la temperatura de una superficie
Con base en la ley de Stefan-Boltzmann se puede calcular la radiancia de un material multplicando la emisividad espectral del material y la temperatura radiante.


### **Cuerpos negros y su relación con la emisividad** 
(dar ejemplos de emisividad de diferentes superficies)

> Un cuerpo negro es un radiador hipotético e ideal que absorbe y reemite totalmente toda la energía que incide sobre él (Weng, 2012).

Mientras que la emisividad es el coeficiente que describe la eficiencia con la que un objeto irradia energía en comparación con un cuerpo negro, y la cantidad de energía radiante emitida por este cuerpo negro depende de la temperatura y longitud de onda. La ley de Planck describe el resplandor espectral de la radiación electromagnética en todas las longitudes de onda emitidas por un cuerpo negro a una temperatura absoluta. específica.

![](https://www.flukeprocessinstruments.com/sites/default/files/emissivity.png)

>Todos los materiales reales tienen un valor de e entre 0 y 1, que es espectralmente dependiente, es decir, cambia con la longitud de onda. Además, el contenido de agua, la composición química, la estructura y la rugosidad también influyen en la emisividad de las características del suelo (Snyder, Wan, Zhang y Feng, 1998).

Como la relación entre emisividad y reflectancia es igual a 1, un buen reflector es un mal emisor. Por ejemplo, los metales son buenos reflectores, por lo tanto su emisividad es mucho menor, que la del asfalto ya que este no refleja nada y mas bien absorbe y emite energía entre 0.94 y 0.97.



### **Aplicaciones de la teledetección térmica: ** 
Desarrolle 3 apps (ilustre cada una de las aplicaciones y mencione los sensores que se pueden utilizar en cada una de dichas aplicaciones)

- Identificación de los materiales de la superficie de la Tierra (como tipos y estructuras de suelos, minerales y rocas).
- Estimar la humedad del suelo y la evapotranspiración de la vegetación.
- Estudiar el balance energético de la superficie terrestre, la cobertura del suelo y el efecto isla de calor urbano.

## Metodología: Datos utilizados, explicación del sensor MODIS LST para medir temperatura diurna y nocturna. 


- Modifique el código para incorporar las Imagenes de MODIS para la noche.

- Realice una serie temporal para larga que inice a partir del 2000 hasta 2016. Explique la variabilidad de la información.

- Luego haga una serie temporal de un año, que va de enero 2015 a diciembre del 2015.

- Realice gráficos para cada una de las series. Analícelos
- Analice el mapa para el periodo temporal de 16 años y el de un año

## Caso de estudio 

El Instituto de Acueductos y Alcantarillados quiere evaluar la duración y el momento de la sequía severa más reciente en Costa Rica, específicamente zona Chorotega, a fin de prepararse mejor para futuras sequías. 
-	La sequía más severa fue en los años 2014-2015
-	Realice series temporales de términos cortos (3-6 meses)
-	Analice las máximas de temperaturas y contrastes de estacionalidad climática.

A finales del siglo XX e inicios del XXI, se registraron sequías severas en la región Chorotega. Cuales fueres las temperaturas registradas entre enero a mayo del año 2000 en esa región.


##### Resultados: Análisis de mapas y gráficos








Weng, Qihao. 2012. “Percepción térmica remota”. Cap. 9 en Introducción a la teledetección contemporánea . 1ª ed. Nueva York: McGraw-Hill Education. https://www-accessengineeringlibrary-com.ezproxy.sibdi.ucr.ac.cr/content/book/9780071740111/chapter/chapter9
