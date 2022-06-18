// practice of java script
var sname ='loki';
console.log(sname);

// practice of java script data type (number ,string,boolean,indefined)//
var data = 3.87;
console.log(typeof data);
var cata = "loki itachi";
console.log(typeof cata);
var bata =  false;
console.log(typeof bata);

// practice of java script array and  objects
var data =[1,2,3,4,5,6,7]
console.log(data [2])
var bata = {
    name :"loki",
    age:23,
    sex:"M"
}
console.log(bata.sex)


function user(call){
    console.log(call);
    
}
user("loki");


function test(num1){
    return num1+10;
}
var output =test(90);
console.log (output);


// practice of java script[ functions]
function user(){
    console.log("hello loki");
    console.log("welcome");
}
user();




//practice of java scripe (condition statements)
//if , if-else and if-else if-else
var marks =35;
if(marks>75){
    console.log("good");
}
else if (marks>50){
    console.log("not bad");
}
else {
    console.log("bad");
}




// practice java script (looping)
//for and while
for (var i=1;i<11;i++){
    console.log(i);
    }
    
for (var j=1;j<5;j++){
    console.log('loki');
}

var test=0;
for (var k=0;k<10;k++){
    test=test+k;
}
console.log(test);



var test =0;
while (test<=10){
    console.log("hello");
    test++;
    }

var data=0;
while (data<6){
    console.log(data);
    data++;
}
 
// practice of java script maping
var data =[1,2,3];
data.map(
  function (ele){
    console.log(ele)
  }
)


var data =[1,2,3,4,5,6,7];
var output = data.map(
  function (ele){
    return ele+1;
     
  }
)
console.log(output)



// practice of java script filter
var data =[1,2,3,4,5,6,7];
var output = data.filter(
  function (ele){
    return ele>2
     
  }
)
	console.log(output)





// practice of java script foreach
var data =[1,2,3,4,5,6,7];
var output = data.forEach(
  function (ele){
  console.log(ele)   
     
  }
)



 //for every
var data = [1,2,3,4,5,6,7];
var output =data.every(
  function(ele){
    return ele>3; 
  }





// index 
var data =[0,1,2,3,4,5,6,7];
console.log(data.indexOf(3));

//last indexOf  
var data =[0,1,2,3,4,2,2,4];
console.log(data.lastIndexOf(2))
)
console.log(output)

 //sum
var data = [1,2,3,4,5,6,7];
var output =data.some(
  function(ele){
    return ele>2; 
  }
)
console.log(output)




//stringfy()
var data ={
  naam :"loki",
  age :28,
  sex :"M"
}
var json =JSON.stringify(data);
console.log(json)
// date
var date = Date();
console.log(date)




//arrow functon
const user =() => console.log("hello")
user();

const main =(num)=> {return num +23}
var output = main(10);
console.log(output);




// class
class user {
  admin(){
    console.log("HELLO SIR");

  }
  pass(){
    console.log("enter passward");

  }
}
let obj = new user();
obj.pass();



//for  of
const  arr =[1,3,4,5,6,7,8,2];
for(const a of arr){
  console.log(a);
}




//jdefault parameter
function user(name,age,sex){
  console.log(name +" "+age+''+ sex);
}
user('john',28, '  male');


//rest operator
function user(name,...rest){
  console.log(name+" : "+rest);
}
user('loki',23,"male","mail address")
.






//spread operator
var arr1 =[1,2,3,4,5];
var arr2 =[6,7,8,9,0];
let arr3 =[...arr1,...arr2];
console.log(arr3)



//destructure
let person ={
  naam : 'loku',
  age : 22,
  mail:'xxxxxxx'
}
console.log(person.naam);
const [naam,age,mail]=person;
console.log(age);

//destruction
let person =[1,2,3]
const [a,b,c] = person;
console.log(a)