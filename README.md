# Instruction for the test

This test has the objective to check you knowledge in CSS.

The .bubble (yellow box) elements are overflowing the .container (red box) element;

To resolve this test you should complete the following tasks:

 - **A** - Fix the issue of the .bubble element overflowing the .container. The .bubble element needs to be inside the .container element

> setting overflow of container div to hidden or auto will pull the paragraph element to the right of bubble div.

 - **B** - Display all texts vertically aligned with the .bubble element;

> setting `position: relative` on parent container and setting the absolute postion on the child (paragraph) would vertically align the paragraph inside its parent container. It is assumed that by virtically aligned, this task would require the text to be aligned in the middle. (`height: 25%; top: 0; bottom: 0;`) In order to align it to top we can simply remove `bottom: 0` and to align to bottom we can remove `top: 0`.

 - **C** - Show the .containers in 3 columns if the browser is bigger then 960px

> currently each container div (red border) will fill the row, therefore, we would have 4 rows and 1 column only. For this task we want to maintain the same layout with screen width less than 960px. wider than 960px we will have 3 columns and 2 rows.

 - **D** - Show the .containers in 2 columns if the browser is bigger then 600px

> with this task we will have 3 different layouts:

> 1. screen width less than 600px: 1 column and 4 rows

> 2. screen width more than 600px and less than 959px: 2 columns and 2 rows

> 3. screen wider than 960px: 3 columns and 2 rows

 - **E** - Change the width of .bubble elements to 90px if the browser is smaller than 600px

> this task will maitain the same layout as previous ones. The increase of bubble width by 30 pixels would require to add up 30px to paragraph left: `left: 125px;`

 - **F** - Display the texts in one line if the browser is smaller than 600px. If text is bigger than the .container display ellipsis

> this task will cover the following changes only for screen smaller than 600px:

> 1. show paragraph in one line (no wrapping): `white-space: nowrap;`

> 2. with text overflowing the container, don't show the overflowing portion and show ... instead (ellipsis): `overflow: hidden; text-overflow: ellipsis;`

> 3. calculate the dynamic width of .container:

> `width: calc(100% - 124px);` where 124px = .bubble width (90px) + .bubble left&right padding (20px) + .bubble left & right border (2px) + .cotainer left & right padding (10px) + .container left & right border (2px)

##TODO
 - **G** - Make a copy of the project and implement the same design without using float: [left | right]


At the end of you test you should submit 2 zip files
 - 1 containing the implementation of tasks A to F
 - 1 containing the implementation of all tasks
