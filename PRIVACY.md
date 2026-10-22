# Outlier (personal): privacy policy

Outlier (personal) is a desktop app that one person uses on their own Windows computer. Its Google Cloud project and
sign-in client exist only so that person can let their own copy of Outlier read their own Google Calendar and Gmail.
There is no Outlier server: nothing is collected, stored or processed anywhere but on that person's computer.

What Outlier reads, and only after the person signs in on Google's own page:
- Google Calendar: the list of the person's calendars and their names; the times of events, their titles, who was
  invited and whether the person accepted, from the calendars they choose. Not descriptions, places, meeting links or
  attachments. Outlier keeps no email address: not the calendars' ids (which are addresses) and not the guests'.
- Gmail: only message labels, dates, and whether four headers that mark bulk mail are present (List-Unsubscribe,
  List-Id, Precedence, Auto-Submitted). Never subjects, addresses or message text.

Where it goes: into a database on that computer. It is not sold, shared or sent to anyone. Outlier may send a short
line about an unusual day (for example a daily count of emails or a number of meeting hours) to an AI service that is
asked to keep nothing, so it can write a one-line note. No email content, email address or event title is sent.

Google user data is used only to show the person their own patterns. It is not used to train AI models and is not
transferred to anyone else. Outlier's use of information received from Google APIs follows the Google API Services
User Data Policy, including the Limited Use requirements.

Sign-in tokens are kept in Windows Credential Manager on that computer.

To stop it: in Outlier, Settings > Connections > Remove Outlier's access at Google, or remove "Outlier (personal)" from
the list of apps with access to your Google Account. Outlier can also delete everything it read.

Questions: open an issue in this repository.
