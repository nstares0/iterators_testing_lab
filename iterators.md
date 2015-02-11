


##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select: returns a new array with all elements that return true for the block passed into it

####reject: returns a new array with all elements that do not return true for the block passed into it

####map: for each item in the array, runs the block of code, creates a  new array 

####detect: returns the first item in the list for which the block returns TRUE

####inject: ** come back to this

http://stackoverflow.com/questions/710501/need-a-simple-explanation-of-the-inject-method **

####partition: returns two new arrays: the first is all things that the block evaluates to true, the second contains the rest

####sort: returns a new array with the items sorted based on the function in the block		

####one: returns true if the block returns true on only one of the elements in the array

####none: returns true if the block never returns true on any of the elements in an array

####all: returns true if the block never returns false or nil

####empty?: returns true if the array contains no elements

####eql?: returns true if the other array passed in is equal to those elements 

####include?: returns true if the array contains the element that is passed in

####nil?: returns true if the object is nil

###Hash methods:

####key?: returns the key of a given value

####keys: returns an array of the keys from a hash		

####delete: deletes a key value pair and returns the value

####delete_if: deletes every key value pair if block evaluates to true 
