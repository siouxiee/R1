# Tesis-2
Repositorio de Datos para el proyecto de investigación: Desarrollo de un modelo de predicción de Carcinoma Hepatocelular (HCC) en pacientes peruanos con base a datos de expresión génica

Dentro de la carpeta "data-peru", se encuentran dos subcarpetas ("tumoral-no-tumoral" y "no-tumoral"), los cuales contienen datos de expresión génica obtenidos de la plataforma GEO (Gene Expression Omnibus), y un cuaderno de Jupyter.
Ambas carpetas incluyen archivos de datos de expresión génica en formato “.txt”, obtenidos a partir de microarrays de Affymetrix. 
Las muestras fueron recolectadas de pacientes peruanos con hepatocarcinoma celular (HCC) y tejidos no tumorales. A continuación, se detalla el contenido:

•	Archivos .gz: Archivos comprimidos que contienen metadatos detallados sobre las muestras, incluyendo información experimental, plataformas utilizadas, y detalles sobre los pacientes y las condiciones de recolección de muestras.

•	Archivos .txt: Cada archivo representa datos de expresión génica para una muestra específica de tejido (tumoral o no tumoral). Estos archivos contienen:
    o	ID_REF: Identificadores de referencia de los genes, típicamente asociados con un número de acceso o anotación genómica.
    o	VALUE: Valores de expresión génica log2-transformados que reflejan la cantidad relativa de ARNm presente en la muestra.

Estos archivos permiten realizar análisis comparativos entre diferentes tipos de tejidos (tumorales y no tumorales) en pacientes peruanos, ayudando a identificar patrones específicos de expresión génica asociados con el HCC.

•	Carpeta "tumoral-no-tumoral": Contiene datos de expresión génica extraídos de la plataforma GEO (GSE136247), que incluye 69 muestras emparejadas de tejidos tumorales (HCC) y no tumorales (NTL) que evalúa 1042 genes. Estas muestras provienen de pacientes tratados mediante resección anatómica del hígado, con tejidos hepáticos no tumorales obtenidos de los márgenes libres de tumor de las piezas quirúrgicas resecadas.

•	Carpeta "no-tumoral": Incluye datos de expresión génica de 9 muestras de tejido no tumoral (NTL) de pacientes peruanos con hepatocarcinoma (GSE111580). Estas muestras fueron seleccionadas según la presencia o ausencia de focos de células claras en el parénquima hepático no tumoral.

•	Cuaderno de Jupyter "load_data_GSE136247.ipynb”: El cuaderno de Jupyter proporciona un script para cargar los datos de expresión génica utilizando la biblioteca GEOparse de Python, permitiendo al usuario descargar los datos.
