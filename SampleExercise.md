
**Sample Exercise (Data Cleansing with Tableau Prep)**

**Exercise type:** Interactive Exercise on Tableau Prep Builder like GUI

**Alternative Exercise type:** Multiple Choice with Console

Learning Objectives:

- Learner will be able to add data cleaning steps

- Learner will be able to modify and convert data types on any related fields

**Exercise Context**

**Title:**  Adding Cleaning Steps and Converting Data Types

One of the most important steps in a data cleaning workflow is to convert our fields to the right data type.

In this exercise, you will learn how to add cleaning steps and convert fields to the appropriate data type.

A dataframe  ‘customers’ is loaded for you.

**Data Sample:** (This data has been synthesized for the purpose of this exercise)

|**City** (Abc) | **Country** (Abc) | **Customer Name** (Abc)| **Customer Last Name** (Abc) | 
| ----------- | -----------------| ---------------------------| --------------- |
| London |United Kingdom |Jack| Dawson|
|Newark |      USA          |     Bobby        |    Keller |       
| New York |United States of America  |Bob| Kell|
|Louvain |      Belgique          |     Martjin       |    Martens |       
| Mexico City |Mexico |Martin| Guttierez|
|Lodnon|      UK        |     Jak        |    Smith |       
|  Leuvin    |   Belgium |      Matjin      | Martens |
| Milan | Italy | Marco | Giuliani | 
| Boston | United States | Tom | Mannings|
| Newyork | USA | Marc | Dubois | 
|Bostn | United States | Martina | Gomez






**Instructions**

· In the editor on the right, Select the “+” sign and add a cleaning step to the workflow from the dropdown menu
![enter image description here](https://lh3.googleusercontent.com/hClX2gXYaIEI87hpJGyRlgMQ7ZiEcMGaO-ooNG4eXGD5l7GIdMZA7ziq1FZYxzEfe1uIqPnz-i8 "Adding Cleaning Step")
· On the ‘City’ field click on Abc and change the geographic role to City on the dropdown menu
![enter image description here](https://lh3.googleusercontent.com/74qazR5unbPXOT3KSjOOzQf0QPzSkFfDyQbSrJYbBikD7WV_7fgsaQYmyHuwpFXChUgTJsWy-v0 "Converting Data Type")
**Note:** Notice the ‘City’ appears next to Abc

· Perform the previous step on the ‘Country’ field. This time we will select ‘Country’ as a geographical role.
![enter image description here](https://lh3.googleusercontent.com/74qazR5unbPXOT3KSjOOzQf0QPzSkFfDyQbSrJYbBikD7WV_7fgsaQYmyHuwpFXChUgTJsWy-v0 "Converting Data Type")
**Solution:**
![enter image description here](https://lh3.googleusercontent.com/7z2qcBhuSDCwh5ToQV-Z_R42Pl9QfKy02SefEj7ahiyIsYcJX34ukTiI7dJchfe8Gvo8fEnryIM "Converted Data Types")
**Sample Success Message:**

Awesome! You have just learned how to add cleaning steps to your workflow and to convert fields to the right data type. Cleaner data yields better analysis. Let’s keep up the good work!

**Note:**The exercise above is of an iterative nature and will potentially cover more than one data type example in the same fashion.

**Motivation for the potential following exercise:**

Great job your first take at cleaning messy data!  You have probably noticed that the data in the ‘Customer’ dataframe had misspelling errors and was not normalized. The process of catching these errors and fixing them can be very tedious and time consuming. Rest assured; Tableau Prep is coming to the rescue!


**Limitations**: In designing this exercise, we assumed that the code editor would play the role of an interactive GUI similar to Tableau Prep in order for the learner to stay within the DataCamp platform. Further options can be contemplated in order to accommodate the integration of similar exercises on DataCamp.
