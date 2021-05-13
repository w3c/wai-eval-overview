---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Visión general sobre la evaluación de la accesibilidad web"
nav_title: "Visión general sobre la evaluación"

lang: es
last_updated: 2019-07-21
permalink: /test-evaluate/es

translators:
- name: "Jorge Rumoroso"
  link: "https://twitter.com/rumoroso"
contributors:
- name: "Carlos Muncharaz"

github: 
  repository: w3c/wai-eval-overview
  path: content/index.es.md

ref: /test-evaluate/  #translators do not change this
changelog: /test-evaluate/changelog/

feedbackmail: wai@w3.org
class: tight-page
# Do not translate CHANGELOG in footer below.
footer: >
  <p>Note about video description: The videos on this page do not include synchronized audio description because the visuals only illustrate the audio and do not provide additional information. In this case, audio description would be more distracting than useful to most people, including people who cannot see the visuals. Description of visual information is integrated in the Text Transcript with Description of Visuals (“descriptive transcript”).</p>
  <p><strong>Fecha:</strong> Actualizado el 7 de mayo de 2021. CHANGELOG.</p>
  <p><strong>Editora:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p> Videos developed by the Grupo de Trabajo de Educación y Divulgación (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide</a> project funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245). <a href="./acknowledgements/">Acknowledgements</a>.</p>
  <p><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a> The videos are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.</p>
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Resumen" class="full" %}
{:/}

Esta página contiene enlaces a recursos para ayudar a evaluar la accesibilidad web. La evaluación de la accesibilidad también se denomina "análisis", "auditoría" o "prueba".

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Contenidos de la página" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introducción {#intro}

<div class="video-card">
  {% include video-player.html
      yt-id="C4GIqWeywiI"
      captions="/content-images/wai-eval-overview/evaluating-resources-overview-cc.vtt|en|default"
  %}
  <p><a href="#alternatives">Alternatives for Video Introduction - Resources Overview</a></p>
</div>

Al desarrollar o rediseñar un sitio web o una aplicación web, evalúe la accesibilidad desde el principio y durante todo el proceso de desarrollo para identificar los problemas de accesibilidad lo antes posible, cuando es más fácil resolverlos.

Existen herramientas que ayudan con la evaluación. Sin embargo, ninguna herramienta por sí sola puede determinar si un sitio cumple con los estándares de accesibilidad. Se requieren buenos conocimientos para determinar si un sitio es accesible.

## Pruebas iniciales {#initial}

{% include video-card.html
    video-url="//media.w3.org/wai/evaluation-intros/easy-checks-accessibility.mp4"
    captions="/content-images/wai-eval-overview/easy-checks-accessibility-cc.vtt|en|default"
    poster="video-thumb-easy-checks.png"
    accessible-version="https://www.w3.org/WAI/test-evaluate/preliminary/#video-intro"
    accessible-version-label="Video: Easy Checks Overview"
    poster="/content-images/wai-eval-overview/video-thumb-easy-checks.png"
%}

Incluso si usted no tiene conocimiento sobre accesibilidad y no posee herramientas para evaluarla, aún puede comprobar algunos de los aspectos de la accesibilidad.

[Comprobaciones sencillas — Una primera revisión a la accesibilidad web](/test-evaluate/preliminary/)
:   Facilita una guía paso a paso, junto con sencillas explicaciones, para evaluar algunos aspectos de la accesibilidad.

## Herramientas

{% include video-card.html
    video-url="//media.w3.org/wai/evaluation-intros/tools-for-evaluating.mp4"
    captions="/content-images/wai-eval-overview/tools-for-evaluating-cc.vtt|en|default"
    accessible-version="https://www.w3.org/WAI/test-evaluate/tools/#video-intro"
    accessible-version-label="Video: Evaluation Tools Overview"
    poster="/content-images/wai-eval-overview/video-thumb-tools.png"
%}

Las herramientas de evaluación de la accesibilidad web son programas de software o servicios en línea que ayudan a determinar si el contenido web cumple con los estándares de accesibilidad.

