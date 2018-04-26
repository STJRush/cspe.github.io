<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
/* Center the loader */
#loader {
  position: absolute;
  left: 50%;
  top: 50%;
  z-index: 1;
  width: 150px;
  height: 150px;
  margin: -75px 0 0 -75px;
  border: 16px solid orange;
  border-radius: 50%;
  border-top: 16px solid green;
  border-left: 16px solid white;
  width: 120px;
  height: 120px;
  -webkit-animation: spin 2s linear infinite;
  animation: spin 2s linear infinite;
}

@-webkit-keyframes spin {
  0% { -webkit-transform: rotate(0deg); }
  100% { -webkit-transform: rotate(360deg); }
}

@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

/* Add animation to "page content" */
.animate-bottom {
  position: relative;
  -webkit-animation-name: animatebottom;
  -webkit-animation-duration: 1s;
  animation-name: animatebottom;
  animation-duration: 1s
}

@-webkit-keyframes animatebottom {
  from { bottom:-100px; opacity:0 } 
  to { bottom:0px; opacity:1 }
}

@keyframes animatebottom { 
  from{ bottom:-100px; opacity:0 } 
  to{ bottom:0; opacity:1 }
}

#myDiv {
  display: none;
  text-align: center;
}
</style>
</head>
<body onload="myFunction()" style="margin:0;">

<div id="loader"></div>

<div style="display:none;" id="myDiv" class="animate-bottom">
  <head>
<style>
h1,p,li{
    color: white;
    text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;
}
</style>
</head>

<head>
<style>

p.italic {
    font-style: italic;
}

</style>
</head>

<head>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover {
    background-color: #111;
}
</style>
</head>

<html>
<body>

<img src="http://www.stjosephsrush.ie/wp-content/uploads/2018/03/schoolbanner3.png"  width="7000" height="200">


<h1 style="text-align:center;">About</h1>
   <strong>C.S.P.E</strong> 

 <ul>
   <li><a class="active" href="https://stjrush.github.io/cspe.github.io/">About</a></li>
   <li><a href="https://lukedoyle03.github.io/cspe.github.io/">Action project</a></li>
    <li><a href="https://www.curriculumonline.ie/getmedia/b4cf7fd4-46d0-4595-baa9-f6c38923c75f/JCSEC04_CSPE_Syllabus.pdf">C.S.P.E syllabus</a></li>
 </ul> 

<p class="italic">cspe is a subject taught in our school. It is taught from 1st-3rd year once a week.It is mainly based around politics.There are 7 main parts to the course these are Law, Interdepedence, Democracy, Stewardship, Rights and Responsibilities, Human Dignity and Development these will be explained below with examples of topics within them
 
<p class="italic">Rights & Responsibilities
Every human being is entitled to basic rights, but we also have a responsibility to others, and there is a constant need to safeguard peoples’ rights.
Topics include Children’s rights, prisoners of conscience, torture
 
<p class="italic">Human Dignity
Every human being has the right to live their lives with dignity and to be treated with respect.
Topics include Homelessness, bullying, refugees
 
<p class="italic">Stewardship
Caring responsibly for our environment and the planet on which we live
Topics include Recycling, global warming, the ozone layer
    
<p class="italic">Development
Improvements taking place in local, national or international communities
Topics include Tackling poverty in Africa, Third World Debt problems, regional development in Ireland
 
<p class="italic">Democracy
Citizens voting to elect people to represent them in government
Topics include Elections, Dail Eireann, Local Government
 
<p class="italic">Law
The rules and laws necessary to protect citizens. How laws are made, upheld, and the consequences of breaking the law.
Topics include An Garda Siochana, the courts system, the prison system
 
<p class="italic">Interdependence
The way in which we are connected with others in the world
Topics include The European Union, the United Nations, Fair Trade
   
<h1 style="text-align:center;">Examination</h1>
   
<p class="italic">A total of 40% of the marks in the exam are awarded for a written theory test, which includes such things as producing a poster, letter or article on a CSPE topic (such as poverty, racism, discrimination, etc.) and interpreting opinion polls.The written exam also has a number of short questions

<p class="italic">The remaining 60% of the marks are given for a report on an Action Project performed by an entire class of students at a time. This has to be based on one of the core topics - e.g. workers rights, environmentalism, racism, human rights, etc
    
 <body>

<img src="https://www.schoolbooks365.ie/image/cache/catalog/AAA/CSPE%20JC-500x500.jpg" width="250" height="250">

</body>

</div>

<script>
var myVar;

function myFunction() {
    myVar = setTimeout(showPage, 3000);
}

function showPage() {
  document.getElementById("loader").style.display = "none";
  document.getElementById("myDiv").style.display = "block";
}
</script>
