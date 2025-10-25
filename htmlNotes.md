# WHAT IS HTML? 

Simply put its a markup language, everything we see on websites like amazon, youtube is made of HTML, CSS. We give bunch of instructions to the computer and it follows thru it and creates the design. Best way to learn it is to just **START**. 

```
<button> Click me </button>
# creates a boring button
```
- Here <button>button</button> is an HTML element.

All these <> and </> are called **tags**.. we need these to actually display what we want on a web browser. We need to follow the syntax to actually display what we want.
  - <> is called as an **opening tag**
  - </> is alled as a **closing tag**

```
<a></a>
# anchor element
# this is what u use to link another website
```
We can't actually just enter a link inside these two tags and hope it takes us to that specific link.
We need to enter **href** inside the opening tag like: 

```
<a href="https://www.youtube.com"></a>
```
The href is an **attribute**, it modifes how an element behaves, here it modifies which link this will take us.. the href should also be seperate, href is the attribute here. 

we CAN add multiple attributes, lets try...

```
<a href = "https://www.youtube.com" target="_blank"> Link to YouTube </a>

```
- **target** attribute determines what happens when u click the link, will the link open in existing tab or open in a new tab. By default **" "** will open the link in existing tab. **"_blank"** will open it in a new tab.

spaces are ignored in HTML

