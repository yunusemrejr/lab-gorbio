Lab Terminal aka. Lab.Gor.bio is a small web project/blog with appealing front-end animations.
You will find the landing page(s) in this repo. 
I desinged it to execute on modern browsers only and therefore used modern CSS functionalities.
The animations where objects float around randomly with random dimentions and the tv static effects were JavaScript-intensive.
Geometry formulas were implemented to achieve the visually appealing interface.
Only fundemental front-end modern web technologies were used in this project (HTML, JS, CSS).

Resources used during development:
https://developer.mozilla.org/en-US/docs/Web/CSS (for finding needed functions and useful methods)
https://developer.mozilla.org/en-US/docs/Web/javascript (for finding needed functions and useful methods)
https://openai.com/chatgpt (GPT 3.5 and GPT 4 were heavily used to correct both logical and syntax errors regarding the geometric calculations in JavaScript)
https://bard.google.com/ (Bard was heavily used to check for up-to-date methods in CSS)


Examples:
Below variable returns the random new X coordinate considering it to be determined by a random new value which has to be not more than 800px no matter the screen size and if the screen size is less than 800, picks the smaller one which is the screen width in that case.

var newX = Math.random() * (Math.min(window.innerWidth, 800) - asteroid.offsetWidth);
    

Below variable "distance" defines the mathematical formula of distance which can be expressed as --> squareroot[(x2 - x1)^2 + (y2 - y1)^2].
   
var distance = Math.sqrt(Math.pow(newX - asteroidX, 2) + Math.pow(newY - asteroidY, 2));

Both of these example variables were fine-tuned by AI models mentioned in resources.
