# Integrantes del equipo

> Adrián Landaverde Nava
> 
> Jesús Reyes Rojas
> 
> Naomi Padilla Mora
> 
> Sabrina Nicole Rodriguez Salgado

## Base de datos
- _diabetes.csv_
- 15 columnas x 390 filas
  - _colesterol_: nivel de colesterol en el paciente (mg/dL).
  - _glucosa_: nivel de glucosa en el paciente (mg/dL).
  - _hdl_chol_: nivel de colesterol HDL en el paciente (mg/dL).
  - _prop_col_hdl_: 
  - _edad_: edad del paciente (19 a 92).
  - _genero_: género del paciente (female/ male)
  - _altura_: estatura del paciente (pulgadas) **unidades**
  - _peso_: peso corporal del paciente (lb) **unidades**
  - _IMC_: Índice de Masa Corporal del paciente.
  - _ps_sistolica_: presión arterial sistólica en el paciente (mmHg).
  - _ps_diastolica_: presión arterial diastólica en el paciente (mmHg).
  - _cintura_: medida de la cintura del paciente (**unidades**).
  - _caderas_: medida de la cadera del paciente (**unidades**).
  - _prop_cin_cad_: proporción de cintura cadera del paciente (**unidades**).
  - _diabetes_: el paciente está o no diagnosticado con diabetes (No_diabetes/ Diabetes).

## Estadística Descriptiva
![](/images/describe.png)

### Gráfico de Correlación

<iframe src="https://correlacion.netlify.app/" height="500" width="500" align="left"></iframe> 

<br>
<p>El equipo eligió el discurso nombrado “The danger of a single story” o, traducido al español, “El peligro de la historia única” por Chimamanda Ngozi Adichie.</p>


### Matriz de dispersión

<iframe src="https://matriz-dispersion1.netlify.app/" height="600" width="900"></iframe>

## Boxplots

<iframe src="https://boxplot-colesterol.netlify.app" height="500" width="800"></iframe>

<iframe src="https://boxplot-glucosa.netlify.app" height="500" width="800"></iframe>

<iframe src="https://boxplot-edad.netlify.app" height="500" width="800"></iframe>

<iframe src="https://boxplot-cintura-cadera.netlify.app" height="500" width="800"></iframe>

## Clustering por variables

### Corporales

<iframe src="https://matriz-km-corporal.netlify.app" height="500" width="900"></iframe>

<iframe src="https://sunburst-corporal.netlify.app" height="500" width="500"></iframe>

### Sanguineas

<iframe src="https://matriz-km-sanguineas.netlify.app" height="500" width="900"></iframe>

<iframe src="https://sunburst-sanguineo.netlify.app" height="500" width="500"></iframe>

## Análisis de Componentes Principales

<iframe src="https://varianza-pca.netlify.app" height="500" width="900"></iframe>

<iframe src="https://varianza-acumulada-pca.netlify.app" height="500" width="900"></iframe>

<iframe src="https://matriz-dispersion-pca.netlify.app/" height="500" width="900"></iframe>

## Matriz de confusión del modelo

<iframe src="https://matriz-confusion-pca.netlify.app/" height="500" width="500"></iframe>

## Valores SHAP

![](/images/shapcolumnas.png)

![](/images/shapviolin.png)

![](/images/shapejemplo.png)

