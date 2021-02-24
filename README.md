# day-planner

Link:

Git Hub Link: https://github.com/10-kp/day-planner

Snap shot of page: ![Screeshot](https://github.com/10-kp/XXXCCC/main/assets/screen-shot-of-page.png?raw=true)


[Moment.js](https://momentjs.com/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

HTML
- Under the parent <div> class container, created a child id for "hour" (linked to CSS) and class linked to "row", "time-block", and "past" classes
- Under the child class "row", "time-block", and "past", created a grid with column, medium size, with 1 column (out of 12) and link to the hour CSS style. The Time is mentioned i.e. 8 AM.
- <textarea> for a mulit-line input linked to class description in CSS.
- <button> with class button linked to saveBtn in CSS and column size, medium, 1. Also created a "save icon"
- Repeated the steps for each with different times.

CSS

GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist