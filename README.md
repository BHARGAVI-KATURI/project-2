User
 │
 ▼
Internet
 │
 ▼
Internet Gateway
 │
 ▼
Application Load Balancer
 │
 ▼
Target Group
 │
 ├───────────────┐
 ▼               ▼
EC2 Instance   EC2 Instance
(AZ-1)         (AZ-2)
 │               │
 └──────┬────────┘
        ▼
 Auto Scaling Group
        │
 Launch Template
        │
 Private Subnets
        │
 NAT Gateway
        │
 Internet Gateway
        │
 Internet

SSH Administration

Developer
   │
   ▼
Bastion Host
   │
   ▼
Private EC2
