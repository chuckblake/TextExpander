const upperLetters = "QWERTYUPASDFGHJKZXCVBNM";
const lowerLetters = "qwertyupasdfghjkzxcvbnm";
const numbers = "23456789";
const characters = "!@#$%&*";

var stringToReturn = "";

for(let i = 0; i < 2; i++ ){
    stringToReturn += numbers[Math.floor(Math.random() * numbers.length)];
}

for(let i = 0; i < 2; i++ ){
    stringToReturn += lowerLetters[Math.floor(Math.random() * lowerLetters.length)];
}

for(let i = 0; i < 2; i++ ){
    stringToReturn += characters[Math.floor(Math.random() * characters.length)];
}

for(let i = 0; i < 2; i++ ){
    stringToReturn += upperLetters[Math.floor(Math.random() * upperLetters.length)];
}

TextExpander.appendOutput(stringToReturn);
