# Simple OSPF lab using FRR

This lab example consists of three FRR routers connected in a ring topology. Each router has one PC connected to it.

This is also an example of how to pre-configure lab nodes on "linux" node types in Containerlab.

To start this lab, run the *run.sh* script, which will run the containerlab deploy commands, and then configure the PC interfaces.

The lab configuration is documented in detail at: https://www.brianlinkletter.com/2021/05/use-containerlab-to-emulate-open-source-routers/

# Add images
run *topo.sh*

Prerequisites docker, clab, brctl (establishing a bridge)

1. Establish a bridge br0 on a machine and connect it to the broadband interface enp025 2. br0 is connected to containerlab, and the type of br0 is bridge 3. Enter the IP and routing information of br0 in the terminal
