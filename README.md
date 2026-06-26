# MARK 38(mini sumo)

## DESCRIPCIÓN
El proyecto es un robot mini sumo diseñado por nosotros, con un tamaño y peso correspondiente a las [reglas de la LNR (Liga Nacional de Robótica)](https://sistema.lnr-argentina.com.ar/reglamentos/Sumo). este tiene la capacidad de detectar al contrincante para ir y atacar al otro mini sumo con el que este compitiendo para dejarlo fuera del dojo.


## ADMINISTRADORES DEL PROYECTO
1. **Thiago Lopez.** Diseño 3D y montaje de componentes en placa.
2. **Enzo Zapata.** Diseño de PCB, esquemático y montaje de componentes en placa. 
3. **Sebastián Pérez.** Programación, diseño esquemático y PCB y montaje de componentes en placa. 


## OBJETIVO
Nuestra meta con este proyecto es poder participar en la [LNR(Liga Nacional de Robótica)](https://lnr-argentina.com.ar/) y quedar en un puesto alto a la hora de terminar la competencia.Además, queremos lograr también la programación de mini sumo RC para poder competir entre amigos. 


## ESPECIFICACIONES TÉCNICAS
#### Tamaño del mini sumo: 10cm x 10cm x 8cm
#### Alimentación de operación: 11.1v 450mAh
#### Material empleado en la carrocería: PLA
#### Tipos de sensores empleados: Infrarrojo
#### Fuerza de torque:30Nm (Newton metros)


## COMPONENTES
### - SENSORES DE OBSTÁCULOS
#### [VL53L0X](https://components101.com/sensors/vl53l0x-lidar-distance-sensor) *(x5)*
### - SENSORES DE PISO
#### [QRE1113](https://www.alldatasheet.es/datasheet-pdf/view/54347/FAIRCHILD/QRE1113.html) *(x2)*
### - MOTORES
#### [MICROMOTORES N30 500rpm](https://www.aslongdcmotor.com/photo/aslongdcmotor/document/26865/JGA12-N30.pdf) *(x2)*
### - MICROCONTROLADOR 
#### [ESP32 C3 super mini](www.google.com/search?q=esp32+c3+super+mini&oq=esp32+c3+super+mini&gs_lcrp=EgZjaHJvbWUyBggAEEUYOdIBCDg1NzBqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8) *(x1)* 
### - DRIVER DE MOTOR (puente H)
#### [TA6586](https://www.alldatasheet.com/datasheet-pdf/pdf/1761575/RZ-MIC/TA6586.html) *(x2)*
### - BATERIA
#### [Tattu 3S 450mAh 11.1V 75C XT30](https://www.hobbymotors.com.ar/store/index.php?route=product/product&product_id=1127) *(x1)*
> (estos componentes son a grandes rasgos y no se han colocado todos los componentes, en el archivo "lista de componentes se encontrarán todos los materiales utilizados durante la produccion").

## DISEÑO DE LA PLACA

<div align="center">
<img width="1000" height="700" alt="PCB Mini-sumo" src="https://github.com/sebatttyan-lgtm/Mini-sumo-2026/blob/master/docs/MINISUMO-PCB.jpeg?raw=true"/>

## DISEÑO ESQUEMÁMITCO

<div align="center">
<img width="647" height="1082" alt="esquematico Mini-sumo" src="https://github.com/sebatttyan-lgtm/Mini-sumo-2026/blob/master/docs/MINISUMO-SCH.jpeg?raw=true"/>

