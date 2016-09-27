# PySweeper

Usage:

    from PySweeper import PySweeper
    
    network = "111.111"

    sweeper = PySweeper(network)

    network_ips = sweeper.network()

    subnet = 111
    
    subnet_ips = sweeper.subnet(subnet)
