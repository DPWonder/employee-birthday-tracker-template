# Employee birthday tracker template

A free spreadsheet template for keeping your team's birthdays and work anniversaries in one list. One row per person: Name, Birthday, Start date, and two optional columns, Team and Notes.

- `employee-birthday-tracker-template.csv`: the columns with eight made-up people.
- `employee-birthday-tracker-blank.csv`: the same columns, no rows.
- `employee-birthday-tracker-template.xlsx`: the sample for Excel, dates stored as text so they stay as typed.

Dates are YYYY-MM-DD (2022-03-07), which Excel and Google Sheets read the same way everywhere. Leave unknown dates empty.

## Open it

- **Google Sheets:** File > Import > Upload, pick the CSV, then choose "Replace spreadsheet".
- **Excel:** File > Open, pick the CSV or the .xlsx.

## Get reminded

A list doesn't remind anyone by itself. Four ways, free ones first:

1. **A calendar.** For each row, add an event in Google Calendar or Outlook that repeats every year, with a notification the day before. Free; you keep each event up to date.
2. **Slack's `/remind`.** In the channel, type for example:
   `/remind #team to wish Avery a happy work anniversary on March 7 at 9am`
   Free. One reminder per date. Slack's help page shows repeats such as "every Monday" and does not mention a yearly repeat, so plan to set each one again.
3. **A GitHub Action that posts to Slack.** Keep this CSV in a repository and [slack-birthday-reminder-action](https://github.com/DPWonder/slack-birthday-reminder-action) posts each morning's birthdays and work anniversaries to a Slack or Discord channel. Free and open source; it reads these same columns.
4. **Greetigo.** Copy the rows and paste them into https://greetigo.com/employee-birthday-tracker?utm_source=github&utm_campaign=template-1123 . The list's owner gets an email the day before and on the morning of each date, with a message ready to change. It emails you, not the team. Free for up to 50 dates (a team of 25 with a birthday and a start date each); Plus, US$4.99 a month, has no date limit.

Made by the Greetigo team. The template works without Greetigo.

## Privacy

Birthdays are personal data. Ask people before you list them, and leave the birth year out unless you need it: format the Birthday column as plain text, then type the month and day, for example "April 22". Keep the file where only the people who need it can open it.

## License

CC0 1.0 (public domain). Copy, change and share it; no credit needed.
