# Aial Prokopev

## Contacts:

- **tel** : +79999626598
- **email** : freezzforever@gmail.com

## About Myself:

My goal is to become a true **Software Engineer**!

## Skills:

- HTML5, CSS3
- JavaScript
- TypeScript
- C, C++ (Basics)
- Python (Basics)
- React, Redux Toolkit
- GraphQL, Apollo Client
- Git, Github, Gitlab
- SASS
- Next js
- Express js (Basics)
- Figma

## Code Example:

```
const ss16 = [
  "0", "1", "2", "3", "4", "5", "6", "7",
  "8", "9", "A", "B", "C", "D", "E", "F"
]
function div(a, b) {
  return (a - (a % b)) / b
}
function toHex(num) {
  let arr = []
  if (num > 255) num = 255
  if (num < 0) num = 0
  if (num === 0) return String(ss16[num])
  while (num > 0) {
    arr.push(num % 16)
    num = div(num, 16)
  }
  return String(arr.reverse().map(item=>ss16[item]).join(""))
}
function rgb(r, g, b) {
  // complete this function
  r = toHex(r).length < 2 ? `0${toHex(r)}` : toHex(r)
  g = toHex(g).length < 2 ? `0${toHex(g)}` : toHex(g)
  b = toHex(b).length < 2 ? `0${toHex(b)}` : toHex(b)
  return r+g+b
}
```

# Experience:

- **KidsTaxi** - children's taxi aggregator (Since 2022 Q1)

# Education:

- **MIREA - Russian Technological University**
  - Information Security Degree (incomplete)

# English:

- **A2**
