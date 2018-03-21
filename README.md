# Templated Bootstrap Modern Business

This template is based on [Bootstrap Modern Business](https://github.com/BlackrockDigital/startbootstrap-modern-business), but uses [gulp-static-template-resolver](https://github.com/alialavia/gulp-static-template-resolver) in order to generate the htmls based on some json data and javascript commands, stored in src/templates/resolve.

## Install
```npm i```

## Usage
Just run `gulp`, which automatically resolve all the html files in templates/ based on data in templates/resolve/data.json and commands defined in templates/resolve/commands.js.

Change the data in templates/resolve/data.json and see the changes in the browser, live!

## Important
If you have inline javascript in your html files, make sure that you don't use template strings with same names as the ones in the data.json and command.js files.



