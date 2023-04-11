// Callback Function Example
function greet(name, myFunction) {
    console.log('loading');
console.log('loading..');
console.log('loading..');
console.log('loading...');
console.log('loading..');
console.log('loading...');
    // callback function
    // executed only after the greet() is executed
    myFunction(name);
}

// callback function
function sayName(name) {
    console.log(' ' + ' ' + name);
}

// calling the function after 2 seconds
setTimeout(greet, 10000, 'DONE WAITING ON ITEMS', sayName);
