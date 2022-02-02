# UD5-Accesibilidad

**1.** Tu compañero de desarrollo web tienen dudas sobre cuál es la combinación de color más accesible entre las siguientes opciones:

- Color de texto: #1F1FFF y color de fondo: #A3A3A3.
- Color de texto: #000047 y color de fondo: #B8B8B8.

¿Cómo les ayudarías a seleccionar la mejor opción? [[1]](#item1)

**2.** Los subtítulos ponen nuestro contenido a disposición de una audiencia mayor, en la que se incluyen personas con problemas auditivos, o bien personas que hablan un idioma distinto al del vídeo. ¿Cómo incluirías subtítulos en un vídeo? ¿se puede hacer directamente desde YouTube? [[2]](#item2)

**3.** Visualiza tu portal web como lo vería una persona que tuviera las imágenes y el código JavaScript deshabilitado. Existen múltiples formas de hacerlo, pero la más sencilla de todas es utilizar las opciones que vienen incluidas en el propio navegador de Chrome: botón de los tres puntos / Configuración/ Privacidad/ Configuración del sitio web/ deshabilitar imágenes y JavaScript. ¿Qué tal la experiencia?

**4.** La etiqueta de idioma, en HTML, beneficia a todos los usuarios:
- Facilita la lectura de los lectores de pantalla y síntesis de voz baille.
- Los motores de búsqueda identifican los contenidos del idioma deseado.
- Se utiliza para cambiar la voz en la pronunciación de un texto en otro idioma, etc.

a. ¿Cómo indicarías el idioma de una web?
```
<html>
```
b. ¿Y el idioma de una palabra concreta, un enlace, una etiqueta de cita o el de una etiqueta blockquote?
```
<p>Un extracto de <cite>Brave New World</cite></p>
<blockquote>Words can be like X-rays, if you use them properly—they’ll go through anything. You read and you’re pierced.</bloquote>
<a href="eniun.com/en/" title="English translation">English</a>
```

**5.** Prueba a incluir el logo [[3]](#item3) adecuado que acredita el nivel de accesibiliad en tu proyecto. Puedes dejarlo inscrustrado para la entrega si lo deseas.

**6.** ¿Le pondrías un texto alternativo al logotipo de una empresa? ¿Qué texto alternativo? ¿y a una imagen decorativa?

**7.** ¿Qué nivel de conformidad exigirías para un sitio web muy complejo? ¿Qué nivel se exige en España legislativamente a todas las páginas web administrativas?

**8.** En cuanto a accesibilidad, ¿por qué crees que es importante separar los estilos (CSS) de los contenidos y la estructura del documento (HTML)? Instala la extenisón Stylish [[4]](#item4), crea algunos estilos y comprueba que los estilos de tu sitio son sobreescritos.

**9.** Las teclas de acceso rápido permiten rápidamente activa el foco de un elemento en tu página presionando una tecla concreta, usuamente en combinación de la tecla Alt (Ctrl+Alt en Mac). Añade a los enlaces de tu portafolio el atributo 'accesskey' y comprueba que efectivamente puedes acceder a dichos enlaces a través de la combinación de teclas que has definido. Ej: 
```
<a href="google.com" accesskey="g">Link to Google</a>
```
Podríamos acceder a través de Alt+g. ¡Ojo! Con duplicar teclas en estos atributos ya que podría tener un efecto negativo en la navegación de los usuarios.

**10.** Abre tu portafolio en tu navegador Chrome y accede al DevTools, (F12 o a través del menú contextual y seleccionando "Inspeccionar"). Entra en la sección "Lighthouse" y asegúrate que esté solo marcada la opción "Accesibilidad" y "Desktop" a continuación, pulsa en el botón "Generar informe". Adjunta la captura de la puntuación y errores que se han detectado. ¿Son los mismos que ha detectado las otras herramientas de test de accesibiliad online?

**11.** Las etiquetas de encabezado definen la cabecera principal de una página (h1), así como los subencabezados (de h2, h3 al h6) de varias secciones del contenido de una página. Son crucial para la accesibilidad del usuario. Como las etiquetas de encabezado están escritas en HTML, la tecnología de asistencia del lector de pantalla puede interpretar la estructura de cualquier página web y leerla en voz alta para los usuarios con discapacidad. Mientras escuchan los encabezados del contenido, pueden decidir si la página contiene lo que necesitan. Además, los lectores de pantalla proporcionan accesos directos que permiten a los usuarios moverse fácilmente entre encabezados, facilitando su navegación. Por esta razón, es clave observar la jerarquía de los H: siempre comenzar con h1, luego usar h2 y así, sucesivamente. De lo contrario, los usuarios del lector de pantalla se confundirán e irán de un lado a otro para encontrar el siguiente encabezado lógico, provocando su abandono. Revisa que la jerarquía de encabezados de tu portafolio es correcta.

**12.** Te han encargado que mejores la accesibilidad de un sitio web que se encuentra maquetado mediante tablas. Su contenido se encuentra representado de la siguiente forma:
```
<table>
    <tr> 
        <td colspan="2">Cabecera</td>
    </tr>
    <tr>
        <td>Menu</td>
        <td>Contenido principal</td>
    </tr>
    <tr>
        <td colspan="2">Footer</td>
    </tr>
</table>
```
¿Qué mejoras realizarías?

**13.** Como bien sabemos, los CAPTCHAS presentan muchos problemas de accesibilidad para ciertos grupos de usuarios. Las personas daltónicas o con visión reducida pueden no ver bien las combinaciones de colores con letras y números a descifrar. Por otra parte, es evidente que una persona ciega que utiliza un lector de pantalla no puede contestar a los CAPTCHAS basados en imágenes. ¿Qué alternativas hay al uso de un CAPTCHA? ¿Cómo es el nuevo reCAPTCHA v3 de Google y qué mejoras trae? [[5]](#item5)

**14.** Bootstrap nos ayuda a que nuestros sitios web sean accesibles incluyendo en los ejemplos de código los elementos y atributos HTML recomendados para conseguir aplicaciones accesibles. Analiza la página web que creaste en la tarea de Bootstrap (UD2-T16. Bootstrap(https://educacionadistancia.juntadeandalucia.es/centros/cadiz/mod/assign/view.php?id=385777)) y encuentra los atributos WAI-ARIA utilizados. Fíjate, por ejemplo, en los atributos role y aria-hidden. Explica por qué se han utilizado esos atributos.




## REFERENCIAS
<a name="item1"></a>
[1] Color Contrast Checker (Aplicación para comprobar el contraste entre fondo y texto): https://webaim.org/resources/contrastchecker/

<a name="item2"></a>
[2] Añadir subtítulos a videos en YouTube: https://www.youtube.com/watch?v=LCZ-cxfxzvk

<a name="item3"></a>
[3] ¿Cómo usar los logos de conformidad de accesibilidad de la W3C?: https://www.w3.org/WAI/WCAG1-Conformance

<a name="item4"></a>
[4] Saltarse los estilos de una web especificando los del usuario: https://www.itsupportguides.com/knowledge-base/computer-accessibility/how-to-use-a-custom-style-sheet-css-with-google-chrome/

<a name="item5"></a>
[5]Captcha y reCaptcha: https://www.xataka.com/basics/captcha-recaptcha-que-cuales-sus-diferencias-que-cambia-recaptcha-v3
