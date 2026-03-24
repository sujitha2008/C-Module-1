## C-Module-1
## PROGRAM 1 
# AIM: 
Write a C program to find the ASCII value of a given character 
# ALGORITHM: 
```
1)take a character as input from the user. 
2)convert the character into its ASCII value using %d. 
3)print the ASCII value using printf() function.
```
# PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
char ch; 
scanf("%c",&ch); 
printf("ASCII value of %c is %d",ch,ch);     
} 
``` 
# OUTPUT: 
<img width="602" height="243" alt="Screenshot 2025-10-19 181848" 
src="https://github.com/user-attachments/assets/deca7b27-78a1-4203-914e-8d3ba6d77add" 
/> 
# RESULT: 
Thus the program to find the ASCII value of a given character has been executed 
successfully. 
## PROGRAM 2 
# AIM: 
Write a C program to check whether a given number is positive or not. 
# ALGORITHM: 
```
1)Take input from the user. 
2)Check whether it is positive or not using if else statements. 
3)Print the result using printf() function. 
```
# PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int num; 
    scanf("%d",&num); 
    if(num>=0) 
    printf("Number is positive."); 
    else 
    printf("Number is negative."); 
} 
``` 
# OUTPUT: 
<img width="551" height="235" alt="Screenshot 2025-10-19 184927" 
src="https://github.com/user-attachments/assets/123384be-2c53-45ee-b0fd-5b42111aa5ce" 
/> 
 
# RESULT: 
Thus the program to find whether the giv is positive or not is executed successfully. 
 
## PROGRAM 3 
# AIM: 
Write a C program to find whether the given character is the alphabet or not. 
# ALGORITHM: 
```
1)Get input from the user. 
2)Find whether the input is alphabet or not using isalpha() function. 
3)Use if else statement to print the result. 
```
# PROGRAM: 
``` 
#include <stdio.h> 
#include <ctype.h> 
int main() 
{ 
    char ch; 
    scanf("%c",&ch); 
    if(isalpha(ch)) 
    printf("It is ALPHABET"); 
    else 
    printf("It is NOT ALPHABET"); 
} 
``` 
# OUTPUT: 
<img width="529" height="317" alt="Screenshot 2025-10-19 191132" 
src="https://github.com/user-attachments/assets/8651e0b0-bd18-4767-a91c-9ba9579712df" 
/> 
# RESULT: 
Thus the program to find whether the given character is alphabet or not is executed 
successfully. 
 
## PROGRAM 4 
# AIM: 
Write a C program to check whether the given character is a vowel or not. 
# ALGORITHM: 
```
1)Get a character input from the user. 
2)Check whether it is vowel or not using if else statement. 
3)Print the result using printf() function. 
```
# PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    char ch; 
    scanf("%c",&ch); 
    if((ch>='a' && ch<='z') || (ch>='A' && ch<='Z')) 
    { 
        if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U') 
        printf("Vowel."); 
        else 
        printf("Consonant."); 
    } 
} 
``` 
# OUTPUT: 
<img width="380" height="147" alt="Screenshot 2025-10-19 202740" 
src="https://github.com/user-attachments/assets/872bd578-881c-440a-9c50-13003790533e" 
/> 
# RESULT: 
Thus the C program to check whether the given character is vowel or not is executed 
successfully. 

## PROGRAM 5 
# AIM: 
To write a C program to calculate total, average and percentage of marks in 4 subjects. 
# ALGORITHM: 
```
1)Get the input marks from the user. 
2)calculate the total ,average and percentage. 
3)print the outputs using printf() function. 
````
# PROGRAM: 
``` 
#include <stdio.h> 
int main() 
{ 
    int num1,num2,num3,num4; 
    float tot,avg,percent; 
    scanf("%d %d %d %d",&num1,&num2,&num3,&num4); 
    tot=num1+num2+num3+num4; 
    avg=tot/4; 
    percent=tot/4; 
    printf("Total marks = %.2f \n",tot); 
    printf("Average marks = %.2f \n",avg); 
    printf("Percentage = %.2f",percent); 
} 
``` 
# OUTPUT: 
<img width="635" height="314" alt="Screenshot 2025-10-19 210212" 
src="https://github.com/user-attachments/assets/c87123cc-cc1a-4f88-a205-5a91822c35b1" 
/> 
# RESULT: 
Thus the C program to calculate the total, average and percentage of marks in 4 subjects is 
successfully executed. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
