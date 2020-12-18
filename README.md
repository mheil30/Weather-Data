const kelvin = (293); // Temperature for 12/18/2020 is 293K. Change the value of kelvin to calculate any degree celsius, farenheit, or newton
const celsius = (kelvin - 273); // Equation to convert kelvin to celsius
console.log(celsius); // The temperature in degrees Celsius
console.log(Math.floor(celsius)); // The temperature in degrees Celsius rounded down to the smallest integer value
console.log(`The temperature is ${celsius} degree Celsius`); // A string stating that the temperature is (fill in the blank) degrees celsius
console.log(`The temperature is ${Math.floor(celsius)} degree Celsius`); // A string stating that the temperature is (fill in the blank) degrees Celsius rounded down to the smallest integer value
const farenheit = (celsius * (9/5) + 32); // Equation to convert celsius to farengeit
console.log(farenheit); // The temperature in degrees Farenheit
console.log(Math.floor(farenheit)); // The temperature in degrees Farenheit rounded down to the smallest integer value
console.log(`The temperature is ${farenheit} degrees Farenheit`); // A string stating that the temperature is fill in the blank) degrees Farenheit
console.log(`The temperature is ${Math.floor(farenheit)} degrees Farenheit`); // A string stating that the temperature is (fill in the blank) degrees Farenheit rounded down to the smallest integer value
const newton = (celsius * (33/100)); // Equation for converting celsius to newtons
console.log(newton); // The temperature in degree Newton
console.log(Math.floor(newton)); // The temperature in degree Newton rounded down to the smallest integer value
console.log(`The temperature is ${newton} degree Newton`); // A string stating that the temperature is (fill in the blank) degree Newton
console.log(`The temperature is ${Math.floor(newton)} degree Newton`); // A string stating that the temperature is (fill in the blank) degree Newton rounded down to the smallest integer value
