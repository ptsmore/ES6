# React

<b>Codepen:</p> https://codepen.io/phanuwat-thawatrungrote/pen/EOvMmg

<p> <h3> Let </h3> only change and declare variable in block scoped </p>
<pre>
  <code>
    <span>for(let i = 0 ; i < 3 ; i++){ console.log(i);}</span>
    <span>console.log(i);</span> //this line will error beacause it is out on loop.
  </code>

</pre>

<p><h3> Arrow Function </h3> </p>
<pre>
  <code>
    <span>const myFnc = () => {...} </span> //Arrow function
    <span>function myFnc(){...}</span> //Javascript Function
    <span>const multiply = number => number * 2</span> //Javascript Function
  </code>

</pre>


<p>use https://jsbin.com/?html,output to test js</p>

<h3>Export & Import Module</h3>

![ScreenShot](/PIC/ExportImportModule.PNG)

<h3>Class</h3>
<u>basic</u>
<pre>
class Person{
  constructor(){
    this.name = 'Test';
  }
  printTest(){
    console.log(this.name);
  }
}
const person = new Person();
person.printTest();
</pre>

<u>Extend another class</u>
<pre>
class Human{
  constructor(){
    this.gender = 'Male';
  }
  printGender(){
    console.log(this.gender);
  }
}
class Person extends Human{
  constructor(){
    super(); //must have super class when extends another class
    this.name = 'Test';
  }
  printTest(){
    console.log(this.name);
  }
}
const person = new Person();
person.printTest();
person.printGender();
</pre>
