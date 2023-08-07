# AVIATRIX Certified Engineer Quiz Answers - ACE Associate





## About Aviatrix

**Question**: Where is the ‘center of gravity’ in the new computing model?  
**Answer**: Public Cloud

**Question**: What caused a large push to the public cloud?  
**Answer**: Speed of Deployment

**Question**: As applications move to the cloud, their proximity to the Internet is:  
**Answer**: Closer

**Question**: What are common challenges in the cloud?  
**Answer**: All of the Above

**Question**: How does Aviatrix help customers in public clouds?  
**Answer**: Aviatrix is a multi-cloud platform that brings a consistent architecture with Day 2 Operations and Visibility

**Question**: Which group led the initial charge in the cloud?  
**Answer**: DevOps

**Question**: True or false: When things break, DevOps teams can troubleshoot their own network connectivity without needing networking teams for support.  
**Answer**: False

**Question**: Which unique challenge does a network engineer face in the cloud that isn’t present on-perm?  
**Answer**: Accounts/Subscriptions

**Question**: When organizations build in the cloud, the providers typically follow what model:  
**Answer**: Build it yourself – we provide the pieces

**Question**: True or false: Cloud providers can easily help customers in multi-cloud deployments.  
**Answer**: False






## Networking Principles in the Cloud

**Question**: What is the definition of a PaaS Service?  
**Answer**: You as the customer manage just the application and data

**Question**: What is a hybrid cloud?  
**Answer**: A combination of Public and Private Cloud

**Question**: Which is NOT a valid component of the cloud?  
**Answer**: Geographical Zone

**Question**: Is Availability Zone 1A the same for every customer in cloud environments?  
**Answer**: No

**Question**: True or false: We have an architectural gap in cloud today because there is no consistent framework for network and security across clouds.  
**Answer**: True

**Question**: The On-Prem world is most similar to which type of service:  
**Answer**: IaaS

**Question**: Office365 is an example of which service:  
**Answer**: SaaS

**Question**: True or false: A region is the same thing as a data center for cloud providers.  
**Answer**: False

**Question**: True or false: When a cloud provider deploys a region, there are always multiple availability zones present.  
**Answer**: False

**Question**: One advantage of availability zones includes:  
**Answer**: Resources across AZs can survive a data center outage





## AWS Networking 101

**Question**: Which AWS service represents a virtual machine?  
**Answer**: EC2

**Question**: True or false: To connect a VPC, AWS uses an implicit router that customers must configure to allow communication between VPCs.  
**Answer**: False

**Question**: Which AWS service best represents your private virtual walled garden in the cloud?  
**Answer**: VPC

**Question**: True or false: In AWS, subnets are global resources spread across availability zones.  
**Answer**: False

**Question**: Which AWS security component is a stateless filter?  
**Answer**: NACL

**Question**: True or false: Security Groups in AWS can not be shared across VPCs unless they are peered together.  
**Answer**: True

**Question**: Which gateway is not an available option with AWS?  
**Answer**: Virtual Network Gateway

**Question**: True or false: Transit Gateway in AWS fully automates routing so that no manual configuration is required.  
**Answer**: False

**Question**: In AWS, a Direct Connect circuit can terminate on which of the following:  
**Answer**: Direct Connect Gateway

**Question**: Using native AWS constructs, the highest available bandwidth within an IPSEC tunnel is:  
**Answer**: 1.25Gbps

**Question**: True or false: There are currently no limitations to the number of routes supported in AWS Transit Gateway.  
**Answer**: False



## Azure Networking 101

**Question**: What is the private circuit term in Azure that is analogous to Direct Connect in AWS?  
**Answer**: ExpressRoute

**Question**: What are Virtual Network Gateways used for?  
**Answer**: Hybrid Connectivity termination constructs for VPN or Express Route

**Question**: Which Azure component groups items together for better organization control of a specific workload?  
**Answer**: Resource Group

**Question**: What is the top level organizational structure in Azure?  
**Answer**: AD Tenant

**Question**: True or false: In Azure, subnets are created as either private or public.  
**Answer**: False

**Question**: Some challenges with Azure Virtual WAN as a platform include:  
**Answer**: All of the above

**Question**: An ExpressRoute circuit in Azure can terminate on which device (select all that apply)  
**Answer**: ExpressRoute Gateway, Virtual Network Gateway

**Question**: True or false: Using ExpressRoute hairpinning for spoke to spoke traffic is the recommended option for transit within Azure.  
**Answer**: False

**Question**: What is an NVA in Azure (select all that apply)  
**Answer**: Any 3rd party device in the Azure marketplace, Network Virtual Appliance

**Question**: Challenges with using an NVA to provide spoke to spoke communication in Azure include: (select all that apply)  
**Answer**: User Defined Route Management at scale, SNAT required for traffic symmetry



## GCP Networking 101

**Question**: GCP private dedicated connectivity is referred to as  
**Answer**: Cloud Interconnect

**Question**: True or false: All resources within GCP are either Global or Regional or both.  
**Answer**: False

