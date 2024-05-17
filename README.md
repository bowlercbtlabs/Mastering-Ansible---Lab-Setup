# Mastering-Ansible---Lab-Setup
Mastering Ansible - Lab Setup


- VMWare Workstation Download:

https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-player/workstation-player-evaluation.html.html

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/1f99e2b1-d169-4bbe-abb4-f57f87213300)

- Download Ubuntu and add image to VMware Workstation:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f3cceb54-5a9d-4d3d-bdfb-d30c9472f827)


- Power up the Ubuntu machine:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/83536d98-963a-4848-85e5-2e5371aa098c)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ac1e27c0-f412-42e8-b851-04a4a6900a35)

- Update software:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/3390d103-9dcb-4b8c-8081-9a8ba577c9d8)

- Install Interfaces: 

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/6eb93892-0d9e-4d50-b925-f8a0e52fad99)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5fd97ba1-b41c-4b0a-983d-60cc52bd7398)

- Install ssh:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ed9be7de-bfa1-48df-b60f-c63ea01b64b0)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f67a68ec-2324-4d65-b68c-ceb58f5dc40f)

- Shutdown server and add network interface (this will be the interface we connect to GNS3 through the GNS3 VM):

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/4e9262e1-c7a5-4d3f-9fde-eadb0679a518)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5b075498-82a9-43ec-bde8-57860ed5b9af)

- Power up Server and now we have 2 network interfaces:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c17ddc89-f797-4aa2-adcd-fda463b04030)

- Try to ssh to the new interface IP:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/0f2328e7-4a4d-4053-92b8-7c84b5f6f908)

- Download GNS3 VM:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/6b1c7ee0-819f-40d2-9333-c6321f2b4b6c)

- Open GNS3 VM from VMWare Workstation:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b83984cb-151d-46fa-81ed-c4e4b4a6c055)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/eec96c97-759e-4b7e-b368-e6f75d143893)

- DISABLE WINDOWS HYPERVISOR, VIRTUAL MACHINE AND LINUX SUBSYSTEMS IN ORDER TO GET IT TO WORK:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/15d6cec3-11d6-4235-8677-5b4077e20470)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/97f75391-a7ee-4b62-b937-88b952452d28)

- POWER ON THE GNS3 VM

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c1f92480-fb3c-4074-8d87-b89db356e3b7)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/811d6b97-7660-481a-bde1-1408bb0b09e4)

- LOGIN TO UBUNTU VM and try to ping the GNS3 VM:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/0497cd4d-68d0-4f21-81b3-3c19db639767)

- Download the GNS3 software now:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5cd96db3-9bf8-43fa-8c01-a758b5f8b17b)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/838190b9-57e3-463e-aef3-82f5a6a05dcc)

- Run GNS3 installer:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/cd60d6f5-756e-4493-8d0c-bd779b517adf)

- Go back to GNS3 VM and open the shell:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/368dcd24-7fe9-4fab-bccf-66fb51d33e61)

- Run 'ifconfig':

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8aa98879-9557-4d5a-9332-03bb01a3ee15)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/a53fe80c-2cb7-4d2d-80af-ce4f989753f2)

- Go back to GNS3 and select "run appliance in a virtual machine':

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/80bfc77d-e9b6-4467-ada0-2fdf688fe9a4)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/296297f3-7038-4b79-be80-c6d9b8db0ee3)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/16928ef8-4468-4bdd-8647-282f66171369)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/2815357c-a51c-46c1-a30e-ac05035e674a)

- Create new GNS3 Project:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/afed356d-a0f0-40fd-8aa5-d034f17fbe1f)

- Move cloud over to workspace:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/770ba92e-687d-42bc-ac43-ed3713d40964)

- Select the GNS3 VM:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/56d75a99-dd34-4c63-a8ae-e6403e718441)

- Drag and drop an Ethernet switch and choose the GNS3 VM:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/e711f1c6-436c-4ed2-98bd-bc6e512f6455)

- And do the same for the VPCS:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/7a08c2a9-88d0-4ba9-a298-c410c7d4e95d)





