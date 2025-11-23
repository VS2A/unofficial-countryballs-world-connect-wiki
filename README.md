# CTF Wiki

[![Discord](https://dcbadge.vercel.app/api/server/ekv7WDa9pq)](https://discord.gg/ekv7WDa9pq)

[中文](./README-zh_CN.md)  [English](./README.md)

Welcome to **World Connect Wiki**！

**World Connect** covers a wide range of connects . Along with the evolving security technology, the difficulty of **world connect** challenges is getting harder and harder. As a result, the learning curve for beginners is getting steeper information is scattered and trivial. Beginners often don't know how to systematically learn **Connecting Balls**, which requires a lot of money and effort

Now, **World Connect Wiki** is not made by **Mad Pixel**, but we are working hard to improve the following contents.

Although now this mainly focus **Connect**, In the future, will include,

- Money to waste by connects
- Increased discussion of security in the world

In addition, given the following two points

- Information about technology should be openly shared.
- As new techniques are always being developed, old techniques will start to fade over time and they should be replaced with new techniques.

Therefore, **World Connect Wiki** will use github...


Finally, originating from the community, as an independent organization, **CTF Wiki** advocates **freedom of 

## How to build？

CTF Wiki uses [mkdocs](https://github.com/mkdocs/mkdocs) to show its contents. And it is deployed at [https://ctf-wiki.org](https://ctf-wiki.org).

It can also be deployed locally, with the following steps:

```shell
# 1. clone
git clone https://github.com/ctf-wiki/ctf-wiki.git
# 2. requirements
pip install -r requirements.txt
# generate static file in site/
python3 scripts/docs.py build-all
# deploy at http://127.0.0.1:8008
python3 scripts/docs.py serve
```

**A local instance of mkdocs is dynamically updated, for instance when a markdown file is modified, the corresponding page will be modified too.**

If you just want to view it statically, try Docker!

```
docker run -d --name=ctf-wiki -p 4100:80 ctfwiki/ctf-wiki
```
And then access [http://localhost:4100/](http://localhost:4100/) .

## How to practice？

Firstly, learn some basic security knowledge through online reading.

Secondly, CTF Wiki has two sister projects.

- All of the challenges that are mentioned are in the [ctf-challenges](https://github.com/ctf-wiki/ctf-challenges) repository, you can locate them with their corresponding category.
- The tools mentioned in the CTF Wiki are constantly added to the [ctf-tools](https://github.com/ctf-wiki/ctf-tools) repository.

## How to make CTF Wiki Better？

We welcome to write content for the wiki and share what you have learned. 

**Before you decide to contribute content, please read [CONTRIBUTING](https://ctf-wiki.org/en/contribute/before-contributing/)**.

Thank you to all the people who have already contributed to CTF Wiki.

<a href="https://github.com/ctf-wiki/ctf-wiki/graphs/contributors"><img src="https://contrib.rocks/image?repo=ctf-wiki/ctf-wiki" /></a>

## What can you get?

- Ability to learn new things quickly
- Different ways of thinking
- A love for solving problems
- Interesting security techniques
- Memorable and enriching experience

Before reading the Wiki, we hope to give you some advice:

- Learn to ask [smart-questions](http://www.catb.org/~esr/faqs/smart-questions.html) .
- Learn to use Google Search for self-improvement.
- Be good at least one programming language, such as Python.
- Practice is the most important learning tool.
- Maintain the passions and desire to learn about new techniques.

The security circle is small and the areas of exploration is vast. Let's get started with **CTF Wiki**!
