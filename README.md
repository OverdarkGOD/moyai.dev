# moyai.store
Moyai Services, moyai.store, is a commerical website designed to host goods and services. http://moyai.store

## About
Moyai leverages a robust technology stack, incorporating HTML5, CSS, PHP, and JavaScript for its core functionality. The application is containerized using Docker and deployed within a Proxmox virtualization environment. The underlying infrastructure utilizes a Debian-based Linux distribution as the host operating system for the Docker container.

To enhance security and network isolation, a VPN client is implemented on the Debian system, utilizing a static IP configuration. Comprehensive firewall rules have been established at both the Proxmox and VPN client levels, effectively restricting incoming traffic from the ISP's public IP and the VPN's static public IP. Furthermore, the virtual machine has been configured to prevent communication with any devices on the local area network (LAN) or VPN network.

Traffic management is handled by Nginx, a high-performance reverse proxy server, which is also containerized and runs alongside the main application. This setup ensures efficient request routing and load balancing. The domain infrastructure, including moyai.store and its subdomains, is managed through GoDaddy's domain registration and DNS services.

This architecture demonstrates a well-designed, security-focused deployment strategy that prioritizes isolation, access control, and scalability.

## List of Sub-Domains
I have compiled a list of all websites currently hosted under and associated with the moyai.store domain. This list is provided below.
<ul>
  <li>http://pay.moyai.store</li>
  <li>http://cloud.moyai.store</li>
  <li>http://teetime.moyai.store</li>
  <li>http://dev.moyai.store</li> 
</ul>

<em> http://dev.moyai.store may be down. This site is to test programs that I am developing or using.</em>

## Site Version
I will indicate the year followed by the revision count. For example, in the year 2024, including this current revision, it would be denoted as <b><em>2024.3</em></b>.
