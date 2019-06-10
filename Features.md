User logs in

Sees all calendars

Calendar has a name, a task, an interval, and heatmap associated to it from front end

Dates belong to calendars

Calendar has many dates

Date has a date and a count, belongs to calendar

Add new calendar

- name of calendar
- task calendar is tracking
- interval for task

Example
Calendar obj 1
Name of calendar : Gym sessions
What are you tracking : half hours I went to the gym that day
Interval : 30 mins
Dates: ASSOCIATED DATE MODELS

Date obj 1
Date: 05-08-2019
count: 4 (30mins x 4 = 2hrs total at gym)
user: 1
calendar: 1

