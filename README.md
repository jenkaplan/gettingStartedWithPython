#Python

Python is a programming language that has simple syntax that's relatively easy to learn. This allows you to spend less time trying ot find and fix syntax errors. 

Python was created by Guido Van Rossum. It was started in the 1980s, but was first released in February 1991.


##Simple Code Snippet

```python
a = 2
b = 3
sum = a + b
print(sum)
```
##Download Python


Link to download Python: https://www.python.org/downloads/

##Use Case

If you recall, we used Python in the command line to generate a secret key when we added authentication to our Fazbook apps:

These are the instructions from Vince with our comments to help make it understandable:

You can generate a secret key using Python on the command line like so:

 This calls for the bash python commands
```
$ python
```
This calls for the operating system.
```
import os
```
Then you call the os that was declared above and ask for a random string that is 24 characters long
```
os.urandom(24)
```
Then it returns a string like this...
```
"\x02\xf3\xf7r\t\x9f\xee\xbbu\xb1\xe1\x90\xfe'\xab\xa6L6\xdd\x8d[\xccO\xfe"
```
