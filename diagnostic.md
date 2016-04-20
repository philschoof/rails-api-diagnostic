# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
// The purpose of the backend is to interface with a database, which allows the app to
save and retrieve data
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// The model
```

Which layer in the MVC pattern communicates with the model?

```bash
// The controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// They are being phased out in favor of single page applications
```

What does C.R.U.D stand for?

```bash
//Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// The model
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
// index, create, show, update, destroy
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
// -The request is interpreted by the router
  - Necessary information is added to the params hash
  - The router sends it to the appropriate controller for that action
  - The controller method retrieves any requested information from the database
  and renders it
```

What is the command to generate a new rails-api app?

```bash
// rails-api new
```

What is the command to start an instance of a rails server?

```bash
// rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
// -dropdb
  -createbd
  -rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
//rails generate scaffold Pet name:string age:integer
```

List two advantages of using serializers? (2 bullet points)

```bash
// -Customizing what information is sent out by the api
  -Withholding specific information like passwords and credit card numbers
```
