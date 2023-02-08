# js-basics

There are also, of course, "falsey expressions". Falsey expressions are those that JavaScript ultimately converts to false.
There are also other falsey expressions in JS, such as:
* 0 - yes, JavasScript sees the number zero as falsey if it’s used as a number
* "" or '' - an empty string value is also falsey
* undefined
* NaN
* null - this is a special expression that we’ll talk more about later, but it’s a way of saying “no value” that is different from undefined
------------------------
let arr1=[1,2,3,4,5]

let arr2=[...arr1]

arr1[0]=9999

console.log(arr2)
