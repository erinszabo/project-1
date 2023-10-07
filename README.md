# UO CS 322 - Project 1  

## Erin Szabo
#### Fall 2023
### eszabo@uoregon.edu


The purpose of this project is to get familiar with the process of creating a web server by starting with creating this simple webpage server.

-  call `make start` to start up the server
    - if just at the port, only a cat picture in text is served
    - if a request contains the name of a valid file in the DOCROOT, then a status of 200 'OK' is transmitted along with the specified page with associated style if applicable. 
    - if a request contains a file that does not exist in the DOCROOT, then a status of 404 'file not found' is transmitted.
    - if a request contains the illegal charactars ".." or "~", then a status of 403 'forbidden' is transmitted.
    - if a request is not implimented (currently only handles GET requests), then a status of 'not implemented' is transmitted. 

- when done, call `make stop` to stop the server 

- (optional) call `make clean` or `make veryclean`

## Original Authors

Michal Young, Ram Durairajan.
