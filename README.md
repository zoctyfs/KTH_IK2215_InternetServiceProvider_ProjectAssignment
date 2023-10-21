# KTH_IK2215_InternetServiceProvider_ProjectAssignment
This is a two-student project assignment for KTH IK2215 in 2023, including the design of ISP and routing. Got 31 points out of the 32-point test.
The one point lost is in eBGP_transit, which needs to be improved by using the community attribute here. 
Use no-export on AS124R2 to ensure that AS21 does not propagate routes learnt from AS124, to ensure that the backup link AS124-AS21 is not used in the wrong scenario.
