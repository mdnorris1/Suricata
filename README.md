This project was inspired by Empirical Training who are doing some great things supporting the cyber community. 

In this project, I installed a Kali Linux VM, before installing and configuring Suricata.


![install suricata](https://github.com/user-attachments/assets/aea08585-3c78-487a-a0b0-dc3dcf2ea0c5)

I then created a file to enable custom rules to be added to Suricata.

![image](https://github.com/user-attachments/assets/2437ac1c-4c8c-428c-9a95-2d8e0f3a97c1)

I went on to create an yaml alert rule file to alert on any ICMP network traffic on any source IP or port and to any destination IP or port.

![image](https://github.com/user-attachments/assets/fb17058a-11ee-4985-9899-861c4e81e6d0)

I added the file to the list of files used.

![image](https://github.com/user-attachments/assets/1b15e077-8f62-4ca5-a017-6aa0842d7a03)

![Screenshot 2024-11-18 115958](https://github.com/user-attachments/assets/1688c537-92f2-4583-a54a-74d986ef79d2)

I then triggered the alert with an ICMP echo / Ping request before analysing the logs created from the alert.


![ping detected](https://github.com/user-attachments/assets/65fdfb1f-6e58-437f-8b92-a2fa51ee9227)

Hope you enjoyed the walkthrough of the project!
