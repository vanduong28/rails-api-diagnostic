# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
To be able to store data and persist it over time.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The controller fetche data from the model.
```

Which layer in the MVC pattern communicates with the model?

```md
The controller communicates with the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```md
It's easier to test using terminal.
```

What does C.R.U.D stand for?

```md
Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index, Show, Create, Update, Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. Router receives request and directs it to the associated GET controller.
2. Controller calls methods to retrieve information from the database/model
3. Controller receives the output response and passes it to the view to be
displayed to the user
```

What is the command to generate a new rails-api app?

```bash
rails new myapp
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rake db:drop
bin/rake db:create
bin/rake db:migrate
bin/rake db:seed
bin/rake db:examples
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold pet name:string age:integer
```
