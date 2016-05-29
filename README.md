# Instruction for the test

This test has the objective to check you knowledge in CSS.

The .bubble (yellow box) elements are overflowing the .container (red box) element;

To resolve this test you should complete the following tasks:

 - **A** - Fix the issue of the .bubble element overflowing the .container. The .bubble element needs to be inside the .container element
 - **B** - Display all texts vertically aligned with the .bubble element;
 - **C** - Show the .containers in 3 columns if the browser is bigger then 960px
 - **D** - Show the .containers in 2 columns if the browser is bigger then 600px
 - **E** - Change the width of .bubble elements to 90px if the browser is smaller than 600px
 - **F** - Display the texts in one line if the browser is smaller than 600px. If text is bigger than the .container display ellipsis
 - **G** - Make a copy of the project and implement the same design without using float: [left | right]


At the end of you test you should submit 2 zip files
 - 1 containing the implementation of tasks A to F
 - 1 containing the implementation of all tasks


# Testing the tasks

Each task is done inside a separate branch. So there are 7 branches: task_A, task_B, task_C, ..., task_G

### Create folder

`mkdir css_challenge`

`cd css_challenge`

### Test each task individually
checkout to a given branch to see the changes under that particular task, for example for task B:

`cd css_challenge`

`rm -rf css_test`

`git clone -b task_B https://github.com/mehrdust/css_test`

`cd css_test`

### Check tasks A-F
Since branches task_A to task_F are created sequentially, to see the outcome of tasks A-F simply checkout to task_F:

`cd css_challenge`

`rm -rf css_test`

`git clone -b task_F https://github.com/mehrdust/css_test`

`cd css_test`

### Check task G


`cd css_challenge`

`rm -rf css_test`

`git clone -b task_G https://github.com/mehrdust/css_test`

`cd css_test`

### test the web page using python's SimpleHTTPServer

run the following command and point to <ip_address>:8000 on your browser:

`python -m SimpleHTTPServer 8000`
