# jswordchallenge

let reverse = function(hehe) {
let array = hehe.split("")
let string = ""
  for (let i = array.length - 1 ;  i >= 0 ;  i--) {
        string += array[i]
    }
    return string
}
console.log(reverse(""))

for (let i = 1; i <= 100; i++) {
  if (i % 5 == 0 && i % 3 == 0) {
    console.log("FizzBuzz")
  } if (i % 3 == 0) {
    console.log("Fizz")
  } else if (i % 5 == 0) {
    console.log("Buzz")
  } else {
    console.log(i)
  }
}

let vowels = ["a", "e", "i", "o", "u"]
function pigLatin(string) {
  str = prompt("Enter a word")
  let x = str.substr(1)
  let y = str.charAt(0)
  if (!(vowels.includes(y))){
   return x + y + "ay"
  } else {
   return str + "ay"
  }
}
