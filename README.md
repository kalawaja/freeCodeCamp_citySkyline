# Learn CSS Variables by Building a City Skyline, Not Completed

> - CSS variables help you organize your styles and reuse them.
> - In this course, you'll build a city skyline. You'll learn how to configure CSS variables so you can reuse them whenever you want.
---

> **Step 1** <br>
Welcome to the CSS Variables Skyline project! Start by adding the `!DOCTYPE html` declaration at the top of the document so the browser knows what type of document it's reading.

```html
#index.html

```
> **Step 2** <br>
Add opening and closing `html` tags below the `DOCTYPE` so you have a place to start putting some code. Be sure to set the language to English.

```html
#index.html

```
> **Step 3** <br>
Next, add opening and closing `head` and `body` tags within the html element.

```html
#index.html

```
> **Step 4** <br>
Within the `head`, nest a `meta` element with a `charset` of `UTF-8`, a `title` element with a title of `City Skyline`, and a `link` element that links your `styles.css` file.

```html
#index.html

```
> **Step 5** <br>
In CSS, you can target everything with an asterisk. Add a border to everything by using the `*` selector, and giving it a `border` of `1px solid black`. This is a trick that helps visualize where elements are and their size. You will remove this later.

```css
#styles.css

```
> **Step 6** <br>
Also add a `box-sizing` of `border-box` to everything. This will make it so the border you added doesn't add any size to your elements.

