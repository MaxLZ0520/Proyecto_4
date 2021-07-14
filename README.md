# Proyecto_4

Para este proyecto primero se procedio a realizar un código en el cual se utilizaron funciones las cuales se encontraban en el mismo documento, pero haciendole algunas modificaciones para implementarlo en nuestro modelo 16-QAM, el cual era de 4 bits por lo tanto se van atener datos con combinaciones desde 0000 hasta el 1111. Se modificaron las funciones de modulador y la de demulacion, en la primera se procedio a realizar un for el cual nos ayuda a recorrer N donde se encuentran todos los bits, pero tomando en cuenta el metodo 16QAM, por lo tanto toma en cuenta cada bit y la ubicacion de los mismos en el mapa de la constelacion. Por otra parte en la parte de demodulacion se procede a crear el procucto interno para las dos modulaciones.
Luego de esto se procedio a la definicion de parametros tales como la frecuencia de la portadora, las muestras por periodo de la portadora y relación señal-a-ruido del canal, en esta ultima se observo algo interesante pero a la misma vez logico, ya que al inicio se procedio a simular con una relacion de señal a ruido de 10, pero al obvservar la imagen recuperada se podia ver como distorcionada o como unos huecos en ella, por lo que analizando esto se llego a la conclusionn de que es se debia a este parametro por lo que se aumento considerblemente este numero y se obtuvo la siguiente imagen donde la calidad es mucho mejor:

![image](https://user-images.githubusercontent.com/86036883/125568083-4475f29a-ff34-4804-90f7-f94ede7c1e2f.png)

Para las formas de ondas se obtuvieron las siguientes graficas:

![image](https://user-images.githubusercontent.com/86036883/125568312-577e9e3a-6e4a-4c60-82e9-48daf269b07c.png)

Por ultimo para determinar y graficar la densidad espectral de potencia para la señal modulada se procedio a realizar una 


        
