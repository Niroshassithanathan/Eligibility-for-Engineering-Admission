# Eligibility-for-Engineering-Admission
## Aim:
To write a C# program to check whether the student is eligibile for the engineering admission.

## Algorithm:
### Step1:
Create new class.

### Step2:
Calculate the sum of all three subjects and check whether the sum is greater than and equal to 180.

### Step3:
Calculate the sum of physics and maths and check the condition.

### Step4:
Calculate the sum of all three subjects and maths-physics total.

### Step5:
Check for the given criteria for eligibility using if-else statements.

### Step6:
Display whether the person is eligible for admission or not based on the given criteria.

### Step7:
Exit the Program.

## Program:
DEVELOPED BY : NIROSHA S
REG NO : 212222230097
```
using System;
    class Eligibility
    {
        static void Main(string[] args)
        {
           int mpc,mp,maths, physics, chemistry;
        string name;
        Console.WriteLine("Enter mark in maths:");
        maths = int.Parse(Console.ReadLine());

        Console.WriteLine("Enter mark in physics:");
        physics = int.Parse(Console.ReadLine());

        Console.WriteLine("Enter mark in chemistry:");
        chemistry = int.Parse(Console.ReadLine());
        mpc=maths+physics+chemistry;
        mp=maths+physics;
        if(maths>=65&&physics>=55&&chemistry>=50)
        {
            if(mpc>=180||mp>=140)
            {
                Console.WriteLine("eligible for admission.");
            }
            else
            {
                Console.WriteLine("not eligible for admission.");
            }
        }
        else
        {
            Console.WriteLine("not eligible for admission.");
        }
    }
        }
```
## Output:
![image](https://github.com/Niroshassithanathan/Eligibility-for-Engineering-Admission/assets/121418437/f16f1c10-090a-4112-9f6d-441765c67d05)

## Result:
Thus the above C# program to check the eligibility of engineering admission is successfully executed.

