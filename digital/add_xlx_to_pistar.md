# Add XLX147(YSF India) to PI-star Hotspot

XLX147 is a multi protocol gateway reflector hosted in Chennai by VU3TBR Bala, that is connected to various modes like DMR, DSTAR, Peanut, Allstar, Echolink. Configuring this server in Pi-star will enable one to work with stations that use any of the modes mentioned above, using their radio. Follow the below steps for the configuration. DMRGateway allows one xlx server to be added out of 6 possible DMR networks. These steps are same for adding any xlx servers to Pi-star. 
## Enable DMR Gateway in Hotspot

1. Go to Configuration page in Hotspot 
1. In DMR Configuration section, select DMR Gateway as DMR Master 
1. Apply Changes. You will get the additional options as shown in the below picture. 
1. Enable BrandMeister Network (if not enabled) 
1. Choose XLX147 as the XLX Master
1. Enable XLX Master 
1. Apply Changes again. 
Note. There are no changes made to the existing DMR settings and the Hotspot /Radio will continue to work as before. 
![DMR settings in pistar](dmr_gateway_settings.jpg)
## Program Radio

The following channels need to be programmed in the radio for working the YSF India server.
1. Save a contact XLX Connect as a Private Call to ID 64002. This is to connect to the YSF India Server. 
1. Save a contact XLX Disconnect as a Private Call to ID 64000. This is to disconnect from the YSF India Server.
1. Save a contact TG6 as public call to ID 6. This is the channel to have QSO on the YSF Server once connected.

## Operating on XLX server

First connect to YSF India by keying (short PTT) XLX Connect

Change to TG6 and operate. The audio will be routed to YSF India server. Other stations (connected via peanut) on this channel can be heard to. 

The DMR traffic from BrandMeister will also available during this time. 

When done with qsos disconnect by PTTing XLX Disconnect. This step is optional.
## YSF India dashboard 
Server dashboard can be viewed at http://ysf-india.ddns.net/

### Revision history
12/05/2021 VU3BOJ Initial revision
