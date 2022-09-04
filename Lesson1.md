# Introduction to NodeJS

## 🔷What is Node?

Node is an open-source runtime enviornment for executing Javascript code outside of a browser.

It is used to build the API(Application prgramming Interface) to enable client application like Web App and Mobile App to talk to Back-end services.

![api](./Assets/api.png)

## 🔷But Why NodeJS?
There are several back-end frameworks and modeuls such as Django, ASP.NET still NodeJS popular because of three reasons:

<!-- UL -->
* **Fast and highly scalable🚀**: Used by organizations such Paypal, Uber, Wallmart etc
* **Use JavaScript👨‍💻**: It allows front-end developers who know JavaScript, it's easy for them to get started with a brand new projects and also get them grow their career faster.
* **Benefits of Large Open-Source Libs🙌**: NodeJS has got the largest ecosystem of open-source code on Github as a result, you get better support.

## 🔷Node Architecture

In 2009, Ryal Dahl(creator of Node) thought why if we can take out Javascript from client-side and run it on server side to deliver same flexibility.

So he took Google Chrome v8 JavaScript Engine and embedded inside a C++ code and named this program Node.exe. 

![jsengine](./Assets/jsengine.png)


## 🔷Capabilities of NodeJS

We cant use document or window object such as



~~document.getElementById()~~

Instead, we have objects:


```javascript

fs.access(path[, mode], callback) // access file
dir.path //  read-only path of this directory
dir.read() // Asynchronously read 
os.hostname() // Returns the host name
os.platform() // Returns a string identifying the operating system platform


```

## 🔷 Asynchronous/ Non-Blocking
With Node, you can build highly-scalable, data-intensive and real-time applications. This is because of the Asynchronous/ Non-Blocking feature.

In async programming the program doesn’t wait for the task to complete and can move on to the next task.

## 🔷 Installing Node

1. Download NodeJS from [nodejs](https://nodejs.org/)
1. Verify if the installation is successful.
   ```
   ~$ node --version
   v17.9.1
   ```

## 🔷 Simple NodeJS Program

Lets get started!

```
mkdir firstCode \\ create a directory

cd firstCode   \\ move to directory

code .        \\ open yoru default Code editor
```
set the file name firstCode.js

```javascript

function greeter(greet) {
    console.log(greet);
}

greeter("Good Morning!")


```

To execute your code
```javascript

~$ node firstCode.js

```
