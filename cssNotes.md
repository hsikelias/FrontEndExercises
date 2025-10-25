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