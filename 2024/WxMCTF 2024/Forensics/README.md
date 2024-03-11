# WriteUp of WmXCTF 2024 Forensics Category

In Forensics category, i solved 2 challenges
- 諸葛亮
- Covert Chinchillas

# 諸葛亮

In this challenge, we are given a text file its content is binary encoding. After i decode the binary using decoder online (likes cyberchef, dcode.fr), i check the text and find the flag in last content.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/ae128fc1-7b80-4280-b778-4dae3c89558a)

Flag : wxmctf{Eightfold Battle Formation}

# Covert Chinchillas

In this challenge, we are given jpeg file. When i use strings and exiftool command to find a hint about this jpeg file. I find base64 encoding in comment of jpeg file, when i decode thats a password of the image.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/fb98001c-f0bd-44ef-a645-a58a8299a931)

Its meaning there is a file hidden in the image which is probably a flag. I use steghide with the password (after decode the base64) to find the hidden file. Correctly, i find th emb.txt and thats a flag.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/6bad7cb8-872f-4fdd-94ff-58c7f391b054)

Flag : wxmctf{7h1n95_423_n07_41w4y5_wh47_7h3y_533m}
