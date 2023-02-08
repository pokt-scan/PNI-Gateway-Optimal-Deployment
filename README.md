# Gateway Optimal Orchestration and Deployment

Analysis of current Pocket Network Portal deployment and possible optimal deployment strategies.

Report by:
Ramiro Rodríguez Colmeiro (ramiro@poktscan.com) 
Nicolas Aguirre (nicolas@poktscan.com)
Michael O'Rourke (michael@poktscan.com)
POKTscan Data Science Team

### Abstract

This report analyses the current deployment locations of the Pocket Network Portal (PNP) interfaces in the Amazon Web Services ecosystem. Currently the PNPs are deployed in multiple locations, this represents a high cost for both the Pocket Network Inc. and the servicer node operators. In this document we demonstrate that the current deployment strategy is sub-optimal and a better Quality of Service (QoS) can be achieved by reduc- ing the number of portals. More specifically, we show that the average QoS of the net- work can be reduced from 155 ms to 120 ms by keeping only three PNPs: `ap-southeast-1`, `eu-central-1` and `us-east-1`.
