Create your AWS key-pair from Ec2 -> Network & Secutiry -> Key pair

This is advanced level of terraform, this script will perform below:
     1. Create VPC
     2. Create Internet Gateway
     3. Create Custom Route Table
     4. Create a Subnet
     5. Associate Subnet with Route table
     6. Create Secutiry Grop to allow required ports
     7. Create Network Interface with an IP in the subnet that was created in earlier step
     8. Assign an elastic IP to the Network Interface created above
     9. Create Ubuntu server, install/enable tomcat inside it.
