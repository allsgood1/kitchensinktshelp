kitchensink.ts

//set name to a variable with a type of string    **//SOLUTION: let name: string = 'Jillian';  **//SOLUTION
var name = 'Jillian';

console.log(name);

//set the number of states to a variable with a type of number. **//HINT: number = 50; **//Solution
const states = '50';

console.log(states);

//set the result of 4 and 5 to a variable. type = number.      **//SOLUTION: let sum: number = 4 + 5 **//SOLUTION
var sum = 5 + 4;

console.log(sum);


function sayHello(): void {
    console.log("Hello World!");
}
sayHello();


//**I just fixed this function for you. added name: string, age: number, and the value of void */
function checkAge(name: string, age: number): void {
    if (age < 21) {
        alert("Sorry " + name + " You're too young to enter")
    }
}

checkAge('Charles', 27);
checkAge("Abby", 18);
checkAge("James", 27);
checkAge('John', 17)


// edit this variable to have the type of string[]       **// SOLUTION: let favVeggies: string[] = ["broccolli", "brussel sprouts", "beets", "carrot"]; **//SOLUTION
let favVeggies = ["broccolli", "brussel sprouts", "beets", "carrot"];

for (let i = 0; i < favVeggies.length; i++) {
    const beatingcheeks = favVeggies[i];
    console.log(beatingcheeks)
}


//now we are making an interface of Person which looks like an object with a nameL string and age:number in it. the solution is commented out below:

// interface Person {
//     name: string,
//     age: number
// }

//now we are chaninging the array of peopleArr into an array with the parameter type of "Person" we just made above. the changes are commented out below:
let peopleArr//: Array<Person> = [
    {
        name: 'Josh',
        age: 25
    },
    {
        name: 'Carol',
        age: 61
    },
]

//dont know how to explain the next step so i just did it for you. the solution is commented out below:

for (let i = 0; i < peopleArr.length; i++) {
    const element = peopleArray[i];
    checkAge(element.name, element.age)
}

//element is a const variable we are declaring. it doesnt have to say element it could say cheekBeater if we wanted it to. Which we do. :weary:

//I added the type: string and the value of void to the function.
function getLength(word: string) void {
   return word.length
}

let wordLength = getLength('Hello World');
if (wordLength % 2 === 0) {
    console.log('The world is evn and stuff');
} else {
    console.log('the world is odd and floppy');
}

//you shouldnt have to change anything else above this line. All you should have to do is plug the console commands into the terminal and VS code should make a working js version of this TS file automatically. They explain it in the reference material
