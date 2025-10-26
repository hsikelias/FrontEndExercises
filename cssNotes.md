To write CSS we need a **<.style>** element inside HTML.

This element doesn't create anything yet. it only modifies the appearence of HTML elements.

```
<style> 
  button { 
    background-color: red;
    color: white;
  }
</style>
```

- button is the **CSS selector**, we are targeting all the buttons.
- Inside the button { } we have **CSS Property**.
- In CSS we end a style with ;


What if there are multiple buttons? in that case we use the **class** attribute. It basically lets us label HTML elements.

```
<button class = "subscribe-button">
  SUBSCRIBE
</button>
```
- Since we labeled this HTML element, we will refer to it differently in the style as well. so instead of **button** we use **.subscribe-button**
- . is used to target a class
- multiple elements can have the same class.


To add space between things we use **margin**.. so space is margin.


## Hoovers, Transitions and Shadows

To add a hover to a certain button we need to target the same button as a new style like this 
This hoover is an extra styleits called as
**pseudocode**
Not just hoover we can add a style when we actually click a button as well.

```
.subscribe-button:hover{
    
}
```

opacity is used to decrease the opacity, the value for opacity is between 1 to 0.. 1 being the flat solid color.. and as we get close to 0 the opacity decreases

How do we make smooth transitions between different actions in a button.For that we use the transition property in the main button. Below is an example

```
transition: opacity 1s;
```

We can create shadows using **box-shadow**..
Box shadow takes 4 values

x   x   x   x

- 1st one determines the horizontal position of the shadow
- 2nd one sets the vertical position of the shadow.
- 3rd value is the blur
- 4th value is the color


## CSS BOX MODEL

This property in CSS involves spacing, outside our box.. for which we use margin, which is possible in all 4 directions.

Hardcoding the height and width of a button is not a good idea because if content gets big it overflows. Instead we should use something called **padding** which works in all 4 directions