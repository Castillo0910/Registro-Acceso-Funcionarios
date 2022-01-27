# Registro-Acceso-Funcionarios
Documentación y desarrollo del proyecto registro de acceso de funcionarios

#  Programación
• read.py (realiza la lectura del chip y/o tarjeta y valida con los datos guardados para realizar el registro y envío de correo, si el chip y/o no es válido arroja una alerta. Led verde: correcto y led rojo: incorrecto

•	write.py (se encarga de asignar ID a los chip y/o tarjetas para configuración de registros).

•	mfrc522.py (librería para el funcionamiento de read.py y write.py), no se pueden cambiar valores ya que se puede afectar su correcto funcionamiento.

•	ssd1306.py (librería para el funcionamiento de pantalla oled 128x64)

# Tabla estructura de coenxiones por Pines

![image](https://user-images.githubusercontent.com/98502050/151281183-ea081bc8-647a-4627-9c80-72cca6b3458f.png)


