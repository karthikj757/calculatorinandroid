# Ex.No:5 Develop a program to create a simple calculator using android studio.
## AIM:
To Develop a program to create a simple calculator using android studio.

## EQUIPMENTS REQUIRED:
Android Studio(Min. required Artic Fox)

## ALGORITHM:
1. Initialize Project: Create a new Android Studio project using the Empty Views Activity template.

2. Design Layout: Finish activity_main.xml ensuring unique IDs for your two inputs, result display, and four operator buttons.

3. Link UI Elements: In MainActivity.java, use findViewById() to connect all XML elements to corresponding Java variables.

4. Create Logic Method: Define a single Java function (e.g., calculateAndDisplay) that takes the required operator as input.

5. Attach Listeners: Set up OnClickListener for all four buttons, each calling the logic method with its specific operator character.

6. Perform Calculation: Inside the logic method, convert inputs to numbers and use a switch statement to execute the correct math (and check for divide-by-zero).

7.Display Output: Update the tvResult TextView with the final answer or show an appropriate error message using Toast.

## PROGRAM:
