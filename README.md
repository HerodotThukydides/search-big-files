# search-big-files-Node
Gives out a list of the biggest files in a directory (including sub-directories)

## What it is...
- written in node.js
- uses node-walkdir ( https://github.com/soldair/node-walkdir )
- searches directories for the biggest files and returns them in a list
- a fun small project to get familiar with node
- fills in my perosnal need to identifiy the biggest files inside my Google Drive ( I am sure there are 1000 other ways as well )

## How to use?
1. copy & paste a path into app.js (mind the escape characters
2. specify the length of your list
3. run "npm install" 
4. run app.js ( filling the list and results are displayed in logs)

## TODOs
- optimization: instead of searching for folders and files, it should be only files
- (maybe) write the list into a file
- (maybe) make it possible to just copy & paste a windows path into it, instead of filling up with escape characterts
