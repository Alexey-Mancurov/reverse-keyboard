# Reverse-keyboard
The functon `reverseKeyboard` takes text and return string after changed keyboard layout (en => ru || ru => en)

## Installation

```js
npm i reverse-keyboard
```

## Usage
import to your file and pass the string to the parameters of the reverseKeyboard function

```js
import reverseKeyboard from 'reverse-keyboard'
```

### from english to russian

```js
const result = reverseKeyboard('bpvtyb hfcrkflre')

console.log(result) // измени раскладку
```

### from russian to english
```js
const result = reverseKeyboard('ремекыу лунищфкв')

console.log(result) // reverse keyboard
```
