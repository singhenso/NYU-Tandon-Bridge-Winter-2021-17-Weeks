#  Module 2 - Positional Number System


**Learning Objectives**
- [Module 2 - Positional Number System](#module-2---positional-number-system)
    - [Concept](#concept)
    - [Mapping number to represent symbols, images, audios, videos](#mapping-number-to-represent-symbols-images-audios-videos)
    - [Counting in Different Number System](#counting-in-different-number-system)
      - [Counting in Base 10](#counting-in-base-10)
      - [Counting in Base 5](#counting-in-base-5)
      - [Counting in Base 8](#counting-in-base-8)
      - [Counting in Base 2](#counting-in-base-2)
      - [Counting in Base 16](#counting-in-base-16)
  - [Converting Between Different Bases](#converting-between-different-bases)
  - [Base Conversions](#base-conversions)
      - [1. N in base b &#x2192; N in decimal](#1-n-in-base-b--n-in-decimal)
      - [2. N in decimal &#x2192; N in base B](#2-n-in-decimal--n-in-base-b)
      - [3. N in Binary &#x2192; N in base Hexadecimal](#3-n-in-binary--n-in-base-hexadecimal)
    - [Additional Resources](#additional-resources)
    - [Citing Sources | Credit](#citing-sources--credit)

### Concept
Memory is made out of bits and are grouped into a byte. Each bit is made with electrical flow or a magnetic field. Abstractly, we represent each bit as zero and one because it only has two states "on or off." This is **Binary Code** Despite having only two states, it can represent a lot of data using this primitive unit.

### Mapping number to represent symbols, images, audios, videos

Documents, images, audio, video and images are all represented using only zeros and ones. Key thing is that everything would be represented as a number Essentially, All our data is first transformed into numbers (zeros and ones).


    H = 72,
    lowercase e = 101 etc. 
    120 = red
    100 = green
    200 = blue

---

### Counting in Different Number System

---
#### Counting in Base 10
The Base-10 number system is known as the decimal system
and has 10 digits to show all numbers ***0,1,2,3,4,5,6,7,8,9*** using place value and a decimal point to separate whole numbers from decimal fractions.

When we get to the tenth object, instead of having a single symbol to represent the amount (quantity of ten), we group ten ones into a single ten. This ten will be in second position in the number along with zero additional ones.

    - 11 would be one group of ten and a single addition of one
    - 28 would be two group of ten and a eight addition of one
    - 72 would be seven group of ten and two addition of one

After 99, the next object would have ten ones that would be grouped into another ten so we would have ten tens and these ten tens would be grouped into a single one hundred that is represented in the next position. Place value is what gives it the value. The rule is you can only have 1 digit per place value.  **This describes how numbers are written in a positional notation**

***345,862.127***
Within this large number, each digit has a value of:

  - 3 has a place value of 300,000 (three hundred thousand) <span style="color:blue">&mdash; 3 groups of 100,000</span>
  - 4 has a value of 40,000 (forty thousand) <span style="color:blue">&mdash;4 groups of 10,000</span>
  - 5 has a value of 5,000 (five thousand) <span style="color:blue">&mdash;5 groups of 1000</span>
  - 8 has a value of 800 (eight hundred) <span style="color:blue">&mdash;8 groups  100</span>
  - 6 has a value of 60 (sixty) <span style="color:blue">&mdash;6 groups of 10</span>
  - 2 has a value of 2 (two) <span style="color:blue">&mdash;2 groups of 1</span>
  - 1 has a value of 1/10th (one-tenth)
  - 2 has a value of 2/100th (two one-hundredths)
  - 7 has a value of 7/1000th (five one-thousandths)

So base ten means that the value of each place is a power of ten, and ten different digits (0 through 9) are needed.

#### Counting in Base 5

In this world you can only chose 5 digits ( 0 - 4). In base 5, the place values are 1, 5, 25, 125, 625, 3125, and so on.
<mark> In base 5, for example, counting would go like this: 0,1,2,3,4, 10,11,12,13,14, 20,21,22,23,24, 30,31,32,33,34, 40,41,42,43,44, 100,101,102,103,104, 110,... </mark>
It would start zero, one, two, three, four, and now in base five, we are going to group five objects together. 

Remember, 324 <sub>(base 5)</sub> is eighty-nine, not three hundred twenty-four. For instance, the “3”
stands for 3 twenty-fives, not 3 hundreds. It may help us clarify the situation by saying that
the “3” has a face value of three and a place value of twenty-five, for a value of seventy-five.

<!-- <code>
(𝑎𝑏𝑐𝑑)<sub>5</sub>=(𝑎∗5<sup>3</sup>+𝑏∗5<sup>2</sup>+𝑐∗5<sup>1</sup>+𝑑∗5<sup>0</sup>)<sub>10</sub>
</code> -->

![Counting in base 5](/images/w1.jpg)
Another example showing how to convert base 5 to decimal:
![Counting in base 5](/images/w11.jpg)
Example showing how to convert a Base 10 into Base 5
![Counting in base 5](/images/w12.jpg)

#### Counting in Base 8

This is known as Octal. In this system, there are eight symbols to work with:
***0 1 2 3 4 5 6 7***

We start by listing all the symbols after the "zero."
I came across this article<sup>1</sup> that explains it very well and added it's quote:

"When we get to that point, we're out of symbols. So what do we do? We go all the way down to zero, and add a one to our left: we write "one-zero" ***(10)***  .It means "the number that comes after seven," or what we normally call "eight." This is the key turning point in this paper, so make sure you're still with me: when I write "one-oh" (10) in base eight, I don't mean ten, I mean the number eight. The numbers in base eight look just like our normal numbers (except that they never use the symbols 8 or 9), but they don't mean the same things. You have to think in "eights" to understand them, just as you have to think in "tens" to understand our normal system.

Now we start counting on the right again: one-one, one-two, one-three, and so on. (11, 12, 13...) Soon we hit one-seven (17) and we run out of digits again, so we have to increment on the left: two-zero, or 20. Every eighth number, we start over again.

This system works great until we get to ***77***, and then we can't increment the left-hand digit any more. So we move to the left again and write one-zero-zero ***(100)*** . It's important to remember again that this doesn't mean the same thing we normally call "one hundred" so it's best not to call it that: call it "one-zero-zero" and it will help keep things straight.

So, when I write the octal number ***1235*** what do I mean? I mean 5 "ones", 3 "eights", 2 "sixty-fours", and 1 "five-hundred-and-twelve." Each step to the left involves a multiplication by eight—because we are in base eight. So if there were another digit to the left, we know it would count as "four-thousand-and-ninety-sixes" since that is eight times "five-hundred-and-twelves," and so on.

If you've followed everything I've done so far, you have hopefully understood a few things. First, you understand that our normal system of counting is based on the principle that every tenth number, you start over and move to the left—because there are only ten symbols to work with. Second, you understand that there's nothing sacred about the number ten: base eight is exactly the same, except it happens to start over every eighth number, because it has eight symbols to work with. Once you can do base ten counting, there's nothing fundamentally different about base eight.

But you may still be wondering, what does ***1235*** base eight really mean? Well, I said above that it is 5 "ones", 3 "eights", 2 "sixty-fours", and 1 "five-hundred-and-twelve." If you add all that up,

5∗1 + 3∗8 + 2∗64 + 1∗512 = 669

So we can say "***1235*** <sub>(8)</sub> = ***669*** <sub>(10)</sub>." Or, to put it another way, "when you write 1235 in base eight, you really mean the number six-hundred and sixty-nine." That's a kind of base-ten-centric way to put it, but hey, we're base-ten-centric people. And in any case, the point I'm making is that it's easy to convert base eight numbers into their base ten equivalents, once you understand the system."<sup>1</sup>

#### Counting in Base 2

This is the binary base system.
0,1,10,11,100,101,110,111,1000,1001,1010,etc.

You end up grouping together much faster. Much more often the grouping of numbers grow long much faster.

#### Counting in Base 16

Counting in base ten is the exact same way to count for base eight.
For Base 16, we need additional symbols.
***0 1 2 3 4 5 6 7 8 9 A B C D E F***

After 9, instead of grouping together and moving to the next position you still have a single digit number that is the quantity of 10 which is ***a***

The 16th object would be grouped into a single 10. 

What comes before 100?
***ff*** which represents 15 tens and 15 ones

- A represents the number we usually call "ten"
- The highest single digit is ***F*** which represents "fifteen"


## Converting Between Different Bases

Find the equivalent representations between different bases:
This can be counted very easily by fingers that the professor used in the Lecture.

***(13)<sub>10</sub> = (15)<sub>8</sub> = (23)<sub>5</sub> = (1101)<sub>2</sub> = (D)<sub>16</sub>***



## Base Conversions

The Professor showed two ways.
N = Number:

1. N in base b &#x2192; N in decimal
2. N in decimal &#x2192; N in base B

This method allows you to convert numbers to different bases..

#### 1. N in base b &#x2192; N in decimal

![Counting in base 5](/images/w13.jpg)

#### 2. N in decimal &#x2192; N in base B
![Counting in base 5](/images/w14.jpg)

#### 3. N in Binary &#x2192; N in base Hexadecimal

### Additional Resources
* [Base 5 Number System - Basics | Youtube](https://www.youtube.com/watch?v=qGi29E9q_f0)
* [Convert Base 5 to Base 10 | Youtube](https://www.youtube.com/watch?v=S25Le5Kf7SU)
* [Base 5 -> Base 10 Calculator | extraconversion.com](http://extraconversion.com/base-number/base-5)
* [Base 8 | Felderbooks ](http://www.felderbooks.com/papers/bases.html)
* [Hexadecimal Number System | Khan Academy Video](https://www.youtube.com/watch?v=4EJay-6Bioo)
* [Number Base Conversion Practice | Khan Academy Video](https://youtu.be/Fpm-E5v6ddc)
* [Computer Number Systems | Tutorials Point](https://www.tutorialspoint.com/computer_fundamentals/computer_number_system.htm)



### Citing Sources | Credit
1. http://www.felderbooks.com/papers/bases.html | 1998 by Kenny Felder &amp; Gary Felder