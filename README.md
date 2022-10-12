# Welcome to the AirBnB Clone Project!  
   
### What’s a command interpreter?  
Do you remember the Shell? It’s exactly the same but limited to 
a specific use-case. In our case, we want to be able to manage 
the objects of our project:  
  
- Create a new object (ex: a new User or a new Place)  
- Retrieve an object from a file, a database etc…  
- Do operations on objects (count, compute stats, etc…)  
- Update attributes of an object  
- Destroy an object  

### Web static, what?  
Before developing a big and complex web application, 
we will build the front end step-by-step.  
  
The first step is to “design” / “sketch” / “prototype” each element:  
- Create simple HTML static pages  
- Style guide  
- Fake contents  
- No Javascript  
- No data loaded from anything  
  
## Requirements  
  
### General Info  
- Allowed editors: `vi`, `vim`, `emacs`  
- All your files should end with a new line  
- A `README.md` file, at the root of the folder of the project, is mandatory  
- Your code should be W3C compliant and validate with `W3C-Validator`  
- All your CSS files should be in `styles` folder  
- All your images should be in `images` folder  
- You are not allowed to use `!important` and `id` (`#...` in the CSS file)  
- You are not allowed to use tags `img`, `embed` and `iframe`  
- You are not allowed to use Javascript  
- Current screenshots have been done on `Chrome 56` or more  
- No cross browsers  
- You have to follow all requirements but some `margin`/`padding`  
  are missing - you should try to fit as much as you can to screenshots  
  
### Python Scripts  
- Allowed editors: `vi`, `vim`, `emacs`  
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS  
using python3 (version 3.8.5)  
- All your files should end with a new line  
- The first line of all your files should be exactly `#!/usr/bin/python3`  
- A `README.md` file, at the root of the folder of the project, is mandatory  
- Your code should use the pycodestyle (version 2.7.*)  
- All your files must be executable  
- The length of your files will be tested using `wc`  
- All your modules should have a documentation 
`(python3 -c 'print(__import__("my_module").__doc__)')`  
- All your classes should have a documentation 
`(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`  
- All your functions (inside and outside a class) should have a 
documentation `(python3 -c 'print(__import__("my_module").my_function.__doc__)'` 
and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')`  
- A documentation is not a simple word, it’s a real sentence explaining 
what’s the purpose of the module, class or method (the length of it will 
be verified)  
  
### Python Unit Tests  
- Allowed editors: `vi`, `vim`, `emacs`  
- All your files should end with a new line  
- All your test files should be inside a folder `tests`  
- You have to use the `unittest module`  
- All your test files should be python files (extension: `.py`)  
- All your test files and folders should start by `test_`  
- Your file organization in the tests folder should be the 
same as your project  
- e.g., For `models/base_model.py`, unit tests must be in: 
`tests/test_models/test_base_model.py`  
- e.g., For `models/user.py`, unit tests must be in: 
`tests/test_models/test_user.py`  
- All your tests should be executed by using this command: 
`python3 -m unittest discover tests`  
- You can also test file by file by using this command: 
`python3 -m unittest tests/test_models/test_base_model.py`  
- All your modules should have a documentation 
`(python3 -c 'print(__import__("my_module").__doc__)')`  
- All your classes should have a documentation 
`(python3 -c 'print(__import__("my_module").MyClass.__doc__)')`  
- All your functions (inside and outside a class) should have a 
documentation `(python3 -c 'print(__import__("my_module").
my_function.__doc__)'` and `python3 -c 'print(__import__
("my_module").MyClass.my_function.__doc__)')`  
- We strongly encourage you to work together on test cases, 
so that you don’t miss any edge case
  
## More Info  
  
### Execution  
Your shell should work like this in interactive mode:  
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```  
But also in non-interactive mode: (like the Shell project in C)  
```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```  
All tests should also pass in non-interactive mode: 
`$ echo "python3 -m unittest discover tests" | bash`  

<p>
  <img src="/images/hbnb.png" alt="hbnb logo" class="center"/>
</p>