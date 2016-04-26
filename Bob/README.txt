Run Bob's jar before you run Alice's jar, it won't work otherwise.

Run Bob's jar like so:

$ java -jar Bob.jar

You can also use the -help option to see list of available options like so:

$ java -jar Bob.jar -help

The only other option besides -help is the port -p option.
Choosing a port outside of 2112 - 2120 will cause print warning.
Do not use any enclosing characters for the port, e.g. just use -p 2112.

Leave the keys where they are, or the program will not work.

See Alice's README.txt on how to connect her to Bob.