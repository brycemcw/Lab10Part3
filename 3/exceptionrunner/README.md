Tasks to answer in your own README.md that you submit on Canvas:

1.  See logger.log, why is it different from the log to console?
The Log file gives the specifics of how the output is to be formatted and what is to be displayed to the console. Not everything from the Log will be displayed to the console. 


1.  Where does this line come from? FINER org.junit.jupiter.engine.execution.ConditionEvaluator logResult Evaluation of condition [org.junit.jupiter.engine.extension.DisabledCondition] resulted in: ConditionEvaluationResult [enabled = true, reason = '@Disabled is not present']



1.  What does Assertions.assertThrows do?
The assertion either crashes the program or does nothing based on if an exception is thrown or not. If an exception
is not thrown, then the program will crash. 

1.  See TimerException and there are 3 questions
    1.  What is serialVersionUID and why do we need it? (please read on Internet)

    The serialVersionUID is a unique identifier for serializable classes. They are used when an object is becominning deserialized. 

    2.  Why do we need to override constructors?

    If we need to clarify different instructions for a class, then we override constructors. 

    3.  Why we did not override other Exception methods?	

    We would only need to override Exception methods that we consider as necessary for our proogram. 


1.  The Timer.java has a static block static {}, what does it do? (determine when called by debugger)

    This is a static function that is excuted one time when a class is initially loaded. 


1.  What is README.md file format how is it related to bitbucket? (https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html)

    Read Me Files are files that are automatiacally read out by services like github or bitbucket that users write to explain how their program works. Users can stylize .md files using different formats 

    ### Like This
    # or like this
    *or like this*

    you can even specify code

    ```java
        System.out.println("howdy there");
    ```


1.  Why is the test failing? what do we need to change in Timer? (fix that all tests pass and describe the issue)

    The test is failing because the function is throwing a different exception rather than the time exception specified. 
    We can fix it by removing the finally block and adding the TimeException parameter to the catch block to test for. 

1.  What is the actual issue here, what is the sequence of Exceptions and handlers (debug)

    The issue is the exception was throwing a NullPointerException instead of the expected TimeException. 


1.  Make a printScreen of your eclipse JUnit5 plugin run (JUnit window at the bottom panel) 


1.  Make a printScreen of your eclipse Maven test run, with console


1.  What category of Exceptions is TimerException and what is NullPointerException

    NullPointerException is a built in exception and the TimerException is a user defined exception. 

1.  Push the updated/fixed source code to your own repository.

