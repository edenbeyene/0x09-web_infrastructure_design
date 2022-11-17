# Secured and Monitored Web Infrastructure

[![2-secured_and_monitored_web_infrastructure](https://user-images.githubusercontent.com/102972833/202543268-a37b3606-a3b1-4e10-b350-74425a82f870.jpg)
]

[Visit Board](https://miro.com/app/board/uXjVOfNFwbY=/)

# Description

This is a 3-server web infrastructure that is secured, monitored, and serves encrypted traffic.

# Specifics About This Infrastructure

. The purpose of the firewalls.
. The firewalls are for protecting the network (web servers, anyway) from unwanted and unauthorized users by acting as an intermediary between the internal network and the external network and blocking the incoming traffic matching the aforementioned criteria.
. The purpose of the SSL certificate.
. The SSL certificate is for encrypting the traffic between the web servers and the external network to prevent man-in-the-middle attacks (MITM) and network sniffers from sniffing the traffic which could expose valuable information. The SSL certs ensure privacy, integrity, and identification.
. The purpose of the monitoring clients.
. The monitoring clients are for monitoring the servers and the external network. They analyse the performance and operations of the servers, measure the overall health, and alert the administrators if the servers are not performing as expected. The monitoring tool observes the servers and provides key metrics about the servers' operations to the administrators. It automatically tests the accessibility of the servers, measures response time, and alerts for errors such as corrupt/missing files, security vulnerabilities/violations, and many other issues.
