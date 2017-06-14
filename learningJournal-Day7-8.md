Ref. http://htmlandcssbook.com/

Here's what I learned, thus far...

  **Ref. Course Books:

    "HTML & CSS: Designing and Building Web Sites," by Jon Ducket
    "JavaScript & jQuery: Interactive Front-End Development," by Jon Ducket

                      - ISBN-13: 978-1118907443
                      - ISBN-10: 1118907442

            - ~/supercodingninja/HTML and CSS design and build websites.pdf
            - ~/supercodingninja/javascript.pdf

  The more simple you can keep your CSS, the better it is; and remember to Control Flow.**

***Week 2***


***Code 201: Day 7***
- use Google Fonts https://fonts.google.com/
- before you write code, start out by sketching what you need.  Once you have a plan, you can start out by building code to that plan.
- the more that you can break down problem, the better it's going to be.

'use strict';

**Objects**
var AaaronLiteral = {
  firstName: 'Aaron',
  lastInital: 'M',
  hasBeard: true,
  class: '201d23',
  faveNumber: 7,
  isleetHaxx0r: true,
  introduction: function() {
    console.log('Hi, my name is ' + this.firstName + ' and my favorite number is ' + this.firstName + this.lastInital + this.hasBeard + this.faveNumber)
  }
}

**Object Constructor Function**
var mahClass = [];

function Student(firstName) {
  this.firstName = 'firstName';
  this.lastInital = 'lastInitial';
  this.hasBeard = hasBeard;
  this.class = '201d23';
  this.faveNumber = 7;
  this.isleetHaxx0r = true;
  this.introduction= function() {
    console.log('Hi, my name is ' + this.firstName + ' and my favorite number is ' + this.faveNumber);
  }
  mahClass.push(this);
}
    var aaronConstructor = new Student('Aaron','M', true, 7);
    var chaiConstructor = new Student('Chai', 'N', true, 7);
    var katherineConstructor = new Student('Katherine', 'H', false, 9);

    *If you want to check your arrays; then, you can just do: console.table.*

      **THERE'S ANOTHER WAY TO GO ABOUT THIS**
      Student.prototype.beardness = function() {
        console.log('Does ' + this.firstname + ' have a luxurious and thick beard? ' + this.hasBeard);
      };

      Student.'weasels' = 'WEASELS!!!! RUN!!!!' // IS NOT INHERENT BY INSTANCES.

**ALLOW YOUR CONSTRUCTOR FUNCTION TO BE SIMPLE; and do not lead any of your variables with capitalization, unless it is an Object+Constructor.**

***CODE 201: DAY 8***
CODE STRUCTURE: the way you're doing the job matters by the one who is signing your paycheck.  The way that you do your code matters:
- set up data (declare global variables, DOM elements, constructor(s) for data to properties, functions to methOds)
- define behaviors (functions
  ; remember to set up local var; define function logic).
-executing code (function calls)
- event listeners

prototype is the inheritance: the property upon the Constructor.

  **Remember**
    *Object Constructor
      - properties
    *Prototype Methods
      -ex. customers per hour
      -ex. cookies sold  per hours (requires customers per hour)
    *Render to Domain

    *Remember*
    Math.floor(Math.random() * (max min + 1))

***Remember Table Structures***
<table>
  <tbody>
    <thead>
      Value
      <tr>
        <td>
          Value
        </td>
      </tr>
    </thead>
    </tbody>
</table>

***EVENT LISTENERS***
JS BOOK PGS. 254-262
  -Diagram pg. 254

-Event Flow: HTML elements nested inside HTML elements.
  **Know the difference between "Event Bubbling", and "Event Capturing"

***Event Object pg. 269***

***HTML Forms***
  -Demo:
  -Everything that you're passing as an argument, is what you need a form flow for.
  -Goes into the event handler; and wait for someone to do something.

  event.default you're going to need it: because of empty form fills.
