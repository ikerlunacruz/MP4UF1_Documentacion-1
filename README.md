# MP4UF1_Documentacion
## Índice
1. Github
   
   1.1. Instalación de git
   
   1.2. Darse de alta en Github
   
   1.3. Instalación de Visual Studio Code
   
   1.4. Como crear los repositorios en Github
   
   1.5. Como clonar los repositorios para editar en local
2. Markdown
   
   2.1. Sintaxis Markdown
3. HTML
4. CSS
5. Diseño Responsive
--------------------------------------------------------
1. GITHUB
   
   1.1 Instalación de git
      * Descargar el instalador de GIT para Windows
      * Una vez que hayas descargado el instalador, haz doble clic sobre el ejecutable para que           comience el proceso de instalación y sigue las instrucciones que te aparecerán en pantalla.       Al igual que cualquier otro programa, tendrás que dar “Next” (siguiente) en varias               ocasiones hasta que aparezca la opción “Finish” (terminar) para completar la instalación.
      * Ahora tienes que abrir el cmd y escribir los siguientes comandos en la terminal de tu SO:
    ``` 
    git config --global user.name "nombre de usuario"
    git config --global user.mail "ejemplo@gmail.com"
    ```
   1.2. Darse de alta en Github
      1. Ir a [Github.com](https://github.com/join)
      2. Escriba un nombre de usuario, una dirección de correo electrónico y una contraseña
      3. Ir a __Sign up for Github__ y seguir las instrucciones.
   
   1.3. Instalación de Visual Studio Code
      1. Ir a la página Microsoft [Visual Studio Code](https://code.visualstudio.com/) y haz clic          en el botón de descargar.
      2. Abrir el archivo de instalación en nuestra carpeta de descargas para iniciar la                  instalación
      3. Cuando nos aparece la primera pantalla del instalador, tenemos que aceptar el acuerdo de licencia y le damos todo a __Next__ hasta que nos aparezca la última            pantalla que nos saldrá __Finish__ y ya podremos utilizar nuestro programa.

   1.4. Como crear los repositorios en Github
   ![image](https://user-images.githubusercontent.com/90915730/193757398-0ca53db6-2763-405f-b097-bcd2658c9ef5.png)
   
   
   Para crear un nuevo repositorio en Github, tienes que irte a mis repositorios y clicar en la zona marcada que pone New.
   
   
   
   ![image](https://user-images.githubusercontent.com/90915730/193758482-beaf0afc-0754-4438-83ad-d085aa362631.png)
   
   Una vez le das a New, te sale esta ventana donde en las zonas remarcadas son las zonas "más importantes" por así decirlo. La primera es como se va a llamar tu          repositorio y como lo van a ver las personas que lo visitarán. El siguiente punto es decidir si va a ser privado o público, es decir, si quieres todo el mundo o si    es privado, solo la gente que tu decidas que lo pueda ver. El siguiente punto es decidir si va a tener un fichero README.md, eso quiere decir que es un documento      como si fuese de texto pero tiene diferentes funciones que en el siguiente punto os explico. Por último, es el botón para crear el repositorio.

   1.5. Como clonar los repositorios en local
   
   ![image](https://user-images.githubusercontent.com/90915730/193762405-d4ac4112-1057-4b5a-9249-4b1f664a3480.png)
   
   Para que Github nos de el código, tenemos que seguir los pasos como indica la imagen. 
   
   Una vez tenemos el código copiado en el portapapeles, tenemos que irnos a Visual Studio Code para ejecutar el comando que nos lo clona en local. Pero antes de          clonarlo, tenemos que seleccionar en donde queremos guardar el trabajo en local, es decir, en que carpeta queremos que se guarde. Para ello, tenemos que irnos a la    barra de arriba y seleccionar Archivo --> Abrir carpeta y seleccionas la carpeta donde quieres que se guarde. Por último, abrimos un terminal en el propio Visual y    ejecutamos lo siguiente:
   
   ```git clone con el enlace que hemos copiado anteriormente en el Github```
   
2. Markdown
     
     2.1. Sintaxis Markdown
      - Las ```#``` son uno de los métodos utilizados en Markdown para crear encabezados. El más grande es poniendo una almohadilla y el más pequeño es                         poniendo 6 almohadillas.
      - Las citas se generan utilizando el carácter ```>``` la comienzo del bloque o texto.
      - Para crear las listas desordenadas se utilizan tres tipos de símbolos: 
          * Asteriscos 
          * Guiones
          * Símbolo de suma
      - Para crear las listas ordenadas, debemos utilizar la sintaxis de tipo: <<número.>> ```1.```. Al igual que con las desordenadas, podremos combinarlas.
      - Para crear un bloque entero que contenga código, lo único que tenemos que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ```~```                   virgulillas.
      - Para poder hacer la palabra o la frase que quieras en cursiva, hay dos formas de hacerlo:
          * Con asterisco simple tanto a principio como a final de palabra o frase
          * *cursiva*
          * Con guión bajo tanto a principio como a final de palabra o frase
          * _cursiva_
      - Para poder hacer la palabra o el texto en negrita puedes hacerlo de dos formas:
          * Con doble astérisco tanto a principio como a final de palabra o el texto
          * **negrita**
          * Con doble guión bajo tanto a principio como a final de palabra o texto
          * __negrita__
      - Para enlazar a una página web tienes que escribir la palabra o texto enlazado entre ```[]``` corchetes y el link entre ```()``` paréntesis.
      - Para insertar una imagen con Markdown, tienes que añadir una exclamación al principio y el enlace de la propia imagen, tanto si es en local como si has copiado         la URL de Google.
          * ```![Texto alternativo](rutaalaimagen)```

3. HTML

