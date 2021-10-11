
var currentDate = new Date()
var day = currentDate.getDate()
var month = currentDate.getMonth() + 1
var year = currentDate.getFullYear()
document.write(+ day + "/" + month + "/" + year )



function check()
{
    filename = "system.js"
console.log(filename.split('.').pop());
}

check()



function convert(cel=20)
{
    var feh=(cel * (9/5)) + 32;

    console.log(feh)
}


let str = '';


function paramid()
{
    for(i = 0; i <= 5 ; i++) {
        for(j = 1; j <= i; j++) {
           str += '*';
        }
        str += '\n';
    }
    console.log(str);
}

paramid()



const names=["Summet", "Ali Mardan", "Salman", "Naveed", "Umair", "Raza"];


for(i=0; i <= names.length-1;i++)
{
    console.log(names[i]+" greetings my friend and well wishes to you")
}



const names=["Summet", "Ali Mardan", "Salman", "Naveed", "Umair", "Abrar"];


for(i=0; i <= names.length-1;i++)
{   

    if(names[i]!="Abrar"){
        console.log(names[i]+" greetings my friend and well wishes to you")
    }
 

else if(names[i]=="Abrar"){
    console.log(names[i]+" Good Morning Sir, Abrar")
}
}


var num =2;
for(i=0; i<=10; i++)
{

console.log("2"+"*"+i+"="+(2*i));

}
