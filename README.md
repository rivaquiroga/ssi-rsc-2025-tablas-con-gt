# Creación de tablas publicables y reproducibles con {gt} y Quarto
Materiales del workshop sobre creación de tablas con {gt} para el [Research Software Camp 2025](https://www.software.ac.uk/training/research-software-camps) organizado por el [Software Sustainability Institute (SSI)](https://www.software.ac.uk). El taller estará a cargo de [Riva Quiroga](https://rivaquiroga.cl/), fellow del SSI.

## Acerca del taller

Las tablas son un componente central en la comunicación de resultados de investigación. Es por ello que resulta clave que su diseño garantice una comunicación precisa, favorezca la reproducibilidad y se ajuste a estándares de publicación. 

En este taller, introduciremos la "gramática de tablas" usando el paquete {gt} de R. A partir de actividades prácticas, aprenderemos a configurar las distintas secciones de una tabla, a ajustar el estilo en que se muestran los datos y a incorporarlas en documentos reproducibles creados con Quarto. Al finalizar el taller, sus participantes habrán aprendido estrategias para mejorar la calidad de sus tablas e incorporarlas en flujos de trabajo reproducibles.

Requerimientos

- Una versión de R >= 4.4

- Una versión de Quarto >= 1.7.33

- Versiones recientes de los siguientes paquetes: gt, tidyverse y ggsci.

## Sobre el contenido de este repositorio

A lo largo del taller trabajaremos en el archivo ´reporte.qmd´. Los datos que utilizaremos se encuentran en un archivo ´.csv´ dentro de la carpeta ´/datos´. Yo crearé una copia del documento a la que llamaré ´reporte_final.qmd´ en la que quedarán guardados los cambios que vaya haciendo al documento a lo largo de la sesión. De ese modo, al finalizar el taller quedará disponible el archivo tal como empezamos a utilizarlo y la versión con las tablas que creamos. 

## Sobre los datos

Todos los datos utilizados en el taller fueron obtenidos del portal [Gapminder](https://www.software.ac.uk).