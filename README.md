# Passcode Guide

You are closer to the password security.

## Content

- [What is Passcore?](#what-is-passcore)
- [How does Passcore work?](#how-does-passcore-work)
- [Why Passcore?](#why-passcore)
- [LICENSE](#license)



## What is Passcore?

After seeing a new project, almost everyone may ask a very similar question: What's it? Especially projects like Passcore, which has no detail information.

Back to the main point, what is passcore. In some ways, passcore is password generator which is a cryptography tool intends to protect your password.

Wait, don't move away, passcore is not a kind of traditional tool, it is a new, special solution to solve password issue. Let's move forward to understand how it works and why passcore.



## How does Passcore work?

In some ways, passcore is a digest algorithm. It combines three strings into one, and keep it with a high strength. Each part will influence the result completely.

```text
Master Key    ─┐
Password      ─┼──────────→ High-Strength Password
Enhance Field ─┘
```

Maybe you want to ask why we need 3 strings? Isn't one is enough?  
This is a good question. Try think: how to remember a long string without any mistake? It is a really hard task for everyone.  
However, if we seperate it into three parts, you only need to remember one simple part and every thing will be changed. So that is why we set to three fields.



## Why Passcore?

### 1. Cryptography Security

Security is the most important thing. You can access our core to find how we realise the core part. Here is the link:  
<https://github.com/Passcore/core>

### 2. Open Source

Maybe someone may say open source is a basic operation.
However, if you paid attention to current password related field, you may find most of famous tools need to be charged and are closed-source.
Open source is one of the strengths of passcore. Most of Passcore components are licensed under [OKZL](https://github.com/KevinZonda/OKZL/) series.
Most of passcore programmes are licensed under [OKZPL](https://raw.githubusercontent.com/KevinZonda/OKZL/main/okzpl/LICENSE), a derivative license from MIT license by [KevinZonda](https://github.com/KevinZonda).
According to opensource community, we can find do our cryptography algorithms work fine.

### 3. No Storage Needed

Different to traditional password management tools, the core part of passcore does not need any storage. If you do not trust storaging in disk, passcore will not be a bac solution.

### 4. Hard To Wild Kids

Wild kids will not know what this application for, so it may help prevent from their naughty.

### 5. Far From Internet

Core part of passcore does not need any Internet connection, that means most of the threats will disapear.



## LICENSE

Proudly be licensed under ![CC-BY-NC-ND](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-nd.svg)
