# Task
The Two Api's and meet the following requirement
1.The first Api mapped under("/transactions") works exactly as intended
returning 201 for valid epoch timstamp and 204 for invalid timestamp

2.The second Api mapped under("/statistics") Works fine
Using inbuilt functions of the stream utility the 
avg,count, min, max, total are found. So the time complexity is O(1).
 Two datastructures are used List and Map.
The list has a space complexity of O(n)- where n is number of transactions
The map has a space complexity of O(1)- has only 5 will the total elements at any given time.

The maven clean build also generated an executable jar.

The thread safeness of the program is not checked.
