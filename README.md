# Assignment 14
## Data Journalism and D3

This solution provides an HTML page which retrieves and renders a graph produced by a server
side javascript app.  Below are various components that comprise this solution:

* The javascrip app is contained in app.js and is invoked by index.html. The purpose of these
two components is to provide a server side process which listens on default port 8000. To invoke this server side service, run the command "python -m http.server" in the same directory where app.js and index.html files reside.  To view the output of these two components directly via a browser, access the URL http://localhost:8000
* The health_db.html retrieves the same graph from the server app described above, and displays the result using an iframe element, along with some descriptive text.
* screenshot.JPG contains a screen shot of health_db.html.
* In order to run and view the operation of these components follow these steps:
    1. Clone the repo in a local directory.
    2. From this directory, issue the command: python -m http.server.
    3. Once this command executes, you should see: Serving HTTP on 0.0.0.0 port 8000.
    4. Note that the process will appear to hang (no command prompt is displayed); this is normal behavior.  When done viewing the dashboard, you can terminate this server
    process by issuing Ctrl C command (on Windows systems).
    5. From another command shell (gitbash or terminal), go to the cloned directory and issue "explorer health_db.html" (on Windows systems).
