# HHA504_assignment_vms

## 1. Start and Stop a Virtual Machine
* Azure - Steps I Took
    * In Basics tab
        1. Clicked "Virtual Machine"
        2. Clicked "+Create," then "Azure virtual machine"
        3. Clicked "HHA-504" as Resource group
        4. Gave VM a name
        5. Changed security type to standard
        6. Changed VM architecture to Arm64
        7. Chose "Standard_B2pts_v2 - 2 vcpus, 1 GiB memory ($6.13/month)" as the size
        8. Changed the authentication type to "password" and created a username and password
    * In Disks tab
        1. Changed OS disk type to standard SSD
    * In Networking
        1. Deselected "Enable accelerated networking"
    * In Tags
        1. Created one tag called "scratch-instances" with a value of "vm1-test"
    * In Review + Create
        1. Checked the price, which came out to be 0.0084 hourly
        2. Clicked "Create"
    * VM was ran for 15 minutes, then stopped and deleted after 
    * (PLACEHOLDER on cost as it has not appeared yet)
* GCP - Steps I Took
    1. Clicked "Compute Engine" 
    2. Clicked "Create Instance"
    3. Changed the regions to us-east1(South Carolina) and us-east4(Northern Virginia) to see which is cheaper; us-east1 was cheaper, but was also the same the default region of us-central1(Iowa).
    4. Ultimately chose us-central1(Iowa) as it is low CO2
    5. Changed the machine type to e2-micro, resulting in a cheaper price
    6. Created the VM with a final price was $7.11 (0.01 hourly)
    7. VM was ran for 15 minutes, then stopped
    8. Deleted VM about 2 hours later, after learning in class that same day that simply stopping a VM does not stop cost from incurring
    8. Cost did not immediately appear, so I checked the following day. $0.02 was the total cost.
