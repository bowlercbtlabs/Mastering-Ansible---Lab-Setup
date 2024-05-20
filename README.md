# Mastering-Ansible---Lab-Setup
Mastering Ansible - Lab Setup

****
NOTE
*****

- Try this way first with your CentOS9 VM and use the 'virtualbox' VM option, it may be easier:

- https://docs.gns3.com/docs/emulators/adding-vmware-vms-to-gns3-topologies

****
If the above Method fails, try again using the VMWare Workstation option, if that 2nd option fails then proceed on to the below method:
****

****
- VMWare Workstation Download:
****

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

- We will now update the Ubuntu server to allow the old version of ssh by applying the following commands:

sudo vi /etc/ssh/ssh_config

KexAlgorithms diffie-hellman-group1-sha1,curve25519-sha256@libssh.org,ecdh-sha2-nistp256,ecdh-sha2-nistp384,ecdh-sha2-nistp521,diffie-hellman-group-exchange-sha256,diffie-hellman-group14-sha1

HostKeyAlgorithms +ssh-rsa

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/be017911-c1cd-4f65-bfb9-e9a3aef54a70)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/dab69ff9-3478-477f-ae21-96664ba82abb)

https://networkevolution.in/how-to-enable-older-key-exchange-and-host-key-algorithms-in-ubuntu-to-initiate-ssh-connection-to-older-ios-images/

- Try the ssh connection again:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/912ac02a-8d87-4517-af7b-0144779319e9)

- Its working now, you have successfully created a connection from the ubuntu VM to the GNS3 VM running inside of GNS3


******
Install VSCode and Create Remote SSH connection to Ubuntu Server, this is where the Source Code will go
******

- Topology we are going to use with VSCode:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8a5b50d8-a2e8-4bc7-ae5d-08a6d82529bf)

- Install VSCode:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/a99a5e47-8e22-45d2-81da-86c89ea40d4e)
 
- Install Ansible:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ece62dd5-6363-4c50-9de8-a00e0fab3a92)

- Install Remote Development:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c94d5f6e-04d5-4d95-b67e-8d24059e37b3)

- Add remote ssh client 'Remote SSH: Add New SSH Host':

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/74676882-0d40-41d3-8cdd-9ccd414c47d4)

- login to the Ubuntu Server IP 'root@192.168.158.128'

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/300b514f-26a6-4a0d-a7f1-c6191079564a)

- Now select 'Remte SSH: Connect to Host'

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ef972a50-ef7d-4e8b-acaf-16fd99757573)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/62a25039-be93-4907-9a80-0078a18487b4)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c7fdc3fd-e747-452f-bf0b-674d7b9b524a)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b12d84f3-5131-49ca-a3c8-331cf2cad1f6)

- Create the Ansible directory and playbook:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/394108f3-aeb9-46e1-9f9e-581747ef8de4)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ae65876a-8469-4a41-8417-ba08980bd34f)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f56395c0-421a-46eb-9418-66e145058b12)


******
Install Windows Subsystem for Linux (WSL)
******

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8b7c9945-a2b1-4d1e-9e7b-33280ce9aadc)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8f8af806-6002-44b2-8e67-cd5bd95469ed)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/a73815fa-c1b8-4af1-a28e-2ff869d182cf)

- Reboot System and open Ubuntu:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/270a710c-3aa1-4663-8e71-184a1793fb15)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5412632f-f483-4e74-bfa7-7f5b48eee725)

- Create Ansible Directory and Install VSCode:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/43312a77-5b72-4978-8c95-a48f63615d3f)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/81656dee-1cf7-4c7d-9200-29f17ba93602)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/ff8bc7db-8961-4c6f-a48f-785b14d218e6)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/84fc2df0-9d21-4c9b-83c2-fc5d91f46735)


*****
Create New Ansible Repository in Github
*****

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/27b8fbf2-20ea-4fcc-8c81-ba22c92d98a4)

Add README file to ansbile directory:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/415f5673-0fb5-42d7-b31e-abacbe792d69)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8bb65d72-9e17-43e2-b65c-aa6544755395)

Install Git:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/fc8f9219-de38-4026-b527-7a9aa59fd193)

Download Git for Windows:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/e00fecec-93f9-4983-a569-f74585c9b678)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/8b9e21cf-68ed-4b49-94f3-c218f5c3a259)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/65668379-3e3e-4850-9342-6db91bf01135)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/d3ad63c3-6dd5-4eb0-afe2-3f54822b1964)

No Repo found, create it:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/5eb97dc6-431e-4849-b6c6-c370423d20c2)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/47087ccd-fc29-44ce-ad7d-89f6e96b5c4b)

- Point to your github repo, not the instructors (i.e. bowlercbtlabs etc....)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/6cd68620-24b0-47b3-815b-3eecfb29737a)

- Login to Github:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/11f69f7c-4132-4505-9e57-78398fb7dc9e)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/bdf3fef6-9d47-46c0-8232-a814d2962f85)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/2461a5f4-66fc-4ea1-bd6d-501c6339c792)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/b60f03bd-60e1-40cd-b422-80b0e16c04f2)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/4d5803fb-9904-44e4-83df-5d8ca7720674)

- Update README and create new file/playbook:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/49ce9c14-1864-44b2-a0c5-7fb1bc418d58)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/c3b0781c-18c5-44aa-96a1-37a8ee785663)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/817fef38-a0a6-46f9-a461-284e7fb5d948)

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/92f5eb4f-1b56-4dca-8bd2-b0de357c50a3)

- Now we can see the new contents on github:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f7348f57-ed98-4110-9716-a12ce2b58f3f)

- Now make a change inside the new playbook on github:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/e3f4a7bc-b65b-46ee-999b-59e9c369ad7b)

- Now do a git pull from VSCode:

![image](https://github.com/bowlercbtlabs/Mastering-Ansible---Lab-Setup/assets/120626722/f87e5677-2507-46c1-8dd0-7cc9011258c5)

### DONE, Now you can use your github repository to download Ansible files/folders/playbooks etc....




