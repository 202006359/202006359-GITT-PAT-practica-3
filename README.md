# 202006359-GITT-PAT-practica-3
En esta practica se empleará los conocimientos adquirido en el aula sobre HTML, CSS y Javascript, creará un documento web que permita interaccionar con una API REST y visualice en el documento la información.

En la seccion create QR de la navegacion, accederemos a la nueva página creada. Esta página está hecha usando la tecnología de Bootstrap y de **API REST, de forma asíncrona**. He elegido la API "goqr" (https://goqr.me/api/doc/), a la cual llamo mediante un método 'GET' para crear los codigos QR. Para ello, lo que debemos hacer es meter en el input una pagina web, i.e github.com, y darle al boton generate. Si lo hemos hecho correctamente, nos aparecerá el codigo QR de la pagina web introducida.
<img width="731" alt="image" src="https://user-images.githubusercontent.com/113789409/225073550-5fc1a8d7-7c47-47e1-a7f1-2124e98a638c.png">

Si por el contrario NO metemos una pagina web valida, por ejemplo escribimos hola (en vez de https://www.hola.com/), lo que nos hace la API es mostrarnos los resultados de poner hola en el buscador de google.
<img width="683" alt="image" src="https://user-images.githubusercontent.com/113789409/225073844-10ec3bfc-6c31-4e83-8272-75e4126316de.png">

