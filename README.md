# goospf

GoOSPF implemnents the OSPF protocol in Golang.

The goal is to make a pure Go implementation of [OSPFv2](https://www.rfc-editor.org/rfc/rfc2328.txt) and [OSPFv3](https://www.rfc-editor.org/rfc/rfc5340.txt) and possibily other extentions if needed.

The idea is to make a implementation akin to [GoBGP](https://github.com/osrg/gobgp) but for the OSPF iGP protocol.

If route load balancing is possible, on the long term, it would be awesome to integrate this into Cilium or any other kubernetes project that does LB IPAM.
