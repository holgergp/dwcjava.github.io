---
sidebar_position: 160
title: Text Combo Box
---

import ComponentDemo from '@site/src/components/DocsTools/ComponentDemo';

<div style={{width: "100%" , display: "flex", justifyContent: "flex-end", marginBottom: "-50px"}}>
<p style={{color: "gray"}} >API:&nbsp;</p>
<b><a href="https://javadoc.io/static/org.dwcj/dwcj-engine/0.15.0/org/dwcj/controls/textcombobox/TextComboBox.html" style={{justifySelf: "flex-end"}}> Java </a></b>
</div>

### Menu Placement

The text combo box can be configured to open the menu in various positions relative to the position of the control itself.

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.textcomboboxdemos.TextComboBoxPlacement' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/textcomboboxdemos/TextComboBoxPlacement.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/textcomboboxstyles/placement_styles.css' 
javaHighlight='{24,29,33,38}'
height = '350px'
/>

<br/>

### Label

The text combo box control can be easily labeled without the needing to create an extra label control using the `setAttribute()` method and passing the desired label as a string, as shown below: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.textcomboboxdemos.TextComboBoxLabel' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/textcomboboxdemos/TextComboBoxLabel.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/textcomboboxstyles/text_combo_styles.css' 
javaHighlight='{24}'
height = '200px'
/>

<br/>

### Placeholder

It is also possible to set placeholder text within the control to better help users understand what type of input is expected. Similar to a label, this can be accomplished using the `setAttribute()` method: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.textcomboboxdemos.TextComboBoxPlaceholder' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/textcomboboxdemos/TextComboBoxPlaceholder.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/textcomboboxstyles/text_combo_styles.css' 
javaHighlight='{24}'
height = '200px'
/>

<br/>

### Expanses

DWCJ's text combo box comes with 5 expanses for quick styling without the use of CSS. Expanses are supported by use of a built-in enum class.
Below are the various expanses supported for the text box control: <br/>

<ComponentDemo 
path='https://hot.bbx.kitchen/webapp/controlsamples?class=control_demos.textcomboboxdemos.TextComboBoxExpanses' 
javaE='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/java/control_demos/textcomboboxdemos/TextComboBoxExpanses.java'
cssURL='https://raw.githubusercontent.com/DwcJava/ControlSamples/main/src/main/resources/css/textcomboboxstyles/expanse_styles.css' 
javaHighlight='{24,27,30,33,36}'
height = '350px'
/>

|Text Box Expanses|
|-|
|<ul><li>```TextBomboBox.Expanse.XSMALL```</li><li>```TextBomboBox.Expanse.SMALL```</li><li>```TextBomboBox.Expanse.MEDIUM```</li><li>```TextBomboBox.Expanse.LARGE```</li><li>```TextBomboBox.Expanse.XLARGE```</li></ul>|
