# List1 and List2
For this assignment, you'll be coding some list manipulation functions within the `list1.py` and `list2.py` files.

There is some light dependency on knowing how
[functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
work in python in terms of argument passing and return values, but you should
be able to figure it out as you go.

## Instructions
Complete all of the functions in `list1.py` and `list2.py` based on your knowledge of Python lists, indexing, slicing, and methods. Make sure all the included tests are passing before submitting your work.

Run the programs from the command line like this:
```console
$ python list1.py
```
 
Here is a sample output. You can see that for the `match_ends()` function, some tests are passing, others are failing.
```
$ python list1.py
match_ends
 OK  got: 3     expected: 3
  X  got: None     expected: 2
 OK  got: 1     expected: 1

front_x
  X  got: None     expected: ['xaa', 'xzz', 'axx', 'bbb', 'ccc']
  X  got: None     expected: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc']
  X  got: None     expected: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix']

sort_last
  X  got: None     expected: [(2, 1), (3, 2), (1, 3)]
  X  got: None     expected: [(3, 1), (1, 2), (2, 3)]
  X  got: None     expected: [(2, 2), (1, 3), (3, 9, 4), (1, 7)]
```

## PR (Pull Request) Workflow for this assignment
1. *Fork* this repository into your own personal GitHub account.
2. *Clone* your own repo to your local development machine.
3. Create a separate branch named `dev` and checkout the branch.
5. Commit your changes, then `git push` the branch back to your own GitHub account.
5. From your own GitHub repo, create a pull request (PR) *from your `dev` branch back to **your own** master*.
6. Copy/Paste the URL **link to your PR** as your assignment submission.
7. Your grader will post code review comments inline within your pull request in your GitHub account. Be sure to respond to any comments and make requested changes. **RESUBMIT** a new link to your PR after making changes. This is the code review iteration cycle.
