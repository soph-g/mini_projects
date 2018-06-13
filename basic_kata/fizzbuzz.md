# FizzBuzz

A classic! FizzBuzz is a game where the group counts from 1 to as high as they can go remembering to substitute numbers according to the following rules:

- Say 'Fizz' when the number is divisible by 3
- Say 'Buzz' when the number is divisible by 5
- Say 'FizzBuzz' when the number is divisible by 3 and 5
- Say the number when it is not divisible by 3 or 5

## User Stories

```
As a keen FizzBuzzer
So that I am less likely to make mistakes
I want to check a number against the rules of FizzBuzz
```

```
As a keen FizzBuzzer
So that I say know when to say 'Fizz'
I want to see 'Fizz' when I enter a number divisible by 3
```

```
As a keen FizzBuzzer
So that I say know when to say 'Buzz'
I want to see 'Buzz' when I enter a number divisible by 5
```

```
As a keen FizzBuzzer
So that I say know when to say 'FizzBuzz'
I want to see 'FizzBuzz' when I enter a number divisible by both 3 and 5
```

```
As a keen FizzBuzzer
So that I know when to say a number
I want to see the number returned when I enter a number that is not divisible by 3 or 5.
```

### Example output

```
2.4.1 :001 > require './lib/fizzbuzz.rb'
 => true
2.4.1 :002 > fizzbuzz(1)
 => 1
2.4.1 :003 > fizzbuzz(2)
 => 2
2.4.1 :004 > fizzbuzz(3)
 => "Fizz"
2.4.1 :005 > fizzbuzz(4)
 => 4
2.4.1 :006 > fizzbuzz(5)
 => "Buzz"
2.4.1 :007 > fizzbuzz(6)
 => "Fizz"
2.4.1 :008 > fizzbuzz(7)
 => 7
2.4.1 :009 > fizzbuzz(8)
 => 8
2.4.1 :010 > fizzbuzz(9)
 => "Fizz"
2.4.1 :011 > fizzbuzz(10)
 => "Buzz"
2.4.1 :012 > fizzbuzz(15)
 => "FizzBuzz"
```

## Extension Options

- Write a program that takes a number, and returns an array of the FizzBuzz sequence from 1 to the given number, with the appropriate substitutions.

- Play FizzBuzz against a robot by taking it in turns to give the correct answer in the sequence from 1 upwards. Play ends when the player makes a mistake.

- Write a program that tests a player's FizzBuzz skills by giving a random number, the player would then guess it would be equal to the number, Fizz, Buzz or FizzBuzz when playing a game of FizzBuzz. Play ends when the player makes a mistake.
