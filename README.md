Wyncode: The World Needs More Tip Calculators!

Create a file named tip_calculator.rb. Enter the following code:

puts "How much is the bill?"
bill = gets
puts "The bill is $#{bill}"

This won’t work in SublimeText with Command+B. You must run this file from the Terminal using the word ruby followed by the filename.

MacBook-Pro:~$ cd ~/Desktop/
MacBook-Pro:~/Desktop$ ruby tip_calculator.rb

The gets method is the opposite of the puts method. It gets input from the user rather than sending output to the user.

Run this sample program. When prompted, enter a bill amount, press enter, and see what happens.

Edit this program to gets the total bill from the user, calculate the total plus a 20% tip, and output that total to the screen. The last line of your program should be:

puts "The total is $#{total}"