**Question**: A VPC is an example of a:  
**Answer**: Global Resource

**Question**: For a single user, GCP resources are structurally organized in a:  
**Answer**: Project

**Question**: True or false: GCP encourages deployments of multiple VPCs to spread out all your workloads.  
**Answer**: False

**Question**: What does Auto Mode in GCP mean?  
**Answer**: subnets are created in each region

**Question**: True or false: GCP supports dynamic routes within the cloud.  
**Answer**: True

**Question**: True or false: VPC peering in GCP allows VPC to be transitive.  
**Answer**: False

**Question**: A project can access another project’s resource via (select all that apply)  
**Answer**: Shared VPC, VPC Peering

**Question**: What are the caveats of a Global VPC design in GCP?
**Answer**: All of the above




## OCI Networking 101

**Question**: What are virtual cloud networks called in OCI?  
**Answer**: VCN

**Question**: True or false: OCI subnets can be tied to one or all Availability Domains in the region.  
**Answer**: True

**Question**: True or false: DRG supports exactly 2 types of attachments: VCN and FastConnect.  
**Answer**: False

**Question**: In OCI you need to specify a _____________ when creating resources.  
**Answer**: Compartment ID

**Question**: Service Gateways provide _____________ access from VCNs to Oracle Services.  
**Answer**: Private

**Question**: Tenancy IAM metadata is bound to ___________________.  
**Answer**: Home region

**Question**: What are the two options for interconnecting VCNs within a region?  
**Answer**: Local Peering Gateway and DRG Attachments

**Question**: What does a Dynamic Routing Gateway in OCI do?  
**Answer**: All of the above

**Question**: True or false: DRGs within one OCI Region can be peered using an RPC.  
**Answer**: True

**Question**: What is the benefit of Dynamic Routing Gateway attachments?  
**Answer**: They have their own route tables, which allow for flexibility




## Multi-Cloud Network Architecture

**Question**: What are the main pillars of the MCNA?  
**Answer**: Cloud Core, Operations, and Access

**Question**: True or false: Security and Visibility is inserted throughout the MCNA Architecture.  
**Answer**: True

**Question**: Which answer is a benefit of having a Multi-Cloud Network Architecture?  
**Answer**: All of the Above

**Question**: Customer Challenges in cloud include:  
**Answer**: All of the above

**Question**: What is the most important aspect of any multi-cloud network?  
**Answer**: Transit

**Question**: The function of the cloud operations layer includes (select all that apply)  
**Answer**: All of the above

**Question**: The Cloud Core layer of the MCNA provides:  
**Answer**: Normalized Data plane across clouds

**Question**: True or false: With MCNA, security must be configured per cloud provider to maintain consistent governance.  
**Answer**: False

**Question**: Cloud Access in MCNA provides common access for:  
**Answer**: All of the above

**Question**: The core principal of MCNA is:  
**Answer**: a multi-cloud network and security framework for consistent deployment across clouds

**Question**: What are the three columns of the MCNA?  
**Answer**: Management, Application, Cloud Networking

**Question**: What are the three layers of the MCNA?  
**Answer**: Operations, Connectivity, and Core

**Question**: True or false: Security and Visibility are inserted throughout the MCNA Architecture.  
**Answer**: True

**Question**: Which answer is a benefit of having a Multi-Cloud Network Architecture?  
**Answer**: All of the above

**Question**: What is the most important aspect of any multi-cloud network?  
**Answer**: Transit

**Question**: The function of the cloud operations layer includes (select all that apply)  
**Answer**: All of the above

**Question**: True or false: MCNA enables service chaining (i.e., insertion of firewalls).  
**Answer**: True




## Aviatrix Platform Feature Overview - Part 1

**Question**: Which best describes the Aviatrix Transit Solutions?  
**Answer**: Built using Aviatrix IPSEC for encryption by default with option for high performance

**Question**: True or false: Aviatrix transit must be built out per cloud and does not support cross-cloud communication by default.  
**Answer**: False

**Question**: What is a challenge with native encryption within the cloud?  
**Answer**: All of the above

**Question**: What are the components within the Aviatrix Platform?  
**Answer**: All of the above

**Question**: Why is cloud IPSEC limited to 1.25G?  
**Answer**: Native solutions build tunnels across a single core only

**Question**: True or false: The Aviatrix FQDN Egress Filter supports both centralized and distributed egress methods.  
**Answer**: True

**Question**: True or false: Aviatrix can extend native AWS features like Guard Duty to provide enforcement of alerts.  
**Answer**: True

**Question**: The advantage of Aviatrix Transit within the cloud is:  
**Answer**: All of the above

**Question**: With Aviatrix HPE, customers can get:  
**Answer**: All of the above

**Question**: True or false: Aviatrix can provide filtering of partner route advertisements through a BGP Approval Process.  
**Answer**: True

**Question**: An enterprise has workloads in AWS, Azure, and GCP. How many Aviatrix Controllers do they need?  
**Answer**: 1

