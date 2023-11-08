
##  Correo Masivo con Python
Para enviar correos masivos utilizando un script de Python, primero necesitas configurar las credenciales de API gratuitas en formato JSON en https://console.cloud.google.com/. Estas credenciales te permitirán acceder a tus archivos en Google Drive y Google Sheets.

Luego, sigue estos pasos:


1) Crea un correo electrónico en tu cuenta de Google.
2) Ve a "Manage your Google Account" y selecciona "Seguridad".
3) Habilita la "verificación en dos pasos" (2-Step Verification).en este paso algunos se pierden cuidado sigue el 4 y 5 muy cuidadosamente 
4) una vez activado regresa y dale click a verificacion de dos pasos te pedira el pasword de nuevo y te dirigira a una pagina en esa ve hasta abajo y encontrar la ultima opcion que es app pasword.
5)  genera una "contraseña de aplicación" (app password). Esta contraseña se utilizará en lugar de tu contraseña principal para permitir el acceso remoto a través de un script en Python.
6) Asigna un nombre a tu aplicación (por ejemplo, "script_python") y se generará una contraseña similar a esto: "cquemcdywkdumaik".( si te da espacios una vez en el script remueve espacios)
   
Luego, en tu script de Python:

Utiliza estas dos contraseñas que generaste:

La primera contraseña te permitirá acceder a tu base de datos, como hojas de cálculo en Google Sheets, que contendrán las direcciones de correo electrónico.
La segunda contraseña te permitirá iniciar sesión en tu correo electrónico y enviar correos.
Asegúrate de eliminar los espacios en la contraseña antes de usarla en tu script.

Con estos dos pasos resueltos, tendrás los códigos de acceso necesarios para acceder a tu base de datos de correos electrónicos y enviar correos masivos desde Python. Ahora puedes copiar, pegar y seguir las instrucciones de tu notebook para enviar correos masivos de manera eficiente.
