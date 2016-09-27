# PySweeper

Usage:
    network = "111.111"
    sweeper = PySweeper.PySweeper(network)
    
    network_ips = sweeper.network()
    
    #equivalent to 111.111.111
    subnet = 111
    
    subnet_ips = sweeper.subnet(subnet)
