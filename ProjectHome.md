# Mail - 2 - RSS #


---


PHP Application to poll an email account, read all messages contained within, log to a SQL database, and convert to RSS feed

  * Supports multiple feeds, feed selection based on subject of email
  * Authentication made through SQL lookup of subject
  * Full message logging to MSSQL database
  * Connects to IMAP/POP accounts - designed primarily for exchange
  * Generates qualified XML and OPML code