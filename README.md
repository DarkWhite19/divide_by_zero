# divide_by_zero
What happens when you divide by zero?
print(5/0)
#Here's what you should have seen when you submitted the Divide by Zero code above:

Traceback (most recent call last):
  File "/tmp/vmuser_tnryxwdmhw/quiz.py", line 1, in <module>
    print(5/0)

ZeroDivisionError: division by zero
Traceback means "What was the programming doing when it broke"! This part is usually less helpful than the very last line of your error. Though you can dig through the rest of the error, looking at just the final line ZeroDivisionError, and the message says we divided by zero. Python is enforcing the rules of arithmetic!

In general, there are two types of errors to look out for

Exceptions
Syntax
An Exception is a problem that occurs when the code is running, but a 'Syntax Error' is a problem detected when Python checks the code before it runs it.