[Lista de herramientas de evaluación de la accesibilidad web](https://www.w3.org/WAI/ER/tools/)
:   Incluye información sobre más de 100 herramientas. Puede utilizar los filtros para limitar la lista a los tipos de herramientas que le interesan.

[[Elegir herramientas de evaluación de accesibilidad web]](/test-evaluate/tools/selecting/)
:   Proporciona orientación sobre la elección de las herramientas. Describe las características y la funcionalidad de los diferentes tipos de herramientas de evaluación y plantea las cosas a tener en cuenta para su situación.

## Evaluación de la conformidad -> Conformance Evaluation and Reports {#conformance}

{% include video-card.html
    video-url="//media.w3.org/wai/evaluation-intros/conformance-evaluation.mp4"
    captions="/content-images/wai-eval-overview/conformance-evaluation-cc.vtt|en|default"
    accessible-version="https://www.w3.org/WAI/test-evaluate/conformance/#video-intro"
    accessible-version-label="Video: Conformance Evaluation Overview"
    poster="/content-images/wai-eval-overview/video-thumb-conformance.png"
%}

La evaluación de conformidad determina el grado en que las páginas o las aplicaciones web cumplen los estándares de accesibilidad. La "Metodología de evaluación de la conformidad de la accesibilidad de sitios web" (WCAG-EM) del W3C es un acercamiento para determinar la conformidad con las Pautas de Accesibilidad al Contenido Web (WCAG).

[[Visión general de WCAG-EM: Metodología de evaluación de la conformidad de la accesibilidad de sitios web]](/test-evaluate/conformance/wcag-em/)
:   Es una sencilla página con información básica para ayudarle a empezar. Le sugerimos leerla antes de ir al [documento completo de WCAG-EM](https://www.w3.org/TR/WCAG-EM/).

[Herramienta de informes WCAG-EM: Generador de informes de evaluación de la accesibilidad del sitio web](https://www.w3.org/WAI/eval/report-tool/#/)
:   Es una ayuda para generar informes de evaluación de acuerdo a WCAG-EM. No hace las comprobaciones por usted, sino que le ayuda a seguir los pasos de WCAG-EM y genera un informe a partir de la información que usted facilita.

[[Plantilla para informes de evaluación de accesibilidad web]](/test-evaluate/report-template/)
:   Información sugerida para incluir en un informe.

[ATAG Report Tool](https://www.w3.org/WAI/atag/report-tool/)
:   Helps you generate a report on how a tool meets Authoring Tool Accessibility Guidelines ([ATAG](https://www.w3.org/WAI/standards-guidelines/atag/)). Authoring tools are software and services used to create web content – such as content management systems (CMS) and what-you-see-is-what-you-get (WYSIWYG) HTML editors.

Comunique los resultados de la evaluación claramente, incluyendo el ámbito de aplicación.

## Personas

{% include video-card.html
    video-url="//media.w3.org/wai/evaluation-intros/involving-users.mp4"
    captions="/content-images/wai-eval-overview/involving-users-cc.vtt|en|default"
    accessible-version="https://www.w3.org/WAI/test-evaluate/involving-users/#video-intro"
    accessible-version-label="Video: Involving Users in Web Accessibility Overview"
    poster="/content-images/wai-eval-overview/video-thumb-involving-users.png"
%}

La participación de las personas con las habilidades adecuadas hace que sus evaluaciones de accesibilidad sean más eficaces.

[[Participación de los usuarios en la evaluación de la accesibilidad web]](/test-evaluate/involving-users/)
:   Proporciona orientación sobre la inclusión de las personas con discapacidad ("usuarios") en la evaluación durante el desarrollo del proyecto.

[Combinar conocimientos para evaluar la accesibilidad web](/test-evaluate/combined-expertise/)
:   Trata los conjuntos de habilidades y consideraciones a tener en cuenta para una revisión colaborativa.

## Estándares

La [descripción general de las normas de evaluación](/standards-guidelines/evaluation/) introduce las especificaciones para redactar pruebas de accesibilidad (formato de reglas ACT) y mostrar los resultados de las mismas (EARL).



<hr>


{% include excol.html type="start" id="video-intro-transcript" %}

##  Alternatives for Video Introduction - Resources Overview {#alternatives}

{% include excol.html type="middle" %}

_This video is also available on a W3C server: [Video: Evaluating Web Accessibility - Resources Overview (file format: MP4, file size: 45MB)](http://media.w3.org/wai/evaluation-intros/evaluating-resources-overview.mp4)._

###  Text Transcript with Description of Visuals for Video Introduction - Resources Overview {#transcript}

<table aria-labelledby="transcript">
  <tbody>
    <tr>
      <th>Audio</th>
      <th>Visual</th>
    </tr>
    <tr>
      <td>Evaluating web accessibility: resources overview </td>
      <td>Evaluating web accessibility: resources overview.</td>
    </tr>
    <tr>
       <td>Evaluation helps you ensure that your websites and applications meet accessibility requirements. </td>
      <td>A magnifying glass with the word evaluation on a computer screen with a website on it.</td>
    </tr>
    <tr>
      <td>Ideally you evaluate regularly throughout the design and development process. This way you find errors early and avoid costly repairs later in the process. </td>
      <td>The web page components rearrange on the page until following a good design.</td>
    </tr>
    <tr>
      <td>The W3C Web Accessibility Initiative, W-A-I, or WAI, provides free resources to help you with your evaluation. </td>
      <td>W3C and Web Accessibility Initiative (WAI) logos.</td>
    </tr>
    <tr>
      <td>"Easy Checks - A First Review of Web Accessibility" explains how you can do some checks yourself. </td>
      <td>"Easy Checks - A First Review of Web Accessibility". A person in front of the computer. A light bulb appears.</td>
    </tr>
    <tr>
      <td>Even if you are new to web accessibility and not technical, these checks give you a rough idea of the accessibility of any web page. </td>
      <td>A document of checks. Each check is highlighted to show fails or passes.</td>
    </tr>
    <tr>
      <td>WAI also maintains a "Web Accessibility Evaluation Tools List" that you can filter. </td>
      <td>Web Accessibility Evaluation Tools List. A list of tools displayed as icons..</td>
    </tr>
    <tr>
      <td>"Selecting Web Accessibility Evaluation Tools" explains what tools can and cannot do. </td>
      <td>Selecting Web Accessibility Evaluation Tools. The tools icons displayed in a computer.</td>
    </tr>
    <tr>
      <td>For more experienced evaluators, WAI provides "WCAG-EM", the "Website Accessibility Conformance Evaluation Methodology". </td>
      <td>WCAG-EM. Website Accessibility Conformance Evaluation Methodology. A person in front of a computer. A simplified report is displayed.</td>
    </tr>
    <tr>
      <td>The "WCAG-EM Report Tool" helps you record the findings as you follow the methodology. </td>
      <td>WCAG-EM Report Tool. A progress bar shows the various stages of the evaluation methodology.</td>
    </tr>
    <tr>
      <td>To help you better understand how different users experience your website and applications, WAI provides guidance in "Involving Users in Web Projects for Better, Easier Accessibility" and "Involving users in Evaluating Web Accessibility."</td>
      <td>The screen splits into 12 fields each with a different user in front of a computer. Involving Users in Web Projects for Better, Easier Accessibility and Involving users in Evaluating Web Accessibility</td>
    </tr>
    <tr>
      <td>With all these resources, you can learn how to check your website for accessibility and prioritize the issues you need to address first. </td>
      <td>A magnifying glass with the words check for accessibility is replaced with a list of issues.</td>
    </tr>
    <tr>
      <td>Web accessibility: essential for some, useful for all. </td>
      <td>Icons around a computer: hand; eye; brain; ear; and mouth with sound waves.</td>
    </tr>
    <tr>
      <td>For resources on evaluating web accessibility, visit w3.o-r-g/W-A-I/evaluation. </td>
      <td>Evaluation resources, W3C and Web Accessibility Initiative (WAI) logos.</td>
    </tr>
  </tbody>
</table>

{% include excol.html type="end" %}
