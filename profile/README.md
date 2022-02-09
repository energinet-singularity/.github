# Singularity
Singularity is a team working for Energinet, the Danish TSO (Transmission system operator). Our main responsibility is to develop and operate the Energy Management system's future applications. We aim to be at the forefront of future needs for operating the electrical grid, by enabling high availability and quality of data alongside with resilient run of applications. 

## License
We publish all our code under the Apache 2.0 license. We use many different open-source projects in this organization, and we do not overrule their respective licenses. 

## Projects
These are the projects that we are currently working on. 
#### Real Time Platform (RTP)
The transition to green energy poses great requirements to how Energinet operates the grid in the future, the challenges are mostly unknown and therefore the solutions will require us to be agile an innovative in our solutions. Therefore, as a strategic initiative, a platform open to all data and software sources has been deemed a necessity to overcome future challenges. Our goal is to develop a platform where real-time data is handled and where applications can be built, run and managed. We have named it the Real Time Platform (RTP). The idea is to build a platform which can collect data (existing SCADA system, Remote terminal units (RTU), Phasor measurement units (PMU) etc.) from any source and use any source of software (self-developed, open-source, proprietary software etc.) for monitoring, optimized usage of grid, decision support, scenario analysis, automation etc. 

#### Dynamic Line Rating (DLR)
DLR is an application for the control center, operating the electrical grid. The application calculates the ampacity of an overhead line based on forecasted weather conditions and delivers it to the SCADA system used by the grid operators. The operators can then use the information to operate the grid more efficient, since the overhead lines capability can be used fully instead of relying on static worst-case ampacity for the lines.

#### Load frequency control (LFC) 
This project is still in its design phase. However, the goal is to develop a LFC running on RTP enabling aFRR (automatic frequency restoration reserve) to enable Energinet’s participation in PICASSO (The Platform for the International Coordination of Automated Frequency Restoration and Stable System Operation)
