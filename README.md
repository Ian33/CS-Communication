# CS-Communication

The goal of this project is to set up a 'push' interface to force a Campbell Scientific datalogger to communicate to the network on command.  This should overcome callanges where it is not known if a logger will communicate once it is setup, reprogrammed, or the battery is changed.  

The basic communication program can be found at https://github.com/Ian33/CS-Communication/blob/master/Basic%20Triggered%20Communication.  This program looks for DIFF channel 3 to be open (completing a circut) to force the internal SC300 Cell210 modem to communicate.

The push command was integrated with a time based communications protocal https://github.com/Ian33/CS-Communication/blob/master/Modem%20Communication%20with%20Communication%20Button to allow for a logger to operate normally and also recieve special push communications instructions.
