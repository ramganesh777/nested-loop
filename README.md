# nested-loop
This module will create a AWS security group called ramg.

In this module we have ports 22 and 443 declared as key and the respective CIDR blocks are mapped as value.

We have opened all the traffic to 443 port, but we have allowed only specific range to port 22.

when we execute this terraform module, we will have a SG created with the ramg which will have two ingres , one for port 22 and another one for port 443.
