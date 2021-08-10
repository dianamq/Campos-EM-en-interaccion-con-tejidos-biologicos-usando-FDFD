# Campos-EM-en-interaccion-con-tejidos-biologicos-usando-FDFD 

Se cuenta con 3 archivos en este repositorio que describen lo siguiente:

En el primero "Cavidad_aire_FDFD_1D_C.F.Cero" se modela una cavidad con tamaño de 1m 
con solo aire, se usa diferencias finitas en el dominio de la frecuencia para hallar 
los campos EM con una condición de frontera cero. 
Se obtienen los campos eléctricos y magnéticos para un rango de frecuencias deseado.

El rango de frecuencias deseado se importa en el segundo archivo "Estructura_vacío+paredDieléctrica_FDFD_1D".
se modela una estructura con tres secciones, una de dieléctrico en medio de dos de vacío. 
Se acotan las frecuencias para que tengan relación con las importadas.
Se obtienen los campos eléctricos y magnéticos para un rango de frecuencias deseado.
Se evalúa con un dieléctrico con permitividad y permeabilidad iguales para simular una pared
transparente.

El último archivo "Estructura_multicapa" modela al tejido mamario con cáncer, cuenta con 6 secciones:
vacío, piel, tejido adiposo, tejido glandular, tumor y tejido muscular.
Se hallan las permitividades en función de la frecuencia. Se determina un valor de frecuencia a evaluar 
y se escoge un rango alrededor de ese valor para evaluar la interacción de campos EM con el 
tejido mamario afectado con cáncer.

