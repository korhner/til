# Remote Debugging Java applications from Eclipse

Start remote java application with the following parameters:

```-Xdebug -Xrunjdwp:transport=dt_socket,server=y,address=8765```

In Eclipse, go to Debug Configurations and create a new Remote Java Application configuration.
Set up connection properties (use port from java param above) and run the configuration.
After the debugger attaches, you can set up breakpoints and debug as if it was a local application.
