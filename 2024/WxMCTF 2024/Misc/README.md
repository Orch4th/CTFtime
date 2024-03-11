# WriteUp of WmXCTF 2024 Misc Category

In Misc Category, i solved 2 Challenges

- Welcome to WmXCTF
- Firstgrep

# Welcome to WmXCTF

In this challenge, we are given a [opening slide presentation](https://docs.google.com/presentation/d/12cgWgSUAB83NeJXxhiOBrYJiV28mT1NOtnINLMeWoLo/preview?slide=id.g2c116912a8b_0_46) about WmXCTF 2024. Lets try to find the flag in this slides presentation, in slide 4 we find the first piece of the flag.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/698b4d1a-131d-49e4-b56f-01a0c6b14c6c)

After that, we must find the second piece of the flag in this slides presentation. After check the slides, we find the second flag in slide 11. So the rest just needs to combine pieces of flags 1 and 2 into one flag sentence.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/ed6432e1-edd1-415a-bb9c-68cdf49f02f5)

Flag : wxmctf{g0od_l^c3_3ve*y0n!}

# Firstgrep

In this challenge, we are given a [zip file](https://ctf.mcpt.ca/media/problem/C7pHnbVaN3XBfVXfp9ebt2OetfDn0Svro9ysjJZQE-k/firstgrep.zip) which when i unzip the output is many folder and file txt with the fake flag. How to find the real flag in stack folders and files ? We use grep command to find the flag using the format like wxmctf{}.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/26f90f8e-a9db-4c92-8998-22b84fe4643a)

Flag : wxmctf{Wha7_W0uLD_w3_6e_w17HouT_Gr3P}

