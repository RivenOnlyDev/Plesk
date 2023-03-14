# Plesk
##### Plesk is a websites managements tool

---
## Installing Plesk

#### Via CLI
1. Download Plesk installer: 
```
wget https://autoinstall.plesk.com/plesk-installer
sh ./plesk-installer` or `sh ./plesk-installer --all-versions
```
2. Then just go “Go forward” and in case of –all-versions there will be option to choose the certain version of Plesk.
3. Wait until installation process is done.


#### Initial Configuration After Installation
1. You need to open in your browser the following URL – [https://your-host:8443](https://your-host:8443) or [https://your-ip:8443](https://your-ip:8443).
2. Access system using “root” username and its password.
3. Enter contact information ( name and e-mail ) of the administrator.
4. Change administrator’s account password. Next time you login use “admin” username and your new password.
5. Enter license key purchase it [here](https://www.plesk.com/pricing/).


#### Plesk Login
1. Go To [https://your-ip](https://your-ip).
2. Login with previous  **(user & password)** or with the *unix **'root'/'password'**. </br>
3. Voila Your home page : </br>


![Plesk Home :](https://raw.githubusercontent.com/RivenOnlyDev/Plesk/main/Pictures/Plesk%20Home.png)

***
## Configuration

#### Update and Installing
###### First Thing to do is upgrading and adding some packages.
- Go To `Tools & Settings` Then under Plesk click on `Updates`.
- ![Tools & Settings :](https://raw.githubusercontent.com/RivenOnlyDev/Plesk/main/Pictures/tootls%20%26%20settings.png)
- ![Updates :](https://raw.githubusercontent.com/RivenOnlyDev/Plesk/main/Pictures/updates.png)

- Add needed package and click on update and wait (it take some time). 


#### Service Plans
###### You need to setup your hosting plans.
 Hosting plan is a set of resources and services provided to your hosting service customers when they subscribe to it. There are also add-on plans that extend the amount of resources and services provided with a certain subscription.
 
- Go To `Service Plans` in Hosting Plans click on `Add a Plan` and setup like you prefer.


- ![Service Plans :](https://raw.githubusercontent.com/RivenOnlyDev/Plesk/main/Pictures/Service%20Plans.png)


- You can also add `reseller Plans`  which allow creating reseller subscriptions. Unlike your regular hosting service customers, a reseller can be subscribed to only one plan and cannot have add-ons.



#### Customers
Here you can add, delete, manage, convert **Customers**.

###### To Add Customer :
1. click on `Add Customer`.
2. add a user account : Contact name, Email address.
3. create username and password for plesk login, domains and service plan, ip address, ftp and ssh credentials.

***
### Extensions, Monitoring, Resellers, Dns, Mail
