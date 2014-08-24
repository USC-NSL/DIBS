DIBS
====

DIBS: Just-in-time Congestion Mitigation for Data Centers

This is our NS-3 simulation code for DIBS, appearing at Eurosys 2013. We use NS 3.15 version. Please apply the patch to
NS-allinone-3.15/ns-3.15

Abstract:
Data centers must support a range of workloads with differing
demands. Although existing approaches handle routine
traffic smoothly, intense hotspots–even if ephemeral–
cause excessive packet loss and severely degrade performance.
This loss occurs even though congestion is typically
highly localized, with spare buffer capacity at nearby
switches. In this paper, we argue that switches should share
buffer capacity to effectively handle this spot congestion
without the monetary hit of deploying large buffers at individual
switches. Specifically, we present detour-induced
buffer sharing (DIBS), a mechanism that achieves a near
lossless network without requiring additional buffers at individual
switches. Using DIBS, a congested switch detours
packets randomly to neighboring switches to avoid dropping
the packets. We implement DIBS in hardware, on software
routers in a testbed, and in simulation, and we demonstrate
that it reduces the 99th percentile of delay-sensitive query
completion time by up to 85%, with very little impact on
other traffic.

Contact: Rui Miao (rmiao@usc.edu)
