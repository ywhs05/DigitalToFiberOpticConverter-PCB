# DigitalToFiberOpticConverter-PCB

### Descripción
Proyecto del laboratorio LabCES de la Universidad de Costa Rica.

<!-- Este circuito tiene como objetivo recibir las señales digitales enviadas por medio de un microcontrolador para luego convertirlas en fibra óptica para que pueda ser leída por los puentes H [PEH2015 de Imperix](DaFO-PCB/Datasheets/PEH2015-PuenteH.pdf) en su entrada de fibra óptica. -->

Este circuito tiene como objetivo recibir una señal PWM digital enviada por medio de un microcontrolador, para luego ser convertida en una señal de fibra óptica para poder ser leída por los puentes H [PEH2015 de Imperix](DaFO-PCB/Datasheets/PEH2015-PuenteH.pdf) en su entrada de fibra óptica.

![PCB](DAFO-PCB/Imagenes/PCB.png)


Ahora bien, la placa cuenta con la posiblidad de agregar o no, tiempo muerto a la señal PWM por seguridad de los transistores del puente H. Dicho tiempo muerto es ajustable mediante un trimmer. Por otra parte, es posible negar la señal PWM o no.

En adición, se puede agregar una placa igual por encima de otra para aprovechar la señal PWM recibida del microcontrolador y se cuentan 3 huecos para colocar los pilares de nylon para su soporte.

Finalmente, se muestran las vistas superior e inferior de la PCB.
![PCB_3D_sup](DAFO-PCB/Imagenes/PCB_3D_sup.png)

![PCB_3D_inf](DAFO-PCB/Imagenes/PCB_3D_inf.png)

### Soporte
- y.huang@ucr.ac.cr
- mauricio.espinoza_bola@ucr.ac.cr

### Estado del proyecto

Se encuentra en etapas finales de revisión para su fabricación (activo).