### EX NO : 03
### DATE  : 07.04.2022
# <p align="center">Grading-on-marks</p>

## Aim:
To write a C# program to grade the marks

## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare one variable with integer datatype

### Step3:
Get marks from the User.

### Step4:
Use if and elif condition to check the grade

### Step5:
print the grade for the given mark

### Step6:
stop
<br/><br/><br/><br/><br/><br/>

## Program:
```
using System;
namespace Arun
{
    class program
    {
            static void Main(string[] args)
            {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks>90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");

        }
    }
}
```


## Output:
![image](https://user-images.githubusercontent.com/75235747/175766456-8019dbec-4bc1-435a-9e51-5174bbe9e2e5.png)



## Result:
Thus the C# program to grade the marks is executed successfully.
