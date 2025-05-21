# Domainator: DNS Malware Traffic Dataset

This repository contains traffic recordings of DNS malware that was recorded as part of the following paper:

D. Petrov, P. Ruffing, S. Zillien, S. Wendzel: *[Domainator: ...](link to pre-print)*, in Proc. ARES 2025, Springer, 2025.
[BibTex download](todo)

If you want to use the dataset, please refer to our paper.

## Notes
  
- The data has been collected on a bare-metal testbed as described by [Zillien et al.](https://www.researchgate.net/publication/380105932_A_Development_Framework_for_TCPIP_Network_Steganography_Malware_Detection). The produced data only contains the communication packets and poses no danger or harm on its own. The network metadata is of a ficticious network setup that resembles a real environement.  

- Each malware or tool has its own folder within 'malware_recordings', which contains the recordings used for the training.
The recordings used for validation can all be found in 'malware_recordings/others/validation-sets'.
