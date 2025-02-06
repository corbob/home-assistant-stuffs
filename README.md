# home-assistant-stuffs

This is just a repo to hold some things from Home Assistant to share.

Some of my existing setup: I have created a Group Helper that groups my desk lights together. I also created a boolean Helper called Do Not Disturb. I have also added Google Calendar integration and have my calendar as well as an "Automations" calendar.

I currently have two automations:

1. Announce upcoming meetings
1. Automate lights and do not disturb based upon calendar entries.

The Announce upcoming meetings automation will announce the meeting and how much time there is before it starts at 15, 5, and 1 minute before the meeting.

The Automate automation looks to the Automations calendar, and at the start of any entry in it will perform the hashtagged option in the summary (title).