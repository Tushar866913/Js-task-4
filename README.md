# Js-task-4
About implicit coersion , conditional statement ,pre and post increment.


// Implicit coersion:
//practice questions on implicit coersion
//console.log('A' - 1);//NaN
// console.log('A' + 1);//A1
// console.log(2 + '2' + '2');//222
// console.log('hello' + 'world' + 89);//helloworld89
// console.log('hello' - 'world' + 89);//NaN
// console.log('hello' + 78);//hello78
// console.log('78' - 90 + '2');//-122
// console.log(2 - '2' + 90);//
// console.log(89 - '90' / 2);//44
//console.log(true == false) > 2 




//
//var numVal = 30;
//var u = --numVal;//numval= 29,u = 29
//numVal++;numval = 30
//console.log(u);//29
//console.log(numVal);//30

//
//var a = 40;
//var b = a++;//b = 40,a = 41
//b++;//b = 41
//console.log(a);//41
//console.log(b);//41

//
// var f = 50;
// var g = f++;//g = 50,f = 51
// g--;//g = 49
// console.log(g);//49
// console.log(f);//51

//
//var val = 10;
//val++;//val = 11
//var h = --val;//val = 10,h = 10
//h++;//h = 11
//console.log(h);11
//console.log(val);10

//
//var num = 20;
// num++;//num = 21
// var t = ++num; //num=22,t = 22
// num++;//num = 23
// --num;//num = 22
// console.log(num, t);(22,22)

//
//var num = 10;
// --num;// num = 9
// var y = ++num + 10;//num = 10,y = 20
// --y;//y = 19
// console.log(y);//19
// console.log(num);//10

//
//var num = 30;
// ++num;//num = 31
// num++ - 10;//22
// console.log(num); //22


//task-1
//using conditional statements
//find the biggest of 3 numbers (89, 78, 56)

var a = 10;
var b = 90;
var c = 60;

if (a > b && a > c) {
   console.log(a);
}
else if (b > a && b > c) {
   console.log(b);
}
else if (c > a && c > b) {
   console.log(c);
}
else if (a == b && b == c) {
   console.log('wrong input');
}


//task_2
//value is even or odd

var e = 30
if (e % 2 == 0) {
   console.log('it is an even number');
}
else {
   console.log('it is a odd number');
}

// task_3
// given number is multiple of 3 or not e.g.10900

var f = 300
if (f % 3 == 0) {
   console.log('it is multiple of 3');
}
else {
   console.log('it is not a multiple of 3');
}

// task_4
// check particular sub-word exist in a string or not e.g. i am learning js: 'js' exists or not
var h = 'i am learning js';
var i = 'js';//from user
var j = (h.search('js'));
console.log(j);
if (i == j) {
   console.log(j);
}
else {
   console.log('not part of string');
}


//calculate simple interest ((p/r * t) * 100 )

var p = 10;
var r = 20;
var t = 2;

var si = ((p / r) * t) * 100;
console.log('Your simple interest is Rs' + ' ' + si);

//given year leap year or not (29 in feb): 2020
var y = parseInt(1999);

var r = y % 100;
var s = y % 4;
if (r == 0) {
   if (y % 400 == 0) {
      console.log("This is leap year");
   }
   else {
      console.log('This is not leap year');
   }
}
else if (s == 0) {
   console.log('This is leap year');
}
else {
   console.log('This is not leap year');
}


//0-6 display day week depending upon what user is entering (0-> sunday) : using switch
var d = 3;
switch (d) {
   case 0:
      console.log('It is Sunday');
      break;
   case 1:
      console.log('It is Monday');
      break;
   case 2:
      console.log('It is Tuesday');
      break;
   case 3:
      console.log('It is Wednesday');
      break;
   case 4:
      console.log('It is Thursday');
      break;
   case 5:
      console.log('It is Friday');
      break;
   case 6:
      console.log('It is Saturday');
      break;
} 


