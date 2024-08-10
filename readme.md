## 1. Write short notes on below array methods with code examples
### • reverse() : The reverse() method reverses the order of the elements in an array. The reverse() method overwrites the original array
### let arr=[1,2,3,4]
### console.log(arr.reverse())
### • sort() : The sort() sorts the elements of an array.This method overwrites the original array.The sort() sorts the elements as strings in alphabetical and ascending order.
### let arr=[5,8,6,1,0]
### let fruits=["banana","apple","orange","grapes"]
### console.log(arr.sort())
### console.log(fruits.sort())
### • fill() : The fill() method fills specified elements in an array with a value.This method overwrites the original array.Start and end position can be specified. If not, all elements will be filled.
### let fruits = ["Banana", "Orange", "Apple", "Mango"];
### console.log(fruits.fill("Kiwi", 2, 4));
### • filter() : Filter performs a function on each element of the array and returns only those elements that passes the test implemented by the function.
  ###  let isEven=(num) =>{
###    return num % 2 === 0
###    }
   ### let arr=[1,2,3]
   ### let newarr=arr.filter(isEven)
   ### console.log(newarr)
### • some() : Check if some of the elements in the array passes the test (atleast one)
### • every() : Test if the all the elements in the array passes the test and returns the boolean value.
 ### let arr=[1,2,3]
 ### let newarr=arr.every((num)=>{
 ### return num>0
 ### })
### console.log(newarr)
### • map() :Creates new array populated with the function on a every elements.
 ### let arr=[6,4,2,7]
 ### let newarr=arr.map((num)=>{
 ### return num*2
 ### })
### console.log(newarr)
### • forEach() : The forEach() method calls a function for each element in an array.The method is not executed for empty elements.
### let arr=[1,2,3,4,5]
### let newarr=[]
### arr.foreach((item)=>{
  ###  newarr.push(item)
### })
### console.log(newarr)
### • reduce() : Takes in an array,performs a fonction that provide an each elements in that array and returns one single.
### let value=[100,56,89,20]
### let item=(total,num)=>{
  ###  return total+num
### }
### let output=value.reduce(item)
### console.log(output)
### • indexOf() : Return the first index at which a given element can be found in the array,or -1 if it is present.
### let text = "Hello world, welcome to the universe.";
### console.log(text.indexOf("to")); 
## 2. write a function that takes an array of numbers as an argument and returns the sum of its elements.
### Ans.let arr=[100,56,89,20]
### let newarr=(total,num)=>{
  ###  return total+num
### }
### let output=arr.reduce(newarr)
### console.log(output)
## 3. Create a function that filters strings in an array by their length
### Ans.let str=["js","css","html","python"]
### let str1=str.filter((string)=>{
  ###  return string.length>2 
### })
### console.log(str1);
## 4. Create a function that returns a new array containing the square roots of each number in the original array 1,4,9,16,25
### Ans.let arr=[1,4,9,16,25]
### let newarr=arr.map((num)=>{
  ###  return math.sqrt(num)
### })
### console.log(result)
## 5. Write a function that prints the number 1 to 100. But for multiples of 3, print Fizz instead of the number, and for multiples of 5, print Buzz. For the numbers that are multiples of both 3 and 5, print FizzBuzz(write the code in the browser’s snippet and invoke the function inside the console)
### Ans.let count=1
### let output=[]
### let counter=()=>{
  ###  while (count<=100) {
        
  ###  if(count%3==0 && count%5==0){
   ###     output.push("fizzBuzz")
 ###   }
###    else if(count%5==0){
###     output.push("buzz")
   ###     }
###      else if(count%3===0){
   ###             output.push("fizz")
###  }
 ###   else{
### output.push(count)
  ###  }
### count++
   ### }
### console.log(output)
### }
### counter()
