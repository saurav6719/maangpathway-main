# About
This is a beginner's GOlang project.
I have written a program using which you can order food in a restaurant.

# Resources 
1. [Go Beginner Project Tutorial - Learn Golang](https://www.youtube.com/watch?v=LHhsNa_Kgns)
2. [Golang Tutorial for Beginners](https://www.youtube.com/watch?v=yyUHQIec83I)

# Overview
Want to order food!? Well, you have come to the right place(not exactly :P).

This is a program which will help you order food in a restaurant named "Kanpur Bhojanalya".

You can order any item that is there in the menu, and as many times as you want. This program also lets you modify your order by allowing you to update quantity of an item, add an item in the order or delete an item from the order; before generating the final bill.

# Key-topics
* Golang basics
  - Fmt (Printf and Scan) 
  - Variables and Data types
  - Type Conversion
  - String padding
  - Conditionals(if/else)
  - Switch Statement
  - Arrays and Slices 
  - Maps
  - Structs

# Learnings
There are several things that I learnt while building this project. I am sharing it, so that you can refer it if you get stuck.
1. __How to append in a slice of struct?__
		
    Let say struct type name is NewStruct and we defined a new variable with the name a. 
        
        type NewStruct struct{
				   itemName string
				   price uint
				   quantity uint
				}
        
        //To append use the below code: 
      
        a = append(a, NewStruct{itemName: name, price: bill, quantity: noOfPlates}
        
 2. __What happens when you loop through an string, slice, map?__
  
    Read [for-loop range](https://yourbasic.org/golang/for-loop-range-array-slice-map-channel/) and [unexpected values range](https://yourbasic.org/golang/gotcha-unexpected-values-range/) to clear your doubts.
 3. __Time function__   : E.g., `time.Now()` 
      * Read [this](https://www.golangprograms.com/get-current-date-and-time-in-various-format-in-golang.html) article to gain more insights.
 4. __Random function__ : E.g.,`randIntn(500)`, `rand.Seed(time.Now().Unix())`;
      * Refer to [this](https://stackoverflow.com/questions/68203678/golang-rand-int-why-every-time-same-values) if you get stuck
 5. __Delete from a map__ : `delete(mapName, key)`

Here are some images of the workflow 



<img width="661" alt="Screenshot 2025-03-29 at 12 40 56 AM" src="https://github.com/user-attachments/assets/68719a17-ebdc-474a-8c3a-0f06bb6cd51e" />


<img width="808" alt="Screenshot 2025-03-29 at 12 41 31 AM" src="https://github.com/user-attachments/assets/15860871-2385-4a0d-ac2e-c79c58737314" />

<img width="849" alt="Screenshot 2025-03-29 at 12 41 50 AM" src="https://github.com/user-attachments/assets/0b6d14b2-1f95-40b6-990a-7f8c95002d6a" />
