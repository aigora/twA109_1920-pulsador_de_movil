Como no teníamos el material suficiente para hacer el proyecto del pulsador de móvil debido a las condiciones actuales, hemos cambiado a otro proyecto:
## Controlador de Motor DC
Controlar la velocidad del motor DC mediante un sensor de ultrasonido
### Integrantes del equipo
- Fabiana Ricci , _FricciB_
- Gema Sánchez, _gema-upm_
### Descripcicón del trabajo
El objetivo de este trabajo es poder controlar la velocidad de un motor DC mediante un sensor ultrasonido. 
En otras palabras, si el ultrasonido detecta algún objeto, Arduino reducirá la velocidad del motor, llegando a pararse en caso de acercarse mucho.
### Obejetivos del trabajo
- Encontrar un algoritmo capaz de contorlar la velocidad del motor mediante el sensor de ultrasonido.
- Programar el sensor de ultrasonido para que aminore la velocidad del motor a partir de una determinada distancia.
### Hardware
- PC, Arduino UNO, Sonsor de ultrasonidos, Puente H, Motor DC.
### Software
- Desarrollo en C/C++. Programación del microcontrolador a través del IDE de Arduino.
### Funciones
1. El ultrasonido capta por ondas que se acerca un objeto
2. Arduino procesa ese acercamiento
3. Arduino reduce la velocidad del motor conforme el objeto se acerque al sensor
4. Ardino para completamente el motor cuando no haya distancia entre el objeto y el sensor

En caso de que el objeto se aleje, el proceso es el contrario: el motor aumenta de velocidad.
