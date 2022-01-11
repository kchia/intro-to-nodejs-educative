# Quiz Yourself on Introduction to Node.js Part IV - Building a RESTful API with Express

1. What is `npm`?
A) A JavaScript software registry
B) Package management tool for Node.js
C) CLI tool for downloading and managing Node.js packages
D) All of the above
**Answer: D** 

2. You just cloned a project for local development and you find the following list of dependencies in the `package.json`.

```json
...
"dependencies": {
    "awesome_dep": "^0.13.0",
    "another_awesome_dep": "~5.2.0"
}
...
```

Which specific packages _could_ be installed when you run `npm install`?
A) `awesome_dep v1.0.0` & `another_awesome_dep v5.3.1`
B) `awesome_dep v0.15.1` & `another_awesome_dep v5.2.1`
C) `awesome_dep v0.15.1` & `another_awesome_dep v6.2.1`
D) `awesome_dep v1.0.0` & `another_awesome_dep v5.2.1`
**Answer: B** 

3. True or False: You can use the `express.Router` class to create modular route handlers, with each router instance being responsible for handling routing for a specific resource.

A) True
B) False
**Answer: A** 

4. Fill in the blank: __ functions are functions that alter the request and response object(s) in the application's request-response cycle.
A) Static
B) HTTP
C) Route handler
D) Middleware
**Answer: D** 

5. Why has JSON become a universal standard for transmitting data across the web?
A) Easy to parse
B) Lightweight
C) Easy to read
D) All of the above
**Answer: D** 