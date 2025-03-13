# SDN_Assignment3_NetAutomation

# Step One
The first step is to create a VM to host Ansible AWX on Ubuntu 22.04 LTS. Access the AWX web panel.
![image](https://github.com/user-attachments/assets/512ccc86-6539-4ad6-aa37-6bbee21d7e22)

# Step Two
Next create an inventory with hosts, credentials to the networking devices, and a project that links back to this repository
![image](https://github.com/user-attachments/assets/f2d704d7-ad94-4e3a-b5dd-baa9c9e0546b)
![image](https://github.com/user-attachments/assets/6089c64f-5aaf-4077-a5c9-83b9dfd1924f)
![image](https://github.com/user-attachments/assets/23d643f4-e917-4a13-95ba-7bb8e251af88)
![image](https://github.com/user-attachments/assets/5e9d6e12-c879-49f6-991e-2bb40ab972d4)

# Step Three
Create a job template, this one will use the ShowIpIntBr.yml playbook and the expected outcome should be a success with the IP interfaces displaying.
![image](https://github.com/user-attachments/assets/ba7bddf7-842f-4af0-ab07-4e50dca1aa46)
![image](https://github.com/user-attachments/assets/bfa38b9e-7a94-478a-a406-2a0e5f273636)

Create a workflow template for both jobs running the ShowIpIntBr.yml and configure_banner.yml playbooks.
![image](https://github.com/user-attachments/assets/a21adf9a-0126-4fdf-828e-a26b5d840f3a)
![image](https://github.com/user-attachments/assets/d802d66b-5edc-4365-af8b-1b41cea62967)

Create a survey and enable surveys on one of the job templates. Afterwards, launch the job which should display the interfaces.
![image](https://github.com/user-attachments/assets/45c344a5-51da-447d-bf0b-34a04931d626)
![image](https://github.com/user-attachments/assets/46f1bdc2-bdf6-4375-9959-190aa2d3d3ea)
