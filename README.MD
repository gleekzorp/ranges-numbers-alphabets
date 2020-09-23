# ranges-numbers-alphabets

- Get a full range of numbers based on your start and stop or a full range of letters a-z in uppercase or lowercase.

## Methods Available For Alphabet:
```javascript
arrayAtoZ('lowercase')
arrayAtoZ('UPPERCASE')
```

## Methods Available For Numbers:
*(still working on error checking for this method)*

- **full range 1 to 100**
```javascript
arrayNumberRange(1, 100)
// returns an array [ 1, 2, 3, 4, 5, ...100 ]
```

- **full range 2 to 100 of even numbers**
```javascript
arrayNumberRange(2, 100, 2)
// returns an array [ 2, 4, 6, 8, 10, ...100 ]
```

- **full range 1 to 99 of odd numbers**
```javascript
arrayNumberRange(1, 99, 2)
// returns an array [ 1, 3, 7, 9, ...99 ]
```

- **Step backwards from 5 to 1**
```javascript
arrayNumberRange(5, 1, -1)
// returns an array [ 5, 4, 3, 2, 1 ]
```