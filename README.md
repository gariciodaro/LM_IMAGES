# AMT. Creacion de etiquetas para Machine learning.
Estebitan, Tomasiño. Deberan seguir el siguiente tutorial para ayudarme con los peces nuevamente. En esta ocasión, utilizaremos un software, que deben instalar. Por favor, sigan el siguiente tutorial al pie de la letra.

## Instalacion de git en windows.

Primero deben instalar **git** en sus pcs. Para eso vayan [aqui](https://gitforwindows.org/) y lo descargan y lo instalan. Luego en el buscandor de windowns escriben 'git', y luego entran a "Git bash" y escriben cada comando uno por uno. Para ejecutar el comando solo deben presionar enter.

+ `cd Desktop`
+ `mkdir fotos_peces`
+ `cd fotos_peces`
+ `git clone https://github.com/gariciodaro/LM_IMAGES.git`

<img src="http://garisplace.com//help_col/im11.png" />
======
<img src="http://garisplace.com/help_col/im12.png" />

+ si todo esta bien, en el escritorio de sus pcs deberian tener una carpeta llamada fotos_peces, adentro tienen dos carpetas con sus nombres, estas son las fotos que cada uno va trabajar.

## Instalacion de Anaconda.

Anaconda en un paquete de herramientas construidas alrededor de **python**. **Python** es un lenguaje de programacion muy poderoso que permite contruir algoritmos de machine learning([ver](http://garisplace.com/ch_2.html)
), construir paginas web ([ver](http://garisplace.com/betting)), construir aplicaciones([ver](https://github.com/gariciodaro/AMT)), y todo lo que se les ocurra, aprendan esto seran imparables como yo. Pasos para instalar anaconda:

+ entren aqui: [https://www.anaconda.com/distribution/#download-section](https://www.anaconda.com/distribution/#download-section), descarguen(click download) e luego instalen(next a todo).

<img src="http://garisplace.com/help_col/im1.png" />

+ Una vez tengan anaconda, escriban anaconda en el buscador y entren a la terminal:

<img src="http://garisplace.com/help_col/im2.png" />

+ Escriban en la terminal (uno por uno):
+ `conda create -n image_annotation python=3.7`
+ `conda activate image_annotation`
+ `pip install labelImg`

<img src="http://garisplace.com/help_col/im3.png" />

+ Cuando termine la instalacion cierren todo. y abran nuevamente una terminal de anaconda (escriban en buscador de windows "anaconda" y entren al anaconda power shell, ya esto lo habian hecho). Una vez ahi, escriban los siguientes comandos uno por uno.

+ `cd .\Desktop\fotos_peces\`
+ `conda activate image_annotation`
+ `labelImg`

<img src="http://garisplace.com/help_col/im5.png" />

Luego del ultimo comando deberia abrise el sofware que van a usar. Le dan "Open Dir" y seleccionan su nombre (esteban o tomas):

<img src="http://garisplace.com/help_col/im13.png" />

+ Una vez en el software, le van a dar "Create \nRectBox", esto les abre la herramienta de creacion de rectangulos, van a crear 5, con los siguientes nombres **boca**, **ojo**, **cola**, **aleta** y **cuerpo**.

<img src="http://garisplace.com/help_col/im7.png" />

+ Luego le dan guardar, y pasan a la siguiente foto. Cuando se cierren y para volver a iniciar, de nuevo hacen en la terminal:

+ `cd .\Desktop\fotos_peces\`
+ `conda activate image_annotation`
+ `labelImg`