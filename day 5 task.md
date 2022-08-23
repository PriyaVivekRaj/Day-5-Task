1. Do the below programs in anonymous function & IIFE:
------------------------------------------------------
a. Print odd numbers in an array.
----------------------------------

var a=[1,2,3,4,5];

(function (a){
  for(var i in a)
  if(a[i]%2!=0)
  {
    var n=a[i]+2;
  console.log(n);
    
  }
})(a);


---------------------------------------------------------------------------------------------------------------------------------------------------
    b. Convert all the strings to title caps in a string array

var arr=["apple","beetroot","carrot","drumstick","eggplant","fig"];
      var title=function() {
        for(var i=0;i<arr.length;i++)
        
     console.log(arr[i][0].toUpperCase()+arr[i].substr(1));
      }
      title();
      




---------------------------------------------------------------------------------------------------------------------------------------------------
    c. sum of all numbers in an arry
    
Answer

 var a=[1,2,3,4,5];var s=0;
 var sum=	(function (){
  for(var i in a)
  s=s+a[i];console.log(s);  
})(sum);


-------------------------------------------------------------------------------------------------------------------------------------------------
    d. Return all the prime numbers in an array

    
    
 ----------------------------------------------------------------------------------------------------------------------------------
    e. Return all the palindromes in an array





 


    f. Return median of two sorted arrays of the same size


    g. Remove duplicates from an array
var a=['a','b','c','A','d','d'];
    var dup = function(a){
    for(var i=0; i < a.length; i++){
      if(newArr.indexOf(a[i]) == -1) {
    newArr.push(a[i]);
    } }
    console.log(dup);
   }
   res();  

    h. Rotate an array by k times.
  var a = [1,2,3,4,5,6,7,8,9,0];
var k = 3;
k = a.length % k;
(function() {
 // a = [];
 out = a.slice(k + 1, a.length);
 var count = out.length;
 for (var i = 0; i < k + 1; i++) {
 out[count] = a[i];
 count += 1;
 }
 console.log(out);})();








Do the below program in arrow functions:
----------------------------------------
a. print odd numbers in an array:
Answer:

var a = [23,56,89,45,12,34,7,85,78,54];
var odd=(n)=>{ for(var i in a) if(a[i]%2!=0)
console.log(a[i]);}
odd();
 


b. Convert all the strings to title caps in a string array

var arr = ["bala", "aswin", "simbu", "kalai"];
var a=(cap)=>{
for (var i in arr) 
console.log(arr[i][0].toUpperCase() + arr[i].substr(1));
}
a();


c. sum of all numbers in an arry


var a=[1,2,3,4,5,6,7,8,9];var s=0;
const sum=(n)=>{for(i in a)
{s=s+a[i]}
console.log(s)}
sum();




d. Return all the prime numbers in an array


    



e. Return all the palindromes in an arry
 

 


