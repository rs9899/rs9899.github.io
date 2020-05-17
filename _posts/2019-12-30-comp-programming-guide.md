---
layout: post
title: A Hacker’s Guide to Competitive Programming
subtitle: Things to revise before a comp coding test
cover-img: /assets/img/path.jpg
tags: [guide, coding]
---

This blog post started with a personal search for such a post. I have a coding
interview in an hour, and I was searching for a good medium post, which can
point me out some basic concepts of Competitive Coding so that I can brush up
just in time. <br> Inability to find such a post gave me the motivation to write
one myself. This blog is mainly for my personal use in the future, and maybe the
title is more of a fancy one that a summarizing one. Anyway, so bottom-line is,
this is a post to take a look just before you are giving a coding competition. I
will try to list down the most commonly used strategies to tackle a Codeforces
Round 2 questions or a similar level based on my experience. Hence that being
summarized, let’s get our hands dirty with some algorithm.<br> So the list,

* **Dijkstra’s shortest path: **Doesn’t show up that often in a question but
always a good deal to look into graph traversal and how to use priority queue.
And God, **Priority Queue** is such an angel, shows up almost everywhere.
[Link](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-using-priority_queue-stl/)
to an implementation.
* **GCD** and **Inverse Modular:** Again, a small code but the use-case in
numerous. [The
link](https://www.geeksforgeeks.org/multiplicative-inverse-under-modulo-m/) will
give you a brief overview. If you’ve done CP(Competitive Programming), you will
again see this notorious guy coming up everywhere.
* **Dynamic Programming:** This is like one of the standard ones every one likes
to ask you in a while. The idea of dynamic programming is simple. Why calculate
something twice? If you see that in the problem statement, few repetitive
calculations can be avoided, a high chance is that DP will get you the desired
complexity. [Fibonacci
](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)and [Longest
Palindrome](https://www.geeksforgeeks.org/longest-palindrome-substring-set-1/)
will help you get the flavor.
* **Greedy:** I always think this a gut feeling approach. Most of the time, you
will end up missing some small corner cases while using this and won’t get the
correct answer. Nevertheless, always, at least for an initial 5 min, think a
possible greedy approach and back-test against some test-cases. If you are good
with coding and implementation, I’ll suggest to code up and give an upload.
Finger’s crossed.
* **Binary Search:** More than often, you are asked to find a minimum or a maximum
number satisfying some property. Chances are, the property has a sequence
property. f(x) => f(x+1) but f(x+1) does not imply f(x). This is best exploited
by binary search. Easy implementation:-

— — — — 1. Convert all input data to **global variable**.

— — — — 2. Make a **check function** for property f.

— — — — 3. [Binary search](https://www.geeksforgeeks.org/binary-search/)
function to find the answer

* **Sorting, Sieve of Eratosthenes …. : **Just some randoms that many times show
up. I will request readers to comment here on some of their personal favorites
observed.
* **Stack: **As it might have been clear by now, I am no expert in the field, more
of a hacker. And I just know that stack can be answer to questions at times. I
don’t know when and many times I get the answer wrong.
* **LONG LONG INT:** This one seems silly, but at some of the times, I just
multiply two integers that go out of range and have wrong answers. So folks, if
there is no limit of memory, **ALWAYS, **use Long Long int.
* **C++14:** This one’s easy. No overselling, but this guy is a goto. Unless your
question involves string manipulation, then **python **is the answer. I know it
will be slow, but a comfortable place to start and who knows, the question
setter was easy on you with the test-cases.
* **BFS and DFS:** One of the easiest ways to traverse a tree, and if you are
storing the right variables, many times, you will get the answer quicker than
you think.
* Again a part for further comments and addition.

Some Advance topics that may be helpful, not always but who knows,

* Min Cut Max Flow
* Grundy Number
* Segment Tree
* Union Find : Specially for number of connected components.

May the Force be with you.

*****

![](https://cdn-images-1.medium.com/max/1000/1*75hcomSr_Llw-f0SePvhcA.png)
<span class="figcaption_hack">Just a pic for the preview screen</span>

**P.S.** *Please see the comments on the original post for links to other good posts for Competitive
Programming 101.*

Originally posted on [Medium](https://medium.com/@rupeshkumar_9557/a-hackers-guide-to-competitive-programming-f3247bf8ce4)
