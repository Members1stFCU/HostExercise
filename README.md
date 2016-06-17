#Host Programming Exercise

The goal of the programming exercises is to provide a foundation for the technical interview.  Complete the exercises to the best of your ability.

There are two exercises:

 - Sweepstakes – Submit an Entry
 - Sweepstakes – Pick a Winner

Details and instructions for each are provided in this document.  Please submit your completed exercise prior to the interview so our team has time to review your completed work.

Please let us know if you do not have access to the resources required to complete these exercises and we will schedule time at our facilities to allow you time to work on the exercise prior to the interview.

##Sweepstakes
M1 is running a pretend sweepstakes.  The following programs have been built to meet this need, but are not finished.

Requirements:

 - Users enter the sweepstakes online.
 - Users must provide their name, address, birthdate and contact info to enter the sweepstakes.
 - Winner cannot be an employee.
 - Winner must be over 18.

The business requirements may not be complete and are subject to changes.  Please review the code provided and execute the defined tasks and resolve the reported bugs for each program.

And one final note, please exercise some suspended disbelief as there are gaps and some programming magic not defined here to get the data from the online entry to our batch process.  Thanks and Happy Programming!

####Submit an Entry – HTML exercise

Using the program provided on [Plunker](http://plnkr.co/edit/bURBD9KioV7vxZwJMp6Q?p=info) please execute the following tasks and resolve the reported bugs.  You can fork the solution to solve it or download the contents to a zip file.

**Tasks**

 - Users now have an option to use phone number instead of email address.
   - Add in phone number field
   - Add in drop down to pick contact method
   - If drop down is phone number show phone number field
   - If drop down is email address show email address field
 - Add in simple date validation for the birthdate field (required if shown)
 - Add in simple email validation to the email field (required if shown)
 - We are getting requests to always adjust the label font size, is there an easier way?
 - The labels look strange, could you put them on top of the input boxes?
 - Once the page is submitted display confirmation page of what the user just submitted.
​

**Bugs**
​
 - It appears the Reset button does not work, how can this be fixed?
 - Users are hitting Reset by accident, space the buttons further apart and adjust size of Reset and make Submit more prominent.
 - People are submitting information without reviewing their entry information.  Please add in a message before the form is submitted.
​
​
####Pick a Winner – Batch Programming Exercise
Because `PowerOn` is a proprietary language we adapted this program to pseudo code like language with a hint of javascript.  The code has been commented to provide some guidance.  Use a text editor to write your code to address the bugs and new tasks.
​
**Tasks**
​
 - 3 new reports are needed
​

    *NOTE:  between the page margins output is limited to 100 characters per line or the report terminates in error.*
​
 - Valid Entry Report
   - Output:  `Name, Address, Email, Phone`
 - Invalid Entry Report:
   - Output:  `Name, Email, Phone, Rule Violation`
 - Winner Report
    - Output: `Name, Address, Email, Phone`
​
 - Marketing wants to run the sweepstakes each month.  With this additional requirement we need to track the winners and check to ensure that a previous winner does not win again.
​
 - Code review time – do you have any clean-up suggestions for this program?
​

**Bugs**
​
 - We finally tested and the same person keeps winning every time we test.  Please fix.
