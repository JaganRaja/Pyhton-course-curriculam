---


---

<blockquote>
<pre><code>                   jk
</code></pre>
</blockquote>
<h1 id="python-programming">Python Programming</h1>
<p>Python has simple easy-to-use syntax and it is a general-purpose language. It has wide range of applications from Web development (like: Django and Bottle), scientific and mathematical computing (Orange, SymPy, NumPy) to desktop graphical user Interfaces (Pygame, Panda3D).</p>
<h3 id="features-of-python-programming">Features of Python Programming</h3>
<ol>
<li><strong>A simple language which is easier to learn</strong><br>
Python has a very simple and elegant syntax. It’s much easier to read and write Python programs compared to other languages like: C++, Java, C#. Python makes programming fun and allows you to focus on the solution rather than syntax.<br>
If you are a newbie, it’s a great choice to start your journey with Python.</li>
<li><strong>Free and open-source</strong><br>
You can freely use and distribute Python, even for commercial use. Not only can you use and distribute softwares written in it, you can even make changes to the Python’s source code.<br>
Python has a large community constantly improving it in each iteration.</li>
<li><strong>Portability</strong><br>
You can move Python programs from one platform to another, and run it without any changes.<br>
It runs seamlessly on almost all platforms including Windows, Mac OS X and Linux.</li>
<li><strong>Extensible and Embeddable</strong><br>
Suppose an application requires high performance. You can easily combine pieces of C/C++ or other languages with Python code.<br>
This will give your application high performance as well as scripting capabilities which other languages may not provide out of the box.</li>
<li><strong>A high-level, interpreted language</strong><br>
Unlike C/C++, you don’t have to worry about daunting tasks like memory management, garbage collection and so on.<br>
Likewise, when you run Python code, it automatically converts your code to the language your computer understands. You don’t need to worry about any lower-level operations.</li>
<li><strong>Large standard libraries to solve common tasks</strong><br>
Python has a number of standard libraries which makes life of a programmer much easier since you don’t have to write all the code yourself. For example: Need to connect MySQL database on a Web server? You can use MySQLdb library using  <code>import MySQLdb</code>  .<br>
Standard libraries in Python are well tested and used by hundreds of people. So you can be sure that it won’t break your application.</li>
<li><strong>Object-oriented</strong><br>
Everything in Python is an object. Object oriented programming (OOP) helps you solve a complex problem intuitively.<br>
With OOP, you are able to divide these complex problems into smaller sets by creating objects.</li>
</ol>
<h3 id="applications-of-python">Applications of Python</h3>
<p><strong>Web Applications</strong></p>
<p>Some of the popular platforms for creating Web Apps are: Django, Flask, Pyramid, Plone, Django CMS.</p>
<p>Sites like Mozilla, Reddit, Instagram and PBS are written in Python.</p>
<p><strong>Scientific and Numeric Computing</strong></p>
<p>There are numerous libraries available in Python for scientific and numeric computing. There are libraries like: SciPy and NumPy that are used in general purpose computing. And, there are specific libraries like: EarthPy for earth science, AstroPy for Astronomy and so on.</p>
<p>Also, the language is heavily used in <strong>machine learning, data mining and deep learning</strong>.</p>
<p><strong>Creating software Prototypes</strong></p>
<p>Python is a great language for creating prototypes. For example: You can use Pygame (library for creating games) to create your game’s prototype first. If you like the prototype, you can use language like C++ to create the actual game.</p>
<h4 id="few-important-things-to-remember">Few Important Things to Remember</h4>
<p>To represent a statement in Python, newline (enter) is used. The use of semicolon at the end of the statement is optional (unlike languages like C/C++, PHP). In fact, it’s recommended to omit semicolon at the end of the statement in Python.</p>
<p>Instead of curly braces { }, indentations are used to represent a block.</p>
<pre><code>  im_a_parent:
	    im_a_child:
	        im_a_grand_child
	    im_another_child:
        im_another_grand_child
</code></pre>
<h1 id="curriculum">Curriculum</h1>
<h3 id="python-introduction">Python Introduction</h3>
<ul>
<li>Getting started</li>
<li>Keywords and Identifier</li>
<li>Statments and Comments</li>
<li>Python variable</li>
<li>Python Datatypes</li>
<li>Python Type Conversion</li>
<li>Python I/O and Import</li>
<li>Python Operators</li>
<li>Python Variable Scope</li>
</ul>
<h3 id="python-flowcontrol"><strong>Python FlowControl</strong></h3>
<ul>
<li>Python if…else</li>
<li>Python for Loop</li>
<li>Python while Loop</li>
<li>Python break and continue</li>
<li>Python pass</li>
</ul>
<h3 id="python-functions">Python Functions</h3>
<ul>
<li>Python Function</li>
<li>Function Argument</li>
<li>Anonymous Function</li>
<li>Python Global keyword</li>
<li>Python Modules</li>
</ul>
<h3 id="python-datatypes">Python Datatypes</h3>
<ul>
<li>Python Numbers</li>
<li>Python List</li>
<li>Python Tuple</li>
<li>Python String</li>
<li>Python Set</li>
<li>Python Dictionary</li>
</ul>
<h3 id="python-files">Python Files</h3>
<ul>
<li>Python File Operation</li>
<li>Python Directory</li>
<li>Python Exception</li>
<li>Exception Handling</li>
<li>User-defined Exception</li>
</ul>
<h3 id="python-object-and-class">Python Object and Class</h3>
<ul>
<li>Python OOP</li>
<li>Python Class</li>
<li>Python Inheritance</li>
<li>Multiple Inheritance</li>
<li>Operator Overloading</li>
</ul>
<h2 id="lets-start-with-python">Lets Start with Python</h2>
<p>We are going to see all the above mentioned curriculum briefly…</p>
<h4 id="getting-started">Getting started:</h4>
<p>Learn how to install Python on your operating system and different ways to run it. Also, you will learn to write “Hello, World!” program in Python</p>
<p>Python is a cross-platform programming language, meaning, it runs on multiple platforms like Windows, Mac OS X, Linux, Unix and has even been ported to the Java and .NET virtual machines. It is free and open source.</p>
<h4 id="installation">Installation:</h4>
<p>Go to  <a href="https://www.python.org/downloads" title="Get Python for Mac">Download Python</a>  page on the official site and click  <strong>Download Python 3.7.2</strong> (As it is getting updated, you may see different version name).</p>
<p><strong>To check python installed:</strong><br>
Open command prompt then type “python” in it.  If python installed successfully, you can see the python version.</p>
<p><strong>Writing your First Python Program:</strong></p>
<ul>
<li>
<p>Immediate mode:<br>
Typing <code>python</code> in the command line will invoke the interpreter in immediate mode. We can directly type in Python expressions and press enter to get the output.<br>
To exit this mode type  <code>exit()</code>  or  <code>quit()</code>  and press enter.</p>
<pre><code> &gt;&gt;&gt;
</code></pre>
</li>
<li>
<p>Integrated Development Environment (IDE):<br>
We can use any text editing software to write a Python script file.<br>
We just need to save it with the  <code>.py</code>  extension. But using an IDE can make our life a lot easier. IDE is a piece of software that provides useful features like code hinting, syntax highlighting and checking, file explorers etc. to the programmer for application development.<br>
Example: Sublime Text3, Atom, Thonny, Pycharm, Visual Studio Code etc<br>
Now that we have Python up and running, we can continue on to write our first Python program.<br>
Type the following code in any text editor or an IDE and save it as<br>
“<a href="http://helloWorld.py">helloWorld.py</a>”<br>
<code>print("Hello world!")</code></p>
</li>
</ul>
<h2 id="python-keywords-and-identifier">Python Keywords and Identifier</h2>
<h3 id="python-keywords">Python Keywords</h3>
<p>You will learn about keywords (reserved words in Python) and identifiers (name given to variables, functions etc).</p>
<p>Keywords are the reserved words in Python.</p>
<p>We cannot use a keyword as  variable name,  function name or any other identifier. They are used to define the syntax and structure of the Python language.</p>

<table>
<thead>
<tr>
<th>Keyword</th>
<th>Keyword</th>
<th>Keyword</th>
<th>Keyword</th>
<th>Keyword</th>
</tr>
</thead>
<tbody>
<tr>
<td>False</td>
<td>class</td>
<td>finally</td>
<td>is</td>
<td>return</td>
</tr>
<tr>
<td>None</td>
<td>continue</td>
<td>for</td>
<td>lambda</td>
<td>try</td>
</tr>
<tr>
<td>True</td>
<td>def</td>
<td>from</td>
<td>nonlocal</td>
<td>while</td>
</tr>
<tr>
<td>and</td>
<td>del</td>
<td>global</td>
<td>not</td>
<td>with</td>
</tr>
<tr>
<td>as</td>
<td>elif</td>
<td>if</td>
<td>or</td>
<td>yield</td>
</tr>
<tr>
<td>assert</td>
<td>else</td>
<td>import</td>
<td>pass</td>
<td></td>
</tr>
<tr>
<td>break</td>
<td>except</td>
<td>in</td>
<td>False</td>
<td></td>
</tr>
</tbody>
</table><h3 id="python-identifiers">Python Identifiers</h3>
<p>Identifier is the name given to entities like class, functions, variables etc. in Python. It helps differentiating one entity from another.</p>
<h3 id="rules-for-writing-identifiers">Rules for writing identifiers</h3>
<ol>
<li>
<p>Identifiers can be a combination of letters in lowercase (a to z) or uppercase (A to Z) or digits (0 to 9) or an underscore (_). Names like <code>myClass</code>,  <code>var_1</code>  and  <code>print_this_to_screen</code>, all are valid example.</p>
</li>
<li>
<p>An identifier cannot start with a digit.  <code>1variable</code>  is invalid, but  <code>variable1</code>  is perfectly fine.</p>
</li>
<li>
<p>Keywords cannot be used as identifiers.</p>
<pre><code>
&gt;&gt;&gt; global = 1
  File "&lt;interactive input&gt;", line 1
    global = 1
           ^
SyntaxError: invalid syntax
</code></pre>
</li>
<li>
<p>We cannot use special symbols like !, @, #, $, % etc. in our identifier.</p>
<pre><code>
&gt;&gt;&gt; a@ = 0
  File "&lt;interactive input&gt;", line 1
    a@ = 0
     ^
SyntaxError: invalid syntax
</code></pre>
</li>
<li>
<p>Identifier can be of any length.</p>
</li>
</ol>
<h3 id="things-to-care-about">Things to care about</h3>
<p>Python is a case-sensitive language. This means,  <code>Variable</code>  and  <code>variable</code>are not the same. Always name identifiers that make sense.</p>
<p>While,  <code>c = 10</code>  is valid. Writing  <code>count = 10</code>  would make more sense and it would be easier to figure out what it does even when you look at your code after a long gap.</p>
<p>Multiple words can be separated using an underscore,  <code>this_is_a_long_variable</code>.</p>
<p>We can also use camel-case style of writing, i.e., capitalize every first letter of the word except the initial word without any spaces. For example:  <code>camelCaseExample</code></p>
<h2 id="python-statement-indentation-and-comments">Python Statement, Indentation and Comments</h2>
<p>In this article, you will learn about Python statements, why indentation is important and use of comments in programming.</p>
<h3 id="python-statement">Python Statement</h3>
<p>Instructions that a Python interpreter can execute are called statements</p>
<pre><code>a = 1
</code></pre>
<p>Multi-line statement:</p>
<pre><code>a = 1 + 2 + 3 + \
  4 + 5 + 6 + \
  7 + 8 + 9
</code></pre>
<p>his is explicit line continuation. In Python, line continuation is implied inside parentheses ( ), brackets [ ] and braces { }</p>
<pre><code>a = (1 + 2 + 3 +
    4 + 5 + 6 +
    7 + 8 + 9)
</code></pre>
<h3 id="python-indentation">Python Indentation</h3>
<p>Most of the programming languages like C, C++, Java use braces { } to define a block of code. Python uses indentation.</p>
<p>A code block (body of a function, loop etc) starts with indentation and ends with the first unindented line. The amount of indentation is up to you, but it must be consistent throughout that block.</p>
<p>Generally four whitespaces are used for indentation and is preferred over tabs. Here is an example.</p>
<pre><code>for i in range(1,11):
    print(i)
    if i == 5:
        break
