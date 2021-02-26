# day-planner

Link: https://10-kp.github.io/day-planner/

Git Hub Link: https://github.com/10-kp/day-planner

Snap shot of page: ![Screeshot](https://github.com/10-kp/day-planner/blob/main/assets/screenshot-day-planner.png)


HTML
- Under the parent <div> class container, created a child id for "hour" (linked to CSS) and class linked to "row", "time-block", and "past" classes
- Under the child class "row", "time-block", and "past", created a grid with column, medium size, with 1 column (out of 12) and link to the hour CSS style. The Time is mentioned i.e. 8 AM.
- <textarea> for a mulit-line input linked to class description in CSS.
- <button> with class button linked to saveBtn in CSS and column size, medium, 
- Also created a "save icon"
- Repeated the steps for each with different times.
- Moment.js for time
- Created variables to update the past, present and future time and link it to the CSS and added jQuery.
- Called the function to run the code. Avoid bubbling and other events to be called simultaneously.

CSS 
- Slight changes to ensure the format in the page is fine.