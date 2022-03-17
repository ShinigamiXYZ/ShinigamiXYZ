### ohayo gozaimasu👋 

Watashi wa shinigamiXYZ desu

<!-- trying to recreate W shanks life time achievement with JS ->>

var readline = require("readline-sync");

var number = readline.question("Veuillez entre un nombre Premier : ");

let nPrime = true;


// check if number is equal to 1
if (number === 1) {
    console.log("1 is neither prime nor composite number.");
}

// check if number is greater than 1
else if (number > 1) {

    // looping through 2 to number-1
    for (let i = 2; i < number; i++) {
        if (number % i == 0) {
            nPrime = false;
            break;
        }
    }

    if (nPrime) {
        console.log(`${number} is a prime number`);
    } else {
        console.log(`${number} is a not prime number`);
    }
}

// check if number is less than 1
else {
    console.log("The number is not a prime number.");
}



// une fois le nombre accepté maitenant obtenir le résultat de 1 divisé par se nombre


console.log( 1 / number )  ;


/** maitenant comment looper le tout afin de créee une validation et ne pas divisé le nombre
 * Tant que nous n'obtenons pas une nombre Premier.
 * 
 **/


