# Change generator

Given a number in pounds and pence, work out the most efficient way of breaking it down into notes and coins, e.g. 11.55 becomes ["£10", "£1", "50p", "5p"]

## Example Output

```
2.4.1 :001 > require './lib/change_generator.rb'
 => true
2.4.1 :002 > change_generator(7.42)
 => ["£5", "£1", "£1", "20p", "20p", "2p"]
2.4.1 :003 > roman_numeral(40)
 => ["£20", "£20"]
2.4.1 :004 > roman_numeral(16.30)
 => ["£10", "£5", "£1", "20p", "10p"]
2.4.1 :005 > roman_numeral(19.99)
 => ["£10", "£5", "£1", "£1", "1", "£1", "50p", "20p", "20p", "5p", "1p", "1p", "1p", "1p"]
2.4.1 :006 > roman_numeral(76.81)
 => ["£50", "£20", "£5", "£1", "50p", "20p", "10p", "1p"]
```

## Extension Options

- Write a program that takes an array of note and coin values and returns the result of summing these amounts, in `£00.00` format.

- Write a change generator for a different currency e.g. USD.
