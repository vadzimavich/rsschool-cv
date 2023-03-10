# Andrei Kaspiarovich

## Contacts
Email: *vadzimavich@gmail.com*
rs-school Discord: *Andreo Vajima (@vadzimavich)*

## About Me
...with a passion for creative solutions and new technologies. 
Looking for an entry-level position at company...

## Hard Skills
* HTML/CSS
* JS
* Git
* Figma
* Adobe CC

## Core Skills
* Problem-solving
* Attention to details
* Adaptability

## Education
* B.S., BSUIR, Computer-Aided Design, 2016
* Currently enrolled in a JS course by **RS School**

## Language
* Russian - Native
* Belarusian - Native
* English - B2

## Code Example
```
// My solution for this kata: https://www.codewars.com/kata/5552101f47fc5178b1000050
function digPow(n, p) {
  let arr = Array.from(String(n), Number);
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    sum += Math.pow(arr[i], p + i);
  }
  if (Number.isInteger(sum / n)) return sum / n;
  else return -1;
}
```


