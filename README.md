# p4-ipv6-switch-ml
This paper was presented at the 2019 P4 Worship at Stanford:  https://arxiv.org/pdf/1903.06701.pdf

The paper implemented switch ML using IPv4 broadcast messages.
I had to write a new IETF draft to extend switch ML to use IPv6: https://datatracker.ietf.org/doc/draft-hsingh-ipv6-coin-ml/

The p4-16 code in this repo supports the above draft

Code has been compiled with p4lang/p4c and tested with bmv2 simple_switch and STF packets.  

During the end of the Hackathon, several deficiences were seen with latest P4-16 specification.  This P4 code will not compile for the bmv2 backend.  The issues are discussed at this URL:

https://mailarchive.ietf.org/arch/msg/coin/0ywn5VdEO7GI4xFohrZrebtXZPI
