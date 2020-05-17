---
layout: post
title: Salts and Hashes
cover-img: /assets/img/path.jpg
tags: [websecurity, random]
---

![](https://cdn-images-1.medium.com/max/1000/0*m12Mo1pHiOM3c5xL.png)
<span class="figcaption_hack">Source:
[https://www.thesslstore.com/blog/difference-encryption-hashing-salting/](https://www.thesslstore.com/blog/difference-encryption-hashing-salting/)</span>

For the time being, I want you p33ps to ignore the general meaning of these
words used in daily context and give a new meaning to them for the current time
being.

I guess more than often, you have heard about 1000s of accounts’ passwords being
compromised and leaked online. All this may have given you thought that these
Computer science guys, try to make an AI that can automate phone calls, can’t
they solve this issue of data leaks.

Turns out, actually, they have solved the issue of such compromises, but more
than often, the companies haven’t been holistically following the protocols
resulting in such matters.

So let me try to tell you the story of what happens when you try to login to
*yourSocialMedia.com* .

* **The website sends you a webpage that you will see and a public key which your
browser will see.**

*“What is a public key, Rupesh?”.* Glad you asked.

You can find a really great answer to this question
[here](https://medium.com/@vrypan/explaining-public-key-cryptography-to-non-geeks-f0994b3c2d5),
which I encourage you to check out. A simple answer is that now the
*yourSocialMedia.com *will know that it was you who sent the message. No-one in
the middle of your communication channel like telecom company, government, even
FBI :P will have any clue about what you are posting to the website.

![](https://cdn-images-1.medium.com/max/1000/0*aEWNSEIQNMshApZC.jpg)
<span class="figcaption_hack">For illustration purposes only</span>

A good check of such security is in the browser. On the left of the website
name, you will see a lock symbol which is a proof of the same. **Always check
for the lock symbol, when you are doing any crucial communications like bank
transaction, or anything privileged.** The exact meaning of the logo can be
found [here in
detail](https://www.maketecheasier.com/padlock-in-browsers-address-bar/). And
one of his statements sums it well, *the padlock means you’re on a safe
connection, not a safe website. *The website still knows what you are sending,
but no-one in mid will know.

* **I send my ID and password to the website through a secured method, and they
will know it’s me. They need to store my password to match right.**

*NOOOOOOOOOOOO***, ***not really***.**

This is where the **HASHing** comes in. Hashing work in a simple way. It takes
whatever your input is, and applies an irreversible function so that the output
is now a fixed-size string, 256 characters in general. Guessing a 256 random
sized string is very tough. The best thing about hash functions is that it’s
irreversible. You cannot tell the input password even if you know the output
hash. You can check a detailed explanation for the hash
[here](https://komodoplatform.com/cryptographic-hash-function/).

![](https://cdn-images-1.medium.com/max/1000/0*JxNLPum2L9ry-SPY)

Just to put in simple words, there is a computer science technique to store
something else instead of a password in the database, and knowing that won’t
give you the password. But that stored value is enough to check that the
password is correct.

* *Hey, you mentioned salt. Was it just for fun, or does it have significance?*

A detailed story can be found
[here](https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/)
for salts. In a normal tongue, pun intended, salt makes sure that 2 people, even
using the same password, don’t have the same hash output stored. By uniquely
assigning another random text for every user. Salt is a text added to your
password to calculate a new text that can be further used as input to the hash
function.

E.g.

(yourPassword + Salt1) goes to hash and gives output A.

(youFriendsPassword[same as your’s] + Salt2) gives B[not the same as A].

So, even though both used the same password, an attacker won’t get a clue of
that.

Long story short, it is trying to even protect you when you end up using a
common password like “password”, “12345678”, “I’m Shivaji the boss, cool”.

![](https://cdn-images-1.medium.com/max/1000/0*nMYvupVERMm75I2d)
<span class="figcaption_hack">Cool, but not safe.</span>

**Never keep such a password**. There is a simple method known as [dictionary
attack](https://en.wikipedia.org/wiki/Dictionary_attack). If your password is a
simple word of everyday use or any of the most used passwords, even a guy
sitting with a laptop can match it by hit and trial.

* *So after I am logged in, now what. All done??? I’ve heard something about
cookies.*

Ya, that is what carries over for further procedure. The cookie becomes your
unique identifier, which also, at times, stores when you logged in, from which
device, and was it authenticated or not. The cookie is a very *sacred* thing,
and now the browser has to keep it safe from any attacks.

Cookies are just stored in your computer somewhere. If anyone gets access to
your computer, it can just pretend as you and any website can’t have a clue. So,
don’t ever give physical access to the device to any untrusted personnel.

![](https://cdn-images-1.medium.com/max/1000/0*9Q4wyY79TcHr4ZpI.png)

* Thanks, but do all the company take the pain to complete this process. Isn’t it
simple to code if (a == b) allow; else don’t.

![](https://cdn-images-1.medium.com/max/750/0*ZcMMvrJpfgKISZmf.png)
<span class="figcaption_hack">Source:
[https://me.me/i/using-oauth2-storing-cryptographically-hashed-and-salted-passwords-locally-storing-12006243](https://me.me/i/using-oauth2-storing-cryptographically-hashed-and-salted-passwords-locally-storing-12006243)</span>

Ya, there is an easy way to do things, and there is the right way. It comes down
to the reputation of a site and how much you can trust it. Do the websites that
we know of, do it the easy way or right way. The news gives you the idea all the
time. But, experts have made useful approaches and techniques. Various
certification companies make this check and give them green signals so that web
users can trust them.

In the end, I will just mention that I am not a security expert, and this is
just what I learned through my course and some personal exploration. There are
many trickier methods to even break some seemingly secure systems, but it’s not
as simple as an actor making some keyboard presses in a movie and getting access
to anything anywhere.

**TL;DR**

Just keep a “**tough to guess**” password, something not related with you
personally or any common dictionary words. Make sure you are using a **secure
network by checking the lock symbol** on the address bar of your server. And do
not click any **malicious link on a random website**.

> **There is no such thing as free lunch.** So, if something seems too good to be
> true, most probably it isn’t. Like African prince trying to give you a million
dollars only after he knows your bank details.

> Thanks for reading ❤

Originally posted on [Medium](https://medium.com/@rupeshkumar_9557/salts-and-hashes-8c937e8815e8)

