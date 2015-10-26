# Eviews6

### Para importar un archivo excel, debemos primero convertirlo a una version que el programa sea capaz de leer, como version 97-2003. Pasos posteriores a seguir:
*File->Open->Foreign data as a Workfile

## Para hallar el Coeficiente de Correlación de Pearson (por ej):
Una vez que ya he importado la bbdd, selecciono dos columnas dentro del fichero que se llama "workfile". Pulso boton derecho y "abrir como grupo". Despues en View, puedo encontrar las diferentes alternativas que busco, como por ejemplo, "Covariance Analysis", alli dentro, selecciono "correlation" y "prob/t/..." para ver si dicho contraste rechaza la hipotesis nula o no. (Segun el pvalor, y el nivel de confianza que deseemos abarcar)

## Para calcular regresiones: 
Abrimos las variables que queramos en grupo. Proc->Make equation. Para solucionar el problema de heterocedasticidad, debemos seleccionar en la pestaña siguiente "white". Para asi poder obtener la regresion sin este problema.

## Series temporales:
######Test de raices unitarias: view, Unit Root test 
######ARMA/ARIMA: View -> Correlograma. 
######Correlograma de residuos: View -> Residual test
