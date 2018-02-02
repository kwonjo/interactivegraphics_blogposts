# interactivegraphics_notes
## Week 2
## January 19, 2018
	
Creating libraries 
Jos-MacBook-Pro:p5_hello_world jkwon$ touch index.html
Jos-MacBook-Pro:p5_hello_world jkwon$ touch main.css
Jos-MacBook-Pro:p5_hello_world jkwon$ mkdir libraires

"	Websites (3 languages): 
HTML-words and images, CSS (Cascading style sheet), Javascript (action)

1.	doc-basic html written out
2.	index.html -> it's the main…other pages are communicating with index

3.	main.css title
#title{
    color: red;
}

4.	sketch.js
function setup(){
    createCanvas(800, 800);
}

function draw(){
    fill(255, 0, 0);
    rect(400, 400, 200, 200);
    ellipse(400, 100, 20, 20);
}
5.	Go live

"	Questions
1.	several sketches?
-iframes
-Instantiation Cases https://github.com/processing/p5.js/wiki/Instantiation-Cases

2.	Sketches in function draw() later part seems to override the previous shapes. How can I stop that? All of the examples only have one shape in the function draw() so…
-3D overrides 2D
	-backgorund() should only be written only once!
    background(0, 191, 255);

## Week 2
## January 24 & 26, 2018

"	How to put code on github
-download git
-what is git? Keep track
git init
git status : track files
git add . : all of the files
git commit -m "added circle"
git remote add origin https://github.com/kwonjo/helloworld_interactivegraphics.git
git push -u origin master : upload to github

git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/kwonjo/interactivegraphics_project1.git
git push -u origin master


git status
git add .
git commit -m "added sth"
git push

	-branch: new ideas from the main idea
Review
"	Coordinate system
function setup(){
createCanvas(x,y); ->size of the canvas
} 
where we set up the variables, canvas, artist's set up their canvas and everything in this place
pixel scale
	


(0,0)
	Working here all the time
	rect(x ,y, width, height)
rect(x,y,w,h,[tl],[tr],[br],[bl])
rect(x,y,w,h,[detailX],[detailY])
	ellipse(x,y,w,[h])
"	Color system
fill(R, G, B)
fill(Black to White)
