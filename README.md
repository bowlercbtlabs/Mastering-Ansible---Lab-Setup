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

- Build eth0 connection from VPCS and to eth1 on the Switch:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8d8f4fc7-e98d-460e-99a4-2751345c8423)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/0911c97b-9c60-444c-ab7a-08677a4fd859)

- Build Cloud1 eth0 connection to eth0 connection on the Switch:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/4c1bedc1-adc8-40f4-94be-92ae84ad1bf4)

- Start the VPCS:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/50f86ca5-b4a4-4e51-b4c7-f580a6bb9f2d)

- Open the console:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/0ba04c9b-4baa-4c2c-85d5-b6a35b357f44)

- Give the PC an IP address on the Network between the Ubuntu VM and the GNS3 VM (in this case, 192.168.79.0/24 | It may be different on your local network ):

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b42c9109-ee84-4ed9-95c2-9618e41eeb0f)

- Now ping from Ubuntu Server to the PC:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c1a3a14c-6f6d-4fd3-b5d1-13de4a6e4fd0)

- Now that we have reachability to everything, its time to add the Cisco IOS into GNS3:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/e5296e71-32db-4ccd-8ee9-90b4723ad848)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/1dcdcd07-6e97-4042-97c9-93be863ce39d)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f83f8a9f-d89b-4ded-830c-043cf673c26d)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b2826cc9-273a-4d9d-845c-27cb9eacc614)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/bbf1b968-f2e1-4df4-b37f-7d22bf21731c)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/44dbec01-fcd7-4c7d-bde1-61f86edb59ed)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/05a400d7-4cbc-4a4b-b9a0-7fc9bb20e27b)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b6a43104-ebf0-4dd5-a3cc-a2a07453dac3)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/9e111149-406b-4b22-87f3-7b0172c43682)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ee782e7a-18de-4a38-9764-414ff604bc54)

- Add the new device to the workspace area:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/4400b64b-5d2a-41f9-b617-fd88dabb9bfd)

- Connect Gi0/0 on the Cisco router to the switch Ethernet2 interface:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/811d5e3b-02d1-4e82-8acb-7db50de8c4dd)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/022adf0b-8102-4f3b-9c79-eff6aaf83688)

- Start the router and open the console:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/edfb14a3-e31e-4bf9-84fd-7494265ebe15)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/4b00bdc2-add2-47fa-b638-f813718ecebe)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/15602cd8-7179-4598-9e86-f823606db726)

- Add in the following commands to allow for ssh access from the Ubuntu VM server to the router:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5ae27208-62d4-4b03-b76f-0d02ef2df892)

- Add the interface configuration on Gi0/0 with an IP address on the network between the GNS3 VM and the Ubuntu server:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/9108a0cf-f46f-4e48-aa0e-fb77c7d71af4)

- Try the ssh connection from the Ubuntu Server that is going to be running Ansible:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/e735161f-58e0-41a2-afbc-b6020a7ed1d1)

- ssh may fail like below:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/83a16c7d-bca3-47b6-9abb-ce36d46d277f)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ef6d4528-4312-4561-947c-d92cf3bc0eed)


- This is because the Cisco device is not running a newer version of ssh that the Ubuntu server is trying to use to connect.

- We will now update the Ubuntu server to allow the old version of ssh:

- 
