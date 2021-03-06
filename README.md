# About This Repository

This is an example on how you could use the variant manager to setup a signle NIC port for multiple differnt protocols. 
Based on what variant is selected, will determine what protocol will be used. 
The variant manager is setup to enable and disable the IO devices respectively. 
All devices are configured to use the same NIC port/Adapter.

This repository contains two soultions.
Soultion "SimMaster" implements controllers or clients (Master devices).
Soultion "VariantGateway" implements devices or servers (Slave devices).

To test out the two projects, a setup could look like this:
![image](https://user-images.githubusercontent.com/19829308/162477781-59f2b2d3-df79-4591-a717-c8e999e4f798.png)


![6B1EEE30-A2A5-4CCF-A9D2-88000595D03A](https://user-images.githubusercontent.com/19829308/162747861-f79b3bcf-06cf-4103-91ab-2dff5459816d.GIF)

This sample is created by [Beckhoff Automation LLC.](https://www.beckhoff.com/en-us/), and is provided as-is under the Zero-Clause BSD license.

# How to get support

Should you have any questions regarding the provided sample code, please contact your local Beckhoff support team. Contact information can be found on the official Beckhoff website at https://www.beckhoff.com/en-us/support/.

# Further Information

Further Information on variant manger can be found at the [Beckhoff Infosys](https://infosys.beckhof.com) under (https://infosys.beckhoff.com/content/1033/variant_management/index.html?id=640168702518993771)

## Requirements

The following components must be installed to run sample code:

- [TE1000 TwinCAT 3 Engineering](https://www.beckhoff.com/en-en/products/automation/twincat/te1xxx-twincat-3-engineering/te1000.html) version 3.1.4024.0 or higher
