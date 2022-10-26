# REPLIT
Replit is an interface running a rep with basics environment needs.
This meeans this has the back environment of programming languages to  
kick start some course straight away.  
( includes interpreters, compiler, the language itself )
However this is not the same as running in into one's own environment  
as we do not have access that freely to the terminal  

Ex: command to run a file
`python <path-file>.py`
The environment mainly runs main.py  no other paths unless we provide config.
```sh
run="python 01_basics/01-fundamentals_discovering-python.py"
run="python 01_basics/02-fundamentals_data-types-number.py"
run="python 01_basics/03-fundamentals_math-functions.py"
run="python 01_basics/04-fundamentals_operator-precedence.py"
```



## Configure Replit
### Enabling Replit to run a specific page
- .replit file: either you replace run command opening by default a path  
  resource: https://replit.com/talk/ask/How-to-run-another-python-file-not-the-mainpy/29188
  WARNING: the .replit file approach does not last between session which mean each time you have to instruct replit to run the updated command
- either you import your code to run with main ( mentioned in above URL )


# DEVELOPER FUNDAMENTALS
Don't read the dictionary: Do not read and learn everything about a  
programming languages: know only what exists in order to get back to it  
instead of memorizing it


# INDENTATION IN PYTHON
Identation and spaces are important with Python turning it mandatory
whereas in other languages it is not and is mainly relate to enhance
code readability
The Python interpretor considers spaces ( space or tab ) with meanings
to interprete the code

https://stackoverflow.com/questions/39983695/what-is-truthy-and-falsy-how-is-it-different-from-true-and-false

# WHAT IS OOP?
Object Oriented Programming is a 
Every thing is an objects - Object have methods and attributes on their own
We can create our own types

OOP is a paradigm to structure the code in order to    
ease to maintainability.
Breaking up the code in smaller pieces (*in objects*) in order to have those objects enable to be worked on separately

https://en.wikipedia.org/wiki/History_of_programming_languages

## VOCABULARY WITH CLASS
- instanciate: fact to associate a class to a variable

## CUSTOM OBJECT / TYPE
Can create our own type using `class` keyword (Advanced/OOP)['./03_advanced-python_OOP/01_OOP.py']
### Under __init__
Lines with self => will associate dynamic attributes

### METHODS
All functions defined within and starting with `def`
are methods that will be available for all instance