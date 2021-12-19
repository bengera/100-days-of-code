# 100 Days Of Code - Log

### Day 0: December 19, 2021 

**Today's Progress**: Set up the basic files for a Christmas lights project. Styled the lights and added on and off buttons to add and remove color from the lights. I added a ```forEach``` method to select each circle and change the colors of the lights to transparent. I copied and pasted this forEach method to remove the transparent styles using the removeAttribute method to reset the default colors of each circle. 

**Thoughts:** The aim of the project is to create a light display with 7 colored lights. I have started with a very basic HTML document with minimal styling and JavaScript. There was some trial and error with the Javascript but I managed to figure it out after some time. The way I have coded the on off buttons in JavaScript may not be the best method of changing multiple elements but it at least works for now and I have learned a few new things. 

```JavaScript
// TURN ON
document.querySelectorAll('.circle').forEach(circle => {
    btnOff.addEventListener('click', () => {
        circle.style.backgroundColor = "transparent";
        console.log('switch-off');
        
    })
    
})

// TURN OFF
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



