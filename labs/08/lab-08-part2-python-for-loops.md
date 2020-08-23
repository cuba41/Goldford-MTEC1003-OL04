---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
<!-- http://www.iangoodfellow.com/blog/jekyll/markdown/tex/2016/11/07/latex-in-markdown.html -->

# Lab 8 / Part 2: Python For Loops   

#### C O N T E N T S  
<a href="#setup">Setup for Python3</a>  
1. <a href="#js-stuff">Recreating JavaScript For Loop Exercises in Python</a>  
2. <a href="#dictionary">Parsing a Dictionary</a>  

* * *

<a id="setup"></a>
## Setup for Python3   

Let's be sure your Terminal session will run Python3 (instead of the prepackaged Python 2.7.x) when calling `python` on the command line. We can create an "alias" for python3 by running the following command:  

  {% highlight terminal %}
  $ alias python=/usr/local/bin/python3 {% endhighlight %}

Alternatively, you can simply run `python3` in the Terminal instead of `python`, but this gets annoying after awhile.  

Once you've done this, you're all set.  

* * *  

<a id="js-stuff"></a>
## 1. Recreating JavaScript For Loop Exercises in Python    

_**NOTE:** This section starts with the same 5 exercises from Lab 8 / Part 1. If you feel more comfortable with Python rather than JavaScript, you can start with this section in Python and then complete the JavaScript exercises last. Either way, click on the link below for Lab 8 / Part 1 to see the details for each program._  

In [Lab 8 / Part 1](/Goldford-MTEC1003-OL04/labs/08/lab-08-part1-javascript-for-loops.html){:target="_blank"}, you made 3 programs that returned different results depending on user input:  

  1. tens.html  
  2. party.html  
  3. average.html  
  4. largest.html
  5. fizzbuzz.html

Using your own knowledge of Python, translate your 3 HTML/JavaScript programs into Python, and save them as: tens.py, party,py, average.py, largest.py, and fizzbuzz.py.  

Make sure they're in your **/lab-08-for-loops** repository!

Now we just have to **test** our python scripts by running them on the command line.

Back in Terminal, simply type `python`, then a space, and then drag-and-drop one of your new files, e.g. **fizzbuzz.py**, onto the Terminal window (**remember:** this will quickly create a `full path` to your file on the command line!). Run the command by hitting `enter`, of course.

Make sure your file is included in your **/lab-08-for-loops** repo, and don't forget to **add**, **commit**, and **push** your changes. Use your [_git cheatsheet_ (from lab 3)](/Goldford-MTEC1003-OL04/labs/03/lab-03-git-intro.html){:target="_blank"} if you need it.  

* * *   

<a id="dictionary"></a>
## 2. Parsing a Dictionary  

Using your text editor (e.g. Atom, Sublime Text, etc.), create a new file called **dictionary.py** in your repository directory: **~/Desktop/myClasses/mtec1003/lab-08-for-loops/**.  

Copy the following into the top line of your new file:  

  {% highlight py %} myData = {"effective top tube length": 515, "seat tube length": 500, "seat tube angle": 74.4, "head tube angle": 70.5, "stack": 513, "reach": 367, "standover height": 755} {% endhighlight %}

Continue typing your code so that your program reads in this data and:
  1. **concatenates** + **prints** a series of **key** and **value** pairs _for each_ of its **key/value pairs**,  
  2. **collects** all **keys** into one list and **prints** it,  
  3. and **collects** all values into another list and **prints** it.  

Save your code, make sure your **dictionary.py** file is included in your **/lab-08-for-loops** folder, and don't forget to **add**, **commit**, and **push** your changes. Use your [_git cheatsheet_ (from lab 3)](/Goldford-MTEC1003-OL04/labs/03/lab-03-git-intro.html){:target="_blank"} if you need it.  

At the end of this lab, your **/lab-08-for-loops** folder should contain the following files:  
  * tens.html  
  * tens.py  
  * party.html  
  * party.py  
  * average.html  
  * average.py  
  * largest.html  
  * largest.py  
  * fizzbuzz.html  
  * fizzbuzz.py  

* * *