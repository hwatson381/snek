# Custom Color Schemes for Google Snake


This project has JavaScript code that, when pasted directly into the developer console in the browser, changes colors in the Google Snake Game.<br/>
This mod is supported on Chrome and Opera. Other browser may or may not work.

## Making It Work
Simply click the bookmark.<br/>
To import the bookmark, follow this [video](https://imgur.com/ofQky1B)<br/><br/>
Alternatively, you can do the following:<br/>
As mentioned earlier, copy and paste the code in `custom_color_scheme.js` into the console, here's a screenshot:     
![image](https://user-images.githubusercontent.com/6286286/111076598-95cc9a00-84f5-11eb-9a38-e71bddeb97e4.png)<br/>
And press Enter.<br/>
As of now, this must be done everytime you refresh/open the game.

## Create a Bookmark for a Custom Scheme
Go to [Google Snake Scheme Bookmark Maker](https://fizhes.github.io/scheme_bookmark_maker/), <br/>select your colors<br/>and click The Button™.

## Enable Dark Mode
```
window.snake.dark();
```
If you want to disable, just refresh.

## Enable a Custom Scheme
```
window.snake.scheme({
  scoreBar:      '#rrggbb', // hex code for score bar, defaults to the default color if omitted
  background:    '#rrggbb', // hex code for background, defaults to score bar color if omitted
  walls:         '#rrggbb', // hex code for border and wall mode walls, defaults to default color
  shadows:       '#rrggbb', // hex code for snake and fruit shadows, defaults to default
  lightSquares:  '#rrggbb', // hex code for the light board squares, defaults to default
  darkSquares:   '#rrggbb', // hex code for the dark board squares, defaults to default
  lightGoal:     '#rrggbb', // hex code for the dark sections of the Sokoban goals; optional: OMISSION RECOMMENDED
  darkGoal:      '#rrggbb', // hex code for the light sections of the Sokoban goals; optional: OMISSION RECOMMENDED
  keyBlockMarks: '#rrggbb', // hex code for the marks on the key walls; optional: OMISSION RECOMMENDED
  sky:           '#rrggbb', // hex code for the sky color in the menu, defaults to default
  separators:    '#rrggbb', // hex code for thin separators in menu, defaults to default
  buttons:       '#rrggbb', // hex code for color of play and options buttons, defaults to default
}); // if not given any arguments, it will be the default scheme (with the page background the same color as the score bar)
```
If you want to disable, just refresh.

## Contributors
* Llama
* Fishes
* Yarmiplay
