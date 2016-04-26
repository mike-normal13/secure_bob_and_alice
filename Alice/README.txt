Run Bob's jar first!
Otherwise it won't work.

Run Alice's jar file like so:

$ java -jar Alice.jar

There are also a few options.
If you run the jar like so you will get a list of available options:
$ java -jar Alice.jar -help.

In order to connect to Bob on a different host,
you can use 

	$ ifconfig 

on one of the CADE machines,
and look for the listed inet ip address.
Then when you run this jar, 
use the -a option followed by the listed inet address.
On the CADE machines the inet address is on the first or second line of the ifconfig printout.
Don't enter Bob's ip address with quotes or anything,
Just enter the address exactly how it appears in the ifconfig printout.

You can also add your own custom message with the -m option.
No need to use quotes for the custom message.

The port -p option is self explanatory.
I do have both my jars printing warnings if you use a port number outside of 2112-2120.

Leave the keys where they are, or the program will not work.