# piecalendar
This repository is the home of a calendar application that I want to develop in my freetime

## Description
I have been using TimeTree for a shared calendar with my partner for some time now and it's been very helpful in organizing my time.
But there is one feature missing from the app that I would like to implement in PieCalendar:

The option to create an event in a shared calendar, that not all people using the calendar can see.
I don't want to be forced to switch to a personal calendar every time I want to see events that are only relevant for me.

Also I'd like the application to be more customizable stylistically.

The calendar should feature a customizable weekly view.

## Database model

### User

- User Id
- Username
- Password
- Birthday
- Profile Picture

### Calendar

- Id
- Name
- Administrator
- Description
- Participants
- Category Options

### Category Options

- Option Id
- Option name
- Option default color

### Event

- Id
- Name
- Creator
- Category
- Color
- Start Date
- End Date
- All day?
- Start time
- End time
- Recurring (Never/Daily/Weekly/Monthly/Yearly)
- Recurring frequency
- Participants
- Access rule