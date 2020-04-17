# Introducing CSS

The key to understanding how CSS works is to imagine that there is an invisible bos around every HTML element

### Block and inline elements

Block level elements look like they start on a new line.

Inline elements flow within the text and do not start on a new line.

- CSS allows you to vreate rules that control the way that each individual box (and the contents of that box) is presented

A Css rule contains two parts: a selector and a declaration

![css rule](https://3wga6448744j404mpt11pbx4-wpengine.netdna-ssl.com/wp-content/uploads/2012/10/css-rule.jpg)

Selectors indicate which element the rule applies to

Declarations indicate how the elements referred to in the selector should be styled

Css declarations sit inside curly brackets and each is made up of two parts:

- Properties indicate the aspects of the element you want to change

- Values specify the settings you want to use for the chosen properties

The 	``` <link> 	``` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page

Include CSS rules within an HTML page by placing the inside a ``` <style> ``` element which sits inside the ``` <head> ```

## selectors

- *Universal* - Applies to all the elements in the document ``` *{} ```

- *Type* - matches element names ``` h1, h2, h3 ```

- *Class* - Matches an element whose class attribute has a value that matches the on specifies after period ``` .note{} ```

- *Id* - element whose id attribute has a value that matches the one after pound ``` #intro{} ```

- *Child* - direct child of another ``` li>a {} ```

- *Descendant* -descendent of another specified element ``` p a {} ```

- *adjacent sibling* -  ``` h1+p {} ```

- *general sibling* -  ``` h1~p {} ```

## Color

color in css can be specified by the following methods
- Hexadecimal colors

- RGB colors

- RGBA colors

- HSL colors

- HSLA colors

- Predefined/Cross-browser color names

- With the currentcolor keyword
