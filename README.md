# Upgrading-Windows-Server-to-Domain-Controller
Here I am upgrading my Windows Server into a Domain Controller -  A DC  controls things like logins, permissionss and security across all users and computers across a network. 

From the time I added in my Roles and Features into my Server, there is an option in the installation wizard which enables me to upgrade my Server into a Domain Controller.
<img width="935" height="838" alt="image" src="https://github.com/user-attachments/assets/42b59385-f4a9-4c53-90f7-a4675d3ba61e" />

Once I clicked this hyperlink, I was directed to a Configuration Wizard, the style of operation for this deployment I chose was "New Forest" and I named my Root Domain "lab.local".

<img width="1062" height="858" alt="image" src="https://github.com/user-attachments/assets/f4332834-cba8-4315-b212-bcbc3aca964b" />

Next I created a password for my DSRM, and default accepted the next couple of pages until my next specification

<img width="1008" height="797" alt="image" src="https://github.com/user-attachments/assets/286cf417-233d-4f71-90b9-bcaeca883afd" />

Finally at the Prerequisites Check, after final reviews, I click Install. 
<img width="987" height="822" alt="image" src="https://github.com/user-attachments/assets/a6dee0ce-765b-490a-b40e-cca4000415d3" />

Once the Domain Controller has been created, my virtual machine restarts. I open up the search bar and look for "Active Directory Users & Computers" in order to begin creating Users for my Directory.

<img width="1057" height="900" alt="image" src="https://github.com/user-attachments/assets/64cbca57-a611-47a5-adc8-53a7bbf515f5" />

Once ADUC is opened, I navigate to my domain controller which I have named "lab.local", right click it, click New > Organizational Units.

<img width="1018" height="846" alt="image" src="https://github.com/user-attachments/assets/281d597d-5414-4f2b-b4cd-0e0bd53154d2" />

I name my first OU, "branch1" and within the branch1 OU I create another OU and call it "Users". I make two more and title them, "Computers" and "Users"

<img width="1025" height="807" alt="image" src="https://github.com/user-attachments/assets/5b6f5d80-eb11-4ca1-b96a-0fa0645e2735" />

<img width="1046" height="847" alt="image" src="https://github.com/user-attachments/assets/48105554-fdc8-470c-9f8e-d635a93de858" />

<img width="1002" height="821" alt="image" src="https://github.com/user-attachments/assets/d13da018-a60e-4cae-a320-fe6e6d806be6" />

<img width="172" height="68" alt="image" src="https://github.com/user-attachments/assets/5fe950eb-4e5d-4332-aa4c-de6f9cd5ae48" />

To create my first user in my organisation, I right click the newly created OU titled "Users" navigate to Next . Create User. Once completed, a pop-up window shows up with text boxes in which I fill out for "User1Adept" credentials. 

<img width="1031" height="846" alt="image" src="https://github.com/user-attachments/assets/164d6e83-e7be-4939-931a-9eb4641ad479" />

The following screen is the password credentials setup
<img width="1017" height="847" alt="image" src="https://github.com/user-attachments/assets/c4044c68-4055-4cc1-9742-afbf930e2413" />

After confirming everything, here is my User1Adept's account listed in the main dashboard of the Domain Controller. I've now taken my Windows Server Instance and trasformed it into a Domain Controller.

<img width="1027" height="821" alt="image" src="https://github.com/user-attachments/assets/06a0ae91-1788-4347-b139-b7140ddc9015" />









