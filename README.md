# fizzbuzz

A Makers pre-course week 4 challenge that introduces Test Driven Development (TDD) and Pair Programming.

* **Languages used**: Ruby
* **Testing frameworks**: RSpec

## Gems Required

### RSpec Gem
RSpec
```
gem install rspec
```

RSpec options
```
rspec --h
```


## Instructions

* Work through the challenge using a TDD approach with a pair partner. 
* Take turns to drive/navigate, swapping every 15 mins.
* Write a failing test (RED) - describe a single expectation of the program. 
* Write the simplest code possible to pass the test (GREEN)
* Clean up (REFACTOR): tidy up and ensure tests still pass without adding any additional functionality.
* Repeat RED - GREEN - REFACTOR
* Satisfy the TDD objectives:
    1. Write production code that fully meets the expectation of our tests.
    2. Write tests that fully meet the specification of the program.


## FizzBuzz Challenge Specification

* The program can be passed a number.
* When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
* When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
* When passed a number that is a multiple of both 3 and 5, the program ignores the previous 2 rules and returns the message 'FizzBuzz'.
* In all other cases, the program simply returns the given number.
* When complete we should be able to play in irb like so:

```irb
2.2.1 :001 > require './lib/fizzbuzz'
true
2.2.1 :002 > (1..20).each {|number| puts "#{number} --> #{fizzbuzz(number)}"}
1 --> 1
2 --> 2
3 --> fizz
4 --> 4
5 --> buzz
6 --> fizz
7 --> 7
8 --> 8
9 --> fizz
10 --> buzz
11 --> 11
12 --> fizz
13 --> 13
14 --> 14
15 --> fizzbuzz
16 --> 16
17 --> 17
18 --> fizz
19 --> 19
20 --> buzz
```


## Usage

From irb require the fizzbuzz.rb file.
``` 
require './lib/fizzbuzz'
```

To get a fizzbuzz number:
```
fizzbuzz(x)
```

To run FizzBuzz for all numbers from 1 to 100:
```
(1..100).each {|number| puts "#{number} --> #{fizzbuzz(number)}"}
```

To run the RSpec tests in the command line type:
```
rspec
```


## Files

| File    | Description |
| ----------- | ----------- |
| .rspec  | This file was generated when initialising RSpec |
| ./lib/fizzbuzz.rb  | The fizzbuzz program  |
| ./spec/fizzbuzz_spec.rb  | The RSpec file containing all the tests scenarios for fizzbuzz.rb |
| ./spec/spec_helper.rb | This file was generated when initialising RSpec |

