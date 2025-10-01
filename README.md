let fruits=["Apple","Banana","Grapes","Mango"];
let result="";
for(let fruit of fruits){
    result +="<li>" + fruit + "</li>";
}
document.getElementById("fruits").innerHTML=result;
