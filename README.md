# sumcoin-node-docs
A server side Sumcoin node setup Instructions 

# Purpose

Sumcoin is a decentralized cryptocurrency which uses independent Nodes, also referred to as a wallet.
These Nodes store and share the entire history of the Sumcoin Networks ledger activity.  The Nodes are an essential component to sharing and storage of this ledger information.

# Setup

## Get a droplet server 

* Use THIS LINK and Register at Digital Ocean for a $100 Credit to get started.  https://m.do.co/c/b7bfce81f64d

After you've registered your own account and included billing info from this link, you'll be presented with a $100 credit showing in the upper right hand corner of your DigialOcean account.

* Create up to 10 droplet servers.

Click Create and Select Droplets
![image](https://user-images.githubusercontent.com/37975862/82746212-8bfd5e80-9d4a-11ea-8c75-ca4c9e1a1053.png)

* Next select the Distrobution of "Ubuntu" 18.04

![image](https://user-images.githubusercontent.com/37975862/82746244-d979cb80-9d4a-11ea-82ef-716011fbc2a8.png)

* Choose a plan

Starter / Basic is the default. We will keep that.
Next we want to select the $10 per moth droplet as shown below.

![image](https://user-images.githubusercontent.com/37975862/82746272-13e36880-9d4b-11ea-86d7-d10d61ddb97b.png)


Next,  You can *ignore* **"Add block storage"**

We need to select a region though under "Choose a datacenter region"
Pick any area you like.   Want to be the most helpful?  Look at http://sumnode.io to see where there are fewer nodes and consider adding your node(s) there.

![image](https://user-images.githubusercontent.com/37975862/82746309-7fc5d100-9d4b-11ea-89be-1bf8843e20c4.png)


**"VPC Network"**
Optional

**"Select additional options"**
* Select Monitoring

**Authentication**
If you know how to use ssh keys, you should use this.   If not, you should set a very secure password which also uses special characters.

![image](https://user-images.githubusercontent.com/37975862/82746369-27430380-9d4c-11ea-8431-f1c148cd7e33.png)

**Finalize and create**

You can mimic the setup below

![image](https://user-images.githubusercontent.com/37975862/82746429-c8ca5500-9d4c-11ea-97f3-01288be6325c.png)

**Add backups**
Optional

## Create

### Click create droplet and it will make your droplet in the settings selected.
