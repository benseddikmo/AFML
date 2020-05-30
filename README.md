# Advances in Financial Machine Learning
All the answers for exercises from Advances in Financial Machine Learning by Dr Marco Lopez de Prado. I will strongly recommend you to do the same.

Not only his book can  teach you necessary quant skills, the exercises provided in the book is a great way to ensure you will have a solid understanding of implementating quantitative strategy. From "A" to "Z".

The book itself teaches very rational methods to quantitative finance, most of the concepts (especially triple barriers) can be cross-reference to other strategies types (not just mean-reversion) such as volatilities, trends.

**Prerequistes**

This is what I think as I go through this book.

* You need to understand econometrics
* You need to know Python development
* Understand and appreciate parallization computering
* Required to know advance mathematics and statistics
* Understand finance and investment (Preferably with real investment experience for behaviorial economics)
* Know how computer hardwares and latency can impact your codes
* Alot of common sense beyond just textbooks-smart (To relate and evaluate how practical implementations are done)

**Fun Fact**

AFML is actually a graduate textbook used in Cornell university. (If you manage to complete it correctly and implement the concepts. Congratuations!)

Before I proceed to next chapter, I will try to match my answers to the book, hence my answers are almost identical.

**Other References**

There is another library that was created way before mine (Actually more than 1 before mine), I will strongly recommend you to download their library, as a reference as you try to implement the codes. As well as their exercises, to see if our answers are somewhat similar to yours. (They have about 14 contributors and I'm just a part-time cashier. So logically, you should use their library)

* [mlfinlab library](https://github.com/hudson-and-thames/mlfinlab)
* [mlfinlab Exercises](https://github.com/hudson-and-thames/research/tree/master/Advances%20in%20Financial%20Machine%20Learning)

All the codes used in this exercise was created from scratch by myself based on what was taught in the book (Which took quite an effort), therefore the answers might be different from theirs.

However, our sample data (Based on dollar bar) are identical.

If you decide to write the code from scratch (Highly recommend!) and use my notebook answers as a reference, you will need the below:

* Python 3.7.4
* numpy 1.17.3
* numba 0.49.1
* pandas 1.0.3
* matplotlib 3.1.1
* sklearn 0.23.1
* statsmodels 0.10.1

As much as possible, I used multiprocessing (parallelisation) and pandas only. (As a challenge.)

The only time I used numba (njit) was in chapter 5 (frac diff), out of convenience. But they are really fast.

Believe it or not, without numpy or numba I somehow managed to clock up to 700x improvement in processing speed. (I will strongly encourage you to do the same, to get the best out of the book)

**Advice:**
It's always best to write code from scratch, in that way you will know completely what you use. As well as how to implement them.

**Note:**
Anyone can be absolutely wrong, that includes me. Have confident in yourself. That was my mindset when I started this book.

Here's a quote from AFML

> There are very few things which we know, which are not capable of being reduced to a mathematical reasoning.
>
> And when they cannot, it's a sign our knowledge of them is very small and confused.
>
> Where a mathematical reasoning can be had, it's a great folly to make use of others, as to grope for a thing in the dark, when you have a candle standing by you.
>
> &mdash; Of Laws of Chances, Preface (1692), John Arbuthnot (1667 - 1735).

All notebook research was done in private alone, You may contact directly me at <boyboi86@gmail.com> for further discussion on research outcome.