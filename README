Requirements 
============

Yii 1.1.x

Install 
=======

Extract to extensions directory
Add following to the import section of the main config
```
'application.extensions.states.*'
```

Usage 
=====

```
$options = array(
  "name" => "thestates",
  "seperateCountries" => true,
  "selected" => "VA",
);
$htmlOptions = array(
  "prompt" => "Please selecte a state",
);
 
echo States::render(array("US","canada","us territories"), $options, $htmlOptions);

Active Form
===========

$form->dropDownList($address, 'state', My_States::getStates(array("US"), true), 
       array('prompt' => 'State', 'class' => 'abc', 'style' => "width:75px;")),
```
