**Snapshot**:

##1.It often represents a backup of specific ebs volume, it might be any volume (Root volume,Data volume ,etc)/
##2.It is just a data backup/
##3.It is an ebs volume where you are able to save state and reboot with the same data at a certain point in time/
##4.we use ebs snapshot as backup solutions for a database volume/


**AMI(AMAZON MACHINE INSTANCE)**:
##1.It is a backup of entire EC-2 instances. For example: with proper cinfigiration its possible to create ami
   which includes multiples ebs volumes/
##2.AMI is representation of system state at specific time./
##3.An ami is similar,but its for the EC-2 instance themselves you cannot take a snapshot of a non ebs backed instamce,
   butyou can create a ami of one/
##4.we use an AMI to save instance configuration/
