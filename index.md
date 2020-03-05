---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "Evaluating Web Accessibility Overview"
nav_title: "Evaluation Overview"

lang: en
last_updated: 2018-09-20
permalink: /test-evaluate/

github: 
  repository: w3c/wai-eval-overview
  path: index.md

feedbackmail: wai@w3.org
class: tight-page
footer: >
  <p><strong>Date:</strong> Updated 20 September 2018.</p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
ref: /test-evaluate/
---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page links to resources to help evaluate web accessibility. Accessibility evaluation is also called "assessment", "audit", and "testing".

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Introduction {#intro}

{% include video-player.html
    yt-id="93UgG72os8M"
    captions="/keyboard-en.vtt|en|Captions"
    descriptions=""
%}

_This video is also available on a [W3C server (file format: MP4, file size: 45MB) - Overview of Evaluation Resources](http://media.w3.org/wai/evaluation-intros/evaluating-resources-overview.mp4)._

{% include excol.html type="start" id="video-intro-transcript" %}

Text Transcript with Description of Visuals {#transcript}

{% include excol.html type="middle" %}

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
    <td>WCAG-EM. Website Accessibility Conformance Evaluation Methodology. A person in front of a computer. A simplified report is displayed. A person in front of a computer, and the screen showing a simplified report.</td>
  </tr>
  <tr>
    <td>The "WCAG-EM Report Tool" helps you record the findings as you follow the methodology. </td>
    <td>WCAG-EM Report Tool. A progress bar shows the various stages of the evaluation methodology.</td>
  </tr>
  <tr>
    <td>To help you better understand how different users experience your website and applications, WAI provides guidance in "Involving Users in Web Projects for Better, Easier Accessibility" and Involving users in Evaluating Web Accessibility.</td>
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

When developing or redesigning a website or web application, evaluate accessibility early and throughout the development process to identify accessibility problems early, when it is easier to address them.

There are evaluation tools that help with evaluation. However, no tool alone can determine if a site meets accessibility standards. Knowledgeable human evaluation is required to determine if a site is accessible.

## Initial Checks {#initial}

{% include video-card.html
    video-url="http://media.w3.org/wai/evaluation-intros/easy-checks-accessibility.mp4"
    captions="http://media.w3.org/wai/evaluation-intros/easy-checks-accessibility.mp4"
    accessible-version="/perspective-videos/cc/keyboard_ad_desc-en.vtt|en|Descriptions"
    accessible-version-label="Video Overview of Easy Checks for Web Accessibility"
%}

Even if you don’t know anything about accessibility and you don’t have a robust accessibility tool, you can check some aspects of accessibility.

[Easy Checks — A First Review of Web Accessibility](/test-evaluate/preliminary/)
:   Provides step-by-step guidance and brief explanations for checking some aspects of accessibility.

## Tools

Web accessibility evaluation tools are software programs or online services that help determine if web content meets accessibility standards.

[Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/)
:   Includes information on more than 100 tools. You can use the filters to narrow down the list to the types of tools you are interested in.

[[Selecting Web Accessibility Evaluation Tools]](/test-evaluate/tools/selecting/)
:   Provides guidance on choosing tools. It describes the features and functionality of different types of evaluation tools, and discusses things to consider for your situation.

## Conformance Evaluation {#conformance}

Conformance evaluation determines how well web pages or applications meet accessibility standards. W3C’s Website Accessibility Conformance Evaluation Methodology (WCAG-EM) is an approach for determining conformance to Web Content Accessibility Guidelines (WCAG).

[[WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology]](/test-evaluate/conformance/wcag-em/)
:   A short page with basic information to get you started. We suggest you read it before going to the [full WCAG-EM document](https://www.w3.org/TR/WCAG-EM/).

## Reports

Communicate the results of evaluation clearly, including the scope of the evaluation.

[WCAG-EM Report Tool: Website Accessibility Evaluation Report Generator](https://www.w3.org/WAI/eval/report-tool/#/)
:   Helps you generate evaluation reports according to WCAG-EM. It does not do the checking for you. It helps you follow the steps of WCAG-EM and it generates a report from the input you provide.

[[Template for Web Accessibility Evaluation Reports]](/test-evaluate/report-template/)
:   Suggests information to include in a report.

## People

Getting the right people and skills involved makes your accessibility evaluations more effective.

[[Involving Users in Evaluating Web Accessibility]](/test-evaluate/involving-users/)
:   Provides guidance on including people with disabilities ("users") in evaluation throughout project development.

[Using Combined Expertise to Evaluate Web Accessibility](/test-evaluate/combined-expertise/)
:   Discusses skill sets and considerations for collaborative review.

## Standards

Specifications for writing accessibility test rules (ACT Rules Format) and expressing test results (EARL) are introduced in [Evaluation Standards Overview](/standards-guidelines/evaluation/).
