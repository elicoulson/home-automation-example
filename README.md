Example App
==================

This application is a simple demonstration.

It's written as a React app with ****** modules and endpoints.


Using This Example
------------------


Clone this repository, and then build the application:

```
npm install
npm run compile
```

To deploy, first install the ****** command line tool.
 

```
sudo pip install ************************************************
```

Initialize the project with your solution and product id. These IDs may be found here: ********************************.

````
****** --init 
```

Then deploy this sample application into your solution:

```
****** --deploy
```

To run the web application static assets locally, create a .env file in the root of the project with your solution URL, like this:

```
API_BASE_URL=https://<solution-name>.apps.exosite-dev.io
```

Install this [Chrome plugin](https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj/related?hl=en) and import this configuration:

```
{"title":"Local Debugging","hideComment":true,"headers":[{"enabled":true,"name":"","value":"","comment":""}],"respHeaders":[{"enabled":true,"name":"Access-Control-Allow-Origin","value":"http://localhost:8080","comment":""},{"enabled":true,"name":"Access-Control-Allow-Credentials","value":"true","comment":""}],"filters":[],"appendMode":""}
```

Then run this and go to http://localhost:8080 in your browser.

```
npm run start:dev
```
