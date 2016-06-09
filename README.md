# Open To-do API

API for a to-do list application, so that users can authenticate and manage their information externally.

This app powers Open Todo APi located [here](Heroku Project URL)

## Getting Started

## Software requirements

- Rails 4.2.6

- Ruby 2.3.0p0

- PostgreSQL 9.5.x or higher

## Navigate to the Rails application

```
$ cd /path/to/rails/application
```

## Set configuration files

```
$ cp config/database.yml.template config/database.yml
$ cp config/initializers/mail.rb.template config/initializers/mail.rb
```

Note:  You may need to edit the above files as necessary for your system.

## Create the database

 ```
 $ pgstart
 $ rake db:create
 ```

## Migrating and seeding the database

```
$ rake db:migrate
$ rake db:seed
```

## Starting the local server

```
$ rails server

   or

$ rails s
```

## Production Deployment

  ```
  $ git push heroku master
  $ heroku run rake db:migrate
  ```

## Support

Bug reports and feature requests can be filed with the rest for the Ruby on Rails project here:

* [File Bug Reports and Features](https://github.com/<user-name>/<project-repo>/issues)

## License

Open Todo API is released under the [MIT license](https://mit-license.org).

## Copyright

copyright:: (c) Copyright 2016 Omar Mendoza. All Rights Reserved.
