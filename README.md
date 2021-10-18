# Administrador_Portafolio

Este código permite la creación, optimización y administración de un portafolio de inversión a través de acciones que se pueden comprar o vender en la Bolsa Mexicana de Valores (BMV).

El código fue desarrollado en el ambiente de programación Google Colab, por lo que implica instalar algunas librerias antes de ejecutar el Administrador de Portafolios. Esta instalación se puede omitir después de la primera ejecución en un ambiente local.

Este código se muestran los resultados de una inversión de 100,000 a 60 días, sin una ventana de tiempo y con ventanas de tiempo de 10 días, 20 días y 30 días.

#Ejecución de Administrador

Para ejecutar el Administrador del Portafolio de requiere seguir los siguientes pasos:
  1. Descargar o Cargar la carpeta **"Codigo"**, el cual se encuentra disponible en este repositorio
  2. Ajustar las rutas de acuerdo a sus ubicación actual, en el Notebook **"Administrador_Inversion"**
  3. Ya actualizadas las rutas, se definen los parametros de fecha para poder ejecutar el código.
  4. Posteriormente, se ejecuta el administrador el cual requiere de los siguientes parámetros:
     a) **mto_invertir: **Monto inicial a invertir, el valor por default es 100,000.00
     b) **mto_invertido:** Monto invertido en el mercado, el valor por default es 0.00
     c) **tam_port:** El número de emisoras que formaran parte de portafolio de inversión, el valor por default es 5
     d) **emisoras:** Lista de las emisora que contizan en un mercado, la lista por default es de 138 emisoras de acciones de la BMV
     e) **fecha_ini:** Fecha inicial de los precios de acciones a considerar para la creación y optimización del portafolio de inversión, el valor por default es 01-Enero-2020
     f) **fecha_fin:** Fecha final de los precios de acciones a considerar para la creación y optimización del portafolio de inversión, el valor por default es 30-Mayo-2021
     g) **tiempo:** Número de días naturales en la que permanece la inversión en el mercado, el valor por default es 10
     h) **ventana:** Valor booleano para considerar una ventana de tiempo en el filtro de las emisoras del portafolio, el valor por default es True - No considera una ventana de tiempo
     i) **tam_vent:** Tamaño de la ventana de tiempo o rendimientos a considerar para el filtro de emisoras, el valor por default es 20
    

#Ejecución de Experimentos

En este notebook, se visualizan algunos experimentos realizados con la optimización de portafolios de inversión a través de simulaciones de Monte Carlo o Teoría de Portafolios. Además de evaluaciones de las redes neuronales para la identificación de un momento alcista o bajista del portafolio de inversión creado.

#Notebook Datos

Este Notebook es un completo para la ejecución del Administrador del Portafolio para la extracción de información y métricas requeridas para la creación de un portafolio de inversión.

#Notebook Portafolio

Este Notebook es un completo para el Administrador del Portafolio para la creación y optimización de un portafolio de inversión, así como la obtención de métricas relacionadas a este instrumento de inversión

#Notebook Trading_ML

Este Notebook es un completo para el Administrador del Portafolio para la toma de decisión de inversión, a través de la identificación de momentos alcistas y bajistas que puede tener el portafolio creado.
