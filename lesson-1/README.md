## Task description:
Convert logo.png to a responsive logo by using html and css

### Steps:
0-  Set your repo:

    Fork this repository 

    Clone your repository on your device 

    Set upstream to this repository by on of following commands

    ```html
      Using SSH:
      git remote add upstream git@github.com:mehrzadnaini/tutorial.git
      Using HTTPS:
      git remote add upstream https://github.com/mehrzadnaini/tutorial.git
    ```

1- Create a new folder with your name 

2- Add `index.html` and `style.css` into the folder

3- Create a wrapper div and set width and height based on window width

```html
<div id="logo">
</div>
```

4- Add 4 containers inside wrapper div: 
```html
<div id="logo">
    <div id="sec1" class="section"></div>
    <div id="sec2" class="section"></div>
    <div id="sec3" class="section"></div>
    <div id="sec4" class="section"></div>
</div>`
```
5- By using the Grid layout divide the main container into 2x2 square 

6- By using CSS update each section

7- Create a PR