</code></pre>
<p>Incorrect indentation will result into  <code>IndentationError</code>.</p>
<h3 id="python-comments">Python Comments</h3>
<p>It describes what’s going on inside a program so that a person looking at the source code does not have a hard time figuring it out. You might forget the key details of the program you just wrote in a month’s time. So taking time to explain these concepts in form of comments is always fruitful.<br>
In Python, we use the hash (#) symbol to start writing a comment.</p>
<pre><code>#This is a comment
#print out Hello
print('Hello')
</code></pre>
<h3 id="multi-line-comments">Multi-line comments</h3>
<p>We can achieve Multiline comments by using triple quotes, either <code>'''</code> or <code>"""</code></p>
<pre><code>"""This is also a
perfect example of
multi-line comments"""
</code></pre>
<h2 id="python-variables-constants">Python Variables, Constants</h2>
<h3 id="variable">Variable</h3>
<p>a variable is a named location used to store data in the memory. Each variable must have a unique name called identifier.<br>
Non technically, you can suppose variable as a bag to store books in it and those books can be replaced at anytime.</p>
<h3 id="declaring-variables-in-python">Declaring Variables in Python</h3>
<p>In Python, variables do not need declaration to reserve memory space. The “variable declaration” or “variable initialization” happens automatically when we assign a value to a variable.</p>
<h3 id="assigning-value-to-a-variable-in-python">Assigning value to a Variable in Python</h3>
<p>You can use the assignment operator <code>=</code> to assign the value to a variable.</p>
<pre><code>website = "Apple.com"

print(website)
</code></pre>
<h4 id="changing-value-of-a-variable">Changing value of a variable</h4>
<pre><code>website = "Apple.com"

# assigning a new variable to website
website = "Programiz.com"

print(website)
</code></pre>
<h4 id="assigning-multiple-values-to-multiple-variables">Assigning multiple values to multiple variables</h4>
<pre><code>a, b, c = 5, 3.2, "Hello"

print (a)
print (b)
print (c)
</code></pre>
<h3 id="constants">Constants</h3>
<p>A constant is a type of variable whose value cannot be changed. It is helpful to think of constants as containers that hold information which cannot be changed later.</p>
<p>Non technically, you can think of constant as a bag to store some books and those books cannot be replaced once placed inside the bag.</p>
<h3 id="assigning-value-to-a-constant-in-python">Assigning value to a constant in Python</h3>
<p>In Python, constants are usually declared and assigned on a module. Here, the module means a new file containing variables, functions etc which is imported to main file. Inside the module, constants are written in all capital letters and underscores separating the words.</p>
<h4 id="declaring-and-assigning-value-to-a-constant">Declaring and assigning value to a constant</h4>
<p>Create a <a href="http://constant.py">constant.py</a></p>
<pre><code>PI = 3.14
GRAVITY = 9.8
</code></pre>
<p>Create a <a href="http://main.py">main.py</a></p>
<pre><code>import constant

print(constant.PI)
print(constant.GRAVITY)
</code></pre>
<h2 id="python-data-types">Python Data Types</h2>
<p>In this tutorial, you will learn about different data types you can use in Python.</p>
<p>Every value in Python has a datatype. Since everything is an object in Python programming, data types are actually classes and variables are instance (object) of these classes.</p>
<h3 id="python-numbers">Python Numbers</h3>
<p>Integers, floating point numbers and complex numbers falls under  Python numbers category. They are defined as  <code>int</code>,  <code>float</code>  and  <code>complex</code>  class in Python.</p>
<p>We can use the  <code>type()</code>  function to know which class a variable or a value belongs to and the  <code>isinstance()</code>  function to check if an object belongs to a particular class.</p>
<pre><code>a = 5
print(a, "is of type", type(a))

a = 2.0
print(a, "is of type", type(a))

a = 1+2j
print(a, "is complex number?", isinstance(1+2j,complex))
</code></pre>
<p>Output:</p>
<pre><code>5 is of type &lt;class 'int'&gt;
2.0 is of type &lt;class 'float'&gt;
(1+2j) is complex number? True
5 is of type &lt;class 'int'&gt;
2.0 is of type &lt;class 'float'&gt;
(1+2j) is complex number? True
</code></pre>
<h3 id="python-list">Python List</h3>
<p>List is an ordered sequence of items. It is one of the most used datatype in Python and is very flexible. All the items in a list do not need to be of the same type.</p>
<h4 id="how-to-create-a-list">How to create a list?</h4>
<p>In Python programming, a list is created by placing all the items (elements) inside a square bracket [ ], separated by commas.</p>
<p>It can have any number of items and they may be of different types (integer, float, string etc.).</p>
<pre><code># empty list
my_list = []

# list of integers
my_list = [1, 2, 3]

# list with mixed datatypes
my_list = [1, "Hello", 3.4]
</code></pre>
<p>Also, a list can even have another list as an item. This is called nested list.</p>
<pre><code>### nested list
my_list = ["mouse", [8, 4, 6], ['a']]
</code></pre>
<h3 id="how-to-access-elements-from-a-list">How to access elements from a list?</h3>
<p>There are various ways in which we can access the elements of a list.</p>
<h3 id="list-index">List Index</h3>
<p>We can use the index operator [] to access an item in a list. Index starts from 0. So, a list having 5 elements will have index from 0 to 4.<br>
Trying to access an element other that this will raise an  <code>IndexError</code>. The index must be an integer. We can’t use float or other types, this will result into  <code>TypeError</code>.<br>
Nested list are accessed using nested indexing.</p>
<pre><code>my_list = ['p','r','o','b','e']
# Output: p
print(my_list[0])

# Output: o
print(my_list[2])

# Output: e
print(my_list[4])

# Error! Only integer can be used for indexing
# my_list[4.0]

# Nested List
n_list = ["Happy", [2,0,1,5]]

# Nested indexing

# Output: a
print(n_list[0][1])    

# Output: 5
print(n_list[1][3])
</code></pre>
<h3 id="negative-indexing">Negative indexing</h3>
<pre><code>my_list = ['p','r','o','b','e']

# Output: e
print(my_list[-1])

# Output: p
print(my_list[-5])
</code></pre>
<h3 id="how-to-slice-lists-in-python">How to slice lists in Python?</h3>
<pre><code>my_list = ['p','r','o','g','r','a','m','i','z']
# elements 3rd to 5th
print(my_list[2:5])

# elements beginning to 4th
print(my_list[:-5])

# elements 6th to end
print(my_list[5:])

# elements beginning to end
print(my_list[:])
</code></pre>
<h4 id="how-to-change-or-add-elements-to-a-list">How to change or add elements to a list?</h4>
<p>List are mutable, meaning, their elements can be changed unlike string, tuple</p>
<p>We can use assignment operator (=) to change an item or a range of items.</p>
<pre><code># mistake values
odd = [2, 4, 6, 8]

# change the 1st item    
odd[0] = 1            

# Output: [1, 4, 6, 8]
print(odd)

# change 2nd to 4th items
odd[1:4] = [3, 5, 7]  

# Output: [1, 3, 5, 7]
print(odd)                   
</code></pre>
<p>We can add one item to a list using <code>append()</code> method or add several items using <code>extend()</code>method.</p>
<pre><code>odd = [1, 3, 5]

odd.append(7)

# Output: [1, 3, 5, 7]
print(odd)

odd.extend([9, 11, 13])

# Output: [1, 3, 5, 7, 9, 11, 13]
print(odd)
</code></pre>
<p>We can also use + operator to combine two lists. This is also called concatenation.</p>
<p>The * operator repeats a list for the given number of times.</p>
<pre><code>odd = [1, 3, 5]

# Output: [1, 3, 5, 9, 7, 5]
print(odd + [9, 7, 5])

#Output: ["re", "re", "re"]
print(["re"] * 3)
</code></pre>
<p>Furthermore, we can insert one item at a desired location by using the method <code>insert()</code> or insert multiple items by squeezing it into an empty slice of a list.</p>
<pre><code>odd = [1, 9]
odd.insert(1,3)

# Output: [1, 3, 9] 
print(odd)

odd[2:2] = [5, 7]

# Output: [1, 3, 5, 7, 9]
print(odd)
</code></pre>
<h4 id="how-to-delete-or-remove-elements-from-a-list">How to delete or remove elements from a list?</h4>
<pre><code>my_list = ['p','r','o','b','l','e','m']

# delete one item
del my_list[2]

# Output: ['p', 'r', 'b', 'l', 'e', 'm']     
print(my_list)

# delete multiple items
del my_list[1:5]  

# Output: ['p', 'm']
print(my_list)

# delete entire list
del my_list       

# Error: List not defined
print(my_list)
</code></pre>
<p>We can use  <code>remove()</code>  method to remove the given item or  <code>pop()</code>  method to remove an item at the given index.</p>
<p>The  <code>pop()</code>  method removes and returns the last item if index is not provided. This helps us implement lists as stacks (first in, last out data structure).</p>
<p>We can also use the  <code>clear()</code>  method to empty a list.</p>
<pre><code>my_list = ['p','r','o','b','l','e','m']
my_list.remove('p')

# Output: ['r', 'o', 'b', 'l', 'e', 'm']
print(my_list)

# Output: 'o'
print(my_list.pop(1))

# Output: ['r', 'b', 'l', 'e', 'm']
print(my_list)

# Output: 'm'
print(my_list.pop())

# Output: ['r', 'b', 'l', 'e']
print(my_list)

my_list.clear()

# Output: []
print(my_list)
</code></pre>
<p>Finally, we can also delete items in a list by assigning an empty list to a slice of elements.</p>
<pre><code>&gt;&gt;&gt; my_list = ['p','r','o','b','l','e','m']
&gt;&gt;&gt; my_list[2:3] = []
&gt;&gt;&gt; my_list
['p', 'r', 'b', 'l', 'e', 'm']
&gt;&gt;&gt; my_list[2:5] = []
&gt;&gt;&gt; my_list
['p', 'r', 'm']
</code></pre>
<h4 id="list-comprehension-elegant-way-to-create-new-list">List Comprehension: Elegant way to create new List</h4>
<p>List comprehension is an elegant and concise way to create new list from an existing list in Python.</p>
<p>List comprehension consists of an expression followed by for statement inside square brackets.<br>
Here is an example to make a list with each item being increasing power of 2.</p>
<pre><code>pow2 = [2 ** x for x in range(10)]

# Output: [1, 2, 4, 8, 16, 32, 64, 128, 256, 512]
print(pow2)
</code></pre>
<p>Equals to</p>
<pre><code>pow2 = []
for x in range(10):
   pow2.append(2 ** x)
</code></pre>
<p>A list comprehension can optionally contain more <code>for</code> or if statements An optional <code>if</code>statement can filter out items for the new list. Here are some examples.</p>
<pre><code>&gt;&gt;&gt; pow2 = [2 ** x for x in range(10) if x &gt; 5]
&gt;&gt;&gt; pow2
[64, 128, 256, 512]
&gt;&gt;&gt; odd = [x for x in range(20) if x % 2 == 1]
&gt;&gt;&gt; odd
[1, 3, 5, 7, 9, 11, 13, 15, 17, 19]
&gt;&gt;&gt; [x+y for x in ['Python ','C '] for y in ['Language','Programming']]
['Python Language', 'Python Programming', 'C Language', 'C Programming']
</code></pre>
<h4 id="list-membership-test">List Membership Test</h4>
<p>We can test if an item exists in a list or not, using the keyword <code>in</code>.</p>
<pre><code>my_list = ['p','r','o','b','l','e','m']

# Output: True
print('p' in my_list)

# Output: False
print('a' in my_list)

# Output: True
print('c' not in my_list)
</code></pre>
<h4 id="iterating-through-a-list">Iterating Through a List</h4>
<pre><code>for fruit in ['apple','banana','mango']:
    print("I like",fruit)
</code></pre>
<h3 id="python-tuple">Python Tuple</h3>
<p>Tupleis an ordered sequence of items same as list.The only difference is that tuples are immutable. Tuples once created cannot be modified.</p>
<p>Tuples are used to write-protect data and are usually faster than list as it cannot change dynamically.</p>
<p>It is defined within parentheses () where items are separated by commas.</p>
<pre><code>&gt;&gt;&gt; t = (5,'program', 1+3j)
</code></pre>
<p>We can use the slicing operator [] to extract items but we cannot change its value.</p>
<p>t = (5,‘program’, 1+3j)</p>
<pre><code># t[1] = 'program'
print("t[1] = ", t[1])

# t[0:3] = (5, 'program', (1+3j))
print("t[0:3] = ", t[0:3])

# Generates error
# Tuples are immutable
t[0] = 10
</code></pre>
<p>output:</p>
<pre><code>t[1] =  program
t[0:3] =  (5, 'program', (1+3j))

Traceback (most recent call last):
  File "&lt;stdin&gt;", line 11, in &lt;module&gt;
    t[0] = 10
TypeError: 'tuple' object does not support item assignment
</code></pre>
<h3 id="python-strings">Python Strings</h3>
<p>String is sequence of Unicode characters. We can use single quotes or double quotes to represent strings. Multi-line strings can be denoted using triple quotes, <code>'''</code> or <code>"""</code>.</p>
<p>Like list and tuple, slicing operator [ ] can be used with string. Strings are immutable.</p>
<p>s = ‘Hello world!’</p>
<pre><code># s[4] = 'o'
print("s[4] = ", s[4])

# s[6:11] = 'world'
print("s[6:11] = ", s[6:11])

# Generates error
# Strings are immutable in Python
s[5] ='d'
</code></pre>
<p>output:</p>
<pre><code>s[4] =  o
s[6:11] =  world

Traceback (most recent call last):
  File "&lt;stdin&gt;", line 11, in &lt;module&gt;
    s[5] ='d'
TypeError: 'str' object does not support item assignment
</code></pre>
<h3 id="python-set">Python Set</h3>
<p>Set is an unordered collection of unique items. Set is defined by values separated by comma inside braces { }. Items in a set are not ordered.</p>
<pre><code>a = {5,2,3,1,4}

# printing set variable
print("a = ", a)

# data type of variable a
print(type(a))
</code></pre>
<p>output:<br>
a =  {1, 2, 3, 4, 5}<br>
&lt;class ‘set’&gt;</p>
<p>We can perform set operations like union, intersection on two sets. Set have unique values. They eliminate duplicates.</p>
<pre><code>&gt;&gt;&gt; a = {1,2,2,3,3,3}
&gt;&gt;&gt; a
{1, 2, 3}
</code></pre>
<p>Since, set are unordered collection, indexing has no meaning. Hence the slicing operator [] does not work.</p>
<pre><code>&gt;&gt;&gt; a = {1,2,3}
&gt;&gt;&gt; a[1]
Traceback (most recent call last):
  File "&lt;string&gt;", line 301, in runcode
  File "&lt;interactive input&gt;", line 1, in &lt;module&gt;
TypeError: 'set' object does not support indexing
</code></pre>
<h3 id="python-dictionary">Python Dictionary</h3>
<p>Dictionary is an unordered collection of key-value pairs.</p>
<p>It is generally used when we have a huge amount of data. Dictionaries are optimized for retrieving data. We must know the key to retrieve the value.</p>
<p>In Python, dictionaries are defined within braces {} with each item being a pair in the form  <code>key:value</code>. Key and value can be of any type.</p>
<pre><code>&gt;&gt;&gt; d = {1:'value','key':2}
&gt;&gt;&gt; type(d)
&lt;class 'dict'&gt;
</code></pre>
<p>We use key to retrieve the respective value. But not the other way around.</p>
<pre><code>d = {1:'value','key':2}
print(type(d))

print("d[1] = ", d[1]);

print("d['key'] = ", d['key']);

# Generates error
print("d[2] = ", d[2]);
</code></pre>
<p>output:</p>
<pre><code>&lt;class 'dict'&gt;
d[1] =  value
d['key'] =  2

Traceback (most recent call last):
  File "&lt;stdin&gt;", line 9, in &lt;module&gt;
    print("d[2] = ", d[2]);
KeyError: 2
</code></pre>
<h3 id="conversion-between-data-types">Conversion between data types</h3>
<p>We can convert between different data types by using different type conversion functions like int(), float(), str() etc.</p>
<pre><code>&gt;&gt;&gt; float(5)
5.0
</code></pre>
<p>Conversion from float to int will truncate the value (make it closer to zero).</p>
<pre><code>&gt;&gt;&gt; int(10.6)
10
&gt;&gt;&gt; int(-10.6)
-10
</code></pre>
<p>Conversion to and from string must contain compatible values.</p>
<pre><code>&gt;&gt;&gt; float('2.5')
2.5
&gt;&gt;&gt; str(25)
'25'
&gt;&gt;&gt; int('1p')
Traceback (most recent call last):
  File "&lt;string&gt;", line 301, in runcode
  File "&lt;interactive input&gt;", line 1, in &lt;module&gt;
ValueError: invalid literal for int() with base 10: '1p'
</code></pre>
<p>We can even convert one sequence to another.</p>
<pre><code>&gt;&gt;&gt; set([1,2,3])
{1, 2, 3}
&gt;&gt;&gt; tuple({5,6,7})
(5, 6, 7)
&gt;&gt;&gt; list('hello')
['h', 'e', 'l', 'l', 'o']
</code></pre>
<p>To convert to dictionary, each element must be a pair</p>
<pre><code>&gt;&gt;&gt; dict([[1,2],[3,4]])
{1: 2, 3: 4}
&gt;&gt;&gt; dict([(3,26),(4,44)])
{3: 26, 4: 44}
</code></pre>
<h1 id="python-type-conversion-and-type-casting">Python Type Conversion and Type Casting</h1>
<p>In this article you will learn about the Type conversion and uses of type conversion.</p>
<h3 id="type-conversion">Type Conversion:</h3>
<p>The process of converting the value of one data type (integer, string, float, etc.) to another data type is called type conversion. Python has two types of type conversion.</p>
<ol>
<li>Implicit Type Conversion</li>
<li>Explicit Type Conversion</li>
</ol>
<h3 id="implicit-type-conversion">Implicit Type Conversion:</h3>
<p>In Implicit type conversion, Python automatically converts one data type to another data type. This process doesn’t need any user involvement.</p>
<p>Let’s see an example where Python promotes conversion of lower datatype (integer) to higher data type (float) to avoid data loss.</p>
<h4 id="converting-integer-to-float">Converting integer to float</h4>
<p>num_int = 123<br>
num_flo = 1.23</p>
<p>num_new = num_int + num_flo</p>
<p>print(“datatype of num_int:”,type(num_int))<br>
print(“datatype of num_flo:”,type(num_flo))</p>
<p>print(“Value of num_new:”,num_new)<br>
print(“datatype of num_new:”,type(num_new))</p>
<h4 id="addition-of-stringhigher-data-type-and-integerlower-datatype">Addition of string(higher) data type and integer(lower) datatype</h4>
<pre><code>num_int = 123
num_str = "456"

print("Data type of num_int:",type(num_int))
print("Data type of num_str:",type(num_str))

print(num_int+num_str)
</code></pre>
<p>output:</p>
<pre><code>Data type of num_int: &lt;class 'int'&gt;
Data type of num_str: &lt;class 'str'&gt;

Traceback (most recent call last):
  File "&lt;stdin&gt;", line 7, in &lt;module&gt;
    print(num_int+num_str)
TypeError: unsupported operand type(s) for +: 'int' and 'str'
</code></pre>
<h3 id="explicit-type-conversion">Explicit Type Conversion:</h3>
<p>In Explicit Type Conversion, users convert the data type of an object to required data type. We use the predefined functions like  <code>int()</code>,  <code>float()</code>,  <code>str()</code>, etc to perform explicit type conversion.</p>
<p>This type conversion is also called typecasting because the user casts (change) the data type of the objects.<br>
Syntax :</p>
<pre><code>(required_datatype)(expression)
</code></pre>
<p>Typecasting can be done by assigning the required data type function to the expression.</p>
<pre><code>num_int = 123
num_str = "456"

print("Data type of num_int:",type(num_int))
print("Data type of num_str before Type Casting:",type(num_str))

num_str = int(num_str)
print("Data type of num_str after Type Casting:",type(num_str))

num_sum = num_int + num_str

print("Sum of num_int and num_str:",num_sum)
print("Data type of the sum:",type(num_sum))
</code></pre>
<p>output:</p>
<pre><code>Data type of num_int: &lt;class 'int'&gt;
Data type of num_str before Type Casting: &lt;class 'str'&gt;
Data type of num_str after Type Casting: &lt;class 'int'&gt;
Sum of num_int and num_str: 579
Data type of the sum: &lt;class 'int'&gt;
</code></pre>
<h2 id="python-input-output-and-import">Python Input, Output and Import</h2>
<p>This tutorial focuses on two built-in functions print() and input() to perform I/O task in Python. Also, you will learn to import modules and use them in your program.</p>
<p>Python provides numerous built-in functions that are readily available to us at the Python prompt.</p>
<h4 id="python-output-using-print-function">Python Output Using print() function</h4>
<pre><code>print('This sentence is output to the screen')
# Output: This sentence is output to the screen

print(1,2,3,4)
# Output: 1 2 3 4

print(1,2,3,4,sep='*')
# Output: 1*2*3*4

print(1,2,3,4,sep='#',end='&amp;')
# Output: 1#2#3#4&amp;
</code></pre>
<pre><code>    x = 5; y = 10
    print('The value of x is {} and y is {}'.format(y,x))
    0/p: The value of x is 10 and y is 5

</code></pre>
<p>We can even use keyword arguments to format the string.</p>
<pre><code>print('Hello {name}, {greeting}'.format(greeting = 'Goodmorning', name = 'John'))
Hello John, Goodmorning
</code></pre>
<p>We can even format strings like the old <code>sprintf()</code> style used in C programming language. We use the <code>%</code> operator to accomplish this.</p>
<pre><code>x = 12.3456789
print('The value of x is %3.2f' %x)
The value of x is 12.35
print('The value of x is %3.4f' %x)
The value of x is 12.3457
</code></pre>
<h3 id="python-input">Python Input</h3>
<p>Up till now, our programs were static. The value of variables were defined or hard coded into the source code.</p>
<p>To allow flexibility we might want to take the input from the user. In Python, we have the  <code>input()</code>  function to allow this. The syntax for  <code>input()</code>  is</p>
<pre><code>input([prompt])
</code></pre>
<p>where <code>prompt</code> is the string we wish to display on the screen. It is optional.</p>
<pre><code>num = input('Enter a number: ')
Enter a number: 10
&gt;&gt;&gt; num
'10'
</code></pre>
<h3 id="python-import">Python Import</h3>
<p>When our program grows bigger, it is a good idea to break it into different modules.</p>
<p>A module is a file containing Python definitions and statements.  Python modules  have a filename and end with the extension  <code>.py</code>.</p>
<p>Definitions inside a module can be imported to another module or the interactive interpreter in Python. We use the  <code>import</code>  keyword to do this.</p>
<p>For example, we can import the  <code>math</code>  module by typing in  <code>import math</code>.</p>
<pre><code>import math
print(math.pi)
o/p: 3.141592653589793
</code></pre>
<h2 id="python-operators">Python Operators</h2>
<p>In this article, you’ll learn everything about different types of operators in Python, their syntax and how to use them with examples.</p>
<h4 id="what-are-operators-in-python">What are operators in python?</h4>
<p>Operators are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the operand.</p>
<pre><code>&gt;&gt;&gt; 2+3
5
</code></pre>
<p>Here, <code>+</code> is the operator that performs addition. <code>2</code> and <code>3</code> are the operands and <code>5</code> is the output of the operation.</p>
<h3 id="arithmetic-operators-in-python">Arithmetic operators in Python</h3>
<pre><code> x = 15
  y = 4

  # Output: x + y = 19
  print('x + y =',x+y)

  # Output: x - y = 11
  print('x - y =',x-y)

  # Output: x * y = 60
  print('x * y =',x*y)

  # Output: x / y = 3.75
  print('x / y =',x/y)

  # Output: x // y = 3
  print('x // y =',x//y)

  # Output: x ** y = 50625
  print('x ** y =',x**y)
</code></pre>
<p>output:</p>
<pre><code>x + y = 19
x - y = 11
x * y = 60
x / y = 3.75
x // y = 3
x ** y = 50625
</code></pre>
<h3 id="comparison-operators-in-python">Comparison operators in Python</h3>
<pre><code>x = 10
y = 12

# Output: x &gt; y is False
print('x &gt; y  is',x&gt;y)

# Output: x &lt; y is True
print('x &lt; y  is',x&lt;y)

# Output: x == y is False
print('x == y is',x==y)

# Output: x != y is True
print('x != y is',x!=y)

# Output: x &gt;= y is False
print('x &gt;= y is',x&gt;=y)

# Output: x &lt;= y is True
print('x &lt;= y is',x&lt;=y)
</code></pre>
<h3 id="logical-operators">Logical operators</h3>
<p>Logical operators are the <code>and</code>, <code>or</code>, <code>not</code> operators.</p>
<pre><code>x = True
y = False

# Output: x and y is False
print('x and y is',x and y)

# Output: x or y is True
print('x or y is',x or y)

# Output: not x is False
print('not x is',not x)
</code></pre>
<h3 id="assignment-operators">Assignment operators</h3>
<p>Assignment operators are used in Python to assign values to variables.</p>
<p><code>a = 5</code>  is a simple assignment operator that assigns the value 5 on the right to the variable  a  on the left.</p>
<p>There are various compound operators in Python like  <code>a += 5</code>  that adds to the variable and later assigns the same. It is equivalent to  <code>a = a + 5</code></p>

<table>
<thead>
<tr>
<th>Operator</th>
<th>Example</th>
<th>Equivatent to</th>
</tr>
</thead>
<tbody>
<tr>
<td>=</td>
<td>x = 5</td>
<td>x = 5</td>
</tr>
<tr>
<td>+=</td>
<td>x += 5</td>
<td>x = x + 5</td>
</tr>
<tr>
<td>-=</td>
<td>x -= 5</td>
<td>x = x - 5</td>
</tr>
<tr>
<td>*=</td>
<td>x *= 5</td>
<td>x = x * 5</td>
</tr>
<tr>
<td>/=</td>
<td>x /= 5</td>
<td>x = x / 5</td>
</tr>
<tr>
<td>%=</td>
<td>x %= 5</td>
<td>x =x % 5</td>
</tr>
<tr>
<td>//=</td>
<td>x //= 5</td>
<td>x = x // 5</td>
</tr>
<tr>
<td>**=</td>
<td>x **= 5</td>
<td>x = x ** 5</td>
</tr>
<tr>
<td>&amp;=</td>
<td>x &amp;= 5</td>
<td>x = x &amp; 5</td>
</tr>
<tr>
<td></td>
<td>=</td>
<td>x</td>
</tr>
<tr>
<td>^=</td>
<td>x ^= 5</td>
<td>x = x ^ 5</td>
</tr>
<tr>
<td>&gt;&gt;=</td>
<td>x &gt;&gt;= 5</td>
<td>x = x &gt;&gt; 5</td>
</tr>
<tr>
<td>&lt;&lt;=</td>
<td>x &lt;&lt;= 5</td>
<td>x = x &lt;&lt; 5</td>
</tr>
</tbody>
</table><h3 id="identity-operators">Identity operators</h3>
<p><code>is</code> and <code>is not</code> are the identity operators in Python. They are used to check if two values (or variables) are located on the same part of the memory. Two variables that are equal does not imply that they are identical.</p>
<pre><code>x1 = 5
y1 = 5
x2 = 'Hello'
y2 = 'Hello'
x3 = [1,2,3]
y3 = [1,2,3]
# Output: False
print(x1 is not y1)
# Output: True
print(x2 is y2)
# Output: False
print(x3 is y3)
</code></pre>
<h3 id="membership-operators">Membership operators</h3>
<p><code>in</code>  and  <code>not in</code>  are the membership operators in Python. They are used to test whether a value or variable is found in a sequence (String, List, Tuple, Set and Dictionary).</p>
<p>In a dictionary we can only test for presence of key, not the value.</p>
<pre><code>x = 'Hello world'
y = {1:'a',2:'b'}
# Output: True
print('H' in x)
# Output: True
print('hello' not in x)
# Output: True
print(1 in y)
# Output: False
print('a' in y)
</code></pre>
<p>Here, <code>'H'</code> is in x but <code>'hello'</code> is not present in x (remember, Python is case sensitive). Similary, <code>1</code> is key and <code>'a'</code> is the value in dictionary y. Hence, <code>'a' in y</code> returns <code>False</code>.</p>
<h3 id="python-variable-scope">Python Variable Scope</h3>
<p>Scope is the portion of the program from where a namespace can be accessed directly without any prefix.<br>
At any given moment, there are at least three nested scopes.</p>
<ol>
<li>Scope of the current function which has local names</li>
<li>Scope of the module which has global names</li>
<li>Outermost scope which has built-in names</li>
</ol>
<p>When a reference is made inside a function, the name is searched in the local namespace, then in the global namespace and finally in the built-in namespace.</p>
<p>If there is a function inside another function, a new scope is nested inside the local scope.</p>
<h4 id="scope-and-namespace-in-python">Scope and Namespace in Python</h4>
<pre><code>def outer_function():
    b = 20
    def inner_func():
        c = 30
         
a = 10
</code></pre>
<p>Here, the variable  a  is in the global namespace. Variable  b  is in the local namespace of  <code>outer_function()</code>  and  c  is in the nested local namespace of  <code>inner_function()</code>.</p>
<p>When we are in  <code>inner_function()</code>,  c  is local to us,  b  is nonlocal and  a  is global. We can read as well as assign new values to  c  but can only read  b  and  a from  <code>inner_function()</code>.</p>
<p>If we try to assign as a value to  b, a new variable  b  is created in the local namespace which is different than the nonlocal  b. Same thing happens when we assign a value to  a.</p>
<p>However, if we declare  a  as global, all the reference and assignment go to the global  a. Similarly, if we want to rebind the variable  b, it must be declared as nonlocal. The following example will further clarify this.</p>
<pre><code>def outer_function():
    a = 20
    def inner_function():
        a = 30
        print('a =',a)

    inner_function()
    print('a =',a)
     
a = 10
outer_function()
print('a =',a)
</code></pre>
<p>As you can see, the output of this program is<br>
a = 30<br>
a = 20<br>
a = 10</p>
<p>In this program, three different variables a are defined in separate namespaces and accessed accordingly. While in the following program,</p>
<pre><code>def outer_function():
    global a
    a = 20
    def inner_function():
        global a
        a = 30
        print('a =',a)

    inner_function()
    print('a =',a)
     
a = 10
outer_function()
print('a =',a)
</code></pre>
<p>output:<br>
a = 30<br>
a = 30<br>
a = 30</p>
<p>Here, all reference and assignment are to the global a due to the use of keyword <code>global</code></p>
<h1 id="python-flow-control">Python Flow Control</h1>
<h2 id="python-if...else-statement">Python if…else Statement</h2>
<p>In this article, you will learn to create decisions in a Python program using different forms of if…else statement.</p>
<h4 id="what-are-if...else-statement-in-python">What are if…else statement in Python?</h4>
<p>Decision making is required when we want to execute a code only if a certain condition is satisfied.</p>
<p>The  <code>if…elif…else</code>  statement is used in Python for decision making.</p>
<pre><code>if test expression:
    statement(s)
# If the number is positive, we print an appropriate message

num = 3
if num &gt; 0:
    print(num, "is a positive number.")
print("This is always printed.")

num = -1
if num &gt; 0:
    print(num, "is a positive number.")
print("This is also always printed.")
</code></pre>
<p>O/p:</p>
<pre><code>3 is a positive number
This is always printed
This is also always printed.
</code></pre>
<h3 id="python-if...else-statement-1">Python if…else Statement</h3>
<pre><code>if test expression:
    Body of if
else:
    Body of else
</code></pre>
<p>The  <code>if..else</code>  statement evaluates  <code>test expression</code>  and will execute body of  <code>if</code>  only when test condition is  <code>True</code>.</p>
<p>If the condition is  <code>False</code>, body of  <code>else</code>  is executed. Indentation is used to separate the blocks.</p>
<pre><code># Program checks if the number is positive or negative
# And displays an appropriate message

num = 3

# Try these two variations as well. 
# num = -5
# num = 0

if num &gt;= 0:
    print("Positive or Zero")
else:
    print("Negative number")
</code></pre>
<p>o/p: Positive or Zero</p>
<p>In the above example, when  num  is equal to 3, the test expression is true and body of  <code>if</code>  is executed and  <code>body</code>  of else is skipped.</p>
<p>If  num  is equal to -5, the test expression is false and body of  <code>else</code>  is executed and body of  <code>if</code>  is skipped.</p>
<p>If  num  is equal to 0, the test expression is true and body of  <code>if</code>  is executed and  <code>body</code>  of else is skipped.</p>
<h3 id="python-if...elif...else-statement">Python if…elif…else Statement</h3>
<pre><code>if test expression:
    Body of if
elif test expression:
    Body of elif
else: 
    Body of else
</code></pre>
<p>The  <code>elif</code>  is short for else if. It allows us to check for multiple expressions.<br>
If the condition for  <code>if</code>  is  <code>False</code>, it checks the condition of the next  <code>elif</code>  block and so on.<br>
If all the conditions are  <code>False</code>, body of else is executed.<br>
Only one block among the several  <code>if...elif...else</code>  blocks is executed according to the condition.<br>
The  <code>if</code>  block can have only one  <code>else</code>  block. But it can have multiple  <code>elif</code>  blocks.</p>
<pre><code># In this program, 
# we check if the number is positive or
# negative or zero and 
# display an appropriate message

num = 3.4

# Try these two variations as well:
# num = 0
# num = -4.5

if num &gt; 0:
    print("Positive number")
elif num == 0:
    print("Zero")
else:
    print("Negative number")
</code></pre>
<p>o/p:<br>
Positive number</p>
<p>When variable  num  is positive,  Positive number  is printed.<br>
If  num  is equal to 0,  Zero  is printed<br>
If  num  is negative,  Negative number  is printed</p>
<h3 id="python-nested-if-statements">Python Nested if statements</h3>
<p>We can have a  <code>if...elif...else</code>  statement inside another  <code>if...elif...else</code>  statement. This is called nesting in computer programming.</p>
<p>Any number of these statements can be nested inside one another. Indentation is the only way to figure out the level of nesting. This can get confusing, so must be avoided if we can.</p>
<pre><code># In this program, we input a number
# check if the number is positive or
# negative or zero and display
# an appropriate message
# This time we use nested if

num = float(input("Enter a number: "))
if num &gt;= 0:
    if num == 0:
        print("Zero")
    else:
        print("Positive number")
else:
    print("Negative number")
</code></pre>
<p><strong>Output 1</strong></p>
<pre><code>Enter a number: 5
Positive number
</code></pre>
<p><strong>Output 2</strong></p>
<pre><code>Enter a number: -1
Negative number
</code></pre>
<p><strong>Output 3</strong></p>
<pre><code>Enter a number: 0
Zero
</code></pre>
<h2 id="python-for-loop">Python for Loop</h2>
<p>In this article, you’ll learn to iterate over a sequence of elements using the different variations of for loop.</p>
<h4 id="what-is-for-loop-in-python">What is for loop in Python?</h4>
<p>The for loop in Python is used to iterate over a sequence(List,tuple,string) or other iterable objects. Iterating over a sequence is called traversal.</p>
<pre><code>for val in sequence:
	Body of for
</code></pre>
<p>Here,  <code>val</code>  is the variable that takes the value of the item inside the sequence on each iteration.<br>
Loop continues until we reach the last item in the sequence. The body of for loop is separated from the rest of the code using indentation.</p>
<pre><code># Program to find the sum of all numbers stored in a list
# List of numbers
numbers = [6, 5, 3, 8, 4, 2, 5, 4, 11]
# variable to store the sum
sum = 0
# iterate over the list
for val in numbers:
	sum = sum+val
# Output: The sum is 48
print("The sum is", sum)
</code></pre>
<p>o/p: The sum is 48</p>
<h3 id="the-range-function">The range() function</h3>
<p>We can generate a sequence of numbers using  <code>range()</code>  function.  <code>range(10)</code>  will generate numbers from 0 to 9 (10 numbers).<br>
We can also define the start, stop and step size as  <code>range(start,stop,step size)</code>. step size defaults to 1 if not provided.<br>
This function does not store all the values in memory, it would be inefficient. So it remembers the start, stop, step size and generates the next number on the go.<br>
To force this function to output all the items, we can use the function  <code>list()</code>.<br>
The following example will clarify this.</p>
<pre><code># Output: range(0, 10)
print(range(10))

# Output: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
print(list(range(10)))

# Output: [2, 3, 4, 5, 6, 7]
print(list(range(2, 8)))

# Output: [2, 5, 8, 11, 14, 17]
print(list(range(2, 20, 3)))
</code></pre>
<p>We can use the range() function in for loops to iterate through a sequence of numbers. It can be combined with the <code>len()</code> function to iterate though a sequence using indexing. Here is an example.</p>
<pre><code># Program to iterate through a list using indexing

genre = ['pop', 'rock', 'jazz']

# iterate over the list using index
for i in range(len(genre)):
	print("I like", genre[i])
</code></pre>
<p>o/p:</p>
<pre><code>I like pop
I like rock
​I like jazz
</code></pre>
<h4 id="for-loop-with-else">for loop with else</h4>
<p>A for loop can have an optional else block as well. The  <code>else</code>  part is executed if the items in the sequence used in for loop exhausts.<br>
break statement can be used to stop a for loop. In such case, the else part is ignored.<br>
Hence, a for loop’s else part runs if no break occurs.</p>
<pre><code>digits = [0, 1, 5]
for i in digits:
    print(i)
else:
    print("No items left.")
</code></pre>
<p>o/p:</p>
<pre><code>0
1
5
No items left.
</code></pre>
<h2 id="python-while-loop">Python while Loop</h2>
<p>Loops are used in programming to repeat a specific block of code. In this article, you will learn to create a while loop in Python.</p>
<h4 id="what-is-while-loop-in-python">What is while loop in Python?</h4>
<p>The while loop in Python is used to iterate over a block of code as long as the test expression (condition) is true.</p>
<p>We generally use this loop when we don’t know beforehand, the number of times to iterate.</p>
<pre><code>while test_expression:
    Body of while
</code></pre>
<p>In while loop, test expression is checked first. The body of the loop is entered only if the  <code>test_expression</code>  evaluates to  <code>True</code>. After one iteration, the test expression is checked again. This process continues until the  <code>test_expression</code>  evaluates to  <code>False</code>.</p>
<p>In Python, the body of the while loop is determined through indentation.</p>
<p>Body starts with indentation and the first unindented line marks the end.</p>
<p>Python interprets any non-zero value as  <code>True</code>.  <code>None</code>  and  <code>0</code>  are interpreted as  <code>False</code></p>
<pre><code># Program to add natural
# numbers upto 
# sum = 1+2+3+...+n

# To take input from the user,
# n = int(input("Enter n: "))

n = 10

# initialize sum and counter
sum = 0
i = 1

while i &lt;= n:
    sum = sum + i
    i = i+1    # update counter

# print the sum
print("The sum is", sum)
</code></pre>
<p>o/p:</p>
<pre><code>Enter n: 10
The sum is 55
</code></pre>
<p>In the above program, the test expression will be  <code>True</code>  as long as our counter variable  i  is less than or equal to  n  (10 in our program).</p>
<p>We need to increase the value of counter variable in the body of the loop. This is very important (and mostly forgotten). Failing to do so will result in an infinite loop (never ending loop).<br>
Finally the result is displayed.</p>
<h3 id="while-loop-with-else">while loop with else</h3>
<p>Same as that of for loop, we can have an optional  <code>else</code>  block with while loop as well.</p>
<p>The  <code>else</code>  part is executed if the condition in the while loop evaluates to  <code>False</code>.</p>
<p>The while loop can be terminated with a break statement. In such case, the  <code>else</code>  part is ignored. Hence, a while loop’s  <code>else</code>  part runs if no break occurs and the condition is false.</p>
<pre><code># Example to illustrate
# the use of else statement
# with the while loop

counter = 0

while counter &lt; 3:
    print("Inside loop")
    counter = counter + 1
else:
    print("Inside else")
</code></pre>
<p>o/p:</p>
<pre><code>Inside loop
Inside loop
Inside loop
Inside else
</code></pre>
<p>Here, we use a counter variable to print the string  <code>Inside loop</code>  three times.<br>
On the forth iteration, the condition in while becomes  <code>False</code>. Hence, the  <code>else</code>  part is executed.</p>
<h2 id="python-break-and-continue">Python break and continue</h2>
<p>You will learn to use break and continue statements to alter the flow of a loop.</p>
<h3 id="what-is-the-use-of-break-and-continue-in-python">What is the use of break and continue in Python?</h3>
<p>In Python, break and continue statements can alter the flow of a normal loop.<br>
Loops iterate over a block of code until test expression is false, but sometimes we wish to terminate the current iteration or even the whole loop without checking test expression.<br>
The break and continue statements are used in these cases.</p>
<h4 id="python-break-statement">Python break statement</h4>
<p>The break statement terminates the loop containing it. Control of the program flows to the statement immediately after the body of the loop.<br>
If break statement is inside a nested loop (loop inside another loop), break will terminate the innermost loop.</p>
<pre><code>break
</code></pre>
<p>Ex:</p>
<pre><code># Use of break statement inside loop
for val in "string":
    if val == "i":
        break
    print(val)
print("The end")
</code></pre>
<p>o/p:</p>
<pre><code>s
t
r
The end
</code></pre>
<p>In this program, we iterate through the <code>"string"</code> sequence. We check if the letter is <code>"i"</code>, upon which we break from the loop. Hence, we see in our output that all the letters up till <code>"i"</code> gets printed. After that, the loop terminates.</p>
<h3 id="python-continue-statement">Python continue statement</h3>
<p>The continue statement is used to skip the rest of the code inside a loop for the current iteration only. Loop does not terminate but continues on with the next iteration.</p>
<pre><code>continue
</code></pre>
<p>Ex:</p>
<pre><code># Program to show the use of continue statement inside loops
for val in "string":
    if val == "i":
        continue
    print(val)
print("The end")
</code></pre>
<h3 id="python-pass-statement">Python pass statement</h3>
<p>You’ll learn about pass statement. It is used as a placeholder for future implementation of functions, loops, etc.</p>
<h4 id="what-is-pass-statement-in-python">What is pass statement in Python?</h4>
<p>In Python programming,  <code>pass</code>  is a null statement. The difference between a  comment and  <code>pass</code>  statement in Python is that, while the interpreter ignores a comment entirely,  <code>pass</code>  is not ignored.<br>
However, nothing happens when pass is executed. It results into no operation (NOP).</p>
<pre><code>pass
</code></pre>
<p>We generally use it as a placeholder.<br>
Suppose we have a loop or a function  that is not implemented yet, but we want to implement it in the future. They cannot have an empty body. The interpreter would complain. So, we use the  <code>pass</code>  statement to construct a body that does nothing.</p>
<pre><code># pass is just a placeholder for
# functionality to be added later.
sequence = {'p', 'a', 's', 's'}
for val in sequence:
    pass
</code></pre>
<p>We can do the same thing in an empty function or class as well.</p>
<pre><code>def function(args):
    pass
</code></pre>
<pre><code>class example:
    pass
</code></pre>
<h3 id="loop-with-condition-at-the-bottom">Loop with condition at the bottom</h3>
<pre><code># Python program to illustrate a loop with condition at the bottom
# Roll a dice untill user chooses to exit

# import random module
import random

while True:
   input("Press enter to roll the dice")

   # get a number between 1 to 6
   num = random.randint(1,6)
   print("You got",num)
   option = input("Roll again?(y/n) ")

   # condition
   if option == 'n':
       break

</code></pre>
<pre><code>Press enter to roll the dice
You got 1
Roll again?(y/n) y
Press enter to roll the dice
You got 5
Roll again?(y/n) n
</code></pre>
<h2 id="python-functions-1">Python Functions</h2>
<p>You’ll learn about functions; what is a function, the syntax, components and types of a function. Also, you’ll learn to create a function in Python.</p>
<h4 id="what-is-a-function-in-python">What is a function in Python?</h4>
<p>In Python, function is a group of related statements that perform a specific task.<br>
Functions help break our program into smaller and modular chunks. As our program grows larger and larger, functions make it more organized and manageable.<br>
Furthermore, it avoids repetition and makes code reusable.</p>
<pre><code>def function_name(parameters):
	"""docstring"""
	statement(s)
</code></pre>
<p>Above shown is a function definition which consists of following components.</p>
<ol>
<li>Keyword  <code>def</code>  marks the start of function header.</li>
<li>A function name to uniquely identify it. Function naming follows the same rules of writing identifiers in Python.</li>
<li>Parameters (arguments) through which we pass values to a function. They are optional.</li>
<li>A colon (:) to mark the end of function header.</li>
<li>Optional documentation string (docstring) to describe what the function does.</li>
<li>One or more valid python statements that make up the function body. Statements must have same indentation level (usually 4 spaces).</li>
<li>An optional  <code>return</code>  statement to return a value from the function.</li>
</ol>
<h4 id="example-of-a-function">Example of a function</h4>
<pre><code>def greet(name):
	"""This function greets to
	the person passed in as
	parameter"""
	print("Hello, " + name + ". Good morning!")
</code></pre>
<h4 id="how-to-call-a-function-in-python">How to call a function in python?</h4>
<p>Once we have defined a function, we can call it from another function, program or even the Python prompt. To call a function we simply type the function name with appropriate parameters.</p>
<pre><code>greet('Paul')
Hello, Paul. Good morning!
</code></pre>
<h3 id="docstring">Docstring</h3>
<p>The first string after the function header is called the docstring and is short for documentation string. It is used to explain in brief, what a function does.<br>
Although optional, documentation is a good programming practice. Unless you can remember what you had for dinner last week, always document your code.<br>
In the above example, we have a docstring immediately below the function header. We generally use triple quotes so that docstring can extend up to multiple lines. This string is available to us as  <code>__doc__</code>  attribute of the function.</p>
<pre><code>&gt;&gt;&gt;print(greet.__doc__)
This function greets to
	the person passed into the
	name parameter
	
</code></pre>
<h3 id="the-return-statement">The return statement</h3>
<pre><code>return [expression_list]
</code></pre>
<p>This statement can contain expression which gets evaluated and the value is returned. If there is no expression in the statement or the <code>return</code> statement itself is not present inside a function, then the function will return the <code>None</code> object.</p>
<pre><code>&gt;&gt;&gt; print(greet("May"))
Hello, May. Good morning!
None
</code></pre>
<pre><code>def absolute_value(num):
	"""This function returns the absolute
	value of the entered number"""

	if num &gt;= 0:
		return num
	else:
		return -num

# Output: 2
print(absolute_value(2))

# Output: 4
print(absolute_value(-4))
</code></pre>
<h4 id="scope-and-lifetime-of-variables">Scope and Lifetime of variables</h4>
<pre><code>def my_func():
	x = 10
	print("Value inside function:",x)

x = 20
my_func()
print("Value outside function:",x)

Value inside function: 10
Value outside function: 20
</code></pre>
<p>Here, we can see that the value of  x  is 20 initially. Even though the function  <code>my_func()</code>changed the value of  x  to 10, it did not effect the value outside the function.<br>
This is because the variable  x  inside the function is different (local to the function) from the one outside. Although they have same names, they are two different variables with different scope.<br>
On the other hand, variables outside of the function are visible from inside. They have a global scope.<br>
We can read these values from inside the function but cannot change (write) them. In order to modify the value of variables outside the function, they must be declared as global variables using the keyword  <code>global</code>.</p>
<h2 id="python-function-arguments">Python Function Arguments</h2>
<p>you can define a function that takes variable number of arguments. You will learn to define such functions using default, keyword and arbitrary arguments in this article.</p>
<h4 id="arguments">Arguments</h4>
<p>In user-defined function topic, we learned about defining a function and calling it. Otherwise, the function call will result into an error.</p>
<pre><code>def greet(name,msg):
   """This function greets to
   the person with the provided message"""
   print("Hello",name + ', ' + msg)

greet("Monica","Good morning!")
</code></pre>
<p>o/p:</p>
<pre><code>Hello Monica, Good morning!
</code></pre>
<p>Here, the function  <code>greet()</code>  has two parameters.</p>
<p>Since, we have called this function with two arguments, it runs smoothly and we do not get any error.</p>
<p>If we call it with different number of arguments, the interpreter will complain. Below is a call to this function with one and no arguments along with their respective error messages.</p>
<pre><code>&gt;&gt;&gt; greet("Monica")    # only one argument
TypeError: greet() missing 1 required positional argument: 'msg' 

&gt;&gt;&gt; greet()    # no arguments
TypeError: greet() missing 2 required positional arguments: 'name' and 'msg'
</code></pre>
<h3 id="variable-function-arguments">Variable Function Arguments</h3>
<p>Up until now functions had fixed number of arguments. In Python there are other ways to define a function which can take variable number of arguments.<br>
Three different forms of this type are described below.</p>
<h3 id="python-default-arguments">Python Default Arguments</h3>
<p>Function arguments can have default values in Python.<br>
We can provide a default value to an argument by using the assignment operator (=).</p>
<pre><code>def greet(name, msg = "Good morning!"):
   """
   This function greets to
   the person with the
   provided message.

   If message is not provided,
   it defaults to "Good
   morning!"
   """

   print("Hello",name + ', ' + msg)

greet("Kate")
greet("Bruce","How do you do?")
</code></pre>
<p>In this function, the parameter  <code>name</code>  does not have a default value and is required (mandatory) during a call.</p>
<p>On the other hand, the parameter  <code>msg</code>  has a default value of  <code>"Good morning!"</code>. So, it is optional during a call. If a value is provided, it will overwrite the default value.</p>
<p>Any number of arguments in a function can have a default value. But once we have a default argument, all the arguments to its right must also have default values.</p>
<p>This means to say, non-default arguments cannot follow default arguments.For example, if we had defined the function header above as:</p>
<pre><code>def greet(msg = "Good morning!", name):
</code></pre>
<p>We would get an error as:</p>
<pre><code>SyntaxError: non-default argument follows default argument
</code></pre>
<h3 id="python-keyword-arguments">Python Keyword Arguments</h3>
<p>When we call a function with some values, these values get assigned to the arguments according to their position.</p>
<p>For example, in the above function  <code>greet()</code>, when we called it as  <code>greet("Bruce","How do you do?")</code>, the value  <code>"Bruce"</code>  gets assigned to the argument  name  and similarly  <code>"How do you do?"</code>  to  msg.</p>
<p>Python allows functions to be called using keyword arguments. When we call functions in this way, the order (position) of the arguments can be changed. Following calls to the above function are all valid and produce the same result.</p>
<pre><code>&gt;&gt;&gt; # 2 keyword arguments
&gt;&gt;&gt; greet(name = "Bruce",msg = "How do you do?")

&gt;&gt;&gt; # 2 keyword arguments (out of order)
&gt;&gt;&gt; greet(msg = "How do you do?",name = "Bruce") 

&gt;&gt;&gt; # 1 positional, 1 keyword argument
&gt;&gt;&gt; greet("Bruce",msg = "How do you do?")
</code></pre>
<p>As we can see, we can mix positional arguments with keyword arguments during a function call. But we must keep in mind that keyword arguments must follow positional arguments.<br>
Having a positional argument after keyword arguments will result into errors. For example the function call as follows:</p>
<pre><code>greet(name="Bruce","How do you do?")
</code></pre>
<p>will result into error as:</p>
<pre><code>SyntaxError: non-keyword arg after keyword arg
</code></pre>
<h3 id="python-arbitrary-arguments">Python Arbitrary Arguments</h3>
<p>Sometimes, we do not know in advance the number of arguments that will be passed into a function.Python allows us to handle this kind of situation through function calls with arbitrary number of arguments.</p>
<p>In the function definition we use an asterisk (*) before the parameter name to denote this kind of argument. Here is an example.</p>
<pre><code>def greet(*names):
   """This function greets all
   the person in the names tuple."""

   # names is a tuple with arguments
   for name in names:
       print("Hello",name)

greet("Monica","Luke","Steve","John")
</code></pre>
<p>o/p:</p>
<pre><code>Hello Monica
Hello Luke
Hello Steve
Hello John
</code></pre>
<p>Here, we have called the function with multiple arguments. These arguments get wrapped up into a tuple before being passed into the function. Inside the function, we use a <code>for</code> loop to retrieve all the arguments back.</p>
<h2 id="python-anonymouslambda-function">Python Anonymous/Lambda Function</h2>
<p>You’ll learn about the anonymous function, also known as lambda functions. You’ll learn what is it, its syntax and how to use it (with examples).</p>
<h4 id="what-are-lambda-functions-in-python">What are lambda functions in Python?</h4>
<p>In Python, anonymous function is a function  that is defined without a name.<br>
While normal functions are defined using the  <code>def</code>  keyword, in Python anonymous functions are defined using the  <code>lambda</code>  keyword.<br>
Hence, anonymous functions are also called lambda functions.</p>
<h3 id="how-to-use-lambda-functions-in-python">How to use lambda Functions in Python?</h3>
<pre><code>lambda  arguments: expression
</code></pre>
<p>Lambda functions can have any number of arguments but only one expression. The expression is evaluated and returned. Lambda functions can be used wherever function objects are required.</p>
<pre><code># Program to show the use of lambda functions
double = lambda x: x * 2
# Output: 10
print(double(5))
</code></pre>
<p>In the above program,  <code>lambda x: x * 2</code>  is the lambda function. Here  x  is the argument and  <code>x * 2</code>  is the expression that gets evaluated and returned.<br>
This function has no name. It returns a function object which is assigned to the identifier  <code>double</code>. We can now call it as a normal function. The statement</p>
<pre><code>double = lambda x: x * 2
</code></pre>
<p>is nearly the same as</p>
<pre><code>def double(x):
   return x * 2
</code></pre>
<h3 id="use-of-lambda-function-in-python">Use of Lambda Function in python</h3>
<p>We use lambda functions when we require a nameless function for a short period of time.<br>
In Python, we generally use it as an argument to a higher-order function (a function that takes in other functions as arguments. Lambda functions are used along with built-in functions like  <code>filter()</code>,  <code>map()</code>  etc.</p>
<h4 id="example-use-with-filter">Example use with filter()</h4>
<p>The  <code>filter()</code>  function in Python takes in a function and a list as arguments.<br>
The function is called with all the items in the list and a new list is returned which contains items for which the function evaluats to  <code>True</code>.<br>
Here is an example use of  <code>filter()</code>  function to filter out only even numbers from a list.</p>
<pre><code># Program to filter out only the even items from a list
my_list = [1, 5, 4, 6, 8, 11, 3, 12]
new_list = list(filter(lambda x: (x%2 == 0) , my_list))

# Output: [4, 6, 8, 12]
print(new_list)
</code></pre>
<h4 id="example-use-with-map">Example use with map()</h4>
<p>The  <code>map()</code>  function in Python takes in a function and a list.<br>
The function is called with all the items in the list and a new list is returned which contains items returned by that function for each item.<br>
Here is an example use of  <code>map()</code>  function to double all the items in a list.</p>
<pre><code># Program to double each item in a list using map()
my_list = [1, 5, 4, 6, 8, 11, 3, 12]
new_list = list(map(lambda x: x * 2 , my_list))

# Output: [2, 10, 8, 12, 16, 22, 6, 24]
print(new_list)
</code></pre>
<h2 id="python-modules">Python Modules</h2>
<p>You will learn to create and import custom modules in Python. Also, you will find different techniques to import and use custom and built-in modules in Python.</p>
<h4 id="what-are-modules-in-python">What are modules in Python?</h4>
<p>Modules refer to a file containing Python statements and definitions.<br>
A file containing Python code, for e.g.:  <code>example.py</code>, is called a module and its module name would be  <code>example</code>.<br>
We use modules to break down large programs into small manageable and organized files. Furthermore, modules provide reusability of code.<br>
We can define our most used functions in a module and import it, instead of copying their definitions into different programs.<br>
Let us create a module. Type the following and save it as  <code>example.py</code>.</p>
<pre><code># Python Module example

def add(a, b):
   """This program adds two
   numbers and return the result"""

   result = a + b
   return result
</code></pre>
<p>Here, we have defined a function  <code>add()</code> inside a module named <code>example</code>. The function takes in two numbers and returns their sum.</p>
<h3 id="how-to-import-modules-in-python">How to import modules in Python?</h3>
<p>We can import the definitions inside a module to another module or the interactive interpreter in Python.<br>
We use the  <code>import</code>  keyword to do this. To import our previously defined module  <code>example</code>  we type the following in the Python prompt.</p>
<pre><code>&gt;&gt;&gt; import example
</code></pre>
<p>his does not enter the names of the functions defined in  <code>example</code>  directly in the current symbol table. It only enters the module name  <code>example</code>  there.</p>
<p>Using the module name we can access the function using the dot  <code>.</code> operator. For example:</p>
<pre><code>&gt;&gt;&gt; example.add(4,5.5)
9.5
</code></pre>
<h4 id="python-import-statement">Python import statement</h4>
<p>We can import a module using <code>import</code> statement and access the definitions inside it using the dot operator as described above.</p>
<pre><code># import statement example
# to import standard module math

import math
print("The value of pi is", math.pi)
</code></pre>
<p>o/p:</p>
<pre><code>The value of pi is 3.141592653589793
</code></pre>
<h4 id="import-with-renaming">Import with renaming</h4>
<pre><code># import module by renaming it

import math as m
print("The value of pi is", m.pi)
</code></pre>
<p>We have renamed the  <code>math</code>  module as  <code>m</code>. This can save us typing time in some cases.<br>
Note that the name  <code>math</code>  is not recognized in our scope. Hence,  <code>math.pi</code>  is invalid,  <code>m.pi</code>  is the correct implementation.</p>
<pre><code>#### Python from...import statement
# import only pi from math module

from math import pi
print("The value of pi is", pi)
</code></pre>
<p>We imported only the attribute pi from the module.<br>
In such case we don’t use the dot operator. We could have imported multiple attributes as follows.</p>
<pre><code>&gt;&gt;&gt; from math import pi, e
&gt;&gt;&gt; pi
3.141592653589793
&gt;&gt;&gt; e
2.718281828459045
</code></pre>
<h4 id="import-all-names">Import all names</h4>
<pre><code># import all names from the standard module math

from math import *
print("The value of pi is", pi)
</code></pre>
<h2 id="python-file-io">Python File I/O</h2>
<p>You’ll learn about Python file operations. More specifically, opening a file, reading from it, writing into it, closing it and various file methods you should be aware of.</p>
<h4 id="what-is-a-file">What is a file?</h4>
<p>ile is a named location on disk to store related information. It is used to permanently store data in a non-volatile memory (e.g. hard disk).</p>
<p>Since, random access memory (RAM) is volatile which loses its data when computer is turned off, we use files for future use of the data.</p>
<p>When we want to read from or write to a file we need to open it first. When we are done, it needs to be closed, so that resources that are tied with the file are freed.</p>
<p>Hence, in Python, a file operation takes place in the following order.</p>
<ol>
<li>Open a file</li>
<li>Read or write (perform operation)</li>
<li>Close the file</li>
</ol>
<h4 id="how-to-open-a-file">How to open a file?</h4>
<p>Python has a built-in function <code>open()</code> to open a file. This function returns a file object, also called a handle, as it is used to read or modify the file accordingly.</p>
<pre><code>&gt;&gt;&gt; f = open("test.txt")    # open file in current directory
&gt;&gt;&gt; f = open("C:/Python33/README.txt")  # specifying full path
</code></pre>
<p>We can specify the mode while opening a file. In mode, we specify whether we want to read <code>'r'</code>, write <code>'w'</code> or append <code>'a'</code> to the file. We also specify if we want to open the file in text mode or binary mode.</p>
<pre><code>f = open("test.txt")      # equivalent to 'r' or 'rt'
f = open("test.txt",'w')  # write in text mode
f = open("img.bmp",'r+b') # read and write in binary mode
</code></pre>
<p>Unlike other languages, the character  <code>'a'</code>  does not imply the number 97 until it is encoded using  <code>ASCII</code>  (or other equivalent encodings).</p>
<p>Moreover, the default encoding is platform dependent. In windows, it is  <code>'cp1252'</code>  but  <code>'utf-8'</code>  in Linux.</p>
<p>So, we must not also rely on the default encoding or else our code will behave differently in different platforms.</p>
<p>Hence, when working with files in text mode, it is highly recommended to specify the encoding type.</p>
<pre><code>f = open("test.txt",mode = 'r',encoding = 'utf-8')
</code></pre>
<h4 id="how-to-close-a-file-using-python">How to close a file Using Python?</h4>
<p>When we are done with operations to the file, we need to properly close the file.</p>
<p>Closing a file will free up the resources that were tied with the file and is done using Python <code>close()</code>  method.</p>
<p>Python has a garbage collector to clean up unreferenced objects but, we must not rely on it to close the file.</p>
<pre><code>f = open("test.txt",encoding = 'utf-8')
# perform file operations
f.close()
</code></pre>
<p>This method is not entirely safe. If an exception occurs when we are performing some operation with the file, the code exits without closing the file.</p>
<p>A safer way is to use a try…finally block.</p>
<pre><code>try:
   f = open("test.txt",encoding = 'utf-8')
   # perform file operations
finally:
   f.close()
</code></pre>
<p>This way, we are guaranteed that the file is properly closed even if an exception is raised, causing program flow to stop.</p>
<p>The best way to do this is using the  <code>with</code>  statement. This ensures that the file is closed when the block inside  <code>with</code>  is exited.</p>
<p>We don’t need to explicitly call the  <code>close()</code>  method. It is done internally.</p>
<pre><code>with open("test.txt",encoding = 'utf-8') as f:
   # perform file operations
</code></pre>
<h4 id="how-to-write-to-file-using-python">How to write to File Using Python?</h4>
<p>In order to write into a file in Python, we need to open it in write  <code>'w'</code>, append  <code>'a'</code>  or exclusive creation  <code>'x'</code>  mode.</p>
<p>We need to be careful with the  <code>'w'</code>  mode as it will overwrite into the file if it already exists. All previous data are erased.</p>
<p>Writing a string or sequence of bytes (for binary files) is done using  <code>write()</code>  method. This method returns the number of characters written to the file.</p>
<pre><code>with open("test.txt",'w',encoding = 'utf-8') as f:
   f.write("my first file\n")
   f.write("This file\n\n")
   f.write("contains three lines\n")
</code></pre>
<p>This program will create a new file named  <code>'test.txt'</code>  if it does not exist. If it does exist, it is overwritten.</p>
<p>We must include the newline characters ourselves to distinguish different lines.</p>
<h4 id="how-to-read-files-in-python">How to read files in Python?</h4>
<p>To read a file in Python, we must open the file in reading mode.</p>
<p>There are various methods available for this purpose. We can use the  <code>read(size)</code>  method to read in  size  number of data. If  size  parameter is not specified, it reads and returns up to the end of the file.</p>
<pre><code>&gt;&gt;&gt; f = open("test.txt",'r',encoding = 'utf-8')
&gt;&gt;&gt; f.read(4)    # read the first 4 data
'This'

&gt;&gt;&gt; f.read(4)    # read the next 4 data
' is '

&gt;&gt;&gt; f.read()     # read in the rest till end of file
'my first file\nThis file\ncontains three lines\n'

&gt;&gt;&gt; f.read()  # further reading returns empty sting
''
</code></pre>
<p>We can see that, the <code>read()</code>  method returns newline as  <code>'\n'</code>. Once the end of file is reached, we get empty string on further reading.</p>
<p>We can change our current file cursor (position) using the  <code>seek()</code>  method. Similarly, the  <code>tell()</code>  method returns our current position (in number of bytes).</p>
<pre><code>&gt;&gt;&gt; f.tell()    # get the current file position
56

&gt;&gt;&gt; f.seek(0)   # bring file cursor to initial position
0

&gt;&gt;&gt; print(f.read())  # read the entire file
This is my first file
This file
contains three lines
</code></pre>
<pre><code>&gt;&gt;&gt; for line in f:
...     print(line, end = '')
...
This is my first file
This file
contains three lines
</code></pre>
<p>The lines in file itself has a newline character  <code>'\n'</code>.</p>
<p>Moreover, the  <code>print()</code>  end parameter to avoid two newlines when printing.</p>
<p>Alternately, we can use  <code>readline()</code>  method to read individual lines of a file. This method reads a file till the newline, including the newline character.</p>
<pre><code>&gt;&gt;&gt; f.readline()
'This is my first file\n'

&gt;&gt;&gt; f.readline()
'This file\n'

&gt;&gt;&gt; f.readline()
'contains three lines\n'

&gt;&gt;&gt; f.readline()
''
</code></pre>
<p>Lastly, the <code>readlines()</code> method returns a list of remaining lines of the entire file. All these reading method return empty values when end of file (EOF) is reached.</p>
<pre><code>&gt;&gt;&gt; f.readlines()
['This is my first file\n', 'This file\n', 'contains three lines\n']
</code></pre>
<h3 id="python-directory-and-files-management">Python Directory and Files Management</h3>
<p>You’ll learn about file and directory management in Python, i.e. creating a directory, renaming it, listing all directories and working with them.</p>
<h4 id="what-is-directory-in-python">What is Directory in Python?</h4>
<p>If there are a large number of files to handle in your Python program, you can arrange your code within different directories to make things more manageable.</p>
<p>A directory or folder is a collection of files and sub directories. Python has the  <code>os</code>  module, which provides us with many useful methods to work with directories (and files as well).</p>
<h4 id="get-current-directory">Get Current Directory</h4>
<p>We can get the present working directory using the  <code>getcwd()</code>  method.</p>
<p>This method returns the current working directory in the form of a string. We can also use the  <code>getcwdb()</code>  method to get it as bytes object.</p>
<pre><code>&gt;&gt;&gt; import os

&gt;&gt;&gt; os.getcwd()
'C:\\Program Files\\PyScripter'

&gt;&gt;&gt; os.getcwdb()
b'C:\\Program Files\\PyScripter'
</code></pre>
<p>The extra backslash implies escape sequence. The <code>print()</code> function will render this properly.</p>
<pre><code>&gt;&gt;&gt; print(os.getcwd())
C:\Program Files\PyScripter
</code></pre>
<h4 id="changing-directory">Changing Directory</h4>
<p>We can change the current working directory using the  <code>chdir()</code>  method.</p>
<p>The new path that we want to change to must be supplied as a string to this method. We can use both forward slash (/) or the backward slash () to separate path elements.</p>
<p>It is safer to use escape sequence when using the backward slash.</p>
<pre><code>&gt;&gt;&gt; os.chdir('C:\\Python33')

&gt;&gt;&gt; print(os.getcwd())
C:\Python33
</code></pre>
<h4 id="list-directories-and-files">List Directories and Files</h4>
<p>All files and sub directories inside a directory can be known using the <code>listdir()</code> method.</p>
<p>This method takes in a path and returns a list of sub directories and files in that path. If no path is specified, it returns from the current working directory.</p>
<pre><code>&gt;&gt;&gt; print(os.getcwd())
C:\Python33

&gt;&gt;&gt; os.listdir()
['DLLs',
'Doc',
'include',
'Lib',
'libs',
'LICENSE.txt',
'NEWS.txt',
'python.exe',
'pythonw.exe',
'README.txt',
'Scripts',
'tcl',
'Tools']

&gt;&gt;&gt; os.listdir('G:\\')
['$RECYCLE.BIN',
'Movies',
'Music',
'Photos',
'Series',
'System Volume Information']
</code></pre>
<h4 id="making-a-new-directory">Making a New Directory</h4>
<p>We can make a new directory using the  <code>mkdir()</code>  method.</p>
<p>This method takes in the path of the new directory. If the full path is not specified, the new directory is created in the current working directory.</p>
<pre><code>&gt;&gt;&gt; os.mkdir('test')

&gt;&gt;&gt; os.listdir()
['test']
</code></pre>
<h4 id="renaming-a-directory-or-a-file">Renaming a Directory or a File</h4>
<p>The  <code>rename()</code>  method can rename a directory or a file.</p>
<p>The first argument is the old name and the new name must be supplies as the second argument.</p>
<pre><code>&gt;&gt;&gt; os.listdir()
['test']

&gt;&gt;&gt; os.rename('test','new_one')

&gt;&gt;&gt; os.listdir()
['new_one']
</code></pre>
<h4 id="removing-directory-or-file">Removing Directory or File</h4>
<p>A file can be removed (deleted) using the  <code>remove()</code>  method.</p>
<p>Similarly, the  <code>rmdir()</code>  method removes an empty directory.</p>
<pre><code>&gt;&gt;&gt; os.listdir()
['new_one', 'old.txt']

&gt;&gt;&gt; os.remove('old.txt')
&gt;&gt;&gt; os.listdir()
['new_one']

&gt;&gt;&gt; os.rmdir('new_one')
&gt;&gt;&gt; os.listdir()
[]
</code></pre>
<p>However, note that  <code>rmdir()</code>  method can only remove empty directories.</p>
<p>In order to remove a non-empty directory we can use the  <code>rmtree()</code>  method inside the  <code>shutil</code>  module.</p>
<pre><code>&gt;&gt;&gt; os.listdir()
['test']

&gt;&gt;&gt; os.rmdir('test')
Traceback (most recent call last):
...
OSError: [WinError 145] The directory is not empty: 'test'

&gt;&gt;&gt; import shutil

&gt;&gt;&gt; shutil.rmtree('test')
&gt;&gt;&gt; os.listdir()
[]
</code></pre>
<h2 id="python-errors-and-built-in-exceptions">Python Errors and Built-in Exceptions</h2>
<p>Python (interpreter) raises exceptions when it encounter errors. For example: divided by zero. In this article, you will learn about different exceptions that are built-in in Python.</p>
<p>When writing a program, we, more often than not, will encounter errors.</p>
<p>Error caused by not following the proper structure (syntax) of the language is called syntax error or parsing error.</p>
<pre><code>&gt;&gt;&gt; if a &lt; 3
  File "&lt;interactive input&gt;", line 1
    if a &lt; 3
           ^
SyntaxError: invalid syntax
</code></pre>
<p>We can notice here that a colon is missing in the  <code>if</code>  statement.</p>
<p>Errors can also occur at runtime and these are called exceptions. They occur, for example, when a file we try to open does not exist (<code>FileNotFoundError</code>), dividing a number by zero (<code>ZeroDivisionError</code>), module we try to import is not found (<code>ImportError</code>) etc.</p>
<p>Whenever these type of runtime error occur, Python creates an exception object. If not handled properly, it prints a traceback to that error along with some details about why that error occurred.</p>
<pre><code>&gt;&gt;&gt; 1 / 0
Traceback (most recent call last):
 File "&lt;string&gt;", line 301, in runcode
 File "&lt;interactive input&gt;", line 1, in &lt;module&gt;
ZeroDivisionError: division by zero

&gt;&gt;&gt; open("imaginary.txt")
Traceback (most recent call last):
 File "&lt;string&gt;", line 301, in runcode
 File "&lt;interactive input&gt;", line 1, in &lt;module&gt;
FileNotFoundError: [Errno 2] No such file or directory: 'imaginary.txt'
</code></pre>
<h4 id="python-built-in-exceptions">Python Built-in Exceptions</h4>
<p>Illegal operations can raise exceptions. There are plenty of built-in exceptions in Python that are raised when corresponding errors occur. We can view all the built-in exceptions using the  <code>local()</code>  built-in functions as follows.</p>
<pre><code>&gt;&gt;&gt; locals()['__builtins__']
</code></pre>
<h2 id="python-exception-handling---try-except-and-finally">Python Exception Handling - Try, Except and Finally</h2>
<p>You’ll learn how to handle exceptions in your Python program using try, except and finally statements. This will motivate you to write clean, readable and efficient code in Python.</p>
<h4 id="what-are-exceptions-in-python">What are exceptions in Python?</h4>
<p>Python has many built-in exceptionswhich forces your program to output an error when something in it goes wrong.</p>
<p>When these exceptions occur, it causes the current process to stop and passes it to the calling process until it is handled. If not handled, our program will crash.</p>
<p>For example, if  function  <code>A</code>  calls function  <code>B</code>  which in turn calls function  <code>C</code>  and an exception occurs in function  <code>C</code>. If it is not handled in  <code>C</code>, the exception passes to  <code>B</code>  and then to  <code>A</code>.</p>
<p>If never handled, an error message is spit out and our program come to a sudden, unexpected halt.</p>
<h4 id="catching-exceptions-in-python">Catching Exceptions in Python</h4>
<p>In Python, exceptions can be handled using a try statement.</p>
<p>A critical operation which can raise exception is placed inside the try clause and the code that handles exception is written in except clause.</p>
<p>It is up to us, what operations we perform once we have caught the exception. Here is a simple example.</p>
<pre><code># import module sys to get the type of exception
import sys

randomList = ['a', 0, 2]

for entry in randomList:
    try:
        print("The entry is", entry)
        r = 1/int(entry)
        break
    except:
        print("Oops!",sys.exc_info()[0],"occured.")
        print("Next entry.")
        print()
print("The reciprocal of",entry,"is",r)
</code></pre>
<p>o/p:</p>
<pre><code>The entry is a
Oops! &lt;class 'ValueError'&gt; occured.
Next entry.

The entry is 0
Oops! &lt;class 'ZeroDivisionError' &gt; occured.
Next entry.

The entry is 2
The reciprocal of 2 is 0.5
</code></pre>
<p>In this program, we loop until the user enters an integer that has a valid reciprocal. The portion that can cause exception is placed inside try block.</p>
<p>If no exception occurs, except block is skipped and normal flow continues. But if any exception occurs, it is caught by the except block.</p>
<p>Here, we print the name of the exception using  <code>ex_info()</code>  function inside  <code>sys</code>  module and ask the user to try again. We can see that the values ‘a’ and ‘1.3’ causes ValueError and ‘0’ causes ZeroDivisionError.</p>
<h4 id="catching-specific-exceptions-in-python">Catching Specific Exceptions in Python</h4>
<p>In the above example, we did not mention any exception in the  <code>except</code>  clause.</p>
<p>This is not a good programming practice as it will catch all exceptions and handle every case in the same way. We can specify which exceptions an except clause will catch.</p>
<p>A try clause can have any number of except clause to handle them differently but only one will be executed in case an exception occurs.</p>
<p>We can use a tuple of values to specify multiple exceptions in an except clause. Here is an example pseudo code.</p>
<pre><code>try:
   # do something
   pass

except ValueError:
   # handle ValueError exception
   pass

except (TypeError, ZeroDivisionError):
   # handle multiple exceptions
   # TypeError and ZeroDivisionError
   pass

except:
   # handle all other exceptions
   pass
</code></pre>
<h4 id="raising-exceptions">Raising Exceptions</h4>
<p>In Python programming, exceptions are raised when corresponding errors occur at run time, but we can forcefully raise it using the keyword raise.</p>
<p>We can also optionally pass in value to the exception to clarify why that exception was raised.</p>
<pre><code>&gt;&gt;&gt; raise KeyboardInterrupt
Traceback (most recent call last):
...
KeyboardInterrupt

&gt;&gt;&gt; raise MemoryError("This is an argument")
Traceback (most recent call last):
...
MemoryError: This is an argument

&gt;&gt;&gt; try:
...     a = int(input("Enter a positive integer: "))
...     if a &lt;= 0:
...         raise ValueError("That is not a positive number!")
... except ValueError as ve:
...     print(ve)
...    
Enter a positive integer: -2
That is not a positive number!
</code></pre>
<h4 id="try...finally">try…finally</h4>
<p>The try statement in Python can have an optional  <code>finally</code>  clause. This clause is executed no matter what, and is generally used to release external resources.</p>
<p>For example, we may be connected to a remote data center through the network or working with a file or working with a Graphical User Interface (GUI).</p>
<p>In all these circumstances, we must clean up the resource once used, whether it was successful or not. These actions (closing a file, GUI or disconnecting from network) are performed in the finally clause to guarantee execution.</p>
<p>Here is an example of file operations to illustrate this.</p>
<pre><code>try:
   f = open("test.txt",encoding = 'utf-8')
   # perform file operations
finally:
   f.close()
</code></pre>
<p>This type of construct makes sure the file is closed even if an exception occurs.</p>
<h2 id="python-custom-exceptions">Python Custom Exceptions</h2>
<p>You will learn to define custom exceptions depending upon your requirements.</p>
<p>Python has many built-in exceptions which forces your program to output an error when something in it goes wrong.</p>
<p>However, sometimes you may need to create custom exceptions that serves your purpose.</p>
<p>In Python, users can define such exceptions by creating a new class. This exception class has to be derived, either directly or indirectly, from  <code>Exception</code>  class. Most of the built-in exceptions are also derived form this class.</p>
<pre><code>&gt;&gt;&gt; class CustomError(Exception):
...     pass
...

&gt;&gt;&gt; raise CustomError
Traceback (most recent call last):
...
__main__.CustomError

&gt;&gt;&gt; raise CustomError("An error occurred")
Traceback (most recent call last):
...
__main__.CustomError: An error occurred
</code></pre>
<p>Here, we have created a user-defined exception called  <code>CustomError</code>  which is derived from the  <code>Exception</code>  class. This new exception can be raised, like other exceptions, using the  <code>raise</code>statement with an optional error message.</p>
<p>When we are developing a large Python program, it is a good practice to place all the user-defined exceptions that our program raises in a separate file. Many standard modules do this. They define their exceptions separately as  <code>exceptions.py</code>  or  <code>errors.py</code>  (generally but not always).</p>
<p>User-defined exception class can implement everything a normal class can do, but we generally make them simple and concise. Most implementations declare a custom base class and derive others exception classes from this base class. This concept is made clearer in the following example.</p>
<h4 id="example-user-defined-exception-in-python">Example: User-Defined Exception in Python</h4>
<p>In this example, we will illustrate how user-defined exceptions can be used in a program to raise and catch errors.</p>
<p>This program will ask the user to enter a number until they guess a stored number correctly. To help them figure it out, hint is provided whether their guess is greater than or less than the stored number.</p>
<pre><code># define Python user-defined exceptions
class Error(Exception):
   """Base class for other exceptions"""
   pass

class ValueTooSmallError(Error):
   """Raised when the input value is too small"""
   pass

class ValueTooLargeError(Error):
   """Raised when the input value is too large"""
   pass

# our main program
# user guesses a number until he/she gets it right

# you need to guess this number
number = 10

while True:
   try:
       i_num = int(input("Enter a number: "))
       if i_num &lt; number:
           raise ValueTooSmallError
       elif i_num &gt; number:
           raise ValueTooLargeError
       break
   except ValueTooSmallError:
       print("This value is too small, try again!")
       print()
   except ValueTooLargeError:
       print("This value is too large, try again!")
       print()

print("Congratulations! You guessed it correctly.")
</code></pre>
<p>Here is a sample run of this program.</p>
<pre><code>Enter a number: 12
This value is too large, try again!

Enter a number: 0
This value is too small, try again!

Enter a number: 8
This value is too small, try again!

Enter a number: 10
Congratulations! You guessed it correctly.
</code></pre>
<p>Here, we have defined a base class called  <code>Error</code>.</p>
<p>The other two exceptions (<code>ValueTooSmallError</code>  and  <code>ValueTooLargeError</code>) that are actually raised by our program are derived from this class. This is the standard way to define user-defined exceptions in Python programming, but you are not limited to this way only.</p>
<h2 id="python-object-oriented-programming">Python Object Oriented Programming</h2>
<p>you’ll learn about the Object Oriented Programming (OOP) in Python and their fundamental concept with examples.</p>
<h4 id="introduction-to-oops-in-python">Introduction to OOPs in Python</h4>
<p>Python is a multi-paradigm programming language. Meaning, it supports different programming approach.</p>
<p>One of the popular approach to solve a programming problem is by creating objects. This is known as Object-Oriented Programming (OOP).<br>
An object has two characteristics:</p>
<ul>
<li>attributes</li>
<li>behavior</li>
</ul>
<p>Let’s take an example:<br>
Parrot is an object,</p>
<ul>
<li>name, age, color are attributes</li>
<li>singing, dancing are behavior</li>
</ul>
<p>The concept of OOP in Python focuses on creating reusable code. This concept is also known as DRY (Don’t Repeat Yourself).</p>
<p>In Python, the concept of OOP follows some basic principles:<br>
Inheritance<br>
A process of using details from a new class without modifying existing class.<br>
Encapsulation<br>
Hiding the private details of a class from other objects.<br>
Polymorphism<br>
A concept of using common operation in different ways for different data input.</p>
<h4 id="class">Class</h4>
<p>A class is a blueprint for the object.</p>
<p>We can think of class as an sketch of a parrot with labels. It contains all the details about the name, colors, size etc. Based on these descriptions, we can study about the parrot. Here, parrot is an object.</p>
<p>The example for class of parrot can be :</p>
<pre><code>class Parrot:
    pass
</code></pre>
<p>Here, we use  <code>class</code>  keyword to define an empty class  Parrot. From class, we construct instances. An instance is a specific object created from a particular class.</p>
<h2 id="object">Object</h2>
<p>An object (instance) is an instantiation of a class. When class is defined, only the description for the object is defined. Therefore, no memory or storage is allocated.</p>
<p>The example for object of parrot class can be:</p>
<pre><code>obj = Parrot()
</code></pre>
<p>Here,  obj  is object of class  <code>Parrot</code>.</p>
<p>Suppose we have details of parrot. Now, we are going to show how to build the class and objects of parrot.</p>
<pre><code>class Parrot:

    # class attribute
    species = "bird"

    # instance attribute
    def __init__(self, name, age):
        self.name = name
        self.age = age

# instantiate the Parrot class
blu = Parrot("Blu", 10)
woo = Parrot("Woo", 15)

# access the class attributes
print("Blu is a {}".format(blu.__class__.species))
print("Woo is also a {}".format(woo.__class__.species))

# access the instance attributes
print("{} is {} years old".format( blu.name, blu.age))
print("{} is {} years old".format( woo.name, woo.age))
</code></pre>
<p>o/p:</p>
<pre><code>Blu is a bird
Woo is also a bird
Blu is 10 years old
Woo is 15 years old
</code></pre>
<p>In the above program, we create a class with name Parrot. Then, we define attributes. The attributes are a characteristic of an object.</p>
<p>Then, we create instances of the  Parrot  class. Here,  blu  and  woo  are references (value) to our new objects.</p>
<p>Then, we access the class attribute using  <code>__class __.species</code>. Class attributes are same for all instances of a class. Similarly, we access the instance attributes using  <code>blu.name</code>  and  <code>blu.age</code>. However, instance attributes are different for every instance of a class.</p>
<h3 id="methods">Methods</h3>
<p>Methods are functions defined inside the body of a class. They are used to define the behaviors of an object.</p>
<pre><code>class Parrot:
    
    # instance attributes
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    # instance method
    def sing(self, song):
        return "{} sings {}".format(self.name, song)

    def dance(self):
        return "{} is now dancing".format(self.name)

# instantiate the object
blu = Parrot("Blu", 10)

# call our instance methods
print(blu.sing("'Happy'"))
print(blu.dance())
</code></pre>
<p>o/p:</p>
<pre><code>Blu sings 'Happy'
Blu is now dancing
</code></pre>
<p>In the above program, we define two methods i.e <code>sing()</code> and <code>dance()</code>. These are called instance method because they are called on an instance object i.e <code>blu</code>.</p>
<h3 id="inheritance">Inheritance</h3>
<p>Inheritance is a way of creating new class for using details of existing class without modifying it. The newly formed class is a derived class (or child class). Similarly, the existing class is a base class (or parent class).</p>
<pre><code># parent class
class Bird:
    
    def __init__(self):
        print("Bird is ready")

    def whoisThis(self):
        print("Bird")

    def swim(self):
        print("Swim faster")

# child class
class Penguin(Bird):

    def __init__(self):
        # call super() function
        super().__init__()
        print("Penguin is ready")

    def whoisThis(self):
        print("Penguin")

    def run(self):
        print("Run faster")

peggy = Penguin()
peggy.whoisThis()
peggy.swim()
peggy.run()
</code></pre>
<p>o/p:</p>
<pre><code>Bird is ready
Penguin is ready
Penguin
Swim faster
Run faster
</code></pre>
<p>In the above program, we created two classes i.e.  Bird  (parent class) and  Penguin  (child class). The child class inherits the functions of parent class. We can see this from  <code>swim()</code>method. Again, the child class modified the behavior of parent class. We can see this from whoisThis() method. Furthermore, we extend the functions of parent class, by creating a new  <code>run()</code>  method.</p>
<p>Additionally, we use  <code>super()</code>  function before  <code>__init__()</code>  method. This is because we want to pull the content of  <code>__init__()</code>  method from the parent class into the child class.</p>
<h3 id="encapsulation">Encapsulation</h3>
<p>Using OOP in Python, we can restrict access to methods and variables. This prevent data from direct modification which is called encapsulation. In Python, we denote private attribute using underscore as prefix i.e single “ _ “ or double “ __“.</p>
<pre><code>class Computer:

    def __init__(self):
        self.__maxprice = 900

    def sell(self):
        print("Selling Price: {}".format(self.__maxprice))

    def setMaxPrice(self, price):
        self.__maxprice = price

c = Computer()
c.sell()

# change the price
c.__maxprice = 1000
c.sell()

# using setter function
c.setMaxPrice(1000)
c.sell()
</code></pre>
<p>o/p:</p>
<pre><code>Selling Price: 900
Selling Price: 900
Selling Price: 1000
</code></pre>
<p>In the above program, we defined a class Computer. We use <code>__init__()</code> method to store the maximum selling price of computer. We tried to modify the price. However, we can’t change it because Python treats the __maxprice as private attributes. To change the value, we used a setter function i.e <code>setMaxPrice()</code> which takes price as parameter.</p>
<h3 id="polymorphism">Polymorphism</h3>
<p>Polymorphism is an ability (in OOP) to use common interface for multiple form (data types).</p>
<p>Suppose, we need to color a shape, there are multiple shape option (rectangle, square, circle). However we could use same method to color any shape. This concept is called Polymorphism.</p>
<pre><code>class Parrot:

    def fly(self):
        print("Parrot can fly")
    
    def swim(self):
        print("Parrot can't swim")

class Penguin:

    def fly(self):
        print("Penguin can't fly")
    
    def swim(self):
        print("Penguin can swim")

# common interface
def flying_test(bird):
    bird.fly()

#instantiate objects
blu = Parrot()
peggy = Penguin()

# passing the object
flying_test(blu)
flying_test(peggy)
</code></pre>
<p>o/p:</p>
<pre><code>Parrot can fly
Penguin can't fly
</code></pre>
<p>In the above program, we defined two classes  Parrot  and  Penguin. Each of them have common method  <code>fly()</code>  method. However, their functions are different. To allow polymorphism, we created common interface i.e  <code>flying_test()</code>  function that can take any object. Then, we passed the objects  blu  and  peggy  in the  <code>flying_test()</code>  function, it ran effectively.</p>
<pre><code>Thanks!
</code></pre>

