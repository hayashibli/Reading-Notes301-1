# Read: 02 - jQuery, Events, and The DOM

![image](https://miro.medium.com/max/4400/1*NeKYs9ypQ7jkalNxEX3t9Q.png)

**What Is JQuery?**

*jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript.*

**jQuery Features**

Following are the important features of jQuery.

- HTML manipulation

- DOM manipulation

- DOM element selection

- CSS manipulation

- Effects and Animations

- Utilities

- AJAX

- HTML event methods

- JSON Parsing

- Extensibility through plug-ins.

**jQuery Event Methods**

![image](https://cdn.educba.com/academy/wp-content/uploads/2019/10/jQuery-Events.png)

1.Event Handling

*To handle DOM events using jQuery methods, first get the reference of DOM element(s) using jQuery selector and invoke appropriate jQuery event method.*

`$('#saveBtn').click(function () {`
  `  alert('Save button clicked');`
`});`

`<input type="button" value="Save" id="saveBtn" />`

2. Event Object

*jQuery passes an event object to every event handler function. The event object includes important properties and methods for cross-browser consistency e.g. target, pageX, pageY, relatedTarget etc.*


`$('#saveBtn').click(function (eventObj) {`
    `alert('X =' + eventObj.pageX + ', Y =' + eventObj.pageY);`
`});`

`<input type="button" value="Save" id="saveBtn" />`

3.Hover Events
*jQuery provides various methods for mouse hover events e.g. mouseenter, mouseleave, mousemove, mouseover, mouseout and mouseup.*


`$('#myDiv').mouseenter(function (data) {`
       `     $(this).css('background-color','green');`
      `  });`

`$('#myDiv').mouseleave(function (data) {`
        `    $(this).css('background-color','red');`
      `  });`
       
`<div id="myDiv" style="width:100px;height:100px">`
`</div>`

4.Event Bubbling.

`$('div').click(function (event) {`
 `   alert( event.target.tagName + ' clicked');`
`});`

`<div>`
    `<p>`
       ` <span>This is span.</span>`
    `</p>`
`</div>`

## Pair Programming.

![image](https://miro.medium.com/max/10116/1*WhUkymHMzeMTlzDm1tEiEQ.jpeg)

Pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

Pair programming involves two roles : The Driver and the Navigator. **The Driver** is the programmer who is typing and the only one whose hands are on the keyboard. **The Navigator** uses their words to guide the driver but dose not provide ant direct input to the computer.

### Why pair programming?

- **Greater efficiency** : when ttwo people focus on the same code base, it is easier to catch mistakes in the making, it takes slightly longer, but produces higher-quality code that dosen't require later effort in roubleshooting and debugging (let alone exposing users to a broken product).

- **Engaged collaboration** : When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.

