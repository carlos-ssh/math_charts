# Multiply Console App
## By Carlos-SSH

This is an app where you can create multiply charts and export it over a file.txt or print in command console.

How to use:
It's necessary use node app.js and the rule that you want to do. IE:
- Using -b or --base (This is the Base Number)
- -l --limit (You limit here at what number do you want to create a chart.)

Example:  
  node app.js listar -b 1 Number -l 10 (This will show in command line 1 multiplied by 1 till 10.)

  or

  node app.js crear -b 1 Number -l 10 (This will save a file in tablas directory with extention (.txt) 1 multiplied by 1 till 10.)

## Use this command to install required dependencies:
``` 
npm install
````
## List all the things that you can do with this App:
- For Help:
``` 
node app.js --help  
````

## If you want to list Math Charts on Command Console use:

``` 
node app.js listar -b #Selected Number -l #Selected Limit 
````

## Create a File.txt with the requested base and limit:
- In Example:
``` 
node app.js crear -b #Selected Number -l #Selected Limit
````
## Created with:
- Node
- TS
- and <\3

#

Mit License
