# Mininet_reader

# General commands

* sudo mn --custom HPDN_Exercises/week_1/custom_topo.py --topo mytopo                      ------- start a new network from a file
* sudo mn -c  ----- to clean the environment

# After starting mininet commands

* help
* net ---- all switches an host
* dump ----- 

http://mininet.org/walkthrough/

Start RYU(New Terminal)--

cd ~/ryu

PYTHONPATH=. ./bin/ryu-manager ryu/app/simple_switch.py   ---- ryu controller running simple_switch.py app listening on port 6633
