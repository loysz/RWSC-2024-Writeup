# Last Hope 

The challenge was to uncover a hidden flag behind a WiFi password.

 I started by using Wireshark to analyze the network traffic, but it didn't reveal anything useful.
 I then turned to Aircrack-ng and used the rockyou wordlist to crack the WiFi password.


After running the cracking process, I successfully obtained the WiFi password and accessed the network.
![image](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/5974e2a5-783b-4378-8f94-417464901c9c)

Flag : RWSC{anonymous}


# Resign Letter

The challenge give us .dotm type of file.

first i identify what is the .dotm file.
![image](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/0ab10067-792f-41d8-849f-204431f1ccb4)

and then i search on google and ask chatgpt anything that i can do with that type of file. and the i found .dotm file has macro. and the i find out that olevba from oletools can do the job.
![image](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/b1febfb2-456d-494b-b6a1-0c83533e8a31)

and then i get the link to download lenovo.exe from https://github.com/fareedfauzi/Adv_Sim/raw/main/lenovo.exe

and then i download it and strings the file and i got this
![image](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/c3404724-61f8-462d-b36f-11cb853d592b)

and then i go to cyberchef and decode it from base64
![image](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/d0c4307d-a45f-4dab-a880-b9481f258a5f)