```html
#index.html

```
> **Step 7** <br>
You can see the `body` (it's the inner-most box on your page); the box around it is the `html` element. Make your `body` fill the whole viewport by giving it a `height` of `100vh`. Remove the default `margin` from the `body` by setting the `margin` to `0`. Finally, set the `overflow` property to `hidden` to hide any scroll bars that appear when something extends past the viewport.

```html
#index.html

```
> **Step 8** <br>
Create a `div` element in the `body` with a class of `background-buildings`. This will be a container for a group of buildings.

```html
#index.html

```
> **Step 9** <br>
Give your background buildings element a `width` and `height` of `100%` to make it the full width and height of its parent, the `body`.

```html
#index.html

```
> **Step 10** <br>
Nest a `div` with a class of `bb1` in the background buildings container. Open your `styles.css` file, and give `.bb1` a `width` of `10%` and `height` of `70%`. "bb" stands for "background building", this will be your first building.

```html
#index.html

```
> **Step 11** <br>
Nest four `div` elements in the `.bb1` container. Give them the classes `bb1a`, `bb1b`, `bb1c`, and `bb1d` in that order. This building will have four sections.

```html
#index.html

```
> **Step 12** <br>
Give the parts of your building `width` and `height` properties with these values: `70%` and `10%` to `.bb1a`, `80%` and `10%` to `.bb1b`, `90%` and `10%` to `.bb1c`, and `100%` and `70%` to `.bb1d`. Remember that these percentages are relative to the parent and note that the heights will add up to 100% - vertically filling the container.

```html
#index.html

```
> **Step 13** <br>
Give your `.bb1` element these style properties: `display: flex;`, `flex-direction: column;`, and `align-items: center;`. This will center the parts of the building using "flex" or "flexbox". You will learn about it in more detail on another project.

```html
#index.html

```
> **Step 14** <br>
Now you have something that is resembling a building. You are ready to create your first variable. Variable declarations begin with two dashes (`-`) and are given a name and a value like this: `--variable-name: value;`. In the `.bb1` class, create a variable named `--building-color1` and give it a value of `#999`.

```html
#index.html

```
> **Step 15** <br>
To use a variable, put the variable name in parentheses with `var` in front of them like this: `var(--variable-name)`. Whatever value you gave the variable will be applied to whatever property you use it on.<br>
Add the variable `--building-color1` you created in the previous step as the value of the `background-color` property of the `.bb1a` class.

```html
#index.html

```
> **Step 16** <br>
Use the same variable as the `background-color` of the `.bb1b`, `.bb1c`, and `.bb1d` classes to fill in the rest of the building.

```html
#index.html

```
> **Step 17** <br>
Change the value of your variable from `#999` to `#aa80ff` and you can see how it gets applied everywhere you used the variable. This is the main advantage of using variables, being able to quickly change many values in your stylesheet by just changing the value of a variable.

```html
#index.html

```
> **Step 18** <br>
Your first building looks pretty good now. Nest three new `div` elements in the `background-buildings` container and give them the classes of `bb2`, `bb3`, and `bb4` in that order. These will be three more buildings for the background.

```html
#index.html

```
> **Step 19** <br>
Give the new buildings `width` and `height` properties of: `10%` and `50%` for `.bb2`, `10%` and `55%` for `.bb3`, and `11%` and `58%` for `.bb4`. You will be using almost all percent based units and some flexbox for this project, so everything will be completely responsive.

```html
#index.html

```
> **Step 20** <br>
The buildings are currently stacked on top of each other. Add the properties `display: flex;`, `align-items: flex-end;`, and `justify-content: space-evenly;` to the `background-buildings` class to fix that. This will use flexbox again to evenly space the buildings across the bottom of the element.

```html
#index.html

```
> **Step 21** <br>


```html
#index.html

```
> **Step 22** <br>


```html
#index.html

```
> **Step 23** <br>


```html
#index.html

```
> **Step 24** <br>


```html
#index.html

```
> **Step 25** <br>


```html
#index.html

```
> **Step 26** <br>


```html
#index.html

```
> **Step 27** <br>


```html
#index.html

```
> **Step 28** <br>


```css
#styles.css

```
> **Step 29** <br>


```css
#styles.css

```
> **Step 30** <br>


```css
#styles.css

```
> **Step 31** <br>


```css
#styles.css

```
> **Step 32** <br>


```css
#styles.css

```
> **Step 33** <br>


```css
#styles.css

```
> **Step 34** <br>


```css
#styles.css

```
> **Step 35** <br>


```css
#styles.css

```
> **Step 36** <br>


```css
#styles.css

```
> **Step 37** <br>


```css
#styles.css

```
> **Step 38** <br>


```css
#styles.css

```
> **Step 39** <br>


```css
#styles.css

```
> **Step 40** <br>


```css
#styles.css

```
> **Step 41** <br>


```css
#styles.css

```
> **Step 42** <br>


```css
#styles.css

```
> **Step 43** <br>


```css
#styles.css

```
> **Step 44** <br>


```css
#styles.css

```
> **Step 45** <br>


```css
#styles.css

```
> **Step 46** <br>


```css
#styles.css

```
> **Step 47** <br>


```css
#styles.css

```
> **Step 48** <br>


```css
#styles.css

```
> **Step 49** <br>


```css
#styles.css

```
> **Step 50** <br>


```css
#styles.css

```
> **Step 51** <br>


```css
#styles.css

```
> **Step 52** <br>


```css
#styles.css

```
> **Step 53** <br>


```css
#styles.css

```
> **Step 54** <br>


```css
#styles.css

```
> **Step 55** <br>


```css
#styles.css

```
> **Step 56** <br>


```css
#styles.css

```
> **Step 57** <br>


```css
#styles.css

```
> **Step 58** <br>


```css
#styles.css

```
> **Step 59** <br>


```css
#styles.css

```
> **Step 60** <br>


```css
#styles.css

```
> **Step 61** <br>


```css
#styles.css

```
> **Step 62** <br>


```css
#styles.css

```
> **Step 63** <br>


```css
#styles.css

```
> **Step 64** <br>


```css
#styles.css

```
> **Step 65** <br>


```css
#styles.css

```
> **Step 66** <br>


```css
#styles.css

```
> **Step 67** <br>


```css
#styles.css

```
> **Step 68** <br>


```css
#styles.css

```
> **Step 69** <br>


```css
#styles.css

```
> **Step 70** <br>


```css
#styles.css

```
> **Step 71** <br>


```css
#styles.css

```
> **Step 72** <br>


```css
#styles.css

```
> **Step 73** <br>


```css
#styles.css

```
> **Step 74** <br>


```css
#styles.css

```
> **Step 75** <br>


```css
#styles.css

```
> **Step 76** <br>


```css
#styles.css

```
> **Step 77** <br>


```css
#styles.css

```
> **Step 78** <br>


```css
#styles.css

```
> **Step 79** <br>


```css
#styles.css

```
> **Step 80** <br>


```css
#styles.css

```
> **Step 81** <br>


```css
#styles.css

```
> **Step 82** <br>


```css
#styles.css

```
> **Step 83** <br>


```css
#styles.css

```
> **Step 84** <br>


```css
#styles.css

```
> **Step 85** <br>


```css
#styles.css

```
> **Step 86** <br>


```css
#styles.css

```
> **Step 87** <br>


```css
#styles.css

```
> **Step 88** <br>


```css
#styles.css

```
> **Step 89** <br>


```css
#styles.css

```
> **Step 90** <br>


```css
#styles.css

```
> **Step 91** <br>


```css
#styles.css

```
> **Step 92** <br>


```css
#styles.css

```
> **Step 93** <br>


```css
#styles.css

```
> **Step 94** <br>


```css
#styles.css

```
> **Step 95** <br>


```css
#styles.css

```
> **Step 96** <br>


```css
#styles.css

```
> **Step 97** <br>


```css
#styles.css

```
> **Step 98** <br>


```css
#styles.css

```
> **Step 99** <br>


```css
#styles.css

```
> **Step 100** <br>


```css
#styles.css

```
> **Step 101** <br>


```css
#styles.css

```
> **Step 102** <br>


```css
#styles.css

```
> **Step 103** <br>


```css
#styles.css

```
> **Step 104** <br>


```css
#styles.css

```
> **Step 105** <br>


```css
#styles.css

```
> **Step 106** <br>


```css
#styles.css

```
> **Step 107** <br>


```css
#styles.css

```
> **Step 108** <br>


```css
#styles.css

```
> **Step 109** <br>


```css
#styles.css

```
> **Step 110** <br>


```css
#styles.css

```
> **Step 111** <br>


```css
#styles.css

```
> **Step 112** <br>


```css
#styles.css

```
> **Step 113** <br>


```css
#styles.css

```
> **Step 114** <br>


```css
#styles.css

```
> **Step 115** <br>


```css
#styles.css

```
> **Step 116** <br>


```css
#styles.css

```
> **Step 117** <br>


```css
#styles.css

```
> **Step 118** <br>


```css
#styles.css

```