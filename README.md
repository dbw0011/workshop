# workshop

### Instructions
1. Download index.html or copy the raw file into a code/text editor
2. Open the file using a browser and attempt to use the subscription form
3. Add Rollbar to your code by pasting the code snippet generated in the Browser JS project instructions
4. Uncomment the Rollbar method calls on lines 19, 41, and 47
5. Save the code changes to the text editor, refresh the page in the browser
6. Rollbar will now report errors to the web app - use your trial account to investigate the errors & pinpoint the root cause(s)
7. Make code changes, save/refresh and test the changes to see if the errors are still reporting
8. Iterate as needed

### Notifications
1. Go to [webhook.site](webhook.site) and copy the unique URL generated for your session
2. In Rollbar, navigate to Settings > \[project\] > Notifications
3. Choose the Webhook option
4. Paste your URL into the field at the top
5. Optional: send a test notification (this can be a good latency check, webhook.site can be a little slow to report new messages)
6. Add the "Every Occurrence" template to your rule set
7. Generate some occurrences, verify they are being received
