# Workday-Calendar
Creating A Workday Calendar Application For Scheduling Events

I was tasked with refactoring and adding code in order to create a Workday Scheduling Appplication that woul allow an employee of a company to enter and organize data for each hour of the workday from 9am to 5pm. The scheduler also is reset for every new workday and will display the current date at the top of the page. 

## Table Of Contents
1. [Acceptance Criteria](#acceptance-criteria)
2. [Work Completed](#work-completed)
3. [Deployed Page URL](#deployed-page-url)
4. [Deployed Page](#deployed-page)
5. [Credits](#credits)

## Acceptance Criteria 
- GIVEN I am using a daily planner to create a schedule, WHEN I open the planner, THEN the current day is displayed at the top of the calendar;
- WHEN I scroll down, THEN I am presented with time blocks for standard business hours of 9am to 5pm;
- WHEN I view the time blocks for that day, THEN each time block is color-coded to indicate whether it is in the past, present, or future;
- WHEN I click into a time block, THEN I can enter an event;
- WHEN I click the save button for that time block, THEN the text for that event is saved in local storage;
- WHEN I refresh the page, THEN the saved events persist.

## Work Completed
- When the applicaton/planner is opened in the browser, the current date is listed in the header.
- Time blocks between the hours of 9am and 5pm are displayed on the page below the header and date, and the blocks are color coded to mark past as gray, present as pink, and future as green.
- When a time block is clicked, the user/employee can enter an event in the text box.
- When the save button for each time block, which appears in blue with a white save/floppy-disk icon, is clicked, the event in the text box is saved to local storage.
- When the page is refreshed, the saved events remain in the time block text boxes.

## Deployed Page URL
https://sbehashti.github.io/Workday-Calendar/ 

## Deployed Page
Note: Deployed Page Image was taken outside of the 9am-5pm hours

![sbehashti github io_Workday-Calendar_](https://github.com/Sbehashti/Workday-Calendar/assets/135624229/8b154827-45ff-4bef-bd5a-a9698f515a01)

## Credits 
- Starter Code provided by University of California, Davis Coding/Web Development Bootcamp 
- Code Refactored by Sier Behashti https://github.com/Sbehashti
- Link/Framework elements provided b Bootstrap, JQuery, Day.JS; Styles provided by FontAwesome, and Google Fonts

