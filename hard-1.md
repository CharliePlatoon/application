# Challenge 3.1 (Hard #1)

## Pig Latin
For this problem, write a function/method that takes in a string and returns it in Pig Latin. If you are unfamiliar with Pig Latin check out: https://en.wikipedia.org/wiki/Pig_Latin. For our purposes today, let's follow one rule:

```
If a word starts with a consonant move all the letters before the first vowel to the end and add 'ay'. If a word starts with a vowel (count 'y' as a vowel) just add 'way'.
```

Examples:
```javascript
pigLatin('bob') // returns 'obbay'
pigLatin("bob") // returns "obbay"
pigLatin("pig") // returns "igpay"
pigLatin("latin") // returns "atinlay"
pigLatin("banana") // returns "ananabay"
pigLatin("school") // returns "oolschay"
pigLatin("one") // returns "oneway"
pigLatin("or") // returns "orway"
pigLatin("This is a test") // returns "isThay isway away esttay"
```
