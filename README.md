# js-basics

There are also, of course, "falsey expressions". Falsey expressions are those that JavaScript ultimately converts to false.
There are also other falsey expressions in JS, such as:
* 0 - yes, JavasScript sees the number zero as falsey if it’s used as a number
* "" or '' - an empty string value is also falsey
* undefined
* NaN : not a number
* null - this is a special expression that we’ll talk more about later, but it’s a way of saying “no value” that is different from undefined
------------------------
let arr1=[1,2,3,4,5]

let arr2=[...arr1] // copy arr1

arr1[0]=9999

console.log(arr2)
------------------------
let companies = ["Tesla", "Amazon", "Google", "Microsoft"]

for(let i in companies){
  console.log(i) // 0 1 2 3 
}

for(let company of companies){
  console.log(company) // tesla amazon ...  
}

for(let i = 0; i < 10; i++){
  console.log(i)
}
