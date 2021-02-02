# primerproyecto

Primer proyecto GitHub utilizando tecnología React.




Cómo son las aplicaciones?

Las aplicaciones necesitan muchas cosas para que una persona las use como herramienta en su mano, un celu, una pc, por ej.
- Código es lo mismo que decir parte de programa.
- Compilado es cuando se interpreta y empaqueta ese código (no todos los lenguajes necesitan ser compilados)



## Infraestructura:
Las computadoras que corren los programas intervinientes en una aplicación

  Servidor
    para una aplicación puntual, es comun ver que corra la parte del código que llamado backend
  
  
  Clientes (PCs de muchas personas que entran a una web)
    corre programa como el gchrome, el browser, por ejemplo



Se comunican con protocolo HTTP
(
 -https://es.wikipedia.org/wiki/Protocolo_de_transferencia_de_hipertexto

Acá tenés un HyperTexo, el grande,
el genio de los hypertextos
el texto HTML!
 -https://es.wikipedia.org/wiki/HTML
)




Formas de comunicarse con HTTP, las PC de los clientes y la PC del servidor.
el boca vs river es: SOAP vs REST
Nosotros usaremos el más nuevo, el recomendado, REST

https://www.idento.es/blog/desarrollo-web/que-es-una-api-rest/
 


Verbos:

GET:
  (ejemplo, un uso común de este verbo es un llamado a una pagina web,
  es un llamado tipo GET,
  que se hace desde un browser)
POST,
PUT,
DELETE


Aplicacion tiene Sub-aplicaciones

backend
  -Recibe mensajes de una PC en un cliente.
  -maneja la base de datos
  -responde con texto HTML cuando le piden una **vista**
  
frontend
  -programa de las **vistas**
    interfaces de usuario
    hechas en código HTML
    

Para fabricar un backend, se usan muuuuuuuuuchos lenguajes.
Se matan.
una de las peleas que se escuchan es esta:
(compilado vs script)

Lenguajes de backend
 -java (lenguaje compilado, muy frecuente) (NO es javascript, es otra cosa)
 -pyton
 -node.js (se programa en lenguaje javascript)
 -Visual.NET (el de microsoft, es solo para windows, solo hecho con windows)

Lenguajes de frontend
  -HTML, css, javascript


  viene con 2 socios,
  Los browsers, tiene un motor,
  que reconoce HTML,
  con javascript dentro de **tags**, **html** lo entienden,
  lo ejecutan mientras lo leen

  <script>
    var mivariableloca = 16
    var doble_de_mi_variableloca = mivariableloca * 2
  </script>
  
  
  
Flujo de llamado (solo un ejemplo de consumo de un servicio de pagina web)


browser en **cliente** hace un llamado HTTP, del verbo GET
backend en **servidor** lo recibe y devuelve un HTML
HTML se interpreta en browser
Se visualizan elementos HTML con estilo escrito en CSS y funcionalidades programadas en scripts de javascript


https://quimeytabuyo.github.io/primerproyecto/PaginaPrueba.html






Ver estado:
    1  git status

Ver diferencias:
    2  git diff
   
Formas de ver archivo en linux( consola git bash o linux)
Scroll, entero, cabeza, cola

    3 less README.md
    4  cat README.md
    5  head README.md
    6  tail README.md
	
Agregar todos los cambios al paquete:
    8  git add --all

Se cierra paquete con mensaje:
   11  git commit -m "Paquete de cambios numero 3"
  
Configuraciones necesesarias para clonar por primera vez:
   12  git config --global user.email "quimeytabuyo@gmail.com"
   13  git config --global user.name "Quimey Tabuyo"
   
Subir todos los paquetes a la nube:
   15  git push origin master
   
 El linux o git bash pone la historia de comandos:  
   16  history

 
