CONTROL DE VERSIONES

1. ¿Qué es un control de versiones?
    Se le dice control de versiones a la gestión de los diversos cambios que se realizan sobre los archivos de un proyecto de software. Una versión, revisión o edición de un software, es el estado en el que se encuentra el mismo en un momento dado de su desarrollo o modificación.
    Aunque el control de versiones puede realizarse de forma manual, es recomendable utilizar herramientas que faciliten esta gestión dando lugar a los llamados sistemas de control de versiones. Estos sistemas facilitan la administración de las distintas versiones de cada software desarrollado en algun momento en el tiempo.

2. ¿Cuáles son los problemas al no usar un control de versiones?
    Los problemas que veo son:
    - Aparición de conflictos que deban ser solucionados manualmente o posibles inconsistencias que surjan al modificar el mismo archivo por varias personas.
    - Dificulta el trabajo remoto y seguimiento y no saber que cambios se han hecho 
    - No es posible saber quien hizo el cambio de un archivo
    - Probabilidad de sobre escritura de archivos
   
3. ¿Cuáles son los beneficios?
    - Tener un historial de cambios en el sistema sin llenarte de multiples archivos
    - Crear Ramas permite trabajar en simultano a diversos programadores (avance en paralelo de proyectos)
    - Seguimiento y trazabilidad (saber cuando y que cambios se han realizado en el software)

4. ¿Qué tipos de control de versiones existen?
    - Sistemas de control de versiones centralizados.
        Un sistema de control de versiones centralizado utiliza un servidor central para almacenar todos los archivos y permite el trabajo colaborativo de un equipo. Trabaja sobre un repositorio único al que los usuarios pueden acceder desde un servidor central.
    - Sistemas de control de versiones distribuidos.
        Los sistemas de control de versiones distribuidos no dependen necesariamente de un servidor central para almacenar las versiones de los ficheros del proyecto.
        En los SCVD cada programador tiene una copia local o clon del repositorio principal. Esto quiere decir que cada programador mantiene un repositorio local propio que contiene todos los archivos y metadata presente en el repositorio principal. Todos pueden operar con su repositorio local sin ninguna interferencia.

