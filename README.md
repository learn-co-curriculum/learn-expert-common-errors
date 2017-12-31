
## Common Problems

I just want to take a minute to go over a few common problems we see and how to fix them. 

### All JS methods are undefined

![](https://s3.amazonaws.com/learn-experts/common-errors-function-is-not-defined.png)

With the newer JS curriculum (the curriculum with Mocha tests), if there is a syntax error in your JS file, the test will not be able to load up the file and will come back with errors saying that all functions are undefined. 

You may be able to pick out the syntax error with your skilled javascript eyes, but in this case, we want to try and give the student the tools to find this error on their own. The quickest solution here is to simply take the code and paste it in chrome console. When you hit enter, you'll get a message that there is a syntax error, and if you click on the note to the right, Chrome will highlight the location of the error for you.

![](https://s3.amazonaws.com/learn-experts/common-errors-console.gif)

This is a quick way to find the error _and_ give the student the tools find it on their own the next time.

## Resources

* [Other Common Lab Errors](https://github.com/flatiron-labs/learn-support/blob/master/common-lab-errors.md)

# Important Note
If you find you're encountering the same issue frequently and think it might be a good candidate for inclusion in this doc, [create an issue on this Github repo](https://github.com/flatiron-labs/learn-support/issues/new). Make sure the issue title begins with 'Common Problems: '.  In your issue, be sure to first describe the problem in detail, including any information required to recognize it and distinguish it from other possible issues. Next, describe how to resolve the problem. Screenshots are sometimes helpful for this, so be sure to include one or two if relevant.