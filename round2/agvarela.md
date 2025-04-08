# Chrome Extension Idea: Google Calendar Availability Extractor

## Authors

Shafaa Munjal and Andrea González Varela

## Problem Statement

Coordinating meetings or scheduling time with others often involves repeatedly checking one's Google Calendar and manually finding and sharing available times. This process is tedious and error-prone, especially when done frequently or across multiple time zones. This Chrome Extension will streamline the process by automatically extracting availability from a user's Google Calendar and presenting it in a copyable format that can be easily pasted into ChatGPT or shared with others.

## Target Audience

This extension is intended for students, professionals, and teams who regularly use Google Calendar for scheduling. The target audience includes anyone who frequently participates in meetings or collaborative planning sessions and wants a faster way to share availability. It also benefits users who often interact with AI tools like ChatGPT to automate scheduling tasks.

## Description

Google Calendar Availability Extractor is a Chrome Extension that scans a user’s Google Calendar to identify free time blocks and generates a summary of their availability. This availability can then be copied in a clean format and pasted into ChatGPT, email, or scheduling tools. The extension may either function directly on the Google Calendar web interface or use Google OAuth to access calendar data in the background.

## Selling Points

1. Automatically extracts availability from Google Calendar  
2. Produces a clean, readable format for easy sharing or pasting into ChatGPT  
3. Saves time by avoiding manual cross-checking and typing  
4. Option to function with or without visiting the calendar page  
5. Ideal for remote workers, students, and professionals who schedule frequently  

## User Stories

1. As a student, I want to extract my weekly availability from Google Calendar so that I can share it with my study group.  
2. As a professional, I want to copy my available time slots into ChatGPT so it can schedule meetings for me.  
3. As a user, I want the extension to automatically detect my free time on the Google Calendar page without extra clicks.  
4. As a user, I want to authorize the extension with Google OAuth so it can fetch my availability even when I’m not on the calendar site.  
5. As a team member, I want to quickly generate a summary of my availability across multiple calendars so that I can send it in a single message.  
6. As a freelancer, I want to generate a list of my open time slots for the week so I can send it to potential clients quickly.  
7. As a remote team member in a different time zone, I want my availability to be shown in both local and shared time zones so that others can coordinate easily.  
8. As a user, I want to exclude certain types of events (e.g., personal or tentative) from the availability extraction so that only work-related free time is shown.  
9. As a manager, I want to compile availability data from multiple team members so that I can plan team meetings efficiently.  
10. As a user, I want to customize the output format (e.g., plain text, markdown, table) so that I can paste it cleanly into different platforms.  

## Notes

There are multiple potential technical approaches: the extension could scrape data from the open Google Calendar web page or use Google’s Calendar API via OAuth for a more integrated experience. Privacy and permission management will be important considerations. Integration with AI tools like ChatGPT could be emphasized as a unique use case. The challenge lies in reliably detecting free time, especially across multiple calendars, and handling time zones correctly.

## References & Inspiration

- [ChatGPT shared prompt idea](https://chatgpt.com/share/67f52bca-eb64-8005-b3a7-ddf74f5ffe1c)  
- [Google Calendar API documentation](https://developers.google.com/calendar/api)  