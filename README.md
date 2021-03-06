![Project Logo](https://github.com/SwissAS/comparandum/blob/master/misc/logo.png "Logo")
# comparandum
Framework to unit test renderers by visually comparing the generated output with a reference image.

## Introduction
Comparandum is a testing framework build on top of JUnit. It allows you to write unit tests for visual comparison. 
It works by comparing the output of a "renderer" with a predefined reference image.

## Motivation
When working on one of my hobby projects (a Java look and feel) I realized that it is very hard to write good unit tests 
for the rendering of the components. To prevent regression bugs I searched for a good solution to test UI rendering code 
and I found nothing on the web. Therefore I decided to write something on my own.

## The Solution
This library will provide you a framework to write unit tests for visual comparisons. It comes with the following features:

+ Execution of any kind of rendering code
+ Comparison to predefined reference images (a comparandum)
+ Executing the comparison as unit test
+ Creating of reports in HTML or XML
+ Automatically updating the reference images when needed 

## Project Status
The project is feature complete and used productively. 


## Dependencies

+ Java 1.8 or newer
+ JUnit 5 

## More documentation
For some simple usage examples look at the unit tests coming with the project. 
If you need further information you can read the JavaDoc.

Makes use of the 

(http://maxazan.github.io/jquery-treegrid/ "TreeGrid jQuery") component for the test index page


and the 

(http://www.catchmyfame.com/catchmyfame-jquery-plugins/jquery-beforeafter-plugin/ "jQuery BeforeAfter Plugin") under
CC Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0) - http://creativecommons.org/licenses/by-nc-sa/3.0/


Have fun,

Bernd Rosstauscher 