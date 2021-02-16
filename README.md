# LoadBalancer

install_requires=[
    pip3 install requests
    pip3 install json
]

downlaod load-balancer.py script from git and run it `pip3 load-balancer.py`

This is just a simple mock load balacner script. It tries balacne load between two server. Most of my previous load balancer experience came from AWS. I have developed a stack, which contains instances sitting behind elastic load balancer. It balances Https traffic and check check for health of the application. Anytime any of the node fail it will stop sending traffic over to that node. It was also associated with AWS auto scaling group wich will terminate that instances and brings up a new one. 