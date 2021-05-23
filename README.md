# Flask with tensorflow object detection demo

- Frontend and backend are separated, not with common flask template. 

## Server part

Since flask is very simple and wroted by python, we build it with only a few lines of code.

## Front end part
In front end page, with the help of  jQuery ajax, we can send the base64 image to backend, wait for the result, then draw the bounding box on the page.


## How to run.
Step 1: Open the server with 
```
python app.py

```
The server is setup on port 5000.

Step 2: Open the front end page.

If you want to use python.
```
// python3
python -m http.server
// python2
python -m SimpleHTTPServer

```
If you prefer Node.js
```
npm install serve -g // install serve
serve // this will open a mini web serve
// or http-serve
npm install http-server -g
http-server
```

