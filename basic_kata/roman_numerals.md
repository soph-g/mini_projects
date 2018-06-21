# Roman Numerals

A classic kata, with some variations included.

It can be tricky to translate numbers into their roman numeral equivalent, write a program that takes a number between 1 and 1000 and returns the corresponding roman numeral.

## Brief guide to roman numerals:

```
1 = I
5 = V
10 = X
50 = L
100 = C
1000 = M
```

### Example Output

```
2.4.1 :001 > require './lib/roman_numeral.rb'
 => true
2.4.1 :002 > roman_numeral(9)
 => "IX"
2.4.1 :003 > roman_numeral(18)
 => "XVIII"
2.4.1 :004 > roman_numeral(33)
 => "XXXIII"
2.4.1 :005 > roman_numeral(75)
 => "LXXV"
2.4.1 :006 > roman_numeral(99)
 => "XCIX"
2.4.1 :007 > roman_numeral(112)
 => "CXII"
2.4.1 :008 > roman_numeral(164)
 => "CLXIV"
2.4.1 :009 > roman_numeral(250)
 => "CCL"
2.4.1 :010 > roman_numeral(984)
 => "CMLXXXIV"
2.4.1 :011 > roman_numeral(1000)
 => "M"
```

## Extension Options

- Write a program that takes a roman numeral and returns the corresponding integer.

- Write a program that takes a number and returns an array of roman numerals from I to the given number.

- Write a game that asks the player to enter the roman numeral for a given random number, the game ends when they enter an incorrect answer.
