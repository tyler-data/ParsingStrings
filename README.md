# Parsing Strings
 In this Notebook, I took a string variable containing messy medical insurance records, cleansed the data, and outputted meaningful, structured data.


I've accomplished the following in 3 steps: 

Step 1: Data Cleaning 🧼

Step 2: List Sorting 📃 

Step 3: Analyzing the Data 🔎 

Starting Messy String Variable:
```
\
"""Marina Allison   ,27   ,   31.1 , 
#7010.0   ;Markus Valdez   ,   30, 
22.4,   #4050.0 ;Connie Ballard ,43 
,   25.3 , #12060.0 ;Darnell Weber   
,   35   , 20.6   , #7500.0;
Sylvie Charles   ,22, 22.1 
,#3022.0   ;   Vinay Padilla,24,   
26.9 ,#4620.0 ;Meredith Santiago, 51   , 
29.3 ,#16330.0;   Andre Mccarty, 
19,22.7 , #2900.0 ; 
Lorena Hodson ,65, 33.1 , #19370.0; 
Isaac Vu ,34, 24.8,   #7045.0"""
```

From here, I was able to create columns out of this data:

Names - Name of the medical patient

ages - age of the medical patient

bmis - body mass index of the medical patient

insurance_costs - total costs accrued by the patient.

To get the final output:
```
Average BMI:  64.575
Average Insurance Cost:  $8390.7
Marina Allison is 27 years old with a BMI of 31.1 and an insurance cost of $7010.0
Markus Valdez is 30 years old with a BMI of 22.4 and an insurance cost of $4050.0
Connie Ballard is 43 years old with a BMI of 25.3 and an insurance cost of $12060.0
Darnell Weber is 35 years old with a BMI of 20.6 and an insurance cost of $7500.0
Sylvie Charles is 22 years old with a BMI of 22.1 and an insurance cost of $3022.0
Vinay Padilla is 24 years old with a BMI of 26.9 and an insurance cost of $4620.0
Meredith Santiago is 51 years old with a BMI of 29.3 and an insurance cost of $16330.0
Andre Mccarty is 19 years old with a BMI of 22.7 and an insurance cost of $2900.0
Lorena Hodson is 65 years old with a BMI of 33.1 and an insurance cost of $19370.0
Isaac Vu is 34 years old with a BMI of 24.8 and an insurance cost of $7045.0
```

The outcome shows that from the messy string data, I was able to create a meaningful summary for each patient
