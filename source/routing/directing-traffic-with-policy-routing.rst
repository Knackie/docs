Directing Traffic with Policy Routing
=====================================

Policy routing in pfSense® software refers to the capability of routing traffic by
matching it to specific firewall rules. Each firewall rule allows selection of a
gateway. If none is selected, traffic goes out the default gateway or follows the
routing table. If additional WAN interfaces or gateway groups are defined, these
may be selected in the Gateway field when adding or editing rules to direct
matching traffic as desired. This is primary used for multi-WAN, though it has
other uses as well.
