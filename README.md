# Practica_Dos
Autor: Verónica Ruíz Galván 
En este repositorio se contiene a la practica dos correspondiente a la clase de Programacion de microcontroladores
en la cual, el LED 13 (para la placa F401RCT6) debe realizar una secuencia de parpadeo a diferente duracion.
Para implementarlo en otra placa, sólo se debe revisar la documentacion de su placa respecto a la línea:
"HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_13);" 
lo cual es lo único que se deberá cambiar así como la salida para su led en el archivo .ioc
