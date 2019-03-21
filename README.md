# javascript-developer-exercises
#### Some JavaScript developer exercises to use as a pre-screen for job interviews

Just fork this repo (or download it) and look at each of the files in the `exercises` folder.

#### What to do
Each exercise will have the shell of some code as well as a description, in comments, as to what you need to add to the code to get the desired result and what the desired result is.  It will also tell you how to run the code in Node.js, as well.

You are only allowed to add code between the following comments in an exercise:

    // PLACE YOUR CODE BELOW
    
    // PLACE YOUR CODE ABOVE

You can add as many lines as you like, assuming the exercise doesn't specifically restrict that (some do).  If there are multiple instances of those code placement pairs, then you can add code within each of them, if you feel the need to.

For example, given the following exercise:

    function sayHello(name) {
      // add code here that will take the name param and
      // say hello in the form of "Hello, <Name_Here>!" to the console
      // PLACE YOUR CODE BELOW
      
      // PLACE YOUR CODE ABOVE
    }

    sayHello('Michael')

    // Expected output to the console when run with 'node sample_exercise.js' would be:
    // Hello, Michael!

So in this particular case, we're looking for you to modify the code so that it looks something like the following:

    function sayHello(name) {
      // add code here that will take the name param and
      // say hello in the form of "Hello, <Name_Here>!" to the console
      // PLACE YOUR CODE BELOW

      console.log('Hello, %s!', name)
      
      // PLACE YOUR CODE ABOVE
    }

    sayHello('Michael')

Its output when run with the `node sample_exercise.js` command should be:

    Hello, Michael!

There are obviously many ways this could be written.  You get to choose how you do things, but we might have opinions as to which solutions we prefer to see.  Don't try to make things overly complex, but do make sure that you aren't simply hard-coding an answer.  For example, coding the above exercise so that it used `console.log('Hello, Michael!')` hard coded like that, so that it wouldn't work with a call of `sayHello('Jane')`, is not acceptable.

#### Requirements
You will need to have a recent version of Node.js installed to run your code.  We make use of some built-in Node modules for testing the results of your code, such as our use of Node's `assert.deepEqual()` call in exercise 2.  You may feel free to use ES6 constructs for your work, as well.  Some of the exercises might be ES6-specific, even.

#### Rules and Expectations
If you don't know how to do something, feel free to look it up and work up a solution.  Take as long as you like.  This is meant to test your ability to get things done, not necessarily to get things done from memory in a few minutes time.  A real development job rarely leaves you disconnected from the internet with only a few minutes to complete a task....

*Not all positions require you to be able to solve all exercises.  Do what you can.*

#### Submitting your work
Once you have completed your exercises (or as many as you can), email the URL of your forked project or a ZIP file of the actual project to your recruiter so that it may be forwarded on to me.  If you aren't using a recruiter, then just send it to your point of contact with my company.

