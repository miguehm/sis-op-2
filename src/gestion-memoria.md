# Gestión de memoria

# Ideas Previas

## Multiprogramación

Ejecución **concurrente** de múltiples procesos en una sola CPU

> **Ejecución Concurrente**
> 
> Se refiere a la propiedad de un sistema que permite que múltiples procesos se ejecuten a la vez. No significa que los procesos se estén ejecutando exactamente al mismo tiempo. En un solo procesador, la concurrencia se logra cuando el procesador cambia de un proceso a otro tan rápido que parece que todos los procesos se están ejecutando simultáneamente.

Es **la capacidad de un sistema operativo para tener varios programas o procesos en la memoria al mismo tiempo y permitir que la CPU cambie entre ellos**. En un sistema de multiprogramación, cuando un proceso se bloquea o espera la entrada/salida, la CPU puede cambiar a otro proceso que esté listo para ejecutarse, lo que aumenta la utilización de la CPU.

## Multiprocesamiento

Ejecución **simultánea** de procesos en múltiples CPUs.

> **Ejecución Simultanea**
> 
> Se refiere a la ejecución de múltiples procesos **exactamente** al mismo tiempo. Esto se logra a través de un sistema con múltiples procesadores o núcleos, donde cada proceso puede ser asignado a un procesador o núcleo diferente.

El multiprocesamiento se refiere a la capacidad de una computadora de **aprovechar la potencia de múltiples unidades de procesamiento para diferentes partes de un programa al mismo tiempo**.

El sistema operativo se encarga de gestionar la asignación de las diferentes tareas a ser realizadas por los diversos procesadores en el sistema.

## Multiusuario

El término multiusuario se refiere a la característica de ciertos sistemas operativos o programas que permiten **proveer servicio y procesamiento a múltiples usuarios** simultáneamente. Esto significa que varios usuarios pueden utilizar el mismo equipo al mismo tiempo, gracias a la capacidad de los sistemas operativos para separar los recursos del sistema.

<!-- #Duda [x] cual es la diferencia entre multiprocesamiento y multiprogramación -->

<!-- #Duda [x] entoces? la multiprogramación no significa que varios programas se ejecuten simultáneamente en la CPU. En cambio, lo que sucede es que la CPU cambia rápidamente entre los programas, ejecutando una parte de cada uno de ellos a la vez. R: SI-->
