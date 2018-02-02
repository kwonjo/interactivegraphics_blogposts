# Interactive graphics NOTES ON WEEK 2 & 3

## Week 2
## January 19, 2018

###Creating libraries 
Jos-MacBook-Pro:p5_hello_world jkwon$ touch index.html
Jos-MacBook-Pro:p5_hello_world jkwon$ touch main.css
Jos-MacBook-Pro:p5_hello_world jkwon$ mkdir libraires

*	Websites (3 languages): 
HTML-words and images, CSS (Cascading style sheet), Javascript (action)

1.	doc-basic html written out
2.	index.html -> it's the main…other pages are communicating with index

3.	main.css title
#title{
    color: red;
}

4.	sketch.js
```javascript
function setup(){
    createCanvas(800, 800);
}

function draw(){
    fill(255, 0, 0);
    rect(400, 400, 200, 200);
    ellipse(400, 100, 20, 20);
}
```
5.	Go live

"	Questions
1.	several sketches?
-iframes
-Instantiation Cases https://github.com/processing/p5.js/wiki/Instantiation-Cases

2.	Sketches in function draw() later part seems to override the previous shapes. How can I stop that? All of the examples only have one shape in the function draw() so…
-3D overrides 2D
	-backgorund() should only be written only once!
    background(0, 191, 255);


[my_code.ino](code/my_code.ino)

4. Javascript
```javascript

```



  
