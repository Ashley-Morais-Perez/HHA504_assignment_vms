# Running VMs #

## GCP ##

Following the class GitHub HW and Google Cloud instructions, I created an instant vm.

<img width="950" alt="image" src="https://github.com/user-attachments/assets/72241b19-8de6-43d1-990e-1857fbd000a7">

<img width="955" alt="image" src="https://github.com/user-attachments/assets/a197ebd6-52ba-497f-825b-941490e7d5af">

I chose the most cost-effective options, focusing on creating, stopping, and reading a billing report from the VM.

<img width="953" alt="image" src="https://github.com/user-attachments/assets/0f54ac70-9d72-4dfd-8eae-1d8cb1a53975">

I let the vm run for about 3 minutes before clicking the drop-down menu on the right and selecting **stop**.

<img width="808" alt="image" src="https://github.com/user-attachments/assets/a9c9cfca-90d0-4c05-b5d6-7e543cfdefa2">

<img width="298" alt="image" src="https://github.com/user-attachments/assets/db4d2c88-aa4a-4ba9-8070-d1fa11abbc58">

<img width="583" alt="image" src="https://github.com/user-attachments/assets/983f011d-6fd1-4342-bb30-0312e365831f">

Once stopped, I clicked the **View Billing Reports**. 

<img width="793" alt="image" src="https://github.com/user-attachments/assets/2ba7bcc1-2a52-4431-a187-83f7ddcc738d">

There is currently no data on total or remaining costs displayed, but I expect it to be updated within a day or so. 

**_Updated Billing Report_**




## Azure ##

<img width="956" alt="image" src="https://github.com/user-attachments/assets/e173cbe8-2765-41ea-b4ac-dec9a525d88d">

I was having trouble selecting the recommended size suggested in the Github HW instructions. THe B1 sizes were not available and I was prompted to request a quota. 

<img width="964" alt="image" src="https://github.com/user-attachments/assets/f4655b3a-f02d-44c7-910f-ccf40a2c3d4f">

I had to adjust the security type to **standard** and switch the VM architecture to **Arm64** to be able to see the size B-series. WHile the B1 versions were not available, the B2 versions were and I was able to find a low cost.

<img width="951" alt="image" src="https://github.com/user-attachments/assets/713a3fb4-99a8-4edd-b9ef-7888d06ca95e">

For the administrator account, I selected the **SSH public key** and filled in the username and key pair name

<img width="476" alt="image" src="https://github.com/user-attachments/assets/391b8b51-22dc-4c55-a502-f6c019d2a79e">

I decided to select **none** for the inpbound port rules since I was just testing the VM. 

<img width="407" alt="image" src="https://github.com/user-attachments/assets/83175738-23cb-405e-ab47-6497886f3a45">

For some reason, I did not notice the copilot suggestion of **Help me create a low-cost VM**. I decided to click that option to see if it could bring down the cost some more, but I didn't have access to it. 

<img width="1009" alt="image" src="https://github.com/user-attachments/assets/15c26098-a5c1-483b-b136-fe0df79ecb38">

Once created, I let the VM run three minutes before hitting **stop**. 

<img width="945" alt="image" src="https://github.com/user-attachments/assets/fa882922-7e91-4977-bd7e-426876594f29">

<img width="572" alt="image" src="https://github.com/user-attachments/assets/2f4b45d5-3e57-4df8-8f8f-1071e6989ca9">

<img width="524" alt="image" src="https://github.com/user-attachments/assets/a3d8bef6-6dfd-4174-80bf-9cae2d1ae8f7">

Like GCP, Azure does need some time before displaying the cost overview data. 

<img width="947" alt="image" src="https://github.com/user-attachments/assets/b361132a-fc37-43d0-a963-cb6b052a63f7">

**_Updated Billing Report_**


## Comparison Overview ##

GCP was much more user-friendly, with everything easy to find. Azure was trickier; after deploying the VM, I had to navigate around to find the stop button in the VM overview. 

Based on the initial estimates, Azure seems cheaper than GCP, with Azure at *$6.13/month* and GCP at *$7.83/month*. Despite being harder to navigate, Azure offers more size options which allows users to have a greater choice in managing their budget.











