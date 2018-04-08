# Gatherer

This application is a learning experience in test driven development. Clone the repo, and then:

## Install dependencies 

Install all application dependencies by running the following terminal command while inside of the directory where you cloned this repository.

```
bundle install
```

## Generate database file and schema 

Run the following commands in order to create database and schema files:

```
rake db:create:all
rake db:migrate
```

## Run tests

To run the test suite, simply enter the following command into the terminal:

```
rspec
```

(c) 2018 James Martinez. All rights reserved.