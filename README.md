# Maistra support roster

The format of the roster.txt file is broken into two main sections
- defining identities of those covering the support alias
- the roster list for each week of the year

Please be careful with the formatting of the roster file
# Defining Identities
The identity section consists of a sequence of entries of the format `id = textual description`, for example
```
kconner = Kevin Conner <kconner@redhat.com>
```
The textual description is currently copied verbatim into the calendar event, the email address is included in case we want to also send email reminders at a future date.

# Specifying the roster
The roster section consists of a sequence of entries of the format `<week number> <identity> [, <identity> ...]`, for example
```
01 kconner, bavery
02 rcernich
```
You can also define the year for subsequent entries by include the comment `# year <year>`, for example
```
50 kconner
# year 2021
01 rcernich
```
