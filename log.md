# 100 Days Of Code - Log

### Day 01: December 19, 2021 

**Today's Progress**: Set up the basic files for a Christmas lights project. Styled the lights and added on and off buttons to add and remove color from the lights. I added a ```forEach``` method to select each circle and change the colors of the lights to transparent. I copied and pasted this forEach method to remove the transparent styles using the removeAttribute method to reset the default colors of each circle. 

**Thoughts:** The aim of the project is to create a light display with 7 colored lights. I have started with a very basic HTML document with minimal styling and JavaScript. There was some trial and error with the Javascript but I managed to figure it out after some time. The way I have coded the on off buttons in JavaScript may not be the best method of changing multiple elements but it at least works for now and I have learned a few new things. 

```JavaScript
// TURN OFF
document.querySelectorAll('.circle').forEach(circle => {
    btnOff.addEventListener('click', () => {
        circle.style.backgroundColor = "transparent";
        console.log('switch-off');
        
    })
    
})

// TURN ON
document.querySelectorAll('.circle').forEach(circle => {
    btnOn.addEventListener('click', () => {
        circle.removeAttribute('style');
        console.log('switch-on');
        
    })
```
**Link(s) to work:** [Christmas Lights](https://github.com/bengera/christmas-lights)

**Link(s) to resources:** 
\
[forEach method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
\
[How to add an event listener to multiple elements in JavaScript](https://flaviocopes.com/how-to-add-event-listener-multiple-elements-javascript/)
\
[Christmas Lights app-idea](https://github.com/fahamidur/app-ideas/blob/master/Projects/1-Beginner/Christmas-Lights-App.md)


### Day 02: December 20, 2021 

**Today's Progress**: Added pulsing animation to one of the Christmas lights and wrote some simple JS to turn it off.

**Thoughts:** I started the day by attempting some code wars exercises. After trying a few different exercises I realised that I need to review a lot of the basics and methods of JS.
I've been having difficulty with the Christmas Lights project, I need to figure out how I can select multiple classes and change the animation style to none. I have only managed to 
get this working for one light. I don't want my code to become bloated so I will keep looking for a new method so I don't have to write variables for all of the lights.
Looking at some examples of similar projects online has helped me but I am trying to find my own way of doing it.
It is fairly frustrating to fail a lot of times throughout the day, but I suppose it is a necessary part of learning, I'm at least learning about what doesn't work.

```JavaScript
const redLight = document.querySelector('.red')

// TURN OFF
document.querySelectorAll('.circle').forEach(circle => {
    btnOff.addEventListener('click', () => {
        circle.style.backgroundColor = "transparent";
        redLight.style.animation = 'none';
        console.log('switch-off');

    })

})
```
**Link(s) to work:** [Christmas Lights](https://github.com/bengera/christmas-lights)


### Day 03: December 21, 2021 

**Today's Progress**: Went through some codewars challenges, managed to complete a very basic one with if else statements. 
\ Learnt about how  ```split(' ')``` can divide a string into substrings, in this case each word could be separated. Without the gap it would be each letter.
Also learnt some things about the ```reduce``` method but still not it is still not entirely clear to me how it works.
Refreshed my memory of the ternary operator. ```condition ? exprIfTrue : exprIfFalse```

**Thoughts:** I see how important it is to keep coding everyday, a lot of things I have read about or even coded myself can be forgotten very quickly and a lot of time
is spent refreshing my memory on things I have already studied. 
I may need to organise my day a bit better. I need to have a clear goal to work on and projects that I want to work on. There are many projects that I have started but not completed entirely.
I need to make sure I see through each one.

```JavaScript
var age = 26;
var beverage = (age >= 21) ? "Beer" : "Juice";
console.log(beverage); // "Beer"

```


### Day 04: December 22, 2021 

**Today's Progress**: Fixed some bugs on my portfolio. Added more aniamtion to Christmas Lights project. 

**Thoughts:** I have struggled to work out of things in JavaScript by myself, I think now I may do some tutorials and then try to create something on my own after understanding how 
certain things work. I feel like I'm stabbing in the dark most of time and making the wildest guesses. My portfolio is okay for hosting a few projects but I would like to remake it
it a more attractive and interesting way. Tommorow I will do some tutorials and try to learn some new things. This worked very well when I was making my ESL site.


### Day 05: December 25, 2021 

**Today's Progress**: Missed a couple of days for Christmas. To get back into things I started a new Front end mentor challenge. I created a small component card. It is close to finished.

**Thoughts:** I really enjoy setting up new projects and doing HTML and CSS. It is good to practice and I always learn something new with each project. It may be a good idea
to make a lot of little projects and build components or functions in isolation. When I'm more confident I can put all of these things into a bigger project.


**Link(s) to work:** [Christmas Lights](https://github.com/bengera/nft-card)





