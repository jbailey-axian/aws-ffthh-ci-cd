# AWS FFTHH CI/CD
This repository contains sample code to facilitate a FFTHH.

The walkthrough **[can be found here](https://axianinc.atlassian.net/wiki/spaces/AXLND/pages/314867725)** on the Axian wiki.

## Build Light
At some point you'll end up replacing the build light below with one of your own:

<img src="https://codebuild.us-west-2.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiVTFVUTFPU0ZLRi9ReUQ2NmgvUFdZc0FsbFJNNzBwL3EzMnFhblkyMXU5Q0R0RmcrczhMMFM5MkpnaWtYL01RNU15TVRnYkdxeWs1QlIxc01GZ1VwLzNrPSIsIml2UGFyYW1ldGVyU3BlYyI6InlrMW9jUkt5alk5OTZOTFYiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master">

## Add More Sams! (the squirrel bouncing around the page)
Go to app.js file the repo you made in Step 2 and update the line:

```javascript
var DESIRED_SAM_COUNT = 1;
```
to
```javascript
var DESIRED_SAM_COUNT = 15;
```

Commit and push the changes. 

Go back to the pipeline we generated, you will see AWS CodePipeline automatically pick up your change, and start the build and deploy process. Voila! A completely version controlled, serverless, CI/CD solution to give a squirrel a few friends. Technology!
