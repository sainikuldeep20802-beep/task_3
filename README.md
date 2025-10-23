# task_3
step1: create a VPC
<img width="1917" height="1197" alt="Create_vpc" src="https://github.com/user-attachments/assets/254baa63-fc76-49cf-bd7b-edd4acbbadd4" />
VPC created successfully
<img width="1918" height="1198" alt="Vpc_created_successfully" src="https://github.com/user-attachments/assets/ac2859ac-1656-4bf7-8260-6608c5d1cb34" />
step2: create subnets public and private
<img width="1918" height="1196" alt="subnets_created public and private" src="https://github.com/user-attachments/assets/62295359-a1d4-4555-b509-54489bd56b88" />
step3: create and attach an internet gateways
<img width="1918" height="1198" alt="internet_gateways" src="https://github.com/user-attachments/assets/bc9f98ed-a36f-43dd-9e68-d1da8b7f437a" />
step4: Route table configuration public_route and private_route
<img width="1918" height="1147" alt="public_route" src="https://github.com/user-attachments/assets/f7f38354-d6a2-4300-b184-96fd5abf0171" />
<img width="1918" height="1151" alt="private_route" src="https://github.com/user-attachments/assets/810e7387-0770-4e08-a36f-33490d4ce40e" />
  VPC name: kul-vpc
  Region: united states(N.virginia)
  VPC CIDR: 10.0.0.0/16
  PUBLIC_SUBNET: 10.0.0.0/24 (internet access enable via INTERNET GATEWAY)
  PRIVATE_SUBNET: 10.0.2.0/24 (no internet access)
  INTERNET GATEWAY: Kul-IGW attached
