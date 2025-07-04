# 🧑‍💻 Programming - Basics of Programming and Coding

Welcome in the world of Programming and Coding!

![image](https://github.com/user-attachments/assets/8d4d228f-d64c-474e-954a-0612e9d7f431)

---
### 📚 Course Objectives

- **Building Blocks**
- **Logical and Critical Thinking Skill**
- **Learn a Programming Language**

> Anyone and Everyone can learn Programing and coding irrespective of thier background.

---
### 📔 Modules

- **Flowchart**
- **Pseudocode**
- **Real Code / Coding**

|     Programming Vs Coding                 |
|-------------------------------------------|
|Que : Is Programming and Coding both are same?<br>
Ans : **Programming** is like **Planning and thinking**<br> Example : "What should it do?"
**Coding** is like **Writing the instructions in computer language**<br> Example : "Writing code in C/C++ or Java or Python."|

> **Programming is the thinking part 🧠, and coding is the writing part 🖊️.**

---

Let's start with a simple problem statement - <br>
**Problem : Make a cup of Tea**<br>
You will come up with a list of steps that you'll take to make that cup of tea.<br>
So, The sequence of steps, We call it as an **algorithms**
> **Algorithm is a sequence of instructions to solve a particular problem**

Algorithm can be depicted using **flowchart** or **pseudocode** or **real code**.

- **Flowchart** : Flowchart is a diagramatic representation of the process or steps that you're taking to solve a particular problem.

![image](https://github.com/user-attachments/assets/76e771ec-7fe0-49ad-882e-8a44947407a4)


- **Pseudocode** : You can convert your flowchart into a pseudocode that is written in plain English
```
1. Take 1 Spoon Sugar and 1/2 Spoon Tea leaves 
2. Take 1 glass of Water
3. Mix Sugar and Tea leaves in Water
4. Heat for 2-3 minutes
5. Enjoy your Tea
```

You've to be very specific to the constraints of the problem. Like if someone ask you to make ~~some tea~~? Here, You have to define what is some? <br> Example : ~~How far is Delhi?~~ <br> &nbsp; &nbsp; &nbsp; &nbsp; From where, How far is Delhi from Mumbai?

In programming, you can't write ambiguous instructions. Because Compiler or interpreter that needs to be clear. what exactly is the amount that to consider?

- **Real Code** : You can convert your pseudocode into some real code.
```
1. Sugar = input()
2. Tea leaves = input()
3. Water = input()
4. Mixture = Add(Sugar, Tea leaves, Water)
5. Heat(Mixture)
6. Enjoy your Tea

# This code is in a Hypothetical Programming language.
```
> You can write this code in any programming language like C/C++, Java, JavaScript, Python, Go, Rust etc

🤔 If you don't understand, Don't worry!<br>
&nbsp;We're here to break down the fundamental programming concept into very simplified terms.


---
### 💮 Flowcharts

**Diagramatic representation** solution to a problem.<br>
Allows you to **break down any process into smaller steps** and display them in visual way.<br>
So, It become very easy for beginner to draw and understand a flowchart without writing complex code, you'll easily understand what steps you will perform in order to solve a problem.

- **Building Blocks (Components) of Flowchart**

1. First building block of flowchart is **Start** and **End/Stop/Exit/Terminate**<br>
 **Start**, It denotes the starting step that means the solution starts from this particular box.<br>
**End**, It can also be used to terminate the process<br>
Oval shape box for both Start and End

![image](https://github.com/user-attachments/assets/6773d7d1-01a7-425c-9511-080845e19ad3)

3. Second is Read the **Input** and Show the **Output**<br> 
If you want to make tea, you'll read the input for how many guests you want to make? So, you'll read the of N, that will denote the number of guests who want to have tea.<br>
So, We'll store this value inside a bucket N that bucket is created inside RAM(Ramdom Access Memory)<br>
Parallelogram box for both Input and Output.

![image](https://github.com/user-attachments/assets/0c3a41d2-60e1-4488-a941-be0b37005401)

4. Third Component is rectangle box, that is used anywhere you have to have **Process** some data.<br>
All those instructions where processing is happening anything except from Input/Output they'll depicted as in the ractangle box.
 > **= Assignment Vs == Equality**, both are two different operators in programming.

![image](https://github.com/user-attachments/assets/69e8e5d6-0a76-404c-9dc4-c0070e50911d)

4. Fourth Component is **Decision** box, also known as Rhombus. <br>
Whenever you've to check certain condition, which means you want to check whether the condition is True/False bbased upon that there can be two branches.<br>
Example : Is weather Rainy? If True take Umbrella else Take Sun Glasses <br>
It is denoted by using the Diamond Shape box. 

![image](https://github.com/user-attachments/assets/5692f80e-fe35-43d0-9e1b-620f67be95a2)

5. Fifth and the last Component of flowchart is **Arrows** which represent **Connection**<br>
Arrows are used to connet two different boxes.

![image](https://github.com/user-attachments/assets/de836ed5-51fa-4c95-958f-728ec5a26b0a)

---

### 📔Let's See How to create Flowchart?
---
- **Flowchart - Simple Interest Calculator**<br>
Read Principle Amount, Rate of Interest and Time and print Simple Interest.<br>
```
Sample Input
P = 100
R = 5
T = 2
Sample Output
SI = 10

SI = (P*R*T)/100
```

![image](https://github.com/user-attachments/assets/4b0dc706-2fcb-44d1-a21f-16f5cfaefe30)

---
- **Flochart - Largest Number**<br>
Given 3 numbers, find the largest number.
```
Sample Input 
A = 10
B = 30
C = 20
Sample Output
30
```

![image](https://github.com/user-attachments/assets/a0d4795b-3a3c-49bf-bf27-346f59a969fe)

---
- **Flowchart - Sum of first N numbers**<br>
Find the sum of the numbers from 1 to N, N is given as input.
```
Sample Input 
N = 4
Sample Output
10

1+2+3+4=10
```

![image](https://github.com/user-attachments/assets/de2eb45a-5fc6-40a6-8d1f-25789ad45cb6)

---
- **Flowchart - Prime Number**<br>
Given a numbver, Check if it is Prime or Not.
```
Sample Input
11
9
Sample Output
Prime
Not Prime

Prime Number is a number that has only two divisor 1 and itself.
eg: 2,3,5,7,11,13,17,19,23.......
Non Prime Number will have atleast one divisor in the range 2 to N-1
```

![image](https://github.com/user-attachments/assets/bfaa247a-0d54-4544-a730-f141eda950b2)

---
- **Flowcchart - Sum of Multiple Inputs**<br>
Taken input N followed by N more numbers, find the sum of those numbers.
```
Sample Input
N = 4
10 20 30 50
Sample Output
110

10+20+30+50=110

First We have to see How can we take N inputs from user.
N could be anything 50, 100.
So, you cannot create N numbers of buckes to read.
then what we have to do? is read and process the sum as we go through the input which means Read and Update Sum 
```

![image](https://github.com/user-attachments/assets/8cd6ac8e-ce99-4809-b671-703d8839e562)


> Here, In this problem we do not need to store all the number at once. So, We're only storing the current number. But in some problems we might require to store all numbers there we will use a data structure known as Array. We'll see that in future.

---

- **Flowchart - Greatest Common Divisor ( GCD )** also known as **HCF**<br>
Find the GCD of two numbers.
```
Sample Input
a = 8
b = 12
Sample output
gcd = 4

GCD/HCF -> What is the largest number that divides both two numbers.

If you observe carefully, you can see - 
If a and b are 2 numbers then GCD(a,b) <= min(a,b)

"GCD will always be less than or equal to the minimum of the two numbers."
"Minimum number that can divide both the numbers is 1"

Conclusion : GCD range will always lie in the range [1 to min(a,b)]. Now we can easily iterate over this range and find out greatest number in this range which divides both a and b.

```

![image](https://github.com/user-attachments/assets/08994217-3755-4a6e-a1f9-f93802c3c4b5)


> This way of calculating GCD is bruteforce, There is an optimised way to find GCD that is Euclid Algorithm.

---

- **Flowchart - Bank Employee**<br>
A Back is open till 6 PM So Bankers need to process the requests from Customers till 6 PM.<br>
Request can be of any type like<br>
1. cash Deposit
2. Cash Withdrawal
3. Checque Deposit
4. Making a Demand Draft
5. Miscellaneous Request

![image](https://github.com/user-attachments/assets/96384c11-062a-4a32-b96f-4fc7c6d1dadb)

---
- **Flowchart - Bank Security Guard**<br>
Here, Bank Guard is going to wait for the customer outside the bank, if they're coming before 6 PM. He will add the customers to the queue. If there is no customer waiting outside. He will wait for the time reaches 6 PM. Once it's 6 PM then He will close the Bank.

![image](https://github.com/user-attachments/assets/dcc8644d-dc09-4a93-b45f-cb68d70d8deb)

---

### Assignment / Practice of Flowchart

1. Sum of the first N even numbers starting from 2.

![image](https://github.com/user-attachments/assets/260698cb-5209-4958-8c39-72303b689edd)

2. Input 5 Subjects and find the average.

![image](https://github.com/user-attachments/assets/c041a2cc-f96d-4e96-ace7-363e20684863)


3. LCM of 2 numbers.  [ LCM * HCF = Product (A, B) ]

![image](https://github.com/user-attachments/assets/49059575-d709-44b8-a3b6-bcc8dd32bb53)


4. print table of a given number N.

![image](https://github.com/user-attachments/assets/8a47018b-965a-41d0-a5f5-a78850a3ff5b)


5. Print 'Fizz' for multiple of 3,'Buzz' for multiple of, 'Fizz Buzz' for multiple of both 3 and 5 and numbers from 1 to 100.

![image](https://github.com/user-attachments/assets/1493adc6-39db-4451-9600-c31b4a830156)


6. Factorial of a number N.

![image](https://github.com/user-attachments/assets/d870cb7d-8145-4d5a-ab7b-f46532e616fe)


---
### Pseudocode

---

### 📔Let's See How to write Psuedocode?

Pseudocode is nothing but **Human readable description of an algorithm**<br>
**Algorithm** : Sequence of steps to solve a particular problem.<br>
- **Pseudocode** : It is a plain English text, not a real code that machine can execute. Then **why pseudocode?**
  - ✅ Language Independent
  - ✅ Structure your Code before Writing it.
  - ✅ Fastest way to verify or get review

You can have your own notation of writing Pseudocode.But, There're few basic ways of writing it.<br>
**Some 6 types of Instructions set to write a pseudocode**<br>
1️⃣ **Input** [ Read N ]<br>
2️⃣ **Assignment** [ Sum = 0 ]<br>
3️⃣ **Output** [ Print Sum]<br>
4️⃣ **If Else** [ If i<N Then .....End Else Then ...End ]<br>
```
if a>b {
    print(a)
}
else {
    print(b)
}
```
5️⃣ **While Loop** [ while i<N Do .....end ] <br>
```
while num<10 {
    print(num)
    num = num + 1
}
```
6️⃣ **Exit** [ Exit/Stop] <br>

---

- **Pseudocode - Simple Interest**<br>
Read P,R,T and calculate Simple Interest SI.
```
Sample Input 
100 5 2
Sample Output
10

1. Read P,R,T
2. SI = (P*R*T)/100
3. Print SI
4. Exit
```
---
- **Pseudocode - Largest of 3 Numbers**<br>
```
Read A,B,C

if A>=B and A>=C {
    print A
    Exit
}
if B>=A and B>=C {
    print B
    Exit
}
else {
    print C
    Exit
}
```
---
- **Pseudocode - Sum of numbers from 1 to N**<br>
```
Sample Input 
N = 4
Sample Output
10

Sum = 1 + 2 + 3 + 4 = 10

1. Read N
2. i = 1
3. sum = 0
4. while i<=N {
    sum = sum + i
    i = i + 1
   }
5. print sum
6. Exit
```
---

- **Pseudocode - Prime or Not Prime**<br>

```
Sample Input
11
Sample Output
PRIME

Prime Number is a number which is having only two divisors 1 and the number itself

1. Read N
2. i = 2
3. while i<N {
    if N%i == 0 {
        print("NOT PRIME")
        Exit
    }
    i = i + 1
   }
4. print("PRIME")
5. Exit
```
---
- **Pseudocode - Sum of N inputs**<br>
Take input N, follwed by the N inputs. Find the sum of the all the numbers that have been input.
```
Sample Input
N = 4
10 20 40 50
Sample Output
120

Sum = 10 + 20 + 40 + 50 = 120

1. Read N
2. i = 1
3. sum = 0
4. while i<N {
    Read Num
    sum = sum + Num
    i = i + 1
   }
5. print sum
6. exit
```
---
- **Pseudocode - GCD/HCF of 2 numbers**<br>
Find the GCD of two numbers A and B
```
Sample Input
 A = 8
 B = 20
Sample Output
 GCD = 4

GCD/HCF is the greatest/largest number that can divide both the numbers
GCD range always lie between 1 to min(A,B)

1. Read A,B
2. i = 1
3. while i<min(A,B){
    if (A div by i and B div by i){
        GCD = i
    }
    i = i + 1
  }
4. print GCD
5. Exit
```
---
- **Pseudocode - LCM of 2 numbers**<br>
Find the LCM of two numbers A and B. You can use the formula LCM*HCF=Product(A,B)
```
Sample Input
 A = 8
 B = 12
Sample Output
 LCM = 24



1. Read A,B
2. i = 1
3. while i<min(A,B){
    if (A div by i and B div by i){
        GCD = i
    }
    i = i + 1
  }
4. LCM = (A*B)/GCD
5. print(LCM)
6. Exit
                OR
LCM is the Lowest number that is common factor in both the numbers
LCM range always lie between max(A,B) to A*B

1. Read A,B
2. i = max(A,B)
3. while i<= A*B {
    if (i div by A and i is div by B){
        LCM=i
        print(LCM)
        Exit
    }
    i = i + i
   }
4. print(LCM)
5. Exit

```
---

- **Pseudocode - Star Pattern**<br>
```
Sample Input 
N = 4
Sample Ouput
*
**
***
****

Observations :
1. There are N rows
2. In ith row there are i num of start
So we have to use two loop one for Rows and another for each row has i stars.
Note : After each row there is a new line character which is nothing but '\n'

1. Read N
2. i = 1
3. while i<=N {
    stars = 1
    while stars <=i {
        print("*")
        stars = stars + 1
    }
    print(New line)
    i = i + 1
   }
4. Exit

```
---
- **Pseudocode - Star Pyramid Pattern**<br>
```
sample Input 
N = 4
Sample Output
   *
  ***
 *****
*******

Observations : 
i There are N rows
ii There are some spaces " " followed by Starts "*" in ith row
iii New line

Note : If you didn't observe at the you can see the stars in the pattern sequence 1,3,5,7,....

**Sequence** Oh It means A.P
1,3,5,7,.......nth term
Here Difference between the two terms (d) = 2
Therefore, by using AP Formula :-
 Tn = a+(n-1)d
    = 1+(n-1)2
    = 1 + 2n - 2
    = 2n - 1

1. Read N
2. i = 1
   //for rows
3. while i<=N {
    //print spaces
    spaces = 1
    while spaces<=N-i {
        print(" ")
        spaces = spaces + 1
    }
    //print stars
    stars=1
    while stars<=2*i-1 {
        print("*")
        stars = stars + 1
    }
    print(New line)
    //update i
    i = i + 1
   }
4. Exit
```
---

### 🧑‍💻 Writing Code

---
### 📔Let's See How to write real Code?

You can convert any Pseudocode into real code. You just need to know the **rule of that programming language**, which is also known as **Syntax** of a language.

We will write the code in **Python**, Python is a programming language.

- **Code - Simple Interest**<br>
```python
   P = int(input())
   R = int(input())
   T = int(input())

   SI = (P*R*T)/100

   print(SI)
```
---
- **Code - Largest of 3 Numbers**<br>
```python
   def largestNumber():
    A = int(input())
    B = int(input())
    C = int(input())

    if A>=B and A>=C:
        print(A)
        return
    if B>=A and B>=C:
        print(B)
        return
    else:
        print(C)
        return
    
    largestNumber()
```
- **Code - Sum of N inputs**<br>
```python
N = int(input())
i = 1
Sum = 0

while i<=N :
    num = int(input())
    Sum = Sum + num
    i = i + 1

print(Sum)    
```
---
- **Code - Number is Prime or Not**<br>
```python
def checkPrime():
    N = input(input()) 
    i = 2

    while i<N :
        if N%i==0 :
            print("Not PRIME")
            return
        i = i + 1
    
    print("PRIME")
    return

checkPrime()
```
---

- **Code - Star Pyramid Pattern**<br>
```python
N = int(input())
i = 1

while i<=N :
    //print spaces
    spaces = 1
    while spaces <= N-1 :
        print(" ",end="")
        spaces = spaces + 1
    //print stars
    stars = 1
    while stars <= 2*i-1 :
        print("*",end="")
        stars = starts + 1
    //print new line
    print()
    i = i + 1
```
---

- **Code - Number Pyramid Pattern**<br>
```
Sample Input 
N = 4
Sample Output
       1
     2 3 2
   3 4 5 4 3
 4 5 6 7 6 5 4

 Observation : 
 1. There are N rows
 2. N-i spaces
 3. ith row - i nums in the increasing order starting from value i
 4. i-1 numbers in the decreasing order
```
```python
N = int(input())
i = 1

while i<=N :
    //pprint spaces
    spaces = 1
    while spaces <= N-i :
        print(" ",end="")
        spaces = spaces + 1
    //pprint increasing num
    num = i
    count = 1
    while count <= i :
        print(num,end="")
        num = num + 1
        count = count + 1
    //pprint decreasing num
    //reset value by 2 bcuz num value increased iin memory
    num = num - 2
    count = 1
    while count <= i-1 :
        print(num,end="")
        num = num + 1
        count = count + 1
    //pprint new line
    print()
    i = i + 1
```
---

### Thank You!! 😊

### 🌐 Connect with Me 

[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/pawansinghfromindia/)&nbsp;&nbsp;
[![Website](https://img.shields.io/badge/Website-000?logo=Google-Chrome&logoColor=white)](https://yourwebsite.com)&nbsp;&nbsp;
[![X](https://img.shields.io/badge/Twitter-black?logo=X&logoColor=white)](https://x.com/yourusername)&nbsp;&nbsp;
[![YouTube](https://img.shields.io/badge/YouTube-black?logo=youtube&logoColor=red)](https://youtube.com/in/yourusername)&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)&nbsp;&nbsp;
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white)](https://facebook.com/yourusername)&nbsp;&nbsp;
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://instagram.com/yourusername)&nbsp;&nbsp;
[![WhatsApp](https://img.shields.io/badge/Whatsapp-TealGreenDark?logo=whatsapp&logoColor=white)](https://whatsapp.com/+91987654321)

---
