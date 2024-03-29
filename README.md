#Prueba FrontEnd

La siguiente es una prueba para evaluar conocimientos de HTML, CSS y JavaScript.   

Se busca que cumpla con los requerimientos especificados dentro del tiempo límite para esta prueba que es de 3 horas.  

Se evaluará habilidad en HTML y CSS, además aspectos de organización de código, buenas prácticas, priorización y creatividad para resolver los requerimientos.  

**Es necesario contar con una cuenta en GitHub para realizar este ejercicio.**


##Ejercicio

1. Clonar este repositorio.

1. **Maquetación:** Deberás traducir el diseño ubicado en [`assets/Design PSD/`](assets/Design PSD/) a HTML+CSS.  
Si es necesario puede descargar el PSD que esta en la carpeta [`assets/Design PSD/`](assets/Design PSD/)  
**Requerimientos:** Traducir diseño a HTML+CSS. Para simplificar el ejercicio el layout no cuenta con footer ni header. Deberás usar técnicas CSS3 cuando lo requiera.  Además debe realizar el sitio responsive. No se entregan diseños para resoluciones menores a Desktop por lo que la creatividad es a elección. **Se recomienda fuertemente** realizar al menos la maquetación para mobile.
 
1. **JavaScript:** Se deben realizar las siguiente tareas:
	*  **Validaciones**
		*  Valor del auto: requerido, deben ser números
		*  Monto del pie:   requerido
		*  Cifra válida Plazo del crédito: requerido 
		*  Marca del auto: requerido
		*  Año auto: requerido
		*  Cuando planea comprar el vehículo: requerido
	* Enviar los datos al siguiente REST endpoint: `http://postero.meteor.com/foo`. En el archivo [`assets/javascript/application.js`](assets/javascript/application.js) encontrará otros tips. 
Hacer submit de los datos mediante AJAX.

1. **SEO Friendly:** ComparaOnline busca siempre tener una buena posición en ránkings de búsqueda. Crear etiquetas necesarias para un buen **SEO** (hint: use las keywords: crédito automotriz, comparador crédito automotriz).  
¿Crees que se requieran cambios en la maqueta? ¿Cuáles?
En la caje que contiene el formulario encontré un tag h1; lo cambié por h3. El h1 es tiene mayor importancia para los motores búsqueda. Por lo tanto, suelo ocupar h1 en títulos importantes de noticias por ejemplo.
Además, eliminé una buena cantidad de divs.
**Opcional:** agregar share buttons y etiquetas para redes sociales (hint: [http://ogp.me](http://ogp.me)).

1. **Advanced CSS:** Puede usar frameworks a elección para escribir CSS teniendo en cuenta la compatibilidad con distintos browsers (hint opcional: Usar [BrowserStack](http://www.browserstack.com/) para chequear el renderizado en distintos navegadores).  
Opcional: ¿cuál sería tu enfoque en la construcción del diseño?
Mi enfoque principal sería en el trabajo con grillas.

1. **Para finalizar la tarea se requiere hacer un Pull Request al mismo repositorio con las tareas realizadas. Se recomienda al menos hacer un commit por tarea.**
