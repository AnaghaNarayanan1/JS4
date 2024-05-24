## 1. write a chained if/ else-if statement to fill in the following conditions
## val <5 => Tiny
## val <10 => Small
## val <15 => Medium
## val <20 => Large
## val >=20 =>Huge
### ans. let val=prompt("enter a value")
### if(val<5){
###    console.log("Tiny")
### }
### else if(val<10){
###    console.log("Small")
### }
### else if(val<15){
###    console.log("Medium")
### }
### else if(val<20){
###    console.log("Large")
### }
### else if(val>=20){
###    console.log("Huge")
### }

 

## Use the switch case and create an application with the following roles
## admin => gets full access
## subAdmin=>gets access to create and delete courses
## testPrep => gets access to create and delete 
## user => gets access to consume contents
### ans.let app=prompt("choose any number: 1.Admin 2.SubAdmin 3.testPrep 4.user)
 ### switch (app){
 ###   case"1":alert("get full access")
 ###   breake;
 ###   case "2":alert(gets access to create and delete courses")
 ###   break;
 ###   case "3":alert(gets access to create and delete tests")
 ###   break;
 ###   case "4":alert(gets access to consume contents")
 ###   break;
 ###   default:alert("invalid input")

 ### }