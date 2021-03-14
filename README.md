# count-down-timer
Count down timer with optional to-do list tied to an event
Enter today's (or starting date)
After accepting today's date/starting date the process of determining if this is a valid date goes through several steps
first if statement: if not a valid date print first date is invalid
Enter the date of event in mm/dd/yy format
second if statement: if not a valid dte print second date is invalid
third if (nested if statement x 3 else x 2 else if x 1)  statement starts the process of figuring out the difference between the two day dates.  
Same process with the two month dates
is it a leap year?  in the book.
calculate the distance years, months, and days
prompt how many to-do list items to enter
used an open string and fgets to create an empty string that is 60 characters long to contain input
If 0 is entered display countdown timer
otherwise prompt for to-do list items equal to number inputted; at this time this is an infinitie loop and will keep giving more to-do list prompts.
then the due date of to do list item = have written this several times.  Not sure if I missed something on the number of statements that can be put into a for loop but I think I need to restructure this and the to do list task with a do-while loop
display coundown timer with to list item below it and due dates.  
end
