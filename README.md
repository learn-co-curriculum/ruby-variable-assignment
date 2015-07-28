# Variable Assignment
teststes
## Objectives

1. Test your ability to assign a local variable.

## Instructions

You will assign a local variable named `greeting` that is equal to `Hello World`.

You should first make sure the test suite is running correctly by running `learn`.

Upon the first run of the test suite you should see:

```bash
FF

Failures:

  1) defined a local variable called greeting and set it equal to 'Hello World'
     Failure/Error: expect(match).to eq(true)

       expected: true
            got: false

    (compared using ==)

Finished in 0.00048 seconds
2 examples, 1 failure
```
However, if you get:

```bash
-bash: learn: command not found
```
Then you need to install Learn. Do that via: `gem install learn-co` in your command line.

To solve this test failure, create a local variable `greeting` in the `variable.rb` file. Set `greeting` equal to the string `"Hello World"`. Run `learn` to see if you did this correctly.

## Resources
* [Learn to Program](https://pine.fm/LearnToProgram/chap_03.html)
* [Introduction to RSpec](http://blog.teamtreehouse.com/an-introduction-to-rspec)
