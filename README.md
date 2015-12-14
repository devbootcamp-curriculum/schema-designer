# SQL Designer

### About

This is a fork for the popular [WWW SQL Designer](https://github.com/ondras/wwwsqldesigner). WWW SQL Designer was created by Ondrej Zara and is built atop the oz.js JavaScript module. It is distributed under New BSD license.


This tool allows you to draw and create database schemas (E-R diagrams) directly in browser, without the need for any external programs, you only need javascript enabled.

## Development and Deploying

This app is hosted as Heroku app ([dbc-schema-designer](https://dashboard.heroku.com/apps/dbc-schema-designer)) just like the rest of our platform.  You can find it at [schemadesigner.devbootcamp.com](schemadesigner.devbootcamp.com
).


To deploy you'll need to add Heroku remotes to the project first.

```
$ heroku git:remote -a dbc-schema-designer

set git remote heroku to https://git.heroku.com/dbc-schema-designer.git
```

Then deploy changes in typical Heroku fashion.

```
$ git push heroku master
```
