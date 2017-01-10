# Cross compile on Linux with VS Code

This example requires running VS Code on a Linux host. Remote connections from Windows to Linux are not supported in VS Code.

To setup your Linux enviornment for cross compiling targetting a Raspberry Pi follow [this guide](http://hackaday.com/2016/02/03/code-craft-cross-compiling-for-the-raspberry-pi/) by @rud-had.

This example shows you how to map the necessary commands to connect to a gdbserver running on your ARM target board in the launch.json file. It is up to you to launch gdbserver on your ARM target, see the guide above. This example has a simple makefile and tasks.json to run make for building the example. You will need to get the binary produced onto your ARM target via scp etc. That is not shown here.