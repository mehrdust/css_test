# Instruction for the test

This test has the objective to check you knowledge in CSS.

The .bubble (yellow box) elements are overflowing the .container (red box) element;

To resolve this test you should complete the following tasks:

 - **A** - Fix the issue of the .bubble element overflowing the .container. The .bubble element needs to be inside the .container element

> setting overflow of container div to hidden or auto will pull the paragraph element to the right of bubble div.

 - **B** - Display all texts vertically aligned with the .bubble element;

> setting `position: relative` on parent container and setting the absolute postion on the child (paragraph) would vertically align the paragraph inside its parent container. It is assumed that by virtically aligned, this task would require the text to be aligned in the middle. (`height: 25%; top: 0; bottom: 0;`) In order to align it to top we can simply remove `bottom: 0` and to align to bottom we can remove `top: 0`.

##TODO
 - **C** - Show the .containers in 3 columns if the browser is bigger then 960px
 - **D** - Show the .containers in 2 columns if the browser is bigger then 600px
 - **E** - Change the width of .bubble elements to 90px if the browser is smaller than 600px
 - **F** - Display the texts in one line if the browser is smaller than 600px. If text is bigger than the .container display ellipsis
 - **G** - Make a copy of the project and implement the same design without using float: [left | right]


At the end of you test you should submit 2 zip files
 - 1 containing the implementation of tasks A to F
 - 1 containing the implementation of all tasks
