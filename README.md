# Bart strike visualization code

to run on your own computer:

1.) you'll need to run the site through a server. this is because of a browser security restriction imposed to prevent files being loaded directly from your computer like (file:///Documents/...) from random websites. To side step this issue, we'll need to load the data file (the .csv file) from a web server. The simplest way is to do this is to use the following python command from the command line (assuming you're already inside of the project directory and using OS X or some other Unix system.)

    python -m SimpleHTTPServer

2.) this will start a web server on your local computer that you can now access
from a web browser at the following URL

    http://localhost:8000/index.html


happy coding!
