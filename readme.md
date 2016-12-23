#Chapter 13 Project

Define a class named Time for encapsulating a time. The class contains the following:

1. A data field of the long time that stores the elapsed time since midnight, Jan 1, 1970.
2. A no-arg constructor that constructs a Time for the current time. 
3. A constructor with the specified hour, minute, and second to create a Time.
4. A constructor with the specified elapsed time since midnight, Jan 1, 1970.
5. The getHour() method that returns the current hour in the range 0-23.
6. The getMinute() method that returns the current minute in the range 0-59.
7. The getSecond() method that returns the current second in the range 0-59.
8. The getSeconds() method that returns the elapsed total seconds.
9. The toString() method that returns a string such as "1 hour 2 minutes 1 second" and "14 hours 21 minutes 1 second".
10. Implement the Comparable<Time> interface to compare this Time with another one based on their elapse seconds. The compareTo method returns the difference between this object’s elapse seconds and the another’s.
11. Implement the Cloneable interface to clone a Time object.
		
##Tasks
* Design: Create a UML Class diagram for the class
* Code: Implement the class
* Write a test program that produces the following sample run:
    ```bash
		<Sample Run>
		Enter time1 (hour minute second): 331 34 674 <Enter>
		19 hours 45 minutes 14 seconds 
		Elapsed seconds in time1: 1194314

		Enter time2 (elapsed time): 93889345 <Enter>
		16 hours 22 minutes 25 seconds 
		Elapsed seconds in time2: 93889345

		time1.compareTo(time2)? -92695031

		time3 is created as a clone of time1
		time1.compareTo(time3)? 0
		<End Sample Run>

		<Sample Run>
		Enter time1 (hour minute second): 1 2 3 <Enter>
		1 hour 2 minutes 3 seconds 
		Elapsed seconds in time1: 3723

		Enter time2 (elapsed time): 193032 <Enter>
		5 hours 37 minutes 12 seconds 
		Elapsed seconds in time2: 193032

		time1.compareTo(time2)? -189309

		time3 is created as a clone of time1
		time1.compareTo(time3)? 0
		<End Sample Run>
    ```
* Submit the files using git

