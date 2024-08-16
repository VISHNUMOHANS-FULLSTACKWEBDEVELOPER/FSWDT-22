# FSWDT-10
span{
    background-color: black;
    color: white;
    border: 2px solid red;
    border-radius: 25%;
}

/* 
Css Selectors:
    >> Universal Selector (*)
    >> ID Selector (#)
    >> Class Selector (.)
    >> Element Selector
    >> Selector List
    >> Descendant Selector
    >> Direct Child Selector
*/
# FSWDT-11
/* 1. Element Selector */
/* h2{
    color: yellow;
    background-color: black;
} */
/* p{
    color: yellow;
    background-color: black;
} */

/* 2. Element Selector List */
/* h2,p{
    color: yellow;
    background-color: black;
} */

/* 3. Universal Selector */
/* *{
    color: yellow;
    border: 2px dotted red;
    background-color: black;
} */

/* 4. ID Selector */
/* #h2Count3{
    color: green;
    border: 2px dotted red;
    background-color: black;
} */

/* 5. Class Selector */
/* .h2ClassSelector{
    color: pink;
    background: black;
    border: 2px solid blue;
    width: 40px;
    height: 40px;
    border-radius: 80%;
} */

/* Units in CSS */
/* px, %, vh, vw, rem, em */

/* 6. Descendant Selector */
/* parent  any child */
/* li a{
    color: white;
    background: black;
} */
/* b i{
    color: pink;
    background-color: yellow;
} */

/* 7. Direct Child */
/* parent > direct child */
/* u > i{
    color: pink;
    background-color: yellow;
} */

/* 
h5{
    color: yellow;
    background-color: darkmagenta;
} */

h6{
    border: 2px solid black;
    background-color: black;
    color: white;
    /* padding: 10px 15px 20px 25px; */
    /* padding-left: 50px;
    padding-top: 25px;
    padding-bottom: 30px; */
    margin: 30px 25px 20px 10px;

}
# FSWDT-12
/* * {
    box-sizing: border-box;
    /* padding: 0;
    margin: 0; 
} */



/* h6{
    background-color: black;
    color: white;
    border: 2px solid red; */
    /* padding-left: 15px;     */
    /* padding: 10px 0 0 15px; */
    /* margin-left: 20px; */
    /* margin: 0 0 0 20px;
} */

 /* top right bottom left (clk wise directions) */
/* 
Spacings:
    Padding => Internal to Box/Border
    Margin  => External to Box/Border
*/

/* ctrl + alt + down key */

/* block */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: block;
}

.displayInCss2{
    display: block;
    background-color: red;
    height: 45px;
    color: white;
} */

/* 
*{
    padding: 0;
    margin: 0;
} */

/* inline */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: inline;
}

.displayInCss2{
    display: inline;
    background-color: red;
    height: 45px;
    color: white;
} */


/* inline-block */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: inline-block;
}

.displayInCss2{
    display: inline-block;
    background-color: red;
    height: 45px;
    width: 80px;
    color: white;
} */


/* Static Position */

/* .positionInCss{
    position: static;
    background-color: black;
    color: white;
    border: 1px solid red;
} */

/* Relative Position */
.positionInCss{
    position: static;
    top: 80px;
    background-color: black;
    color: white;
    border: 1px solid red;
}
# FSWDT-14
/* 
Hover State: 
        >> Pointing the cursor on the button 
*/
/* button:hover{
    color: white;
    background-color: black;
    cursor: pointer;
} */

/* 
Active State: 
        >> When we we hold left key of the mouse it will be in active statae
*/
/* button:active{
    border: 10px solid red;
} */

/* 
Focus State:
        >> Indicating you already visisted that button / or opened or clicked the btn
 */
 /* button:focus{
    background-color: pink;
    color: white;
 } */


 /* anchor un-visisted link state */
 /* a:link{
    color: red;
 } */

 /* a:visited{
    color: green;
 } */

 /* a:hover{
    cursor: progress;
 } */

 /* span{
    padding: 8px;
    margin: 8px;
    background-color: yellow;
 } */

 /* First Child */
/* span:first-child{
    background-color: red;
} */

/* Last Child */
/* span:last-child{
    background-color: red;
} */

