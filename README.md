# Google Python Class

The whole project is from the [Google Python Class](https://developers.google.com/edu/python/). I am trying to solve the exercise problems and post them here.


## hello.py
Simple "Hello World" task. Just remember to put a standard boilerplate that calls the main() function.

```python
if __name__ == '__main__':
  main()
```
## string.py
Very simple. Remember that multiple "returns" could be used in one function, for example, question A:

```python
def donuts(count):
    
    if count < 10:
        return 'Number of donuts: ' + str(count)
    else:
        return 'Number of donuts: many'
```


## list.py
Still simple. Question E demonstrates the linear merge algorithm, and pay attention to use of list.pop() method.  

## wordcount.py
This one is pretty hard. We need to build up a dictionary, where we map each distinct word (as the key) into its cumulative count (as the value). 

So the work flow:

1. open the file
2. read one line (or the whole file at once) as a string
3. break the string into a list
4. remove punctuations
5. convert into lower case
6. map into dictionary

The print out is just the sorted dictionary, by the key, or by the value.


## mimic.py
This project is a lot like the previous one. What we could learn from the solution is the way they construct loops.



PS: Right now I have finished the all five projects in the Basic Exercise, and I would like to take a break. Honestly speaking, I am not very satisfied with the  current split between Python 2 vs Python 3, and I wish that Python 3 will be stable and popular in the near future.