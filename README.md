| [Event Keycodes](https://github.com/lana-20/50_Projects_in_50_Days/tree/main/KeyBoxes) | [Live Demo](https://lana-20.github.io/event-keycodes/) |
|----|----|

In this project, I am building an application that shows you the key code and the code for any key on your keyboard.

When you come to the page, it says "Press any key to get the keyCode".
If you hit "l", it will show the actual key "l", key code "76", and the code "KeyL".
You can hit a, 9, Tab, or any other key on the keyboard.
It's really simple, but it can  be useful if you need to get the code for something.

.keyCode is actually deprecated, per https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/keyCode.
.keyCode does still work. If it doesn't work for you at the time of viewing this repository,
you can get rid of this box and just display the code.

MDN documentation recommends to use .code from https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/code.
.code property is useful when you want to handle keys based on their physical positions on the input device 
rather than the characters associated with those keys; this is especially common when writing code to handle 
input for games that simulate a gamepad-like environment using keys on the keyboard.
