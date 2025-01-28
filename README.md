# cliDE
Building a Terminal-based Code Editor based on this [awesome guide](https://viewsourcecode.org/snaptoken/kilo/01.setup.html)

## Journal

- Setup the rawmode, where we turned off certain terminal settings for more control. We also setup a handy function that reverts our changes to the original settings everytime we quit our app.

- Then, we added a editorLoop, where we first refresh our screen and render the ui based on current editor state. We introduced a global state variable for the editor.
we start reading the key presses and start mapping functionalities. Particularly we try to read control characters like arrow keys, home, end, del, page up and page down keys.
By the end, we print a welcome screen and are able to navigate using the arrow keys.


