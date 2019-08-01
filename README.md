# IRB

## Learning Goals

+ Explain why REPLs are useful
+ Use IRB to execute Ruby expressions
+ Identify return values in IRB
+ Define Evaluation in the context of a REPL
+ Describe what IRB is

## Outline

+ Describe the process for testing code
  + We want to make sure that code does what we expect it to do
  + Before testing any code, ask yourself, what are you expecting to happen?+ One quick way to test code - type it into something that can evaluate it quickly
+ One great example of this is a REPL - REPL stands for Read, Evaluate, Print, and Loop
+ So the REPL will read the code, evaluate what it returns, print out that return value, and then start over again
+ Ruby comes with a REPL called Interactive Ruby, or IRB. (I for interactive, RB for Ruby, like a .rb file)
+ If I type in 10 + 10, I expect that this will return "20" -> when I type enter, that's what we see
+ this symbol here is letting me know that this is the return value of the previous line - this is just a convention for how to write this. 
+ Now, let's try a different one. I type in 9/2, I expect to see 4.5. When I press enter - whoa, I see 4, not 4.5. Now, I can ask myself why I'm seeing something different. In this case, I forgot that doing division with Integers always returns a whole number. 
+ Sometimes, you may see an error message, or a different return value, or something completely different. But IRB is one great way to quickly test out your code.   