**Question**: What is needed for workloads in two Segments to communicate with each other?  
**Answer**: Configure a Connection Policy

**Question**: True or false: Aviatrix CoPilot can be used to write Terraform scripts.  
**Answer**: False

**Question**: What is a challenge with native encryption within the cloud?  
**Answer**: All of the above

**Question**: What are the components within the Aviatrix Platform?  
**Answer**: All of the above

**Question**: Why is cloud IPsec limited to 1.25G?  
**Answer**: Native solutions build tunnels across a single core only

**Question**: True or false: The Aviatrix FQDN Egress Filter supports both centralized and distributed egress methods.  
**Answer**: True

**Question**: True or false: Aviatrix can extend native AWS features like GuardDuty to provide enforcement of alerts.  
**Answer**: True

**Question**: The advantage of Aviatrix Transit within the cloud is:  
**Answer**: All of the above

**Question**: What does Multi-Cloud Network Segmentation provide?  
**Answer**: All of the above



## Feature Overview - Part 2

**Question**: What are some challenges with inserting firewalls in the cloud?  
**Answer**: All of the above

**Question**: How much throughput can Aviatrix achieve with Firenet?  
**Answer**: Up to 70G

**Question**: What advantages does the Aviatrix Site to Cloud offer?  
**Answer**: All of the above

**Question**: True or false: Aviatrix Firenet can orchestrate the firewall deployment, firewall routing, and VNET/VPC routing for NGFW insertion.  
**Answer**: True

**Question**: True or false: The Aviatrix User VPN solution does not allow profile based granular access control.  
**Answer**: False

**Question**: Which 3rd party integrations are available for Aviatrix User VPN?  
**Answer**: All of the above

**Question**: True or false: Aviatrix Firenet requires that customers use gateways in the spokes, as this is not supported using native constructs for transit (i.e. AWS TGW or Azure Peering).  
**Answer**: False

**Question**: Which Aviatrix feature allows customers to group VPC/VNETs with common security properties for access?  
**Answer**: Security Domains

**Question**: True or false: Aviatrix Site 2 Cloud can also be used to onboard IoT devices.  
**Answer**: True

**Question**: What problems does Aviatrix Private S3 solution solve for? (select all that apply)  
**Answer**: Data exfiltration, Private access (RFC1918 only) to S3 buckets without the need of public addresses

**Question**: What are some challenges with inserting firewalls in the cloud?  
**Answer**: All of the above

**Question**: What is the advantage of the Centralized Stateful Firewall on Aviatrix Single AZ HA?  
**Answer**: All of the above

**Question**: What advantages does the Aviatrix Site2Cloud offer?  
**Answer**: All of the above

**Question**: True or false: Aviatrix FireNet can orchestrate the firewall deployment, firewall routing, and VNet/VPC routing for NGFW insertion.  
**Answer**: True

**Question**: True or false: The Aviatrix User VPN solution does not allow profile-based granular access control.  
**Answer**: False

**Question**: Which third-party integrations are available for Aviatrix User VPN?  
**Answer**: All of the above

**Question**: True or false: With Aviatrix Transit FireNet, workloads cannot be placed in different segments AND be inspected by NGFWs without losing visibility.  
**Answer**: False

**Question**: True or false: Aviatrix can provide filtering of partner route advertisements through a BGP Approval Process.  
**Answer**: True

**Question**: Which Aviatrix feature allows customers to group VPC/VNets with common security properties for access?  
**Answer**: Security Domains (also known as Segments)

**Question**: True or false: Aviatrix Site2Cloud can also be used to onboard IoT devices.  
**Answer**: True




## UI Walkthrough




##Day 2 Operations


## Operations, Visibility, and Troubleshooting Day 2 Operations

**Question**: True or false: Aviatrix is a multi-cloud Terraform provider.  
**Answer**: True

**Question**: True or false: Aviatrix can not provide packet captures of live traffic.  
**Answer**: False

**Question**: True or false: The VPC tracker is only available for AWS.  
**Answer**: False

**Question**: What does Aviatrix use for Controller HA in AWS?  
**Answer**: All of the above

**Question**: How does Flight Path help users troubleshoot connectivity problems?  
**Answer**: Provides a visual walk-through based on source and destination to highlight path issues

**Question**: What are some operational challenges that customers face in the cloud?  
**Answer**: All of the above

**Question**: True or false: The Aviatrix controller can perform auditing of routing constructs. This ensures that no new routes have been added, that can affect end to end network correctness.  
**Answer**: True

**Question**: True or false: Common troubleshooting tasks like ping and traceroute can be run from any Aviatrix gateway.  
**Answer**: True

**Question**: What happens when the Aviatrix components require upgrades?  
**Answer**: Upgrades are hitless

**Question**: Which of the following statements is true?  
**Answer**: Customers can spin up a single controller and on-board multiple cloud accounts for management



## Feedback form 
https://docs.google.com/forms/d/e/1FAIpQLSfG-7IbOFn6cLYcy_LWrciF_2slnbcMbOzgWZUZfAtCgyEa3A/viewform







