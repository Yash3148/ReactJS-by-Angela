# Array.prototype.filter()

const result = words.filter((word) => word.length > 6);
console.log(result);

// Expected output: Array ["exuberant", "destruction", "present"]

# Array.prototype.map()

const array1 = [1, 4, 9, 16];

const map1 = array1.map((x) => x * 2);    // Pass a function to map
console.log(map1);
// Expected output: Array [2, 8, 18, 32]

# Array.prototype.reduce()

const array1 = [1, 2, 3, 4];

// 0 + 1 + 2 + 3 + 4
const initialValue = 0;
const sumWithInitial = array1.reduce(
  (accumulator, currentValue) => accumulator + currentValue,
  initialValue,
);
console.log(sumWithInitial);
// Expected output: 10

# Array.prototype.find()

const array1 = [5, 12, 8, 130, 44];

const found = array1.find((element) => element > 10);
console.log(found);
// Expected output: 12

# Array.prototype.findIndex()

const array1 = [5, 12, 8, 130, 44];

const isLargeNumber = (element) => element > 13;

console.log(array1.findIndex(isLargeNumber));
// Expected output: 3

# String.prototype.substring()

const str = 'Mozilla';

console.log(str.substring(1, 3));
// Expected output: "oz"

console.log(str.substring(2));
// Expected output: "zilla"