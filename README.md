# Validacion de Formularios

***Crearemos a estructura dun pequeno sitio coa axuda de Bootstrap/Sass/Parcel.*** 

***Para instalar ditos paquetes, a través da consola introduciremos os seguintes comandos:***

| ***npm install bootstrap**               |
| ---------------------------------------- |
| ***npm install --save-dev parcel-bundler sass*** |
| ***npm install @popperjs/core***         |

Unha vez creados todos os elementos que temos na árbore da carpeta de arquivos, accedemos na folla de estilos e importamos a biblioteca de bootstrap cos seus respectivos estilos css. Para facer a páxina do formulario un pouco máis estética, introducimos un header e un footer que terán o seu propio código css. 

Cabe destacar que todos os elementos css pódense modificar por parte do usuario ao seu propio gusto personal, de modo que unha vez acabada o estilo estético da páxina introducimos o formulario mediante código HTML. Para a validación do propio formulario, que corresponderia ca parte de JS, o cal fará que se resalten os erros cometidos a hora de encher os campos que foran necesarios cubrir por parte do usuario.

O código js o que vai facer é comprobar que todos os campos se rechean de forma correcta, de tal modo que se non introducimos os elementos da forma en que se nos pide resaltará o erro na pantalla de cor vermello. Así coma se termine de completar todos os campos, púlsase o botón de subscribirse e na seguinte pantalla amósase o información recopilada no formulario.

Unha vez finalizada a validación mediante o código js que se encontran nos arquivos, o último paso e a introducción do formulario na base de datos que teñamos configurada através do método $_POST[nomedoarquivo] . E tamén grazas a codificación con PHP axudámonos para introducir o formulario la base de datos.

Finalmente, para que o formulario recolla ben os estilos que se usan na páxina, temos que engadir un novo paquete de arquivos que introduciremos mediante a consola (no noso caso de Laragón, pero pódese empregar outra) o seguinte comando:

"npm run build"

A cal nos creará unha carpeta chamada "build" no cartafol xeral; asi mesmo, unha vez creada, o seguinte paso e insertar de novo a validación de "login.php"que creamos no cartafol principal (src) e copiala no cartafol "build".  

<img src="https://user-images.githubusercontent.com/89069423/150776346-cbf1ddfe-a220-4220-b704-7ccc3c230936.png"/>

<img src="https://user-images.githubusercontent.com/89069423/150503053-5e0b281f-843d-4018-9db8-0050f43b2a12.png"/>
