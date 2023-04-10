## Do the below programs in anonymous function

Print odd numbers in an array
1). var a = [12,'13','14',1,34,23,547]
var b = function(a) {
var result = []
for (i=0; i<a.length; i++)
{
if(a[i]%2 !=0)
{  
 result.push(a[i])

         }


}
return result
}
console.log(b(a))

---

Convert all the strings to title caps in a string array
var a = [ 'yoga', 'maaya', 'm' ]
var b = function(a) {
var str =[]
for (i=0; i<a.length; i++)
{
st = a[i][0].toUpperCase() + a[i].slice(1,a[i].length)
str.push(st)
}
var aa = str.join(' ')
return aa

}
console.log(b(a))

---

Sum of all numbers in an array
var b = function(a) {

var sum =0
for (i=0; i<a.length; i++)
{
sum = sum + +a[i]
}
return sum
}
console.log(b([ '0', '1', '23', '45', '67', '8' ]))

---

Return all the prime numbers in an
var num = function() {

var arr = []
for (var i=0; i<a.length; i++)
{ var count = 0
for(var j=1;j<=a[i]; j++)
{ if (+a[i]%j ==0)
{
count++
}
}
if(count == 2)
{
arr.push(a[i])
}
}
return arr
}
var a = [ '16', '3', '5' , '9']
console.log(num(a))

---

Return all the palindromes in an array

var val = function() {

var arr = []
for (var i=0; i<a.length; i++)
{
var b = a[i].split('').reverse().join('')
if (a[i] == b)
{
arr.push(a[i])
}

}
return arr
}
var a = [ 'yoga', 'priya', 'maaya' , 'dharshni']
console.log(val(a))

---

Return median of two sorted arrays of the same size.
var val = function (a,b)
{
//console.log(a)
//console.log(b)
var whole = a.concat(b)
// console.log(whole.length)
if((whole.length)%2 == 0 )
{
var a1= a.sort((function (a,b){ return (a-b) })) //1 2 3 4 5 7
//console.log(a1)
var b1 = b.sort((function (a,b){ return (a-b) }))
//console.log(b1)  
 var l1= a1.pop()
//console.log(l1)
var f1= b1.shift()
//console.log(f1)
var mumtaj = (+l1 + (+f1))/2
return mumtaj //console.log()
}
else
{
var kn = whole.sort((function (a,b){ return (a-b) }))
var odd = Math.floor(( whole.length) /2)
return kn[odd] // console.log(kn[odd])  
 }
}

## console.log(val([ '1', '2'],[ '3' , '4','5'] ))

                        Remove duplicates from an array

var sun = function (func)
{
var val = [...new Set(func)]
return val
}
console.log(sun(['a',154, 1, 'a', 2, 1,2,3,4,2,3]));

---

                        Rotate an array by k times

var a = function (res)
{

for(var i=0; i<5;i++)
{
var b= res.shift()
var val = res.push(b)
}
return res
}
console.log(a([ 'a','b', 'c', 'd', 'e', 'f' ]))

---

               Do the below programs in arrow functions.
                        Print odd numbers in an array

1). var a = [12,'13','14',1,34,23,547]
var b = (a) => {
var result = []
for (i=0; i<a.length; i++)
{
if(a[i]%2 !=0)
{  
 result.push(a[i])

         }


}
return result
}
console.log(b(a))

---

                Convert all the strings to title caps in a string array

var a = [ 'yoga', 'maaya', 'm' ]
var b = (a) => {
var str =[]
for (i=0; i<a.length; i++)
{
st = a[i][0].toUpperCase() + a[i].slice(1,a[i].length)
str.push(st)
}
var aa = str.join(' ')
return aa

}
console.log(b(a))

---

                        Sum of all numbers in an array

var b = (a) => {

var sum =0
for (i=0; i<a.length; i++)
{
sum = sum + +a[i]
}
return sum
}
console.log(b([ '0', '1', '23', '45', '67', '8' ]))

---

                Return all the prime numbers in an array

var val = () =>{

var res = []
for (var i=0; i<a.length; i++)
{ var count = 0
for(var j=1;j<=a[i]; j++)
{ if (+a[i]%j ==0)
{
count++
}
}
if(count == 2)
{
res.push(a[i])
}
}
return res
}
var a = [ '16', '3', '5' , '9']
console.log(val(a))

---

          Return all the palindromes in an array

var val = () =>{

var res = []
for (var i=0; i<a.length; i++)
{
var b = a[i].split('').reverse().join('')
if (a[i] == b)
{
res.push(a[i])
}

}
return res
}
var a = [ 'yoga', 'priya', 'maaya' , 'dharshni']
console.log(val(a))
