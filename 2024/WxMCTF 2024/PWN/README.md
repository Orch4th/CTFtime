# WriteUp of WmXCTF 2024 PWN Category
In Forensics category, i solved 1 challenge

- Moodle Madness

In this challenge, we are given a elf 64-bit file when i running its a math polynominal function question (Help, i dont know about math)

![image](https://github.com/Orch4th/CTFtime/assets/161552093/25cacde4-c3d4-4bb7-9033-8c276a4743a0)

I use chatgpt and google to find the correct answer is like 3 and 4, after i use the answer the response is correct so i use gdb to find the function and get the flag. 
By the way, i use gef because its so cool. Anyway i check the function of the elf file and find the interest function like strcmp, i disassemble the function main and break the function main with strcmp function in the inside main function so the command is "b* main+281" and run the file to get the flag but its reversed. I manually reversed the string of flag and submit the flag.

![image](https://github.com/Orch4th/CTFtime/assets/161552093/ad7dc9f6-ae00-4b2f-add7-3b8ca9a44c82)

Flag : wxmctf{m00dl3_m45t3rm1nd!!!}
