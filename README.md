# MeanderingOrder
A few simple lines of code that places a given list of numbers from least to greatest. This Program is written in swift, and hosted by Xcode. The code for the program is below. I also provided an explanation under the code to better communicate my train of thought, as if i were teaching someone else.

var numbers = [-1,5,3,2,6]

numbers.sort(by: <)

print(numbers)

// Meandering order is when the numbers in a sequence are listed from the smallest to largest. In order to achieve the desired result, the numbers must first be declared. Above you can see just that. Once the desired list of numbers is created the coder must then establish the desired course of action, in this case, sorting. However in swift, one must determine what type of sorting must be done, and that is done by the sign that is added after the sort command. To start off from least to greatest, i used the less-than symbol. Once i establised the rule that i wanted to follow, i went ahead and entered the print command. I inputed "numbers" since that is the name of the case that holds information for the sequence, and viola! The numbers are now listed in meandering order!
