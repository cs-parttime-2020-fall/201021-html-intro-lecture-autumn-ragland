# 20-10-21 HTML Intro Lecture

Today's lecture will focus on creating HTML files using multiple elements and linking to both local and online 
files.

### Set Up
- copy the assignment git url from github : `git clone COPIED URL`
- clone the assignment in the `html-css-basics` directory
- open the assignment in VSCode

### HTML
#### Create an HTML file
- create a new file from the explorer called index with the file extension `html`
- open the file and create the skeleton using the `html:5` shortcut
- update the document title to "Lecture"
- paste the text `welcome to my first web page` between the body tags
- open the file in the browser 
    - open a tab in chrome > `Ctrl + O` > choose the newly created html file
    - OR right click in the html file > choose `Open with Live Server`

#### Elements
- create an heading 1 `h1` element above the pasted text with your name between the tags
- wrap the pasted text in an heading 3 `h3` element
- create a paragraph `p` element with lorem ipsum text using the `lorem` shortcut
- create a container `div` element with three nested paragraph elements 
- __checkpoint__ : refresh the page in the browser and inspect using the `ctrl + shift + I` hotkey
- create a `header` element at the top of the page and move the heading 1 and heading 3 elements inside
- create a `footer` element at the bottom of the page with a nested paragraph element with today's date
- create an unordered list `ul` element with three list item `li` elements
- __checkpoint__ : refresh the page in the browser

#### Attributes
- below the container element, create an image `img` element to render [this image](https://images.unsplash.com/photo-1517694712202-14dd9538aa97?ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80) from the site [unsplash](https://unsplash.com/) using the source `src` attribute
- resize the image using the `height` attribute
- __checkpoint__ : refresh the page in the browser
- below the first image element, create another to render the local image provided in the repository using the source `src` attribute
- resize the image using the `height` attribute
- __checkpoint__ : refresh the page in the browser
- link to the [code crew site](https://www.code-crew.org/) using an anchor `a` element with the text `Code Crew`
- link to the html file `example` provided in the repository using an anchor element with the text `Example HTML File`
- specify the example html file to open in a new window using the `target` attribute
- __checkpoint__ : refresh the page in the browser

### Comments
- add comments above all container elements using the `ctrl + /` hotkey

### Push File Changes
- `git status` : check if file changes have been made at any point while pushing local changes
- `git add -A` : stage changes for commit
- `git commit -m "meaningful message"` : commit changes with appropriate message
- `git push` : reflect local changes remotely 

### Useful Extension
- Live Server : Launch a development local Server with live reload feature for static & dynamic pages

### Resources
[Concept Documentation Info on HTML](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/html.md)

[MDN HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

[MDN List of Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
