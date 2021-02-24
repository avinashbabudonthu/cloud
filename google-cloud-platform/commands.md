# Gshell commands
* See the list of regions
```
gcloud compute regions list
```
* See the list compute instances
```
gcloud compute instances list
```
* Connect to GCE VM instance via SSH
```
gcloud compute ssh <instance-name> --zone <zone-name>

gcloud compute ssh instance-1 --zone asia-south1-a
```
* Update the packages in linux VM
```
sudo apt-get update
```
* Install apache2
```
sudo apt-get install -y apache2
```
* Start apache2
```
sudo systemctl start apache2
```
