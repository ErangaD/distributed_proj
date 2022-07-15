# distributed_proj
python3 is required to run the system. We have implemented a user interface to see the available files and nodes.
Since there is a user interface, following two modules should be installed
if they are not already present.

1. flask
2. requests

installation:

    pip3 install flask requests

When the bootstrap server is running (used Java version)

How to run nodes?
    
    commands to run a node.
    python3 runner.py portOftheBootstrapServer BootstrapServerIp IpOfTheMachineNodeIsRunning

    Example: python3 runner.py 9000 192.168.42.100 192.168.42.200
             port of the bootstrap server = 9000
             ip address of the bootstrap server = 192.168.42.100
             ip of the node = 192.168.42.200