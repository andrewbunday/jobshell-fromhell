## Background





## Build it, Release it 

````bash
$ make - builds the contents of src into a deb package using fpm. 
         control information is stored in ./info

$ make install - installs the last build deb package onto the localhost.

$ make publish - publishes the last build deb package to the site apt repository
````
