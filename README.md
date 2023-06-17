# Criptografia

Cifrador de Flujo Rabbit

Se puede correr el código de 2 formas distintas:

### Interfaz Java

Se dispone de un proyecto en Spring Boot con Thymeleaf donde se puede acceder a una interfaz gráfica para encriptar y desencriptar las imagenes.

Se debe modificar el path donde alojar las imagenes en el application.properties y en el archivo de rabbit también modificar donde se van a alojar.
Se debe crear una carpeta al nivel del userName "crypto" con el rabbit.py y con una carpeta "result" donde se van a guardar las imagenes encriptadas o desencriptadas.


### Por línea de comandos

Se debe llamar a al archivo rabbit.py de la siguiente forma:

python3 rabbit.py 
la linea de comandos te solicitara:
	\<path> \<option> \<clave> \<iv>

- \<path>: del archivo a encriptar/desencriptar
- \<option>: cifrado o descifrado (-E o -D)
- \<clave>: con la que va a cifrar el documento
- \<iv>: vector de inicialización (opcional)

En caso de no enviar los argumentos, el programa los solicitará por el shell donde se este llamando al programa.

