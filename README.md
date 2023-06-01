
Materia: Desarrollo de Sistemas web FrontEnd – IFTS 18 
---

Ejercicio nro 3 
Tema: Uso de FlexBox y Media queries. 
Enunciado: 

Se debe desarrollar una mini Landing Page haciendo uso de FlexBox y Media queries.  
La presentación web de la página debe incluir una imagen svg, un encabezado h2, dos párrafos y un link  a en forma de botón. 
Se debe usar FlexBox y Media queries para poder obtener un layout diferente según el medio sea un  mobile, tablet o desktop. 

La carpeta solución del ejercicio debe contener los siguientes archivos: 

-   Un archivo index.html ubicado en la raíz de la solución. 
-   Una subcarpeta llamada “img” que contenga el archivo svg con la imagen de la ilustración. 
-   Una subcarpeta llamada “css” que contenga el archivo “style.css” con la hoja de estilos en cascada  de la página. 

Se deben usar los elementos HTML y estilos CSS que se listan a continuación: 
-   Un color de fondo gradient (según se indica al pie) para toda la página, con un alto de 100vh y un alto  mínimo de 650px. 
-   Un div contenedor general para todos los elementos html con un ancho del 90% y un ancho máximo  de 1200px, un alto de 100%, un display flex, un flex-direction columna y un justify-content center. 
-   Un div contenedor para la imagen con un ancho del 90%, un ancho máximo de 400px y un margen  inferior de 40px. 
-   Una imagen svg (según se indica al pie) con un ancho del 100% y un display block. 
-   Un div contenedor para los elementos de tipo texto de color blanco. 
-   Un párrafo con el texto “#FrontEndDeveloper”. 
-   Un encabezado h2 con el texto “Hola! Bienvenido a Desarrollo de Sistemas Web FrontEnd”, de tamaño  de fuente 2rem. 
-   Un párrafo con el texto “Aprende desarrollo web con HTML5, CSS y JavaScript.”, con alto de línea de  1.5 y margen superior de 0.5em y margen derecho de 0. 
-   Un link a con el texto “Aprende Ahora”, con color de fondo blanco, sin decoración de texto, color de  texto “#667EEA”, un padding superior de 1em y derecho de 2em, un display inline-block, un border radius de 10px y un font-weight de 500. 

Además, se debe incluir una regla @media para que cuando el ancho mínimo de la página sea de 768px se modifiquen los siguientes selectores y propiedades: 
-   El div contenedor general debe tomar el valor row para flex-direction, el valor center para la alineación  de los ítems y el valor space-between para la propiedad justify-content. 
-   El div contenedor para la imagen debe tomar un ancho del 45% y un margen inferior de 0. 
-   El div contenedor para los elementos de tipo texto debe ajustarse a un ancho del 50%. 
-   El encabezado h2 debe ajustar su tamaño de fuente a 2.5rem. 
-   El elemento de párrafo debe tomar un margen superior de 0.7em, derecho de 0 e inferior de 1em.

La renderización de la Landing Page debería verse de la siguiente forma: 
 Versión Mobile Versión Tablet/Desktop 

 Aspectos generales a tener en cuenta: 
-   El código HTML DEBE VALIDAR según el validador de la W3C:  
    * https://validator.w3.org/#validate_by_input 
-   El código CSS DEBE VALIDAR según el validador de la W3C: 
    * https://jigsaw.w3.org/css validator/#validate_by_input 
-   NO está permitido agregar contenido css con el atributo style dentro del html. 
-   La imagen a utilizar en la página debe ser descargada de la web: https://undraw.co/. Buscar “web developer” o “web development” y descargar la imagen SVG. 
-   El color de fondo a utilizar lo pueden obtener de la web: https://webgradients.com/. Buscar y seleccionar el color gradient “028 Plum Plate” y copiar el CSS para usarlo en una clase de  la hoja de estilo con la propiedad “background-image”. 
-   La familia de la fuente debe ser “Poppins”, que la debe descargar de la web  https://fonts.google.com/. 
Seleccionar los tamaños de fuente 300, 400, 500 y 700. Copiar el link generado y usarlo en el tag  “head” de su archivo html, copiar también el font-family para usarlo en su archivo css.  
-   Webs de referencia acerca de CSS Gradients: 
    *    https://www.w3schools.com/css/css3_gradients.asp 
    *   https://developer.mozilla.org/en-US/docs/Web/CSS/gradient 
-   Webs de referencia acerca de CSS Google Fonts: 
    *   https://www.w3schools.com/css/css_font_google.asp 
    *   https://fonts.google.com/knowledge/using_type/using_web_fonts
