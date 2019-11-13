# Competitive Programming

This is an intro to competitive programming. This is supposed to cover some of the basic information needed to get started.

## Tips

1. **The best time to start is now** -- the more practice you get in the better, and if you wait until you're in your last year to practice a lot, you'll have a lot of catching up to do. It can be intimidating to see a difficult problem, but the only way you can solve it is by practicing easier ones until you're comfortable.
2. **Keep at it** -- you make the most progress by doing some amount regularly. If you solve some problems every day or two, you'll become very good in no time.
3. **Talk with others** -- if you don't understand a problem or know a good approach for it, there will probably be someone who you can discuss it with that can help out. Becoming friendly with others is good in general, but especially since they might be your teammates in a competition.

## Platforms

There are several different platforms to practice competitive programming. Here is a few of the important ones:

- [Kattis](https://open.kattis.com/universities/upei.ca): Kattis is the site that most UPEI competitive programmers go to. It has the nicest interface of any platform, and a lot of good problems to solve. You increase rank by solving problems, either in contests or on your own time.
- [CodeForces](https://codeforces.com/): the most active platform with lots of good information, though getting used to the interface can take some time. Ranks are based off an elo system that changes depending on how good you do in regularly hosted contests.
- [Project Euler](https://projecteuler.net/): Project Euler is a platform focused around math problems.

It's important to note you don't have to just go on one! You can do a bit on each if you'd like.

## Example problem

Most competitive programming problems will follow a similar format. It'll usually describe the problem, describe its input, describe its output, then give a sample input/output to test your program. For example:

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
