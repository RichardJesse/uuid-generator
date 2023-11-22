# uuids-generator
This repository holds the code for the uuids-generator NPM package.

This package can be used by other developers to uniquely identify their users in the applications that they create.

The UUIDS that are generated here are unique in that the occurence of one unique number more that once is one in a billion occurence.

--------------------------------------------------------------------------------------------------------------------------------------

To use this package assuming that you have node.js installed and by extenstion npm, run the following command on the command line

 ``npm install uuids-generator``

 --------------------------------------------------------------------------------------------------------------------------------------

 **How to use this in your project**

 To intergrate this into your project is quite simple.
 
 All you need to do is to require the **uuids-generator** module like so

 ``` javascript
   const generateuuid = require('uuids-generator');
```

From there you can use the generateuuid method to get the unique uuid

``` javascript

   const generateuuid = require('uuids-generator');

     console.log(generateuuid())
```
And there you have it you'll have your uuid generated.