/* nth child (eg 3rd child) */
/* span:nth-child(3){
    background-color: pink;
} */

/* styles for even child number */
/* span:nth-child(even){
    background-color: aqua;
} */

/* span:nth-child(odd){
    background-color: aqua;
} */


/* Psuedo Elements :: before */
/* h1::before{
    content: "hello ";
    background-color: black;
    color: white;
} */

/* Psuedo Elements :: after */
/* h1::after{
    content: " g'morning";
} */


.shape{
    margin: 100px;
    width: 150px;
    height: 150px;
    background-color: black;
    border-radius: 50%;
    position: relative;
}

.shape::before{
    content: " ";
    width: 80px;
    height: 80px;
    background-color: yellow;
    position: absolute;
    top: 0;
    left: 0;
    border-radius: 50%;
}

/* px,%,em,rem,vh,vw */

.shape::after{
    content: " ";
    width: 80px;
    height: 80px;
    background-color: yellow;
    position: absolute;
    bottom: 0;
    right: 0;
    border-radius: 50%;
}



/* 
>> Flex Box
>> Animations 
>> Git Sessions
>> Static Projects (HTML, CSS)
>> ....
*/
# FSWDT-15
.parent{
    /* height: 1150px; */
    background-color: black;
    display: flex;
    /* row, row-reverse, column, column-reverse */
    flex-direction: center;
    gap: 10px;
    /* row: flex-start, flex-end, center, space-around, space-between, space-evenly */
    justify-content: center;

    /* column: felx-start, flex-end, center, stretch */
    align-items: center;
    flex-wrap: wrap;
}


.child{
    height: 100px;
    width: 100px;
    /* flex: 1; */
    background-color: white;
    border: 2px solid red;
    /* margin-right: 10px; */
    justify-content: center;
}





/* Animations */
button{
    background-color: black;
    color: white;
    margin: 20px;
    padding: 10px;
    font-size: 20px;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    /* Transition Properties */
    /* transition-delay: 250ms; */
    /* transition-duration: 500ms; */
    /* all */
    /* transition-property: background-color color; */
    /* linear, ease, ease-in, ease-out, ease-in-out, cubic-bezier(0.22, 0.75, 0.85, -0.32); */
    /* transition-timing-function: cubic-bezier(0.22, 0.75, 0.85, -0.32); */
    

    transition: all cubic-bezier(0.22, 0.75, 0.85, -0.32) 250ms 500ms;
}

button:hover{
    background-color: aqua;
    color: black;
    cursor: pointer;
}
# FSWDT-16
.box{
    background-color: black;
    height: 100vh;
    /* width: 100vw; */
}

.ball{
    height: 120px;
    width: 120px;
    border-radius: 100%;
    background-color: yellow;
}

.ball:hover{
    animation: moveTheBall 5s ease-in-out forwards;
}

@keyframes moveTheBall {
    25%{
        transform: translate(400px, 0);
    }
    50%{
        transform: translate(400px,-600px);
        background-color: aqua;
        border-radius: 12%;
    }
    75%{
        transform: translate(0,600px);
        background-color: white;
        border-radius: 25%;
    }
    100%{
        transform: translate(0,0);
    }
}


/* Media Queries */
@media only screen and (max-width: 400px){
    h1{
        
    }
}
# FSWDT-17
/* screen size is in the range of 0-1200 */
/* @media only screen and (max-width: 1200px) {
  h2 {
    color: yellow;
    font-size: 12.5px;
  }
  p {
    color: yellowgreen;
  }
} */

/* screen size is in the range of 0-800 */
/* @media only screen and (max-width: 800px) {
  h2 {
    color: red;
    font-size: 15px;
  }
  p {
    color: aqua;
  }
} */

/* screen size is in the range of 0-400 */
/* @media screen and (max-width: 400px) {
  h2 {
    color: blue;
    font-size: 20px;
  }
  p {
    color: brown;
  }
} */

/* 
>> max-width 
      Eg: max-width: 400px {Screen size is <=400px} => atmost
>> min-width
      Eg: min-width: 400px {Screen size is >=400px} => atleast
*/

