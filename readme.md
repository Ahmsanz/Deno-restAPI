## Description

This is a very simple CRUD APIREST application created just to get my hands on the new Deno, called to succeed NodeJS, but maybe not just yet!

It just uses Oak as a middleware (kind of doing the same thing as Express) to create some routes, based on some simple controllers to manipulate a hardcoded array of products.

All has been tested and work smoothly via **Postman**.

You can start by installing Deno (visit www.deno.land for that) and importing the needed modules (in this case, just __Oak__ and __Uuid__ for creating a new object with the post route)

After setting up the server, just launch it with 

``` bash
$ Deno run + the file containing the server. 
```