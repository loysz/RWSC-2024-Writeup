# Last Hope

The challenge said that the flag is a WiFi password.

Initially, I used Wireshark to analyze the network traffic, but it didn't yield any useful information. So, I turned to Aircrack-ng and utilized the rockyou wordlist to crack the WiFi password.

![WiFi Password Crack](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/5974e2a5-783b-4378-8f94-417464901c9c)

**Flag:** RWSC{anonymous}

# Resign Letter

This challenge provided a .dotm file.

Firstly, I identified the .dotm file type.

![Identifying .dotm File](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/0ab10067-792f-41d8-849f-204431f1ccb4)

Then, through research and chatting with ChatGPT, I discovered that .dotm files contain macros and learned that olevba from oletools could assist in the task.

![Discovering Macros](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/b1febfb2-456d-494b-b6a1-0c83533e8a31)

Next, I obtained a download link for lenovo.exe from [here](https://github.com/fareedfauzi/Adv_Sim/raw/main/lenovo.exe).

After downloading, I extracted strings from the file and found encoded content.

![Extracting Strings](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/c3404724-61f8-462d-b36f-11cb853d592b)

Then, I utilized CyberChef to decode the content from base64.

![Decoding Content](https://github.com/loysz/RWSC-2024-Writeup/assets/116022013/d0c4307d-a45f-4dab-a880-b9481f258a5f)
