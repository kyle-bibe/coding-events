# coding-events

#purpose
This application tracks events around different locations and offers details about them.

#state
The User is able to add events to the application, and attach tags to the events.

#enhancements
We need to include a Person class in order to have our users to select and save their favorite events!

Proposed Architecture:
Fields:
- Name - String
- Email - String
- Password - String
- List Of Events - List<Event> : Many to Many
- Favorite Category - EventCategory : Many To One

Methods:
- Getters And Setters
- Get Back Favorite Events (returns all events that have to do with the favorite category)
