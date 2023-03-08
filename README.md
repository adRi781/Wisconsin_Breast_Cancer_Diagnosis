# Wisconsin_Breast_Cancer_Diagnosis
Se evaluan modelos que identifiquen si un paciente tiene cáncer de mamá.

En el archivo C2_S4_Pry_A_Breast_cancer_APC.ipynb se encuentran todos los comentarios de lo realizado, sin embargo aqui un resumen.

El archivo original de datos usado es: C2_S4_A_wbcd.csv
La descripción del archivo original es: C2_S4_A_wbcd_names.txt
Los datos para trabajar se graban en el archivo: C2_S4_A_wbcd_data.csv

Los encabezados de los datos se definieron de acuerdo a la información proporcionada en el archivo C2_S4_A_wbcd_names en el punto "7. Attribute information":

- 1) ID - Número ID 
- 2) Dg - Diagnóstico (M = maligno, B = benigno)
- 3-12) Valor de media (-p)
- 13-22) Valor de error estandar (-es)
- 23-32) Valor del peor o valor mas grande (-mx)

Las 10 caracterísitcas reales medidas para cada célula se asigno con el prefijo 'C' como se describe a continuación:
- a) r - radio (media de las distancias del centro a los puntos del perímetro)
- b) tx - textura (desviación estándar de los valores de la escala de grises)
- c) p - perímetro
- d) a - área
- e) sv - suavidad (variación local en longitudes de radio)
- f) cmp - compacidad (perímetro ^ 2 / área - 1.0)
- g) cnc - concavidad (severidad de las porciones cóncavas del contorno)
- h) pcnc - puntos cóncavos (número de porciones cóncavas del contorno)
- i) sm - simetría
- j) dfr - dimensión fractal ("aproximación a la línea de costa" - 1)