/* screen size is in the range of 400> */
@media screen and (min-width: 400px) {
    h2 {
      color: blue;
      font-size: 20px;
    }
    p {
      color: brown;
    }
  }
  
  /* screen size is in the range of 800> */
  @media screen and (min-width: 800px) {
    h2 {
      color: red;
      font-size: 20px;
    }
    p {
      color: yellow;
    }
  }
  
  /* 
  atleast 50 % => min-width
  atmost 50 % => max-width
  */

# FSWDT-22
DAY22
INTRO TO JS
var name="vishnu"
undefined
console.log(name)
VM194:1 vishnu
undefined
var age=21;
undefined
console.log(age)
VM266:1 21
undefined
name="vishnu mohan s"
'vishnu mohan s'
console.log(name);
VM348:1 vishnu mohan s
undefined
 age=21+1;
22
console.log(age);
VM416:1 22
undefined
# FSWDT23
DAY23
Js day2 Array and objecs,non primitive datatypes
console.log("hello wrold");
VM131:1 hello wrold
undefined
age=21
21
console.log(age);
VM210:1 21
undefined
var name="vishnu";
undefined
console.log(name);
VM387:1 vishnu
undefined
var isyoung=true;
undefined
console.log(isyoung);
VM530:1 true
undefined
console.log("isyoung");
VM552:1 isyoung
undefined
console.log("is young",isyoung);
VM614:1 is young true
undefined
var stud=["abc", "vbn","klo"];
undefined
console.log(stud);
VM760:1 (3) ['abc', 'vbn', 'klo']
undefined
console.log(stud[0]);
VM857:1 abc
undefined
var objName={
    age=12,
VM918:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
var objName={
    age=12,name="abc",schoolcompleted="true"}
VM993:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
console.log(objName);
VM1074:1 Uncaught ReferenceError: objName is not defined
    at <anonymous>:1:13
(anonymous) @ VM1074:1Understand this error
var objName={
    age=12,name="abc",schoolcompleted="true"};
VM1080:2 Uncaught SyntaxError: Invalid shorthand property initializerUnderstand this error
var objName={
    age:12,name:"abc",schoolcompleted:true};
undefined
console.log(objNmae);
VM1177:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1177:1Understand this error
console.log(objName);
VM1270:1 {age: 12, name: 'abc', schoolcompleted: true}
undefined
console.log(objNmae.age);
VM1300:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1300:1Understand this error
console.log(objNmae.name);



VM1330:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1330:1Understand this error
var objName={
    age:12,name:"abc",schoolcompleted:true};
undefined
console.log(objNmae.name);
VM1358:1 Uncaught ReferenceError: objNmae is not defined
    at <anonymous>:1:13
(anonymous) @ VM1358:1Understand this error
console.log(objName.name);
VM1368:1 abc
# FSWDT24
Day24
<!DOCTYPE html>
<html>
    <head>
        <title>js with html</title>
    </head>
    <body>
        <h3>Js with html</h3>
        <script src="./day24.js"/>
    </body>
</html>
// String manipulation
var data="hey everyone this is js with html session";
console.log("data: ",data);
// slice
console.log("slice:",data.slice(2,4));
// length
console.log("length:",data.length);
// replace
updateddata=data.replace("hey","hi")
console.log("replace: ", updateddata);
console.log("original data:",data);
// includes
console.log(data.includes("is"))
// string to int & int to string
var var1="1234";
console.log(var1);
console.log(parseInt(var1));
var var2=1234;
console.log(var2);
console.log(var2.toString());
console.log(var2.toLocaleString());
// split operator
var var1="gud morning"
console.log(var1.split(" "));
// objects
var var1={
    name:"vishnu",
    Age:21
}
console.log(var1);

var1.name="vishnu mohan";
var1.Age=20;
console.log(var1);
# FSWDT25
Day25
<!DOCTYPE html>
<html>
    <head>
        <title>Array Methods & Promises</title>
    </head>
    <body>
        <h1>Array Methods & Promises</h1>
        <script src="./day26.js"></script>
    </body>
</html>
// arrow function
// var sum = (a,b) =>{
//     console.log("sum:",a+b);
// }
// sum(3,4);
// var sum=(a,b)=>console.log("sum:",sum) If there is a single line only ten curly braces are not required.
// sum(3,4);

// Array Methods

// var array = [1,2,3,4,5];

// // 1.map
// var newArray = array.map((data) => data*2);
// console.log("newArray " ,newArray,"index");


// If you are using {}then you need to use the "return"
// var newArray = array.map((data) => {return data*2});
// console.log(newArray);

// 2.Filter 
// var newArray=array.filter((data) => data>=3);
// console.log(newArray);
// Or
// var newArray=array.filter((data) => {
//  if(data>3){
//     return data;
// }
// });
// console.log(newArray);

// 3.Find
// var newArray=array.find((data)=>data>=2);
// console.log("Find",newArray);
// 

// 4.Reduce
// var totalSum=array.reduce((accumulation,currentvalue)=>accumulation*currentvalue);
// console.log("totalsum:",totalSum);

var FlipkartCart = [
    {
        price: 200,
        quantity:2
    },
    {
        price: 400,
        quantity:1
    },
    {
        price: 300,
        quantity:4
    },
    {
        price: 500,
        quantity:2
    },
    {
        price: 1000,
        quantity:3
    }
];
var totalCost=FlipkartCart.reduce((accumulator,currentValue) => {
    return accumulator + currentValue.price*currentValue.quantity},0);
console.log(totalCost);

// Promises
// It is an object that returns its value that we hope to execute in future not immediately
// 1.Pending State ()
// 2.Fullfill()
// 3.Reject()
// Syntax
// var myPromise=new Promise(()=>{})
// var myPromise=new Promise(function(){})
 
var myPromise=new Promise((resolve,reject)=>{
    setTimeout(function(){
        resolve("sucess");
    },5000);
    setTimeout(function(){
       reject("error occured"); 
    },7000); 
});
myPromise
.then((data)=>{console.log(data)})
.catch((err)=>{console.log(err)});
# FSWDT26
day26
<!DOCTYPE html>
<html>
    <head>
    <title>Promises,Aync Await and DOM tree</title>
</head>
<body>
    <h2>Promises,Aync Await and DOM tree</h2>
    <script src="./day27.js"></script>
</body>
</html>
// var myPromise= new Promise((resolve,reject)=>{
//     setTimeout(function(){
//         resolve("sucess");
//     },3000);

// setTimeout (function(){
//     reject("error");
// },3000);
// });
// myPromise
// // .then((data)=>(data+="hey"))
// // first thhen will only be execued first
// .then((data)=>{console.log(data)})
// .then((data)=>{
//     data="hey"+data;
//     return data;
// })
// .catch((error)=>{console.log(error)});

// Asyn and Awat
// Asynchronous manner operation is usally followed by our compiler in such scenarious we use await for certain operations to carry out eg:Bank transfer
// setTimeout(function(){
//     console.log("1");
// },2000);
// console.log("2");

// Second method other then using then catch we used async await 
var myPromise=new Promise((resolve,reject)=>{
    resolve("sucess");
});
// var getourPromise= async()=>{
//     var getourPromiseresult =await myPromise;
//     console.log("getourPromiseresult",getourPromiseresult);
// }
// getourPromise();

// Third method here we used try and catch method
var getourPromise=async () => {
    try{
    getourPromiseResult=await myPromise;
    console.log(getourPromiseResult);
    }
    catch(error){
        console.log(error);
    }
};
getourPromise();
# FSWDT27
Day27
<!DOCTYPE html>
<html>
    <head>
        <title>Js build Project</title>
        <!-- styles -->
        <link href="./index.css" rel="stylesheet"/>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    </head>
    <body>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Js project</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                      <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    </ul>
                </div>
                      <button class="btn btn-outline-primary align items-center gap-3" type="submit">
                        <i class="fa-solid fa-plus mr-4"></i> Add new item
                  </button>
              </div>
            </div>
          </nav>
          <div class="container">
            <section class="">
              <div class="row justify content-center">
                <div class=".col-md-6">
                   <div class="input-group flex-nowrap shadow-lg rounded">
                    <input type="search"class="form-control" placeholder="Search your ask here"aria-label="Search task" aria-describedby="addon-wrapping"
                    <span class="input-group-text" id="addon-wrapping">
                      <i class="fa-solid fa-magnifying-glass"></i>
                    </span>
                  </div>
                </div>
               <!-- <div class=".col-md-6">
                  
                </div> -->
              </div>
            </section>
            <section>
              <!-- cards -->
            </section>
          </div>

          # FSWDT28
day28
html
<!DOCTYPE html>
<html>
    <head>
        <title>Js build Project</title>
          <!-- Font awesome icons -->
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
        <!-- styles -->
        <link href="./index.css" rel="stylesheet"/>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    </head>
    <body>
<!-- Small Screen size buton -->
      <div class="add__new__button__only d-md-none ">
       <button class="btn btn-outline-primary align items-center gap-3" type="submit"data-bs-toggle="modal" data-bs-target="#addModal">
        <i class="fa-solid fa-plus mr-4 "></i> Add new item
       </button>
      </div>
<!-- open task model -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Task Details...</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body task__modal__body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <!-- <button type="button" class="btn btn-primary">Save changes</button> -->
      </div>
    </div>
  </div>
</div>

<!-- Modal -->
      <div class="modal fade" id="addModal" tabindex="-1" aria-labelledby="addModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="addModal">Add New Task</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <!-- img -->
          <div class="mb-3">
            <label for="Imgurl" class="form-label">Image Url</label>
            <input type="email" class="form-control" id="Imgurl" aria-describedby="ImgDesc" placeholder="https://vishnumohan/img">
            <div id="ImgDesc" class="form-text" >This is an optional field for you</div>
          </div>
          <!-- title -->
          <div class="mb-3">
            <label for="Tilte" class="form-label">Task Title</label>
            <input type="email" class="form-control" id="Imgurl" aria-describedby="TitleDesc" placeholder="TaskTitle">
          </div>
          <!-- Task type -->
          <div class="mb-3">
            <label for="Task Type" class="form-label">Task Type</label>
            <input type="tag" class="form-control" id="Tasktype" aria-describedby="TasktypeDesc" placeholder="TaskType">
          </div>
        <!-- Task Description -->
         <div>
          <label for="Text description" class="form-label">Text description</label>
          <textarea
             type="text" class="form-control" id="Textdescription"  placeholder="Text Description" rows="3" required
          ></textarea>
        </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="submit" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
      </div>
<!-- Nav Bar -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Js project</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                      <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    </ul>
                </div>
                      <button class="btn btn-outline-primary align items-center gap-3" type="submit"data-bs-toggle="modal" data-bs-target="#addModal">
                        <i class="fa-solid fa-plus mr-4 "></i> Add new item
                  </button>
              </div>
            </div>
          </nav>
          <div class="container">
            <section class="mt-4">
              <div class="row justify content-center">
                <div class=".col-md-6">
                   <div class="input-group flex-nowrap shadow-lg rounded">
                    <input type="search"class="form-control" placeholder="Search your ask here"aria-label="Search task" aria-describedby="addon-wrapping"
                    <span class="input-group-text" id="addon-wrapping">
                      <i class="fas fa-search m-2"></i>
                    </span>
                  </div>
                </div>
               <!-- <div class=".col-md-6">
                  
                </div> -->
              </div>
            </section>
            <section class="mt-4">
              <!-- cards -->
               <div class="row task__contents"></div>
            </section>
          </div>







<!-- Scripts -->
        <script src="./index.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>

    </body>
</html>
js
// var state={
//     taskdetails:[
//         {
//         imgUrl:"",
//         taskdetails:"",
//         tasktype:"",
//         taskdescription:"",
//         },
//         {
//          imgUrl:"",
//          taskdetails:"",
//          tasktype:"",
//          taskdescription:"",
//         },
//         {
//          imgUrl:"",
//          taskdetails:"",
//          tasktype:"",
//          taskdescription:"",
//          },
//         {
//         imgUrl:"",
//         taskdetails:"",
//         tasktype:"",
//         taskdescription:"",
//         },
//     ],
// };
const state={
    taskdetails:[]
};
// DOM operations
const taskcontents= document.querySelector(".task__contents");
const taskmodal= document.querySelector(".task__modal__body");
// console.log(taskcontents);
// console.log(taskmodal);
# FSWDT29
Day29
<!DOCTYPE html>
<html>
    <head>
        <title>Js build Project</title>
          <!-- Font awesome icons -->
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
    integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
        <!-- styles -->
        <link href="./index.css" rel="stylesheet"/>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">

    </head>
    <body onload="loadIntialData">
<!-- Small Screen size buton -->
      <div class="add__new__button__only d-md-none ">
       <button class="btn btn-outline-primary align items-center gap-3" type="submit"data-bs-toggle="modal" data-bs-target="#addModal">
        <i class="fa-solid fa-plus mr-4 "></i> Add new item
       </button>
      </div>
<!-- open task model -->
<div class="modal fade" id="showTask" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">Task Details...</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body task__modal__body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <!-- <button type="button" class="btn btn-primary">Save changes</button> -->
      </div>
    </div>
  </div>
</div>

<!-- Modal -->
      <div class="modal fade" id="addModal" tabindex="-1" aria-labelledby="addModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="addModal">Add New Task</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <!-- img -->
          <div class="mb-3">
            <label for="imgurl" class="form-label">Image Url</label>
            <input type="url" class="form-control" id="url" aria-describedby="imgurl" placeholder="https://vishnumohan/img">
            <div id="imgurl" class="form-text" >This is an optional field for you</div>
          </div>
          <!-- title -->
          <div class="mb-3">
            <label for="Tilte" class="form-label">Task Title</label>
            <input type="text" class="form-control" id="taskTitle" aria-describedby="TaskTitle" placeholder="TaskTitle" required>
          </div>
          <!-- Task type -->
          <div class="mb-3">
            <label for="Task Type" class="form-label">Task Type</label>
            <input type="text" class="form-control" id="tags" aria-describedby="TasktypeDesc" placeholder="TaskType"required>
          </div>
        <!-- Task Description -->
         <div>
          <label for="TaskDescription" class="form-label">Text description</label>
          <textarea
             type="text" class="form-control" id="taskDescription"  placeholder="TaskDescription" rows="3" required
          ></textarea>
        </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="submit" class="btn btn-primary"  onclick=" handleSubmit()">Save changes</button>
      </div>
    </div>
  </div>
      </div>
<!-- Nav Bar -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Js project</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                      <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    </ul>
                </div>
                      <button class="btn btn-outline-primary align items-center gap-3" type="submit"data-bs-toggle="modal" data-bs-target="#addModal">
                        <i class="fa-solid fa-plus mr-4 "></i> Add new item
                  </button>
              </div>
            </div>
          </nav>
          <div class="container">
            <section class="mt-4">
              <div class="row justify content-center">
                <div class=".col-md-6">
                   <div class="input-group flex-nowrap shadow-lg rounded">
                    <input type="search"class="form-control" placeholder="Search your ask here"aria-label="Search task" aria-describedby="addon-wrapping"
                    <span class="input-group-text" id="addon-wrapping">
                      <i class="fas fa-search m-2"></i>
                    </span>
                  </div>
                </div>
               <!-- <div class=".col-md-6">
                  
                </div> -->
              </div>
            </section>
            <section class="mt-4">
              <!-- cards -->
               <div class="row task__contents"></div>
            </section>
          </div>




<!-- Scripts -->
        <script src="./index.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>

    </body>
</html>
js
// var state={
//      tasklist:[
//         {
//         imgUrl:"",
//         taskdetails:"",
//         tasktype:"",
//         taskdescription:"",
//         },
//         {
//          imgUrl:"",
//          taskdetails:"",
//          tasktype:"",
//          taskdescription:"",
//         },
//         {
//          imgUrl:"",
//          taskdetails:"",
//          tasktype:"",
//          taskdescription:"",
//          },
//         {
//         imgUrl:"",
//         taskdetails:"",
//         tasktype:"",
//         taskdescription:"",
//         },
//     ],
// };
const state={
    tasklist:[]
};
// DOM operations
const taskcontents= document.querySelector(".task__contents");
const taskmodal= document.querySelector(".task__modal__body");
// console.log(taskcontents);
// console.log(taskmodal);


// Template for card section
const htmltaskcontent=({id,type,title,description,url})=>{`
    <div class='col-md-6 col-lg-4 mt-3' id=${id}>
      <div class='card shadow-sm  task__card__header'>
      <div class='card-header d-flex justify content-end task__card__header'>
      <button type='button' class='btn outline-primary mr-1.5' name='${id}' >
      <i name='${id}'class='fas fa-pencil-alt'></i>
      </button>
      <button type='button' class='btn outline-danger mr-1.5' name='${id}' >
      <i name='${id}'class='fas fa-trash-alt'></i>
      </button>
        </div>
        <div class='card__body'>
        ${
            url &&
            `<img src=${url} atl='Card Image' width=100% class='card-img-top md-3 rounded-lg'/>
            <h4 class="card-title">${title}</h4>
            <p class="description trim-3-lines">${description}</p>
            <div class='tags text-white d-flex flex-wrap'>
            <span class='badge bg-primary m-1'></span>
            </div>
            <div>
            <button type='button' class='btn btn-primary float-right'data-bs-toggle="modal" data-bs-target="#showTask">>Open task</button>
            </div>
        `}
        </div>
    </div>
    </div>
    `};
    // Modal body on click open task
    const task__modal__body=({id,type,title,description,url})=>
    {
        const date=new Date(parseInt(id));
        return`
        <div id=$(id)>
        ${
            url &&
            `<img src=${url} atl='Card Image' width=100% class='card-img-top md-3 rounded-lg'/>`
         }
        <strong class='text-muted text-sm'>Created on:${date.Todatestring()}</strong>
        <h2 class='my-3'>${title}</h2>
        <p class='text-muted'>${description}</p>
        </div>`
    };


    // We are storing the data in the local sorage and converting the json > string
    const updateLocalStorage=()=>{
  localStorage.getItem(
    'tasky',JSON.stringify({tasks:state.tasklist,})
  );
    };
    // We are displaying the data in the local sorage and converting the string > json
    const loadIntialData=()=>{
      const localStoragecopy=JSON.parse(localStorage.tasklist);

      if(localStoragecopy)  state.tasklist=localStorage.tasklist;

      state.tasklist.map(date)=()=>{
        taskcontents.insertAdjacentHTML("beforeend",htmltaskcontent(date));
      }
    };
    // we need o confirm that a single&same card operation at a time
    // At the same  we need to save the updated data
    const handleSubmit=(event)=>{
      const id=`${Date.now()}`;
      const input={
        url:document.getElementById("url").value, 
        title:document.getElementById("taskTitle").value,   
        type:document.getElementById("tags").value,    
        description:document.getElementById("taskDescription").value      
      };
      if(input.title=== ""||input.type=== ""|| input.description=== ""){
        return alert("pls fill the required field;");
      }

      taskcontents.insertAdjacentHTML("beforeend",htmltaskcontent({...input,id}));
       state.tasklist.push({...input,id});
    updateLocalStorage();
    };
    // spread operator
    //  const obj={
    //  name:"vishnu" ,age:1}
    //  undefined
    //  console.log(obj);
    //  VM290:1 {name: 'vishnu', age: 1}
    //  undefined
    //  console.log({obj});
    //  VM340:1 {obj: {…}}obj: {name: 'vishnu', age: 1}age: 1name: "vishnu"[[Prototype]]: Object[[Prototype]]: Objectconstructor: ƒ Object()hasOwnProperty: ƒ hasOwnProperty()isPrototypeOf: ƒ isPrototypeOf()propertyIsEnumerable: ƒ propertyIsEnumerable()toLocaleString: ƒ toLocaleString()toString: ƒ toString()valueOf: ƒ valueOf()__defineGetter__: ƒ __defineGetter__()__defineSetter__: ƒ __defineSetter__()__lookupGetter__: ƒ __lookupGetter__()__lookupSetter__: ƒ __lookupSetter__()__proto__: (...)get __proto__: ƒ __proto__()set __proto__: ƒ __proto__()
    //  undefined
    //  console.log({...obj});
    //  VM415:1 {name: 'vishnu', age: 1}
    //  undefined
    //  console.log({...obj,designation:"student"});
    //  VM545:1 {name: 'vishnu', age: 1, designation: 'student'}
