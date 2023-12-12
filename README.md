# Banner Manager for Atlassian

For ease of use. I'm just going to use Atlassian User Interface Framework.  https://aui.atlassian.com/

## Page Design

```
+---------------------------------------------------------+
| Banner Management                                       |
+---------------------------------------------------------+
| [Add New Banner] [Refresh List]                         |
+---------------------------------------------------------+
| Banners List                                            |
| +----+----------------+--------+---------------------+  |
| | ID | Title          | Status | Last Modified       |  |
| +----+----------------+--------+---------------------+  |
| | 1  | Maintenance... | Active | 2023-07-10 14:00    |E|D|
| | 2  | New Feature... | Active | 2023-07-11 09:30    |E|D|
| +----+----------------+--------+---------------------+  |
+---------------------------------------------------------+
| Banner Details                                          |
| Title: [______________________]                        |
| Content: [HTML Editor Here]                             |
| Status: [Active v]  Creation Date: [2023-07-10 12:00]   |
| Last Modified: [2023-07-10 14:00]                       |
+---------------------------------------------------------+
| Banner Settings                                         |
| Display Location: [Top v]   Background Color: [#_____]  |
| Text Color: [#_____]  Font Size: [___]  Duration: [___] |
+---------------------------------------------------------+
| Banner Schedule                                         |
| [Add Schedule] [Month View v] [ < ] [ > ]               |
| +----+----------------+--------------+--------------+   |
| | ID | Title          | Start Date   | End Date     |   |
| +----+----------------+--------------+--------------+   |
| | 1  | Maintenance... | 2023-07-15   | 2023-07-20   |V|E|D|
| | 2  | New Feature... | 2023-08-01   | 2023-08-05   |V|E|D|
| +----+----------------+--------------+--------------+   |
+---------------------------------------------------------+
| [Save] [Cancel]                                         |
+---------------------------------------------------------+
```






#### Interactive Elements for Banner Schedule
- Calendar View: Implement a calendar view to visually represent the banner schedule.
- Drag and Drop: Optionally, allow drag-and-drop to easily reschedule banners.
- Overlap Warning: Highlight or warn if multiple banners are scheduled simultaneously, potentially causing conflicts.

#### Additional Implementation Considerations
- Integration with Database: Ensure the schedule view is integrated with the database to reflect real-time data.
- Responsive Design: Make sure the calendar and list views are responsive for different screen sizes.
- User Experience: Focus on making the scheduling interface intuitive and user-friendly.






