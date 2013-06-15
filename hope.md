# Evolution of Code
(source control is assumed)

 1. new program in a single source file
 2. code runs from top to bottom
 3. starts to get large and a bit unruly
 4. create some functions to group common functionality
 5. too large, similar functions are moved to new file
 6. multiple files with lots of functions
 7. functions all need to take lots of arguments
 8. calling functions is tedious because of arguments
 9. create objects to save state and group similar functions
10. move similar files into directories (or packages)
11. some packages could be used in other projects
12. move packages into package management for multiple project reuse
13. need same functionality in another project
14. move application (ui/db/etc) to package management
15. need data in another project
16. create api

Need Code = Library
Need User Functionality = Application
Need Data = Web Service / API

