# Lab 1A

**Write the C code in a file in ubuntu terminal and save it as sum.c (source code)**
Next, compile the source code using gcc compiler, this will generate the executable code.
Now, run the executable code to see the output.


![WhatsApp Image 2024-07-19 at 14 10 32](https://github.com/user-attachments/assets/4b446697-49cc-43d1-9d74-d91f9cb2a6cb)





![WhatsApp Image 2024-07-19 at 14 11 22](https://github.com/user-attachments/assets/0362c267-766f-4633-b9dd-44dbd9a7e870)






# Lab 1B
**Compiling a C program with RISCV gcc compiler, execute it, generate the output**
Now, compile the sum.c using RISCV gcc compiler, also see the assembly code for C program.




![WhatsApp Image 2024-07-19 at 14 22 12](https://github.com/user-attachments/assets/533947ac-936b-433b-bb2b-c6d30d3e2808)


![WhatsApp Image 2024-07-19 at 14 26 06](https://github.com/user-attachments/assets/f0ad6227-3dc2-41f5-8731-a6087acf4583)


The object code dump generates main function at location 10184 and 15 instructions are present in assembly code.
Next, we try 0fast of RISCV compiler for same C code and observe the object code dump, now the main function is located at 100b0 and number of instructions is 12.



![WhatsApp Image 2024-07-19 at 14 27 46](https://github.com/user-attachments/assets/97cb2654-bf12-4a9f-ab79-aaeb3b784634)






![WhatsApp Image 2024-07-19 at 14 28 13](https://github.com/user-attachments/assets/0d05c39d-5411-4731-8803-39e2eeef0a0c)


# LAB 2

**First, we will get the output of the program with the risc compiler**

![Screenshot 2024-07-21 123101](https://github.com/user-attachments/assets/3aeea736-844c-41c0-8940-b7ef617f37ec)

Now using the command shown in the figure, we'll get assembly code of our c programme. Now when we calculate no. of instructions in this case, we get no. of instructions here are 12.

![WhatsApp Image 2024-07-21 at 16 24 25](https://github.com/user-attachments/assets/97c52fde-1427-47fc-b438-f29aff11680f)

We ran our code on risc v compiler. Now we'll debug it in spike command. We want our programme counter to run till 100b0 (memory address instruction of first location)


![WhatsApp Image 2024-07-21 at 16 25 27](https://github.com/user-attachments/assets/273d295e-5d72-47d5-9ec2-46fd9d528cba)
![WhatsApp Image 2024-07-21 at 16 26 01](https://github.com/user-attachments/assets/6c984045-a9e1-46fd-9be8-fe85b5485946)

if we check content of sp register, you'll see that there is a subtraction of hexadecimal 10.

![WhatsApp Image 2024-07-21 at 16 27 20](https://github.com/user-attachments/assets/736e566b-0d72-4153-a51e-3453288ffe92)




