                    USERS
                      │
                      ▼
              Route Traffic (Internet)
                      │
                      ▼
             Internet Gateway (IGW)
                      │
                      ▼
          Application Load Balancer
                      │
      ┌───────────────┴───────────────┐
      ▼                               ▼
 EC2 Instance                     EC2 Instance
 (AZ-1)                           (AZ-2)
      │                               │
      └────────── Auto Scaling Group ─┘
                      │
              Launch Template
                      │
              Amazon Machine Image
                      │
                Private Subnets
                      │
                 NAT Gateway
                      │
               Internet Gateway
