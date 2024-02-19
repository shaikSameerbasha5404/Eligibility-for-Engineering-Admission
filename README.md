# Eligibility-for-Engineering-Admission
## Aim:
To write a C# program to check whether the student is eligibile for the engineering admission

## Algorithm:
### Step1: 
Get the maths, chemistry and physics marks from the user using ReadLine().
### Step2: 
Calculate the sum of all three subjects and check whether the sum is greater than and equal to 180

### Step3:
Calculate the sum of physics and maths and check the condition

### Step4:
Check the conditions and end the program

### Step5:
Get the output
## Program:
Name : Shaik Sameer Basha
REG NO: 212222240093
```python
using System;

namespace Admission
{
    class Marks
    {
        static void Main(string[] args)
        {
            int maths, physics, chemistry;
            Console.WriteLine("Welcome to Engineering Admission Eligibility Checker");

            Console.Write("Enter Math marks: ");
            maths = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Physics marks: ");
            physics = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter Chemistry marks: ");
            chemistry = Convert.ToInt32(Console.ReadLine());

            int totalMarks = maths + physics + chemistry;

            if (maths >= 65 && physics >= 55 && chemistry >= 50)
            {
                if (totalMarks >= 180)
                {
                    Console.WriteLine("Congratulations! You are eligible for admission.");

                }
                else
                {
                    Console.WriteLine("Sorry, you are not eligible for admission.");

                }
            }
        }
    }
}
```

## Output:
![Screenshot (251)](https://github.com/shaikSameerbasha5404/Eligibility-for-Engineering-Admission/assets/118707756/fe1402c1-4155-44be-aa78-eb69725ecbb9)


## Result:
Thus the above C# program to check the eligibility of engineering admission is successfully executed

