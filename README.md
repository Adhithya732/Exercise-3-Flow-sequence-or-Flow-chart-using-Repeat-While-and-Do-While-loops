# Exercise-3-Flow-sequence-or-Flow-chart-using-Repeat-While-and-Do-While-loops

~~~
Name : W Allen Johnston Ozario  
Reg.No : 21222411004  
~~~

## Aim:
To create a UiPath workflow using Flow Sequence or Flowchart that demonstrates the use of Repeat, While, and Do While loops for iteration and message display.

## Materials Required::
UiPath Studio (Community or Enterprise Edition)

Windows Operating System

Basic understanding of control flow and looping constructs in UiPath

## Procedure:

## Part 1: Simulated Repeat Loop using While
Open UiPath Studio and create a new process called LoopingExample.

Add a Sequence or Flowchart to your Main.xaml.

Create a variable:

Name: repeatCount

Type: Int32

Default value: 0

Drag and drop a While activity.

Set the condition:

repeatCount < 3
Inside the While block:

Add a Message Box → Text: "Repeat Loop - Count: " + repeatCount.ToString

Add an Assign → repeatCount = repeatCount + 1

## Part 2: While Loop (Count Up)
Create a variable:

Name: i
Type: Int32
Default value: 0
Add a While activity after the Repeat section.
Set the condition:
i < 10
Inside the loop:

Add a Message Box → Text: "While Loop - i: " + i.ToString

Add an Assign → i = i + 1

## Part 3: Do While Loop (Count Down)
Create a variable:

Name: j

Type: Int32

Default value: 10

Add a Do While activity after the While block.

In the Body:

Add a Message Box → Text: "Do While Loop - j: " + j.ToString

Add an Assign → j = j - 1

Set the Condition:
j > 0

## OUTPUT:
![Screenshot 2025-05-05 135858](https://github.com/user-attachments/assets/933f4080-d638-469b-8bc7-7db88b16fe60)

![Screenshot 2025-05-05 140327](https://github.com/user-attachments/assets/2e4c6f44-9188-455b-a9ad-eeb313f3bff3)

![Screenshot 2025-05-05 140409](https://github.com/user-attachments/assets/e0b76bff-47dc-4159-a21c-48f1f1b1841b)

![Screenshot 2025-05-05 140437](https://github.com/user-attachments/assets/0aa21d13-0f46-4eff-816b-4ac1434dab62)

![Screenshot 2025-05-05 140445](https://github.com/user-attachments/assets/0951baff-b12a-4004-9faa-675d78271f84)

## Result:
The workflow successfully demonstrates the use of:
A Repeat-like loop using a While structure,
A standard While loop to count up,
A Do While loop to count down.

