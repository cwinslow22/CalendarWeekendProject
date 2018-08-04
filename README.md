# Calendar   There is a AugustData.js file that features an array of objects date, and day of the week properties available to get started with at least one month. 
This is my own project to recap Week 7 at Lambda School. Building a Calendar that will also have the ability to create task on each day of the week in the month. 
#This is a Project I built to recap Week 7 at Lambda School

The objective is to use the skills learned on the todo list app add a task and delete a task and implement this ability on each day of the week in a month.

Each day should have the ability to add a task as well as see the current task listed.

Upon clicking on a task you should be able to mark it as done. This should be seen via a line through the task. A button should be available to clear the task that has been completed.

Since this is a digital calendar it has the ability to have multiple different pictures so a carousel will be used to display this effect above the days/weeks of the month and just underneath the Month.


One way of approaching this project is to separate the month data into arrays based on the day of the week. Passing the day of the week down as props and then filtering the AugustData.js file based off data and utilizing the curry function we saw on Fridays sprint challenge so that the correct date shows up on the right day of the week. 

The Clear completed and mark shift spots in the design would be the buttons to clear and shift.  Prev month and next month will also be clickable to change the month if it is desired to make a full calendar and not just one month. As this can be a lot, the objective is to use the skills learned this week to design a one month calendar. Developing an algorithm to get every day of the year and moving forward would be a good idea for a portfolio/ resume piece but this weekend's objective is repetition and review. 


Advanced ideas/features.
Saving the task on localhost so that refresh allows the data to remain saved. A search bar to the left of the calendar that allows for the searching of the task and displays the dates on the sidebar where that task shows up.

If a task is not completed the ability to double click and shift the task to the next day. On double click would highlight(in red) the task and then a button would shift that task to the next day. This could be difficult as it was not demonstrated this week but can push for mastery of using React. I believe it to be possible.

Attempt to use moment.js to format the dates for the month to match the day of the week it should be in life. Add other months.

Add functionality so that you can click to different months and also have the same features.
