# Proyecto4
Proyecto 4 del curso Modelos Probabilísticos de Señales y Sistemas 

## Solución

Para la parte 4.1 se modificaron las funciones de modulación de demodulación para que funcionaran con QPSK. En el modulador la señal se separó en la señal I y Q, una con seno y otra con coseno. Luego los bits se acomodaron en una matriz que los emparejaba. Luego a cada par de bits se le aplicaba la modulación I o Q y se agregaban a la señal respectiva. Finalmente la señal modulada I y la Q se sumaban para obtener la señal transmitida. 
En la demodulación se tenía la señal con ruido y al multiplicar sus partes por seno o coseno se obtuvo un producto I y uno Q. Luego se calculaba la pseudo-energía y se demodulaba cada bit. Finalmente se combinaron todos los bits mediante la función dstack. Con un SNR de 5 se obtuvieron 0 errores. 

Para la parte 4.2 
se obtuvo que era estacionario en el sentido amplio. 

En la parte 4.3 se calculó el cuadrado del valor absoulto de la transformada de Fourier de la señal evaluado en todo el tiempo de la señal. Se obtuvo un pico en 5000 ya que esta es la frecuencia de las portadoras. 

