# NetworkAnalysisUsingPython

<b>Ping a list of IP addresses from Amazon Reachability list.</b>

Picked one IP from each region, finding network latency(ping 3 times), and finally sort the average latency by region.

http://ec2-reachability.amazonaws.com/

Expected Output for all 15 regions:

us-west-1 [50.18.56.1] - 100ms (Smallest average latency)
xx-xxxx-x [xx.xx.xx.xx] - 200ms
xx-xxxx-x [xx.xx.xx.xx] - 300ms ...
xx-xxxx-x [xx.xx.xx.xx] - 1000ms (Largest average latency)
