window.onload = function () {
  console.log("(1)");
  /////////////////////////////
  // Lecture: Function constructor

  var Person = function (name, yearOfBirth, job) {
    this.name = name;
    this.yearOfBirth = yearOfBirth;
    this.job = job;
  };

  Person.prototype.calculateAge = function () {
    console.log(2016 - this.yearOfBirth); //26 47 68
  };

  Person.prototype.scientificName = "homo sapiens";

  var john = new Person("John", 1990, "teacher");
  var jane = new Person("Jane", 1969, "designer");
  var mark = new Person("Mark", 1948, "retired");

  john.calculateAge(); //26
  jane.calculateAge(); //47
  mark.calculateAge(); //68

  console.log(john.scientificName); //homosapiens
  console.log(jane.scientificName); //homosapiens
  console.log(mark.scientificName); //homosapiens

  console.log("(2) "); //
  /////////////////////////////
  // Lecture: Object.create

  var personProto = {
    calculateAge: function () {
      console.log(2016 - this.yearOfBirth); //26
    },
  };

  var john = Object.create(personProto);
  john.name = "John";
  john.yearOfBirth = 1990;
  john.job = "teacher";
  john.calculateAge(); //26

  var jane = Object.create(personProto, {
    name: { value: "Jane" },
    yearOfBirth: { value: 1969 },
    job: { value: "designer" },
  });
  console.log(" (3)"); //

  /////////////////////////////

  // Lecture: Primitives vs objects
  var a = 23;
  var b = a;
  a = 46;
  console.log(a); //46
  console.log(b); //23
  // Objects
  var obj3 = {
    name: "John",
    age: 26,
  };
  var obj2 = obj3;
  obj3.age = 30;
  console.log(obj3.age); //30
  console.log(obj2.age); //30
  // Functions
  var age = 27;
  var obj3 = {
    name: "Jonas",
    city: "Lisbon",
  };
  function change(a, b) {
    a = 30;
    b.city = "San Francisco";
  }

  change(age, obj3);

  console.log(age); //27
  console.log(obj3.city); //San Francisco
  ////////passing functions as argument

  var Gazibur = {
    family: [
      "Mofiz uddin",
      "Johura maya",
      "jayeda",
      "Asmina",
      "Halima",
      "Jiabur",
      "Motibur",
      "Hifjur",
      "Azizul",
      "Gazibur ",
    ],
    familyBirthYear: [
      1959,
      1967,
      1982,
      1985,
      1987,
      1986,
      1990,
      1992,
      1995,
      1999,
    ],
    familyAges: [], //This array is filled by callback function(function as an arguement) below  by Gazibur .
    pensiontime: [], //This array is filled by callback function(function as an arguement) below  by Gazibur .
    isMarried: [], //This array is filled by callback function(function as an arguement) below  by Gazibur .
    Job: "student",
  };
  // call back functions

  function AgeCalc(arr, fn) {
    let ages = Gazibur.familyAges;
    for (var i = 0; i < arr.length; i++) {
      //looping over an array(arr)
      ages.push(fn(arr[i]));
    }
    return ages;
  }

  function familyage(el) {
    var age = 2020 - el;
    return age;
  }
  var bornyear = Gazibur.familyBirthYear;
  AgeCalc(bornyear, familyage);

  function pensionyear(arr, fn) {
    var pensionAge = Gazibur.pensiontime;
    for (var i = 0; i < arr.length; i++) {
      //looping
      pensionAge.push(fn(arr[i]));
    }
    return pensionAge;
  }

  function pension(index) {
    var cal = 60 - index;
    return cal;
  }
  var isMarried = Gazibur.isMarried;

  function Married(arr, fn) {
    for (var i = 0; i < ages.length; i++) {
      isMarried.push(fn(arr[i]));
    }
  }

  function name(el) {
    if (el >= 25) {
      return true;
    } else {
      return false;
    }
  }
  var ages = Gazibur.familyAges;
  pensionyear(ages, pension);
  Married(ages, name);
  console.log(Gazibur.isMarried); //(10) [true, true, true, true, true, true, true, true, true, false]
  console.log(Gazibur.pensiontime); //(10) [-1, 7, 22, 25, 27, 26, 30, 32, 35, 39]
  console.log(ages); //(10) [61, 53, 38, 35, 33, 34, 30, 28, 25, 21]
  console.log(
    Gazibur
  ); /* {family: Array(10), familyBirthYear: Array(10), familyAges: Array(10), pensiontime: Array(10), isMarried: Array(10), …}
Job: "student"
family: (10) ["Mofiz uddin", "Johura maya", "jayeda", "Asmina", "Halima", "Jiabur", "Motibur", "Hifjur", "Azizul", "Gazibur "]
familyAges: (10) [61, 53, 38, 35, 33, 34, 30, 28, 25, 21]
familyBirthYear: (10) [1959, 1967, 1982, 1985, 1987, 1986, 1990, 1992, 1995, 1999]
isMarried: (10) [true, true, true, true, true, true, true, true, true, false]
pensiontime: (10) [-1, 7, 22, 25, 27, 26, 30, 32, 35, 39]
__proto__: Object */
  console.log(" (4)"); //

  // Lecture: The this keyword
  //console.log(this);

  calculateAge(1985);

  function calculateAge(year) {
    console.log(2016 - year);
    console.log(this);
  }

  var john = {
    name: "John",
    yearOfBirth: 1990,
    calculateAge: function () {
      console.log(this); //{name: "John", yearOfBirth: 1990, calculateAge: ƒ}
      console.log(2016 - this.yearOfBirth); //26

      function innerFunction() {
        console.log(this); //Window {parent: Window, opener: null, top: Window, length: 0, frames: Window,...
      }
      innerFunction();
    },
  };

  2016 - this.yearOfBirth; //26

  var mike = {
    name: "Mike",
    yearOfBirth: 1984,
  };

  mike.calculateAge = john.calculateAge;
  mike.calculateAge(); ////32

  console.log("(5)");

  /////////////////////////////
  // Lecture: Functions returning functions

  function interviewQuestion(job) {
    return function (name) {
      if (job === "designer") {
        console.log(
          name + ", can you please explain what UX design is?"
        ); /* What subject do you teach, John? ,
            John, can you please explain what UX design is? ,
            jane, can you please explain what UX design is? ,
            Mark, can you please explain what UX design is? ,
            */
      } else if (job === "teacher") {
        console.log(
          "What subject do you teach, " + name + "?"
        ); /* //What subject do you teach, Mark?,          What subject do you teach, Mark? */
      } else {
        console.log("Hello " + name + ", what do you do?"); //
      }
    };
  }

  interviewQuestion("teacher")("John");
  var teacherQuestion = interviewQuestion("teacher");
  var designerQuestion = interviewQuestion("designer");

  teacherQuestion("John");
  designerQuestion("John");
  designerQuestion("jane");
  designerQuestion("Mark");
  designerQuestion("Mike");
  interviewQuestion("teacher")("John");
  interviewQuestion("teacher")("Mark");

  console.log(" (6)"); //

  /////////////////////////////
  // Lecture: IIFE

  function game() {
    var score = Math.random() * 10;
    console.log(score >= 5); //false
  }
  game();

  (function () {
    var score = Math.random() * 10;
    console.log(score >= 5); //false
  })();

  //console.log(score);//error

  (function (goodLuck) {
    var score = Math.random() * 10;
    console.log(score >= 5 - goodLuck); //true
  })(5);

  //console.log(this);

  console.log(" (7)"); //

  /////////////////////////////
  // Lecture: Closures

  function retirement(retirementAge) {
    var a = " years left until retirement.";
    return function (yearOfBirth) {
      var age = 2016 - yearOfBirth;
      console.log(retirementAge - age + a); //
      /* 39 years left until retirement.
        40 years left until retirement. 
        41 years left until retirement. */
    };
  }

  var retirementUS = retirement(66);
  var retirementGermany = retirement(65);
  var retirementIceland = retirement(67);

  retirementGermany(1990);
  retirementUS(1990);
  retirementIceland(1990);

  //retirement(66)(1990);

  console.log(" (8)"); //
  /////////////////////////////
  // Lecture: Bind, call and apply

  var john = {
    name: "John",
    age: 26,
    job: "teacher",
    presentation: function (style, timeOfDay) {
      if (style === "formal") {
        console.log(
          "Good " +
            timeOfDay +
            ", Ladies and gentlemen! I'm " +
            this.name +
            ", I'm a " +
            this.job +
            " and I'm " +
            this.age +
            " years old."
        ); /* //Good morning, Ladies and gentlemen! I'm John, I'm a teacher and I'm 26 years old.
            Good afternoon, Ladies and gentlemen! I'm Emily, I'm a designer and I'm 35 years old. */ /* Good afternoon, Ladies and gentlemen! I'm Emily, I'm a designer and I'm 35 years old. */
      } else if (style === "friendly") {
        console.log(
          "Hey! What's up? I'm " +
            this.name +
            ", I'm a " +
            this.job +
            " and I'm " +
            this.age +
            " years old. Have a nice " +
            timeOfDay +
            "."
        ); /* 
            Hey! What's up? I'm Emily, I'm a designer and I'm 35 years old. Have a nice afternoon. //Hey! What's up? I'm John, I'm a teacher and I'm 26 years old. Have a nice night.
            Hey! What's up? I'm John, I'm a teacher and I'm 26 years old. Have a nice morning. */
      }
    },
  };
  var emily = {
    name: "Emily",
    age: 35,
    job: "designer",
  };

  john.presentation("formal", "morning");

  john.presentation.call(emily, "friendly", "afternoon");

  //john.presentation.apply(emily, ['friendly', 'afternoon']);

  var johnFriendly = john.presentation.bind(john, "friendly");

  johnFriendly("morning");
  johnFriendly("night");

  var emilyFormal = john.presentation.bind(emily, "formal");
  emilyFormal("afternoon");

  console.log(" (9)"); //
  /////////////////////////////////
  // Lecture: let and const

  // ES5
  var name5 = "Jane Smith";
  var age5 = 23;
  name5 = "Jane Miller";
  console.log(name5); //Jane Miller

  // ES6
  const name6 = "Jane Smith";
  let age6 = 23;
  // name6 = 'Jane Miller';
  console.log(name6); //Jane Smith

  // ES5
  function driversLicence5(passedTest) {
    if (passedTest) {
      console.log(firstName); //undefined
      var firstName = "John";
      var yearOfBirth = 1990;
    }

    console.log(
      firstName +
        ", born in " +
        yearOfBirth +
        ", is now officially allowed to drive a car."
    ); //John, born in 1990, is now officially allowed to drive a car.
  }

  driversLicence5(true);

  // ES6
  function driversLicence6(passedTest) {
    //console.log(firstName);//
    let firstName;
    const yearOfBirth = 1990;

    if (passedTest) {
      firstName = "John";
    }

    console.log(
      firstName +
        ", born in " +
        yearOfBirth +
        ", is now officially allowed to drive a car."
    ); //John, born in 1990, is now officially allowed to drive a car
  }

  driversLicence6(true);

  var i = 23;

  for (var i = 0; i < 5; i++) {
    console.log(i); //0 to 4
  }

  console.log(i); //5

  console.log("(10) "); //
  /////////////////////////////////
  // Lecture: Blocks and IIFEs

  // ES6
  {
    const a = 1;
    let b = 2;
    var c = 3;
  }

  //console.log(a + b);//
  console.log(c); //3

  // ES5
  (function () {
    var c = 3;
  })();

  //console.log(c);//

  console.log("(11) "); //
  /////////////////////////////////
  // Lecture: Strings

  let firstname1 = "John";
  let lastname1 = "Smith";
  const yearOfBirth = 1990;

  function calcAge(year) {
    return 2016 - year;
  }

  // ES5
  console.log(
    "This is " +
      firstname1 +
      " " +
      lastname1 +
      ". He was born in " +
      yearOfBirth +
      ". Today, he is " +
      calcAge(yearOfBirth) +
      " years old."
  ); //This is John Smith. He was born in 1990. Today, he is 26 years old.

  // ES6
  console.log(
    `This is ${firstname1} ${lastname1}. He was born in ${yearOfBirth}. Today, he is ${calcAge(
      yearOfBirth
    )} years old.`
  ); //This is John Smith. He was born in 1990. Today, he is 26 years old.

  const n = `${firstname1} ${lastname1}`;
  console.log(n.startsWith("j")); //false
  console.log(n.endsWith("Sm")); //false
  console.log(n.includes("oh")); //true
  console.log(`${firstname1} `.repeat(5)); //John John John John John
  console.log("(12.b)");
  //  common string methods
  var stringOne = "free code camp is the best place to learn";
  var stringTwo = "front end and back development";
  // 1. charAt();
  console.log(stringOne.charAt(1)); //r
  // charCodeAt
  console.log(stringOne.charCodeAt(1)); //114
  // concat
  console.log(stringOne.concat(stringTwo)); //free code camp is the best place to learnfront end and back development"
  // startsWith()
  console.log(stringOne.startsWith("free")); //true
  // endsWith
  console.log(stringOne.endsWith("learn")); //true
  // fromCharCode
  console.log(String.fromCharCode(114)); //r
  // includes
  console.log(stringTwo.includes("end")); //true
  // lastIndexOf
  console.log(stringTwo.lastIndexOf("end")); //6
  // match()
  console.log(stringTwo.match(/end/g)); //["end"]
  // repeat()
  console.log(stringOne.repeat(3)); //free code camp is the best place to learnfree code camp is the best place to learnfree code camp is the best place to learn
  // replace()
  console.log(stringTwo.replace(/end/g, "end")); //front end and back development
  // search()
  console.log(stringTwo.search("end")); //6
  // slice()
  console.log(stringTwo.slice(2, 4)); //on
  // split()

  console.log(stringOne.split(" ")); // ["free", "code", "camp", "is", "the", "best", "place", "to", "learn"]
  // substr()
  console.log(stringTwo.substr(2, 4)); //ont
  // substring()
  console.log(stringTwo.substring(2, 4)); //on
  // toLowerCase()
  console.log(stringTwo.toLowerCase()); //front end and back development
  // toUpperCase()
  console.log(stringTwo.toUpperCase()); //FRONT END AND BACK END DEVELOPMENT
  // trim()
  var stringThree = "Subscribe now!";
  console.log(stringThree.trim()); //Subscribe now!

  console.log(" (12)"); //

  /////////////////////////////////
  // Lecture: Arrow functions

  const years1 = [1990, 1965, 1982, 1937];

  // ES5
  var ages5 = years1.map(function (el) {
    return 2016 - el;
  });
  console.log(ages5); //(4) [26, 51, 34, 79]

  // ES6
  let ages6 = years1.map((el) => 2016 - el);
  console.log(ages6); //(4) [26, 51, 34, 79]

  ages6 = years1.map((el, index) => `Age element ${index + 1}: ${2016 - el}.`);
  console.log(ages6); //(4) ["Age element 1: 26.", "Age element 2: 51.", "Age element 3: 34.", "Age element 4: 79."]

  ages6 = years1.map((el, index) => {
    const now = new Date().getFullYear();
    const age = now - el;
    return `Age element ${index + 1}: ${age}.`;
  });
  console.log(ages6); //(4) ["Age element 1: 30.", "Age element 2: 55.", "Age element 3: 38.", "Age element 4: 83."]

  console.log("(13) "); //

  /////////////////////////////////
  // {Lecture: Arrow functions 2
  // ES5
  var box5 = {
    color: "green",
    position: 1,
    clickMe: function () {
      var self = this;
      document.querySelector(".green").addEventListener("click", function () {
        var str =
          "This is box number " + self.position + " and it is " + self.color;
        alert(str);
      });
    },
  };
  //box5.clickMe();

  // ES6
  const box6 = {
    color: "green",
    position: 1,
    clickMe: function () {
      document.querySelector(".green").addEventListener("click", () => {
        var str =
          "This is box number " + this.position + " and it is " + this.color;
        alert(str);
      });
    },
  };
  box6.clickMe();

  const box66 = {
    color: "green",
    position: 1,
    clickMe: () => {
      document.querySelector(".green").addEventListener("click", () => {
        var str =
          "This is box number " + this.position + " and it is " + this.color;
        alert(str);
      });
    },
  };
  box66.clickMe();

  function Person(name) {
    this.name = name;
  }

  // ES5
  Person.prototype.myFriends5 = function (friends) {
    var arr = friends.map(
      function (el) {
        return this.name + " is friends with " + el;
      }.bind(this)
    );

    console.log(arr); //(3) ["John is friends with Bob", "John is friends with Jane", "John is friends with Mark"]
  };

  var friends = ["Bob", "Jane", "Mark"];
  new Person("John").myFriends5(friends);

  // ES6
  Person.prototype.myFriends6 = function (friends) {
    var arr = friends.map((el) => `${this.name} is friends with ${el}`);

    console.log(arr); //(3) ["Mike is friends with Bob", "Mike is friends with Jane", "Mike is friends with Mark"]
  };

  new Person("Mike").myFriends6(friends);
  /////////////////////////////////
  // Lecture: Destructuring

  // ES5
  var Gazi = ["Gaziburr", 26];
  //var name = Gazi[0];
  //var age = Gazi[1];
  // ES6
  const [Name, Age] = ["Gaziburr", 26];
  console.log(Name); //Gaziburr
  console.log(Age); //26
  const OBJ = {
    FirstName: "Gaziburr",
    LastName: "Rahman",
  };
  const { FirstName, LastName } = OBJ;
  console.log(FirstName); //Gaziburr
  console.log(LastName); //Rahman
  const { FirstName: A, LastName: B } = OBJ;
  console.log(A); //Gaziburr
  console.log(B); // Rahman
  function calcAgeRetirement(year) {
    const Age = new Date().getFullYear() - year;
    return [Age, 65 - Age];
  }
  const [age2, Retirement] = calcAgeRetirement(1990);
  console.log(age2); //30
  console.log(Retirement); //35

  console.log(" (14)"); //

  /////////////////////////////////
  // Lecture: Arrays

  //This code is executed in HTML file(body).

  const boxes = document.querySelectorAll(".box");

  //ES5
  var boxesArr5 = Array.prototype.slice.call(boxes);
  boxesArr5.forEach(function (cur) {
    cur.style.backgroundColor = "dodgerblue";
  });

  //ES6
  const boxesArr6 = Array.from(boxes);
  Array.from(boxes).forEach(
    (cur) => (cur.style.backgroundColor = "dodgerblue")
  );

  //ES5
  for (var i = 0; i < boxesArr5.length; i++) {
    if (boxesArr5[i].className === "box blue") {
      continue;
    }

    boxesArr5[i].textContent = "I changed to blue!";
  }

  //ES6
  for (const cur of boxesArr6) {
    if (cur.className.includes("blue")) {
      continue;
    }
    cur.textContent = "I changed to blue!";
  }

  //ES5
  var ages = [12, 17, 8, 21, 14, 11];

  var full = ages.map(function (cur) {
    return cur >= 18;
  });
  console.log(full); //(6) [false, false, false, true, false, false]

  console.log(full.indexOf(true)); //3
  console.log(ages[full.indexOf(true)]); //21

  //ES6
  console.log(ages.findIndex((cur) => cur >= 18)); //3
  console.log(ages.find((cur) => cur >= 18)); //21
  console.log(" (15)"); //
  /////////////////////////////////
  // Lecture: Spread operator

  function addFourAges(a, b, c, d) {
    return a + b + c + d;
  }

  var sum1 = addFourAges(18, 30, 12, 21);
  console.log(sum1); //81

  //ES5
  var ages = [18, 30, 12, 21];
  var sum2 = addFourAges.apply(null, ages);
  console.log(sum2); //81

  //ES6
  const sum3 = addFourAges(...ages);
  console.log(sum3); //81

  const familySmith = ["John", "Jane", "Mark"];
  const familyMiller = ["Mary", "Bob", "Ann"];
  const bigFamily = [...familySmith, "Lily", ...familyMiller];
  console.log(bigFamily); //(7) ["John", "Jane", "Mark", "Lily", "Mary", "Bob", "Ann"]

  const h = document.querySelector("h1");
  const boxes1 = document.querySelectorAll(".box");
  const all = [h, ...boxes1];

  // Array.from(all).forEach(cur => cur.style.color = 'purple');

  console.log(" (16)");
  /////////////////////////////////
  // Lecture: Rest parameters

  //ES5
  function isFullAge5() {
    //console.log(arguments);//
    var argsArr = Array.prototype.slice.call(arguments);

    argsArr.forEach(function (cur) {
      console.log(2016 - cur >= 18); //
    });
  }

  isFullAge5(1990, 1999, 1965);
  isFullAge5(1990, 1999, 1965, 2016, 1987);

  //ES6
  function isFullAge6(...years) {
    years.forEach((cur) => console.log(2016 - cur >= 18)); //
  }

  isFullAge6(1990, 1999, 1965, 2016, 1987);

  //ES5
  function isFullAge5(limit) {
    var argsArr = Array.prototype.slice.call(arguments, 1);

    argsArr.forEach(function (cur) {
      console.log(2016 - cur >= limit); //false
    });
  }

  //isFullAge5(16, 1990, 1999, 1965);
  isFullAge5(1990, 1999, 1965, 2016, 1987);

  //ES6
  function isFullAge6(limit, ...years) {
    years.forEach((cur) => console.log(2016 - cur >= limit)); //false true false true
  }

  isFullAge6(16, 1990, 1999, 1965, 2016, 1987);

  console.log("(17) "); //
  /////////////////////////////////
  // Lecture: Default parameters

  // ES5
  function SmithPerson(firstName2, yearOfBirth, lastName, nationality) {
    lastName === undefined ? (lastName = "Smith") : (lastName = lastName);
    nationality === undefined
      ? (nationality = "american")
      : (nationality = nationality);

    this.firstName2 = firstName2;
    this.lastName = lastName;
    this.yearOfBirth = yearOfBirth;
    this.nationality = nationality;
  }

  //ES6
  function SmithPerson(
    firstName2,
    yearOfBirth,
    lastName2 = "Smith",
    nationality = "american"
  ) {
    this.firstName2 = firstName2;
    this.lastName2 = lastName2;
    this.yearOfBirth = yearOfBirth;
    this.nationality = nationality;
  }

  var john = new SmithPerson("John", 1990);
  var emily = new SmithPerson("Emily", 1983, "Diaz", "spanish");

  console.log(" (18)");
  // Lecture: Maps

  const question = new Map();
  question.set(
    "question",
    "What is the official name of the latest major JavaScript version?"
  );
  question.set(1, "ES5");
  question.set(2, "ES6");
  question.set(3, "ES2015");
  question.set(4, "ES7");
  question.set("correct", 3);
  question.set(true, "Correct answer :D");
  question.set(false, "Wrong, please try again!");

  console.log(question.get("question")); //What is the official name of the latest major JavaScript version?
  //console.log(question.size);//

  if (question.has(4)) {
    //question.delete(4);
    //console.log('Answer 4 is here')//
  }

  //question.clear();

  //question.forEach((value, key) => console.log(`This is ${key}, and it's set to ${value}`));//

  for (let [key, value] of question.entries()) {
    if (typeof key === "number") {
      console.log(`Answer ${key}: ${value}`); //Answer 1: ES5    Answer 2: ES6    Answer 3: ES2015    Answer 4: ES7
    }
  }

  const ans = parseInt(console.log("Write the correct answer"));
  console.log(question.get(ans === question.get("correct"))); //Wrong, please try again!

  console.log(" (19)"); //

  /////////////////////////////////
  // Lecture: Classes

  //ES5
  var Person5 = function (name, yearOfBirth, job) {
    this.name = name;
    this.yearOfBirth = yearOfBirth;
    this.job = job;
  };

  Person5.prototype.calculateAge = function () {
    var age = new Date().getFullYear - this.yearOfBirth;
    console.log(age); //
  };

  var john5 = new Person5("John", 1990, "teacher");

  //ES6
  class Person6 {
    constructor(name, yearOfBirth, job) {
      this.name = name;
      this.yearOfBirth = yearOfBirth;
      this.job = job;
    }

    calculateAge() {
      var age = new Date().getFullYear - this.yearOfBirth;
      console.log(age); //
    }

    static greeting() {
      console.log("Hey there!"); //Hey there!
    }
  }

  const john6 = new Person6("John", 1990, "teacher");

  Person6.greeting();

  console.log(" (20)"); //

  /////////////////////////////////
  // Lecture: Classes and subclasses

  //ES5
  var Person5 = function (name, yearOfBirth, job) {
    this.name = name;
    this.yearOfBirth = yearOfBirth;
    this.job = job;
  };

  Person5.prototype.calculateAge = function () {
    var age = new Date().getFullYear() - this.yearOfBirth;
    console.log(age); //30
  };

  var Athlete5 = function (name, yearOfBirth, job, olymicGames, medals) {
    Person5.call(this, name, yearOfBirth, job);
    this.olymicGames = olymicGames;
    this.medals = medals;
  };

  Athlete5.prototype = Object.create(Person5.prototype);

  Athlete5.prototype.wonMedal = function () {
    this.medals++;
    console.log(this.medals); //11
  };

  var johnAthlete5 = new Athlete5("John", 1990, "swimmer", 3, 10);

  johnAthlete5.calculateAge();
  johnAthlete5.wonMedal();

  //ES6
  class person7 {
    constructor(name, yearOfBirth, job) {
      this.name = name;
      this.yearOfBirth = yearOfBirth;
      this.job = job;
    }

    calculateAge() {
      var age = new Date().getFullYear() - this.yearOfBirth;
      console.log(age); //30
    }
  }

  class Athlete6 extends person7 {
    constructor(name, yearOfBirth, job, olympicGames, medals) {
      super(name, yearOfBirth, job);
      this.olympicGames = olympicGames;
      this.medals = medals;
    }

    wonMedal() {
      this.medals++;
      console.log(this.medals); //11
    }
  }

  const johnAthlete6 = new Athlete6("John", 1990, "swimmer", 3, 10);

  johnAthlete6.wonMedal();
  johnAthlete6.calculateAge();

  console.log(" (21)"); //

  /////////////////////////////////
  // CODING CHALLENGE

  /*

Suppose that you're working in a small town administration, and you're in charge of two town elements:
1. Parks
2. Streets

It's a very small town, so right now there are only 3 parks and 4 streets. All parks and streets have a name and a build year.

At an end-of-year meeting, your boss wants a final report with the following:
1. Tree density of each park in the town (forumla: number of trees/park area)
2. Average age of each town's park (forumla: sum of all ages/number of parks)
3. The name of the park that has more than 1000 trees
4. Total and average length of the town's streets
5. Size classification of all streets: tiny/small/normal/big/huge. If the size is unknown, the default is normal

All the report data should be printed to the console.

HINT: Use some of the ES6 features: classes, subclasses, template strings, default parameters, maps, arrow functions, destructuring, etc.

*/

  class Element {
    constructor(name, buildYear) {
      this.name = name;
      this.buildYear = buildYear;
    }
  }

  class Park extends Element {
    constructor(name, buildYear, area, numTrees) {
      super(name, buildYear);
      this.area = area; //km2
      this.numTrees = numTrees;
    }

    treeDensity() {
      const density = this.numTrees / this.area;
      console.log(
        `${this.name} has a tree density of ${density} trees per square km.`
      ); /* //Green Park has a tree density of 1075 trees per square km.
        National Park has a tree density of 1221.0344827586207 trees per square km.
        Oak Park has a tree density of 2372.5 trees per square km. */
    }
  }

  class Street extends Element {
    constructor(name, buildYear, length, size = 3) {
      super(name, buildYear);
      this.length = length;
      this.size = size;
    }

    classifyStreet() {
      const classification = new Map();
      classification.set(1, "tiny");
      classification.set(2, "small");
      classification.set(3, "normal");
      classification.set(4, "big");
      classification.set(5, "huge");
      console.log(
        `${this.name}, build in ${this.buildYear}, is a ${classification.get(
          this.size
        )} street.`
      ); /* Ocean Avenue, build in 1999, is a big street.
        1718 Evergreen Street, build in 2008, is a small street.
        1718 4th Street, build in 2015, is a normal street.
        1718 Sunset Boulevard, build in 1982, is a huge street. */
    }
  }

  const allParks = [
    new Park("Green Park", 1987, 0.2, 215),
    new Park("National Park", 1894, 2.9, 3541),
    new Park("Oak Park", 1953, 0.4, 949),
  ];

  const allStreets = [
    new Street("Ocean Avenue", 1999, 1.1, 4),
    new Street("Evergreen Street", 2008, 2.7, 2),
    new Street("4th Street", 2015, 0.8),
    new Street("Sunset Boulevard", 1982, 2.5, 5),
  ];

  function calc(arr) {
    const sum = arr.reduce((prev, cur, index) => prev + cur, 0);

    return [sum, sum / arr.length];
  }

  function reportParks(p) {
    console.log("-----PARKS REPORT-----"); //-----PARKS REPORT-----

    // Density
    p.forEach((el) => el.treeDensity());

    // Average age
    const ages = p.map((el) => new Date().getFullYear() - el.buildYear);
    const [totalAge, avgAge] = calc(ages);
    console.log(`Our ${p.length} parks have an average of ${avgAge} years.`); //Our 3 parks have an average of 75.33333333333333 years.

    // Which park has more than 1000 trees
    const i = p.map((el) => el.numTrees).findIndex((el) => el >= 1000);
    console.log(`${p[i].name} has more than 1000 trees.`); //National Park has more than 1000 trees.
  }

  function reportStreets(s) {
    console.log("-----STREETS REPORT-----"); //-----STREETS REPORT-----

    //Total and average length of the town's streets
    const [totalLength, avgLength] = calc(s.map((el) => el.length));
    console.log(
      `Our ${s.length} streets have a total length of ${totalLength} km, with an average of ${avgLength} km.`
    ); //Our 4 streets have a total length of 7.1000000000000005 km, with an average of 1.7750000000000001 km.

    // CLassify sizes
    s.forEach((el) => el.classifyStreet());
  }

  reportParks(allParks);
  reportStreets(allStreets);

  console.log("(22)");
  ///* Variables and datatypes */

  var firstName = "John";
  console.log(firstName); //John//

  var lastName = "Smith";
  var age = 28;

  var fullAge = true;
  console.log(fullAge); //true//

  var job;
  console.log(job); //undefined//

  job = "Teacher";
  console.log(job); //Teacher//

  // Variable naming rules
  var _3years = 3;
  var johnMark = "John and MArk";
  // var if = 23;

  console.log("(22) ");
  /*****************************
   * Variable mutation and type coercion
   */

  var firstName = "John";
  var age = 28;

  // Type coercion
  console.log(firstName + " " + age); //John 28//

  var job, isMarried;
  job = "teacher";
  isMarried = false;

  console.log(
    firstName +
      " is a " +
      age +
      " year old " +
      job +
      ". Is he married? " +
      isMarried
  ); //John is a 28 year old teacher. Is he married? false//

  // Variable mutation
  age = "twenty eight";
  job = "driver";

  console.log(
    firstName +
      " is a " +
      age +
      " year old " +
      job +
      ". Is he married? " +
      isMarried
  );

  var lastName = console.log("What is his last Name?");
  console.log(firstName + " " + lastName); //John //

  console.log(" (23)");
  /*****************************
   * Basic operators
   */

  var year, yearJohn, yearMark;
  now = 2018;
  ageJohn = 28;
  ageMark = 33;

  // Math operators
  yearJohn = now - ageJohn;
  yeahMark = now - ageMark;

  console.log(yearJohn); //1990//

  console.log(now + 2); //2020//
  console.log(now * 2); ////4036
  console.log(now / 10); //201.8

  // Logical operators
  var johnOlder = ageJohn < ageMark;
  console.log(johnOlder); //true

  // typeof operator
  console.log(typeof johnOlder); //boolean
  console.log(typeof ageJohn); //number
  console.log(typeof "Mark is older tha John"); //string
  var x;
  console.log(typeof x); //undefined

  console.log(" (24)"); //
  /*****************************
   * Operator precedence
   */

  var now = 2018;
  var yearJohn = 1989;
  var fullAge = 18;

  // Multiple operators
  var isFullAge = now - yearJohn >= fullAge; // true
  console.log(isFullAge); //true

  // Grouping
  var ageJohn = now - yearJohn;
  var ageMark = 35;
  var average = (ageJohn + ageMark) / 2;
  console.log(average); //32

  // Multiple assignments
  var x, y;
  x = y = (3 + 5) * 4 - 6; // 8 * 4 - 6 // 32 - 6 // 26
  console.log(x, y); //26 26

  // More operators
  x *= 2;
  console.log(x); //52
  x += 10;
  console.log(x); //62
  x--;
  console.log(x); //61

  console.log(" (25)"); //

  /*****************************
   * If / else statements
   */

  var firstName = "John";
  var civilStatus = "single";

  if (civilStatus === "married") {
    console.log(firstName + " is married!"); //
  } else {
    console.log(firstName + " will hopefully marry soon :)"); ////John will hopefully marry soon :)
  }

  var isMarried = true;
  if (isMarried) {
    console.log(firstName + " is married!"); //John is married!
  } else {
    console.log(firstName + " will hopefully marry soon :)"); //
  }

  var massMark = 78; // kg
  var heightMark = 1.69; // meters

  var massJohn = 92;
  var heightJohn = 1.95;

  var BMIMark = massMark / (heightMark * heightMark);
  var BMIJohn = massJohn / (heightJohn * heightJohn);

  if (BMIMark > BMIJohn) {
    console.log("Mark's BMI is higher than John's."); //Mark's BMI is higher than John's.
  } else {
    console.log("John's BMI is higher than Marks's."); //
  }

  console.log(" (26)"); //

  /*****************************
   * Boolean logic
   */

  var firstName = "John";
  var age = 20;

  if (age < 13) {
    console.log(firstName + " is a boy."); //
  } else if (age >= 13 && age < 20) {
    console.log(firstName + " is a teenager."); //
  } else if (age >= 20 && age < 30) {
    console.log(firstName + " is a young man."); //John is a young man.
  } else {
    console.log(firstName + " is a man."); //
  }

  console.log(" (27)"); //

  /*****************************
   * The Ternary Operator and Switch Statements
   */

  var firstName = "John";
  var age = 14;
  // Ternary operator
  age >= 18
    ? console.log(firstName + " drinks beer.")
    : console.log(firstName + " drinks juice."); //John drinks juice.

  var drink = age >= 18 ? "beer" : "juice";
  console.log(drink); //juice

  if (age >= 18) {
    var drink = "beer";
  } else {
    var drink = "juice";
  }

  // Switch statement
  var job = "instructor";
  switch (job) {
    case "teacher":
    case "instructor":
      console.log(firstName + " teaches kids how to code."); //John teaches kids how to code.
      break;
    case "driver":
      console.log(firstName + " drives an uber in Lisbon."); //
      break;
    case "designer":
      console.log(firstName + " designs beautiful websites."); //
      break;
    default:
      console.log(firstName + " does something else."); //
  }

  age = 56;
  switch (true) {
    case age < 13:
      console.log(firstName + " is a boy."); //
      break;
    case age >= 13 && age < 20:
      console.log(firstName + " is a teenager."); //
      break;
    case age >= 20 && age < 30:
      console.log(firstName + " is a young man."); //
      break;
    default:
      console.log(firstName + " is a man."); //John is a man.
  }

  console.log(" (28)"); //

  /*****************************
   * Truthy and Falsy values and equality operators
   */

  // falsy values: undefined, null, 0, '', NaN
  // truthy values: NOT falsy values

  var height;

  height = 23;

  if (height || height === 0) {
    console.log("Variable is defined"); //Variable is defined
  } else {
    console.log("Variable has NOT been defined"); //
  }

  // Equality operators
  if (height === "23") {
    console.log("The == operator does type coercion!"); //
  }

  console.log(" (29)"); //
  /*****************************
   * Functions
   */

  function calculateAge(birthYear) {
    return 2018 - birthYear;
  }

  var ageJohn = calculateAge(1990);
  var ageMike = calculateAge(1948);
  var ageJane = calculateAge(1969);
  console.log(ageJohn, ageMike, ageJane); //26 68 47

  function yearsUntilRetirement(year, firstName) {
    var age = calculateAge(year);
    var retirement = 65 - age;

    if (retirement > 0) {
      console.log(firstName + " retires in " + retirement + " years."); //John retires in 39 years.
    } else {
      console.log(firstName + " is already retired."); //Mike is already retired.
    }
  }

  yearsUntilRetirement(1990, "John"); //  John retires in 39 years.
  yearsUntilRetirement(1948, "Mike"); // Mike is already retired.
  yearsUntilRetirement(1969, "Jane"); // Jane retires in 18 years.

  console.log(" (30)"); //
  /*****************************
   * Function Statements and Expressions
   */

  // Function declaration
  // function whatDoYouDo(job, firstName) {}

  // Function expression
  var whatDoYouDo = function (job, firstName) {
    switch (job) {
      case "teacher":
        return firstName + " teaches kids how to code";
      case "driver":
        return firstName + " drives a cab in Lisbon.";
      case "designer":
        return firstName + " designs beautiful websites";
      default:
        return firstName + " does something else";
    }
  };

  console.log(whatDoYouDo("teacher", "John")); //John teaches kids how to code
  console.log(whatDoYouDo("designer", "Jane")); //Jane designs beautiful websites
  console.log(whatDoYouDo("retired", "Mark")); //Mark does something else

  console.log(" (31)"); //

  /*****************************
   * Arrays
   */

  // Initialize new array
  var names = ["John", "Mark", "Jane"];
  var years = new Array(1990, 1969, 1948);

  console.log(names[2]); //Jane
  console.log(names.length); //3

  // Mutate array data
  names[1] = "Ben";
  names[names.length] = "Mary";
  console.log(names); //Array(4)0: "John"1: "Ben"2: "Jane"3: "Mary"length: 4__proto__: Array(0)

  // Different data types
  var john = ["John", "Smith", 1990, "designer", false];

  john.push("blue");
  john.unshift("Mr.");
  console.log(john); //Array(4)0: "John"1: "Smith"2: 19903: "designer"length: 4__proto__: Array(0)

  john.pop();
  john.pop();
  john.shift();
  console.log(john); //Array(4)0: "John"1: "Smith"2: 19903: "designer"length: 4__proto__: Array(0)

  console.log(john.indexOf(23)); //-1

  var isDesigner =
    john.indexOf("designer") === -1
      ? "John is NOT a designer"
      : "John IS a designer";
  console.log(isDesigner); //John IS a designer

  console.log("(32)");
  //function example:------
  function tipCalculator(bill) {
    var percentage;
    if (bill < 50) {
      percentage = 0.2;
    } else if (bill >= 50 && bill < 200) {
      percentage = 0.15;
    } else {
      percentage = 0.1;
    }
    return percentage * bill;
  }

  var bills = [124, 48, 268];
  var tips = [
    tipCalculator(bills[0]),
    tipCalculator(bills[1]),
    tipCalculator(bills[2]),
  ];

  var finalValues = [
    bills[0] + tips[0],
    bills[1] + tips[1],
    bills[2] + tips[2],
  ];

  console.log(tips, finalValues); //Array(3)0: 18.5999999999999981: 9.6000000000000012: 26.8length: 3__proto__: Array(0) Array(3)0: 142.61: 57.62: 294.8length: 3__proto__: Array(0)

  console.log("(32)");
  /* SOME  POPULAR USEFULL ARRAY METHODS :--- */
  var arr = ["a", "b", "c", "d"];
  // push()
  arr.push("e");
  console.log(arr); //(5) ["a", "b", "c", "d", "e"]
  var arr2 = ["g", "q"];
  // concat()
  console.log(arr.concat(arr2)); //(7) ["a", "b", "c", "d", "e", "g", "q"]
  // join()
  console.log(arr.join("!")); //a!b!c!d!e
  console.log(arr); //(5) ["a", "b", "c", "d", "e"]
  // reverse()
  console.log(arr.reverse()); //(5) ["e", "d", "c", "b", "a"]
  console.log(arr); //(5) ["e", "d", "c", "b", "a"]
  // shift()
  console.log(arr.shift()); //e
  console.log(arr); //(4) ["d", "c", "b", "a"]
  // unshift()
  console.log(arr.unshift("p")); //5
  console.log(arr); //(5) ["p", "d", "c", "b", "a"]
  // slice()

  // Object literal
  var john = {
    firstName: "John",
    lastName: "Smith",
    birthYear: 1990,
    family: ["Jane", "Mark", "Bob", "Emily"],
    job: "teacher",
    isMarried: false,
  };

  console.log(john.firstName); //John
  console.log(john["lastName"]); //Smith
  var x = "birthYear";
  console.log(john[x]); //1990

  john.job = "designer";
  john["isMarried"] = true;
  console.log(
    john
  ); /* Object
firstName: "John"
lastName: "Smith"
birthYear: 1990
family: (4) ["Jane", "Mark", "Bob", "Emily"]
job: "designer"
isMarried: true
__proto__: Object */

  // new Object syntax
  var jane = new Object();
  jane.firstName = "Jane";
  jane.birthYear = 1969;
  jane["lastName"] = "Smith";
  console.log(jane); //{firstName: "Jane", birthYear: 1969, lastName: "Smith"}

  console.log(" "); //

  /*****************************
   * Objects and methods
   */

  var john = {
    firstName: "John",
    lastName: "Smith",
    birthYear: 1992,
    family: ["Jane", "Mark", "Bob", "Emily"],
    job: "teacher",
    isMarried: false,
    calcAge: function () {
      this.age = 2018 - this.birthYear;
    },
  };

  john.calcAge();
  console.log(john); //{firstName: "John", lastName: "Smith", birthYear: 1992, family: Array(4), job: "teacher", …}firstName: "John"lastName: "Smith"birthYear: 1992family: (4) ["Jane", "Mark", "Bob", "Emily"]job: "teacher"isMarried: falsecalcAge: ƒ ()age: 26__proto__: Object

  /*****************************
   * Loops and iteration
   */

  // for loop
  for (var i = 1; i <= 10; i += 2) {
    console.log(i); //1 to 19
  }
  console.log(" "); //
  // i = 0, 0 < 10 true, log i to console, i++//
  // i = 1, 1 < 10 true, log i to the console, i++//
  //...
  // i = 9, 9 < 10 true, log i to the console, i++//
  // i = 10, 10 < 10 FALSE, exit the loop!

  var john = ["John", "Smith", 1990, "designer", false, "blue"];
  for (var i = 0; i < john.length; i++) {
    console.log(john[i]); //John Smith 1990 designer false blue
  }
  console.log(" "); //
  // While loop
  var i = 0;
  while (i < john.length) {
    console.log(john[i]); //'John Smith 1990 designer false blue
    i++;
  }
  console.log(" "); //

  // continue and break statements
  var john = ["John", "Smith", 1990, "designer", false, "blue"];

  for (var i = 0; i < john.length; i++) {
    if (typeof john[i] !== "string") continue;
    console.log(john[i]); //John Smith  designer   blue
  }
  console.log(" "); //
  for (var i = 0; i < john.length; i++) {
    if (typeof john[i] !== "string") break;
    console.log(john[i]); //John Smith
  }
  console.log(" "); //
  // Looping backwards
  for (var i = john.length - 1; i >= 0; i--) {
    console.log(john[i]); // blue false designer 1990 Smith John
  }

  console.log(" "); //

  // // EXAMINE THE DOCUMENT OBJECT

  console.dir(document); //#document
  console.log(document.domain); //127.0.0.1
  console.log(document.URL); //http://127.0.0.1:5500/a%20basics/index.html
  console.log(document.title); //Item Lister
  document.title = 123;
  console.log(document.doctype); //<!DOCTYPE html>
  console.log(document.head); //all elements inside body head tag
  console.log(document.body); //all elements inside body tag
  console.log(document.all); //all elements
  console.log(document.all[10]); //11th elements in all elements
  document.all[10].textContent = "Hello";
  console.log(document.forms[0]);
  console.log(document.links);
  console.log(document.images);

  // // GETELEMENTBYID
  console.log(document.getElementById("header-title"));
  var headerTitle = document.getElementById("header-title");
  var header = document.getElementById("main-header");
  console.log(headerTitle);
  headerTitle.textContent = "Hello";
  headerTitle.innerText = "Goodbye";
  console.log(headerTitle.innerText);
  headerTitle.innerHTML = "<h3>Hello</h3>";
  header.style.borderBottom = "solid 3px #000";

  // // GETELEMENTSBYCLASSNAME //
  var items = document.getElementsByClassName("list-group-item");
  console.log(items); //HTMLCollection(4) [li.list-group-item, li.list-group-item, li.list-group-item, li.list-group-item]
  console.log(items[1]);
  items[1].textContent = "Hello 2";
  items[1].style.fontWeight = "bold";
  items[1].style.backgroundColor = "yellow";

  // // Gives error
  //items.style.backgroundColor = '#f4f4f4';

  for (var i = 0; i < items.length; i++) {
    items[i].style.backgroundColor = "#f4f4f4";
  }

  // GETELEMENTSBYTAGNAME //
  var li = document.getElementsByTagName("li");
  console.log(li); //HTMLCollection(4) [li.list-group-item, li.list-group-item, li.list-group-item, li.list-group-item]0: li.list-group-item1: li.list-group-item2: li.list-group-item3: li.list-group-itemlength: 4__proto__: HTMLCollection

  console.log(li[1]);
  li[1].textContent = "Hello 2";
  li[1].style.fontWeight = "bold";
  li[1].style.backgroundColor = "yellow";

  // // Gives error
  //items.style.backgroundColor = '#f4f4f4';

  for (var i = 0; i < li.length; i++) {
    li[i].style.backgroundColor = "#f4f4f4";
  }

  // QUERYSELECTOR //
  var header = document.querySelector("#main-header");
  header.style.borderBottom = "solid 4px #ccc";

  var input = document.querySelector("input");
  input.value = "Hello World";

  var submit = document.querySelector('input[type="submit"]');
  submit.value = "SEND";

  var item = document.querySelector(".list-group-item");
  item.style.color = "red";

  var lastItem = document.querySelector(".list-group-item:last-child");
  lastItem.style.color = "blue";

  var secondItem = document.querySelector(".list-group-item:nth-child(2)");
  secondItem.style.color = "coral";

  // // QUERYSELECTORALL //
  var titles = document.querySelectorAll(".title");

  console.log(titles);
  titles[0].textContent = "Hello";

  var odd = document.querySelectorAll("li:nth-child(odd)");
  var even = document.querySelectorAll("li:nth-child(even)");

  for (var i = 0; i < odd.length; i++) {
    odd[i].style.backgroundColor = "#f4f4f4";
    even[i].style.backgroundColor = "#ccc";
  }

  // // TRAVERSING THE DOM
  var itemList = document.querySelector("#items");
  // parentNode

  console.log(itemList.lastChild);
  // lastElementChild
  console.log(itemList.lastElementChild);
  itemList.lastElementChild.textContent = "Hello 4";

  // nextSibling
  console.log(itemList.nextSibling);
  // nextElementSibling
  console.log(itemList.nextElementSibling);

  // previousSibling
  console.log(itemList.previousSibling);
  // previousElementSibling
  itemList.previousElementSibling.textContent =
    "MY name is gazibur rahman ha ha ha ";
  console.log(itemList.previousElementSibling);

  // // createElement

  // Create a div
  var newDiv = document.createElement("div");

  // Add class
  newDiv.className = "hello";

  // Add id
  newDiv.id = "hello1";

  // Add attr
  newDiv.setAttribute("title", "Hello Div");
  console.log(newDiv.attributes);
  // Create text node
  var newDivText = document.createTextNode("Hello World");

  // Add text to div
  newDiv.appendChild(newDivText);

  var container = document.querySelector("header .container");
  var h1 = document.querySelector("header h1");

  console.log(newDiv);

  newDiv.style.fontSize = "30px";

  container.insertBefore(newDiv, h1);

  // // EVENTS //

  // var button = document.getElementById('button').addEventListener('click', buttonClick);

  function buttonClick(e) {
    console.log("Button clicked");
    document.getElementById("header-title").textContent = "Changed";
    document.querySelector("#main").style.backgroundColor = "#f4f4f4";
    console.log(e);

    console.log(e.target);
    console.log(e.target.id);
    console.log(e.target.className);
    console.log(e.target.classList);
    var output = document.getElementById("output");
    output.innerHTML = "<h3>" + e.target.id + "</h3>";

    console.log(e.type);

    console.log(e.clientX);
    console.log(e.clientY);

    console.log(e.offsetX);
    console.log(e.offsetY);

    console.log(e.altKey);
    console.log(e.ctrlKey);
    console.log(e.shiftKey);
  }

  var button = document.getElementById("button");
  var box = document.getElementById("box");

  button.addEventListener("click", runEvent);
  button.addEventListener("dblclick", runEvent);
  button.addEventListener("mousedown", runEvent);
  button.addEventListener("mouseup", runEvent);

  box.addEventListener("mouseenter", runEvent);
  box.addEventListener("mouseleave", runEvent);

  box.addEventListener("mouseover", runEvent);
  box.addEventListener("mouseout", runEvent);

  box.addEventListener("mousemove", runEvent);

  var itemInput = document.querySelector('input[type="text"]');
  var form = document.querySelector("form");
  var select = document.querySelector("select");

  itemInput.addEventListener("keydown", runEvent);
  itemInput.addEventListener("keyup", runEvent);
  itemInput.addEventListener("keypress", runEvent);

  itemInput.addEventListener("focus", runEvent);
  itemInput.addEventListener("blur", runEvent);

  itemInput.addEventListener("cut", runEvent);
  itemInput.addEventListener("paste", runEvent);

  itemInput.addEventListener("input", runEvent);

  select.addEventListener("change", runEvent);
  select.addEventListener("input", runEvent);

  form.addEventListener("submit", runEvent);

  function runEvent(e) {
    e.preventDefault();
    console.log("EVENT TYPE: " + e.type);

    console.log(e.target.value);
    document.getElementById("output").innerHTML =
      "<h3>" + e.target.value + "</h3>";

    output.innerHTML =
      "<h3>MouseX: " + e.offsetX + " </h3><h3>MouseY: " + e.offsetY + "</h3>";

    document.body.style.backgroundColor =
      "rgb(" + e.offsetX + "," + e.offsetY + ", 40)";
  }
};
