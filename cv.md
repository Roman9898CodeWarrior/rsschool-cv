rsschool-cv

Bychkov Roman

Junior Frontend Developer

Contact information:
Phone: +7 999 078 19 53
E-mail: bychkov.roman17@yandex.ru

Briefly About Myself:
Having started my career as a back office worker at a bank. Due to remote work i have had extra free time, which I spend learning Frontend Development.
I’m interested in Web Development because such work seems to me very intresting thanks to the opportunity to be creative in the process of development due to possibility of implementing different ways of solwing the same task. this occupation provides ample opportunities for professional and career growth.
Besides there’s a huge amount of free and high quality resources for self-education and a large community of developers to connect with in the process of learning.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

My Skills and Proficiency:
HTML5, CSS3
Figma
SASS/CSCC
JavaScript
TypeScript
React
Node JS
Webpack
REST API
Git && GitHub
react-testing-library
react-hook-forms

Code example:

1. Simple string characters KATA from CODEWARS:

Task description - In this Kata, you will be given a string and your task will be to return a list of ints detailing the count of uppercase letters, lowercase, numbers and special characters, as follows.

My solution:

function solve(s){
let A = s.match(/[A-Z]/g)||[];
let b = s.match(/[a-z]/g)||[];
let num = s.match(/[0-9]/g)||[];
let sp = s.match(/[^A-Z0-9]/gi)||[];
return [A.length, b.length, num.length, sp.length];
}

2. The First Non Repeated Character In A String KATA from CODEWARS:

Task description - You need to write a function, that returns the first non-repeated character in the given string.

If all the characters are unique, return the first character of the string.
If there is no unique character, return null in JS or Java, None in Python, '\0' in C.

You can assume, that the input string has always non-zero length.

My solution:

function firstNonRepeatedCharacter(str) {
for(let i = 0; i < str.length; i++) {
if (str.indexOf(str[i]) === str.lastIndexOf(str[i])) {
return str[i]
}
}
return null
}

Courses:

RS Schools Course «JavaScript/Front-end 2023Q4»

Languages:

English - Intermediate/Upper-intermediate (according to the online test at EFset Logo www.efset.org)
Russian - Native
