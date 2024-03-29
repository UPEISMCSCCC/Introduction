# Competitive Programming

This is an intro to competitive programming. This is supposed to cover some of the basic information needed to get started.

Competitive programming is problem solving using code. You are given a well defined problem (you know everything about what's an input you need to test, and what your output should look like) and a set of constraints (time limit and memory limit) and have to come up with a valid solution. Sometimes the problem isn't difficult, but you have to be able to code it fast. Sometimes the problem is incredibly difficult, and you need vast knowledge of obscure algorithms and data structures to get a solution. 

## Tips

1. **The best time to start is now** -- the more practice you get in the better, and if you wait until you're in your last year to practice a lot, you'll have a lot of catching up to do. It can be intimidating to see a difficult problem, but the only way you can solve it is by practicing easier ones until you're comfortable.
2. **Keep at it** -- you make the most progress by doing some amount regularly. If you solve some problems every day or two, you'll become very good in no time.
3. **Talk with others** -- if you don't understand a problem or know a good approach for it, there will probably be someone who you can discuss it with that can help out. Becoming friendly with others is good in general, but especially since they might be your teammates in a competition.

## Platforms

There are several different platforms to practice competitive programming. Here is a few of the important ones:

- [Kattis](https://open.kattis.com/universities/upei.ca): Kattis is the site that most UPEI competitive programmers go to. It has the nicest interface of any platform, and a lot of good problems to solve. You increase rank by solving problems, either in contests or on your own time.
- [CodeForces](https://codeforces.com/): the most active platform with lots of good information, though getting used to the interface can take some time. Ranks are based off an elo system that changes depending on how good you do in regularly hosted contests.
- [Project Euler](https://projecteuler.net/): Project Euler is a platform focused around math problems. It's not directly related to competitive programming, but is good practice for solving math-oriented competitive programming questions.

It's important to note you don't have to just go on one! You can do a bit on each if you'd like.

## Example problem

Most competitive programming problems will follow a similar format. It'll usually describe the problem, describe its input, describe its output, then give a couple sample inputs/outputs to test your program. For example:

> Alice and Bob are both carrying a bunch of apples with them. Unfortunately, they bumped into eachother and dropped all their apples. Now they can't tell whose is whose, and they're all mixed together. How many apples are now on the ground?

> Input is two integers "n" and "m", "1 <= n,m <= 1000", where "n" is Alice's apples and "m" is Bob's apples.

> Output is the number of apples on the ground.

> Input: `1 1` Output: `2`

> Input: `500 99` Output: `599`

Very simply, this problem is asking for `n + m`. Here's some c++ code that can solve this problem:
```cpp
#include <iostream>

using namespace std;

int main() {
  int n, m;
  cin >> n >> m; // get the two numbers from input
  cout << n + m; // print out the two numbers added together
}
```

This isn't a real problem, but some of the [easiest problems](https://open.kattis.com/problems?order=problem_difficulty) on kattis are around the same difficulty level as this.

## FAQ

***Will this help with my classes?***

Absolutely! Many competitive programming problems are similar to problems you see in your classes. As you learn more and become faster at competitive programming, you'll also have an easier time with programming for courses.

***Will this help with employment?***

Competitive programming can help with that too. Competition results look very nice on a resume, and can be a good way to show off your knowledge and skills to an employer.

***What language should I use?***

In general, whatever you prefer. The three most popular languages are C++, Python, and Java, so most resources (including the ones here) will only be in those languages. The pros/cons are:
- C++ is very fast, and does have some very good libraries. It misses a few though (arbitrarily large integers is the main one) that mean some problems can't be done in C++, and it has a lot of boilerplate code.
- Python is relatively slow, but is very fast to code in with very little boilerplate. It supports things like arbitrarily large integers by default, but this sort of abstraction also means you can't optimize it as easily as C++.
- Java doesn't have the speed that C++ does, and in fact on kattis it's slower than python too. That said it does have a lot of good libraries and useful utilities, and since it's the language a lot of people learn data structures and algorithms in it can be useful to know.

You don't need to learn another language immediately if you want to become a competitive programmer, but it can be useful to learn some later.

***What Text editor / IDE should I use?***

In online competitions or practice problems, you can use whatever text editor you want. Because you'll be writing one file most of the benefits an IDE provides don't come into play, so it's not a significant difference whichever you use.

In in-person competitions, you often can't use your own computer so you'll usually only have vim, emacs, and simple editors like gedit. Sometimes an IDE will be provided, but you shouldn't be reliant on an IDE and should be able to work in a simple text editor for competitions that require it.

***Where can I learn more?***

There's a lot you can do to learn more! Asking other people who are currently involved in competitive programming can likely give you more resources. Most people who are involved with this club should be helpful when possible.

There's also some resources listed [here](./Resources.md).
