# OSL4
Clook

How to test code:

1. Make kernerl with make && make modules_install
2. Type "% cat /sys/block/sdb/queue/scheduler" on the command line
   and it should show noop deadline cfq [clook] 
