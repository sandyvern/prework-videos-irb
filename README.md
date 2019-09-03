# IRB

## Learning Goals

+ Describe why REPLs are useful for testing code
+ Define Evaluation in the context of a REPL
+ Use IRB to execute Ruby expressions
+ Identify return values in IRB

## Outline

+ Hi guys, it's Ian from Flatiron School. In this video, we're going to learn all about IRB. By the end of this video, you should be able to:
+ Describe why REPLs are useful for testing code
+ Define Evaluation in the context of a REPL
+ Use IRB to execute Ruby expressions
+ Identify return values in IRB
+ Let's go ahead and get started. I'm here in the Learn IDE sandbox, and I'd like to have a way to quickly test out some code.
+ Maybe I just learned about a new string method, or I'm not sure about what a line of code will return, but sometime it's nice to have a little playground if you will to test things out.
+ A really important part of programming is being able to ask yourself - what do you expect a line of code to do? And, did it do what you were expecting? If not, why not? So you really need to be able to test things out like this.
+ One great way to do this is to use a REPL. REPL stands for Read, Evaluate, Print, and
+ In this case, Evaluation means basically running one line of code and showing you what that one line would return.
+ Basically, these are quick interpreters that read the code, evaluate what it does, print you out the return value, and then start over again
+ Ruby comes with a built-in REPL called IRB - short for Interactive Ruby.
+ So, from my terminal, I can type irb and press enter
+ Now, I see this carrot character at the start of the line, and I know I'm in my Interactive Ruby shell.
+ Any code I type here will be evaluated line by line, with the result of that line printed out.
+ When I type `1 + 1` and type enter - we see 2 is printed out. And this arrow-looking thing `=>` - that identifies that was the return value of the previous expression
+ In this case, I can see that the expression `1 + 1` did return what I was expecting. Now, let me test `"1" + "1"` - now, I might be expecting this to return `"2"` as a string. When I run this, I can see the return value is actually `"11"`
+ So now I get to ask myself, why am I not seeing what I was expecting to? In this case, it's because when you use the `+` operator on a string, it just combines it with another string.
+ So that's basically it - you can use IRB to test out all kinds of things, and this will be really useful going forward. Just to recap what we discussed:
+ We talked about what a REPL is and why it's useful for testing code
+ We discussed what we mean by "Evaluation" in this context - the REPL is telling us what that one line of code returns
+ We used IRB to execute, or run, a few different Ruby expressions
+ And we identified the return values by the little arrow `=>` character
+ Thanks so much for watching - happy coding! 
