Overview

QuickText is a lightweight web app that lets you send a pre-written SMS message to any phone number directly from your phone, without needing a desktop computer, a Bluetooth connection, or Phone Link. You open it in your phone's browser, import a list of names and numbers, select a message, and tap to send. Your phone's native Messages app opens with the number and message pre-filled so you can review and send immediately.

How It Works

QuickText uses the standard SMS URI scheme built into mobile operating systems. When you tap the Send button, the app constructs a link. Your phone intercepts that link and opens the Messages app with the recipient and message body already filled in. You review, then tap Send within Messages to deliver the text. QuickText itself does not send any messages. It is a launcher, not a messaging service.

The app also detects whether you are on an Android or iOS device and formats the link accordingly, since the two platforms use slightly different syntax. This happens automatically in the background.

Accessing the Tool

Go to https://mattfmbs.github.io/QuickText/ on your phone's browser. On iPhone, I recommend the Firefox Focus browser. Safari does not work. I have not tested the app on Android, but I assume Firefox Focus would work there too.

Loading Contacts into QuickText

Although you may enter phone numbers manually, what sets QuickText apart from similar apps is its ability to load CSV files. These are the headers you must have in your CSV file, and they must be in this order:

name - This is the name of the person you're texting. First and Last Name like "Bob Johnson"
phone number - Their phone number. Format doesn't matter	
recruiter - This is you. If you are not recruiting, this is still you	
company - The company you work for
role - If you're recruiting, this is the job you're hiring for. If you're doing something else, you can put whatever you want here	
location - Location the job exists in

These will show up as tokens in the text templates. You don't have to use all the tokens. Only the first three are really necessary. 

Additional Notes

QuickText does not store any phone numbers or messages. Nothing is saved between sessions.
The file works entirely offline. No internet connection is required after it is loaded.

Usage Rights

QuickText is free to use without limitations or the need for attribution.
