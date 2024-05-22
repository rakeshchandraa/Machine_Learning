# Machine_Learning
Student Info:
Name: Rakesh Chandra Kolagani
Student ID: 700757119
                                  Assignment 1

Question 1:
Given list of 10 students ages: ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
 • Sort the list and find the min and max age
        To sort the list of functions we use sort () function. 
 • Add the min age and the max age again to the list 
• Find the median age (one middle item or two middle items divided by two) 
• Find the average age (sum of all items divided by their number) 
• Find the range of the ages (max minus min)
 

Explanation:
The code sorts the list of ages, finds the minimum and maximum ages, adds these back to the list, and then sorts it again. It calculates and prints the median, average, and range of the updated list. The median is computed by checking the middle elements, the average by summing all elements and dividing by their count, and the range by subtracting the minimum age from the maximum age. Each of these results is then printed.

Question 2
• Create an empty dictionary called dog 
• Add name, color, breed, legs, age to the dog dictionary 
• Create a student dictionary and add first_name, last_name, gender, age, marital status, skills, country, city, and address as keys for the dictionary
• Get the length of the student dictionary 
• Get the value of skills and check the data type, it should be a list 
• Modify the skills values by adding one or two skills 
• Get the dictionary keys as a list 
• Get the dictionary values as a list

Explanation:
The code creates and populates a dog dictionary with attributes and a student dictionary with various details, including a list of skills. It calculates and prints the length of the student dictionary, retrieves, and checks the type of the skills list, and modifies it by adding new skills. Finally, it retrieves and prints the keys and values of the student dictionary as lists.


Question 3 
• Create a tuple containing names of your sisters and your brothers (imaginary siblings are fine) 
• Join brothers and sisters tuples and assign it to siblings 
• How many siblings do you have? 
• Modify the siblings tuple and add the name of your father and mother and assign it to family_members



Explanation:
The code creates two tuples for sisters and brothers, then joins them into a single siblings tuple. It calculates and prints the number of siblings by determining the length of the siblings tuple. Since tuples are immutable, it creates a new family_members tuple by adding the names of the father and mother to the siblings tuple and prints the result.

Question 4 
it_companies = {'Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon'} A = {19, 22, 24, 20, 25, 26} B = {19, 22, 20, 25, 26, 24, 28, 27} age = [22, 19, 24, 25, 26, 24, 25, 24] 
• Find the length of the set it_companies 
• Add 'Twitter' to it_companies 
• Insert multiple IT companies at once to the set it_companies
• Remove one of the companies from the set it_companies 
• What is the difference between remove and discard 
• Join A and B 
• Find A intersection B 
• Is A subset of B 
• Are A and B disjoint sets 
• Join A with B and B with A 
• What is the symmetric difference between A and B 
• Delete the sets completely 
• Convert the ages to a set and compare the length of the list and the set.
Code and Output:
Difference between remove and discard is remove() throws an error if the element is not found in the list or doesn’t exist whereas discard() doesn’t throw an error.
 
 

Explanation:
The code calculates the length of the it_companies set, adds 'Twitter' and multiple other companies, and removes 'Oracle', demonstrating the difference between remove and discard. It performs union, intersection, subset, and disjoint operations on sets A and B, finds their symmetric difference, and deletes the sets. Finally, it converts a list of ages to a set to compare their lengths, highlighting the removal of duplicates in the set.

Question 5 
The radius of a circle is 30 meters. 
• Calculate the area of a circle and assign the value to a variable name of _area_of_circle_ 
• Calculate the circumference of a circle and assign the value to a variable name of _circum_of_circle_ 
• Take radius as user input and calculate the area


Code and Output:
 

Explanation:
The code calculates and prints the area and circumference of a circle with a given radius of 30 using the math module. It then prompts the user to input a radius, calculates the area of a circle with that user-provided radius, and prints the result.

Question 6 
“I am a teacher and I love to inspire and teach people” 
• How many unique words have been used in the sentence? Use the split methods and set to get the unique words.
Code and Output:
 

Explanation:
The code splits a given sentence into individual words and converts the list of words into a set to eliminate duplicates. It then calculates the number of unique words by finding the length of the set and prints the result.

Question 7 
Use a tab escape sequence to get the following lines. 
Name Age Country City 
Asabeneh 250 Finland Helsinki
Code and Output:
 

Explanation:
The code uses the tab escape sequence \t to format the output into columns. The first print statement prints the headers "Name," "Age," "Country," and "City" separated by tabs. The second print statement prints the corresponding values "Asabeneh," "250," "Finland," and "Helsinki" in the same tab-separated format.




Question 8 
Use the string formatting method to display the following: radius = 10 area = 3.14 * radius ** 2 “The area of a circle with radius 10 is 314 meters square.”
Code and Output:
 


Explanation:
The code calculates the area of a circle with a given radius of 10 using the formula. It then creates a formatted string using an f-string to insert the radius and the integer value of the area into a message. Finally, it prints the message that displays the area of the circle.

Question 9 
Write a program, which reads weights (lbs.) of N students into a list and convert these weights to kilograms in a separate list using Loop. N: No of students (Read input from user) Ex: L1: [150, 155, 145, 148] Output: [68.03, 70.3, 65.77, 67.13]
Code and Output:
 

Explanation:
The code reads the number of students and their weights in pounds from the user, storing the weights in a list. It then converts these weights to kilograms using a conversion factor and rounds the results to two decimal places. Finally, it prints both the original weights in pounds and the converted weights in kilograms.


![image](https://github.com/rakeshchandraa/Machine_Learning/assets/170479917/1385d7f5-c05b-4c06-8421-83ad5cd5a352)
