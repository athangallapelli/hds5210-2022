# Notes on the Midterm

* _Correctness    (out of 40):_ 39
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 6

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

You have good docstring documentation, but you didn't include any test conditions in your docstrings.  I've deducted 4 points from _Docs / Testing_ for that because it was consistent on every part.

## Step 1
* Good work. Not additional comments.

## Step 2
* The more Python style of looping is to use `for item in list` or `for idx, item in enumerate(list)` rather than using `range(len(list))`.  I've deducted 1 point from _Good Practices_ for this because it makes the code much more difficult to read.

## Step 3
* I like the use of `%A` to test for `Monday`
* Your choice to use exceptions here is interesting. It probably isn't a great choice to catch all exception types and return None, as if the matching billing / service code couldn't be found.  That will cause confusion.

## Step 4
* You have a typo in your hospital branch of code here. It says `adj_rate - by_hospital[hp]` instead of `adj_rate = by_hospital[hp]`, so your totals by hospital are not coming up correct.  I've deducted 1 point from _Correctness_ for this.