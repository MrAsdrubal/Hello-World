# ***Into to c***      
## **Mi primer código en C.**
--- 
### ***Pasos a seguir***
---
1. Buscar en el panel : Create c projet.
2. Agregar la carpeta en donde se guardaran los archivos.
3. Verificar los comandos de git( git version, gcc --version, pwd, ls)
4. Crear el directorio del git con git init
5. Ignorar los siguientes archivos:
* Makefile
* todas la extensiones de .json
* Propio .gitignore
6. Pulsar git add . para agregar al seguimiento definitivo.
7. Mandar el git a la rama **Master**, mediante el git commit -m "nombre de la version"
8. Subir a la nube el trabajo, mediante el comando git push.
> **Nota**: tiene que revisar que tenga la cuenta en la nube.
---
## ***Formato del código***.
Código que se muestra en main.c
```c
#include <stdio.h>

void main()
{
	printf("Hello World!\n");

	return (0);
}
```
--- 
### ***Explicaciones**
>  1. En la cabecera de estas lineas de código se encuentra las librerias, el cual son un compilado de comandos que me ayudaran a trabajar con la consola.
```c
#include <stdio.h>
```
---
> 2. En la siguiente parte se especifican las funciones (return) y los procedimientos (void) 
```c
void main ()
```
---
***Por último mandamos a compilar nuestro codigo, en la carpeta ouput que es el ejecutable.***
___

