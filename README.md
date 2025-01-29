## osTicket Post Installation Configuration

Open osTicket and Log In

Log in to osTicket using the credentials you made during the installation tutorial

![](https://imgur.com/759E1Aj.png)

Now that osTicket is up and running, it's time for some system administration! We'll set up roles to control what agents can do in the help desk.
### Step 1: 
-  First Acknowledge Agent Panel and  Admin Panel

![](https://imgur.com/adT5HiC.png)

When you see Agent Panel by your welcome name, you are in admin panel and when you see Admin you are in agent Panel

### Configure Role
-  Go to Admin Panel → Agents → Roles
-  Click "Add New Role"
-  name it "Supreme Admin"
- Give it ALL permissions (since this is the top role!)

![](https://imgur.com/MEnWVu7.png)

Note: Roles decide what agents can access—not everyone gets unlimited power! If done right, your screen should show the new "Supreme Admin" role.

### Configure Departments
-  Ensure you are still in the Admin panel
-  Select the Agent tab > Departments > Add New Department
-  Name: System Administrators
-  Select Create Department

![](https://imgur.com/MIxlojU.png)

### Configure Teams
-  Select the Agent tab > Teams > Add New Team
-  Name: Level I Support
-  Go to the Members tab and select yourself in "Select Agent" dropdown menu (the welcom name, mine is Jonny)
-  Select Create 

![](https://i.imgur.com/M6nRfZ8.png)

### Allow Anyone to Create Tickets
-  Select Settings > User Settings
-  Make sure the following box is unchecked:
-  Registration Required: Require registration and login to create tickets
-  Save Changes

  ![](https://i.imgur.com/mXNn3a6.png)

###  Configure Agents
-  Select the Agent tab > Add New Agents
-  Name: Jane kok
-  Email : jane.kok(@)osticket.com
-  Username: jane.kok
-  Click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"
-  Set your password to anything you like
-  Uncheck the box that says "Require Password Change at Next Login"
-  Select set
![](https://i.imgur.com/omYQLa8.png)
![](https://i.imgur.com/OEa5SCw.png)

Select the Access tab
  -  Under Primary Department:
    -  Select the Department dropdown menu > System Administrators
    -  Select the Role dropdown menu > Supreme Admin
-  Extended Accesss
    -  Select Department > Support > Add > Supreme Admin
-  Select Team tab
  -  Select Team dropdown menu > Level I Support
-  Select Add > create

![](https://i.imgur.com/A8zZsjg.png)
![](https://i.imgur.com/c2cJve5.png)

Create another agent and replace Jane with amaka. (lin.amaka@osticket.com)
  -  Follow the same steps as above, except make some changes to the Primary Department
-  Select the Department dropdown menu > Support
-  Select the Role dropdown menu > View Only
-  Extended Accesss
    -  Select Department > Support > Save Changes
  if well configured you have Both names added in agent interface

![](https://i.imgur.com/m17WvxQ.png)

###  Configure User (agent panal)
This is you end user
-  Select the Users tab to create a user
-  Email Address: kess@osticket.com
-  Full Name: Kess Kriss
-  Select Add User

![](https://imgur.com/KfwM6jL,png)
![](https://imgur.com/UQcbuV0.png)

Select the User tab again to create another user
-  Email Address: ben@osticket.com
-  Full Name: Ken ben
-  Select Add User

### Step Configure Service Level Agreements (SLA) change to admin panal

We will create three SLAs
-  Select the Manage tab > SLA > Add New SLA Plan
-  Name: SEV-A
-  Grace Period: 1
-  Schedule dropdown menu: 24/7
-  Add plan

![](https://i.imgur.com/neaa4IQ.png)

- Name: SEV-B
- Grace Period: 4
- Schedule dropdown menu: 24/7
- Select Add Plan

![](https://i.imgur.com/b7tn9vw.png)

- Name: SEV-C 
- Grace Period: 8
- Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S. Holidays
- Select Add Plan

![](https://i.imgur.com/FrFX00O.png)

### Configure Help Topics
We will create four Help Topics
-  Select the Manage tab > Help Topics > Add New Help Topic
  -  Business Critical Outage
  -  App logging Issue
  -  Equipment Request
  -   Password Reset
Select Add Topic for each topic

![](https://i.imgur.com/tZe2CmE.png)

If you followed up to this stage, Congratulation! You have configured osTicket system succesfully!
Click [here](https://github.com/akpatiudo/osTicket-lifecycle) to move on to the final part of this Lab










