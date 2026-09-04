
The nmstate file is an example config of what I have setup for an existing cluster.... its has xx'd out placeholders

This cluster is built and up, however, we expected teh switvches to have LACP, they dont, thus we need to reconfigure these to use `balance-slb`, see:

https://docs.redhat.com/en/documentation/openshift_container_platform/4.20/html/advanced_networking/network-bonding-considerations#enabling-OVS-balance-slb-mode_network-bonding-considerations

I have drafted up an example of what I think we need to do... but can you verify and create a new one of your own based on what you think we need?
