```Csharp
using System.CodeDom.Compiler;
using System.Collections.Generic;
using System.Collections;
using System.ComponentModel;
using System.Diagnostics.CodeAnalysis;
using System.Globalization;
using System.IO;
using System.Linq;
using System.Reflection;
using System.Runtime.Serialization;
using System.Text.RegularExpressions;
using System.Text;
using System;

class Result
{

    /*
     * Complete the 'solve' function below.
     *
     * The function accepts following parameters:
     *  1. DOUBLE meal_cost
     *  2. INTEGER tip_percent
     *  3. INTEGER tax_percent
     */

    public static void solve(double meal_cost, int tip_percent, int tax_percent)
    {

    }

}

class Solution
{
    public static void Main(string[] args)
    {
       
    double meal_cost = Convert.ToDouble(Console.ReadLine());

    int tip_percent = Convert.ToInt32(Console.ReadLine());

    int tax_percent = Convert.ToInt32(Console.ReadLine());

    Result.solve(meal_cost, tip_percent, tax_percent);

    double tip = meal_cost*((double)tip_percent/100);
    double tax = meal_cost*((double)tax_percent/100);

    double sumOfTotalMeal = meal_cost+tip+tax;
    double result = Math.Round(sumOfTotalMeal);
    Console.Write(result);
    }
}
```