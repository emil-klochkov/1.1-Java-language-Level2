# 1.1-Java-language-Level2

## Phone.java (Clase base)

Define un teléfono con los atributos brand y model.

Tiene un constructor para inicializar estos atributos.

Contiene el método call(String number), que imprime un mensaje indicando que se está llamando a un número.

## Camera.java (Interfaz)

Define la funcionalidad de tomar fotos.

Contiene el método takePhoto(), que imprime: "Taking a photo".

## Clock.java (Interfaz)

Define la funcionalidad de una alarma.

Contiene el método alarm(), que imprime: "The alarm is ringing".

## Smartphone.java (Hereda de Phone e implementa Camera y Clock)

Extiende Phone e implementa las interfaces Camera y Clock.

Sobrescribe takePhoto() para imprimir: "Taking a photo".

Sobrescribe alarm() para imprimir: "The alarm is ringing".

Main.java (Punto de entrada del programa)

Crea un objeto Smartphone con marca y modelo.

Llama a los métodos call(), takePhoto() y alarm(), mostrando los mensajes correspondientes.
