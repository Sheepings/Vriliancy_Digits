# Vriliancy_Digits
This small library will allow you to create a sequence of random numbers and scramble them so they are not orderly. 

For usage, you add a reference to the DLL, or the Vriliancy_Digits class, and call the CreateNumbers method, and pass in a Tuple<int, int>. 

The first integer of the Tuple is your starting point number, and your second integer is your ending point number. The script will generate numbers between and including the starting point/ending point numbers. Note that this method returns a Queue<Tuple<int,int>>

![Screenshot_41](https://user-images.githubusercontent.com/54504605/124365094-bb64e700-dc3d-11eb-81d1-f91d501926c6.jpg)
