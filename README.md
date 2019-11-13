# vue-add-events-to-google-calendar

An Vue component to add events to google calendar.

## Installation

  ```sh
  npm install vue-add-events-to-google-calendar@latest
  ```

## Example

  ```sh
  import { AddToCalendar } from 'add-to-calender';

  <AddToCalendar
      :buttonText: "Add to calendar",
      :details: "Details of event",
      :endTime: "new Date('11/22/2019 5:00 pm')",
      :location: "'mumbai'",
      :startTime: "new Date('11/25/2019 6:00 pm')",
      :title: "'Excellencia'",
    />
  ```

## Props

|  Prop       |             Description             |  Required
|  :---       |                :---:                |      ---: |
|  buttonText |   Text on button                    |  false    |
|  details    |   Description of the event          |  false    |
|  endTime    |   End Date and time of the event    |  true     |
|  location   |   Location of the event             |  false    |
|  startTime  |   Start date and time of the event  |  true     |
|  title      |   Title of the event                |  true     |
