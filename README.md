# contiki
simple-udp-rpl/
------------

A really simple Contiki program that shows how to write Contiki programs. To
compile and test the program, go into the simple-udp-rpl directory:

    cd examples/ipv6/simple-udp-rpl

Run the 'make' command.

    make all

This will compile the simple-udp-rpl program in the 'UbimoteHr' target.  This causes
the entire Contiki operating system and the simple-udp-rpl application to be
compiled into a single program that can be run by typing the following command:

    # sudo make broadcast-example.upload

then run below command

  # sudo picocom -b 115200 dev/ttyUSB0
  
  now you can see the received data in terminal.
