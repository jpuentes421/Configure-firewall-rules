# Configure-firewall-rules

## Objective

 By default, firewalls block all traffic coming into the network. We will be configuring a new rule for a FTP srever. 


### Skills Learned

- How to configure a firewall 

### Tools Used

- Windows Defender Firewall


## Steps
1. In the Windows search bar, type in **Firewall** and click on **Windows Defender Firewall**.
2. You will see the option for turning Windows Defender Firewall on and off. We want to ensure that it is turned on for both the Public and Private network settings.
3. Select **Advanced Settings**, here you can access all of the firewall inbound and outbound rules.
4. We want to run the FTP server, in order to do this we need to create a new inbound rule.
5. Click on **New Rule** and choose **Port Option**. Type in **port 21** for **Specific Local Ports**. Remember, FTP runs on port 21.
6. Apply the rule to **Domain**, **Private** and **Public** settings.
7. Label the rule as **FTP Server** and click **Finish**
8. We can now view the **FTP Server** on **Inbound Rules**. Now we can set up an FTP server. 

**FTP port enabled**
![image](https://github.com/user-attachments/assets/dff4db37-46e6-4f45-a933-65187bc9498d)

