---
sidebar_position: 120 
title: String Edit Box
---

import ComponentDemo from '@site/src/components/DocsTools/ComponentDemo';

<div style={{width: "100%" , display: "flex", justifyContent: "flex-end", marginBottom: "-50px"}}>
<p style={{color: "gray"}} >API:&nbsp;</p>
<b><a href="https://javadoc.io/static/org.dwcj/dwcj-engine/0.15.0/org/dwcj/controls/stringeditbox/StringEditBox.html" style={{justifySelf: "flex-end"}}> Java </a></b>
</div>

### Labeling


The string edit control can be easily labeled without the needing to create an extra label control using the `setAttribute()` method and passing the desired label as a string, as shown below: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.stringeditdemos.StringEditLabelDemo' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/stringeditdemos/StringEditLabelDemo.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/stringeditboxstyles/string_edit_styles.css' 
javaHighlight='{16}'
height = '125px'
/>

<br/>

### Mask

The DWCJ's string edit control supports masking - the following table describes the various masking behaviors.

<table>
<thead>
<tr>
<th align="center">Mask</th>
<th align="center">Supported</th>
<th align="left">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">X</td>
<td align="center">✓</td>
<td align="left">Any printable character.</td>
</tr>
<tr>
<td align="center">a</td>
<td align="center">✓</td>
<td align="left">Any alphabetic character.</td>
</tr>
<tr>
<td align="center">A</td>
<td align="center">✓</td>
<td align="left">Any alphabetic character. Converts lower-case alphabetic characters to upper case.</td>
</tr>
<tr>
<td align="center">0</td>
<td align="center">✓</td>
<td align="left">Any digit.</td>
</tr>
<tr>
<td align="center">z</td>
<td align="center">✓</td>
<td align="left">Any digit or alphabetic character.</td>
</tr>
<tr>
<td align="center">Z</td>
<td align="center">✓</td>
<td align="left">Any digit or alphabetic character. Converts lower-case alphabetic characters to upper case.</td>
</tr>
<tr>
<td align="center">U</td>
<td align="center">✓</td>
<td align="left">Any digit , alphabetic character , whitespace or punctuation. Converts lower-case alphabetic characters to upper case.</td>
</tr>
</tbody>
</table>

<br/>

### Placeholder

It is also possible to set placeholder text within the control to better help users understand what type of input is expected. Similar to a label, this can be accomplished using the `setAttribute()` method: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.stringeditdemos.StringEditPlaceholder' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/stringeditdemos/StringEditPlaceholder.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/stringeditboxstyles/string_edit_styles.css' 
javaHighlight='{17}'
height = '125px'
/>

<br/>

### Expanses

Additionally, the string edit box come with 5 expanses for quick styling without the use of CSS. Expanses are supported by use of a built-in enum class.
Below are the various expanses supported for the string edit box control: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.stringeditdemos.StringEditExpanse' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/stringeditdemos/StringEditExpanse.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/stringeditboxstyles/string_edit_styles.css' 
javaHighlight='{16,19,22,25,28}'
height = '125px'
/>

<br/>

|String Edit Box Expanses|
|-|
|<ul><li>```StringEditBox.Expanse.XSMALL```</li><li>```StringEditBox.Expanse.SMALL```</li><li>```StringEditBox.Expanse.MEDIUM```</li><li>```StringEditBox.Expanse.LARGE```</li><li>```StringEditBox.Expanse.XLARGE```</li></ul>|

