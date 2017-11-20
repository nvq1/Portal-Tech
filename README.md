# Portal-Tech

Task 2
<html>
<head>Task 2</head>
<body>
//Inital array
var events= ['Interview @ Portal', 'Lunch with Cindy', 'Dinner with John', 'Conference'];
var eventMonth=['Feb', 'February', 'Feb', 'Feb'];
var eventDay=[23, 25,24, 24];
var eventYear=[2017, 2017, 2017, 2017];
var eventTime=['3:00PM-4:00PM', '12:00PM-1:00PM', '5:00PM-5:30PM', '11:00AM-5:30PM'];
//1st new event
event.push('Late Lunch');
eventMonth.push('Feb');
eventDay.push(23);
eventYear.push(2017);
eventTime.push('3:30PM-4:00PM');
//2nd
event.push('Call Mom');
eventMonth.push('Feb');
eventTime.push('11:00AM-12:30PM');
eventDay.push(25);
eventYear.push(2017);
//3rd
event.push('Paper due');
eventMonth.push('Feb');
eventDay.push(28);
eventTime.push('3:30PM-4:00PM');
eventYear.push(2017);
//4th
event.push('Sleepover');
eventDate.push('Feb');
eventDay.push(27);
eventTime.push('7:30PM-7:00AM');
eventYear.push(2017);

var counter = 1
if (eventMonth(counter)==eventMonth(counter+1))
{return event(counter)
}
else {counter=counter+1}

eventMonth.find(k => k=='Feb'||'February');
eventDate.find(p => p)

</html>


Task 3
For the calender model, I wanted to separate the dates by month, day, year, time. Then write a function that can find the same 
dates and times within the array to return the position number of the overlapping times. From there, the position number
could be placed into a array with the event names to return a list. However, I couldn't figure out the function that would find
the same dates and times. I tried if/else statements, but that would only work for sequencial dates within the array. I then
tried the .find function, however I couldn't come up with a statement to find equal datasets within the array.
