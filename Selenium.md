Selenium Web Browser Automation

Automation Scripts use Selenium commands for emulating user actions on a web page.

1. for each Selenium command, a HTTP request is created and sent to the browser driver.

2. the browser driver use a HTTP server for getting the HTTP requests

3. the HTTP server determines the steps needed for implementing the Selenium command.

4. the implementation steps are executed on the browser

5. the execution status is sent back to the HTTP server

6. the HTTP server sends the status back to the automation script
