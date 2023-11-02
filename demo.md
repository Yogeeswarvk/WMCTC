load balancer:

Azure load balancer is a layer 4 load balancer that distributes incoming
traffic among healthy virtual machine instances. Load balancers uses a
hash-based distribution algorithm. By default, it uses a 5-tuple (source
IP, source port, destination IP, destination port, protocol type) hash
to map traffic to available servers. Load balancers can either be
internet-facing where it is accessible via public IP addresses, or
internal where it is only accessible from a virtual network. Azure load
balancers also support Network Address Translation (NAT) to route
traffic between public and private IP addresses.

Traffic Manager:

Azure Traffic Manager is a DNS-based traffic load balancer. This service
allows you to distribute traffic to your public facing applications
across the global Azure regions. Traffic Manager also provides your
public endpoints with high availability and quick responsiveness.

virtual network:

Azure Virtual Network (VNet) is the fundamental building block for your
private network in Azure. VNet enables many types of Azure resources,
such as Azure Virtual Machines (VM), to securely communicate with each
other, the internet, and on-premises networks. VNet is similar to a
traditional network that you'd operate in your own data center, but
brings with it additional benefits of Azure's infrastructure such as
scale, availability, and isolation.

Azure Bastion: Azure Bastion provides secure RDP/SSH connectivity to
your virtual machines directly in the Azure portal over SSL. When you
connect via Azure Bastion, your virtual machines do not need a public IP
address.

Azure Firewall: Azure Firewall is a managed cloud-based network security
service that protects your Azure Virtual Network resources.

Azure DDoS Network Protection: Azure DDoS Network Protection is a paid
service that offers enhanced DDoS mitigation capabilities via adaptive
tuning, attack notification, and telemetry to protect against the
impacts of a DDoS attack for all protected resources within this virtual
network.

Protect your public IP resources in the virtual network from distributed
denial of service attacks.

![image](https://github.com/Yogeeswarvk/WMCTC/assets/126942451/f1e9d85f-f7e7-4f0f-9192-bb04926c0464)


![image](https://github.com/Yogeeswarvk/WMCTC/assets/126942451/bc436a46-ebb5-4c63-913c-103344ed24ca)



![image](https://github.com/Yogeeswarvk/WMCTC/assets/126942451/2c5d800a-5ebf-46e7-aa08-3d705d86abda)

