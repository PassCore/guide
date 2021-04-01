# Passcode Guide

You are closer to the password security.

## Content

- [What is PassCore?](#what-is-PassCore)
- [How does PassCore work?](#how-does-PassCore-work)
- [Why PassCore?](#why-PassCore)
- [LICENSE](#license)



## What is PassCore?

After seeing a new project, almost everyone may ask a very similar question: What's it? Especially projects like PassCore, which has no detailed information.

Back to the main point, what is PassCore. In some ways, PassCore is a password generator which is a cryptography tool that intends to protect your password.

Wait, don't move away, PassCore is not a kind of traditional tool, it is a new, special solution to solve password issues. Let's move forward to understand how it works and why PassCore.



## How does PassCore work?

In some ways, PassCore is a digest algorithm. It combines three strings into one and keeps it with high strength. Each part will influence the result completely.

```text
Master Key    ─┐
Password      ─┼──────────→ High-Strength Password
Enhance Field ─┘
```

Maybe you want to ask why we need 3 strings? Isn't one is enough?  
This is a good question. Try to think: how to remember a long string without any mistake? It is a really hard task for everyone.  
However, if we separate it into three parts, you only need to remember one simple part and everything will be changed. So that is why we set to three fields.



## Why PassCore?

### 1. Cryptography Security

Security is the most important thing. You can access our core to find how we realise the core part. Here is the link:  
<https://github.com/PassCore/core>

### 2. Open Source

Maybe someone may say open source is a basic operation.
However, if you paid attention to the current password-related field, you may find most of the famous tools need to be charged and are closed-source.
Open source is one of the strengths of PassCore. Most PassCore components are licensed under [OKZL](https://github.com/KevinZonda/OKZL/) series.
Most PassCore programs are licensed under [OKZPL](https://raw.githubusercontent.com/KevinZonda/OKZL/main/okzpl/LICENSE), a derivative license from MIT license by [KevinZonda](https://github.com/KevinZonda).
According to opensource community, we can find do our cryptography algorithms work fine.

### 3. No Storage Needed

Different from traditional password management tools, the core part of PassCore does not need any storage. If you do not trust storing in the disk, PassCore will not be a bad solution.

### 4. Hard To Wild Kids

Wild kids will not know what this application for, so it may help prevent their naughty.

### 5. Far From Internet

The core part of PassCore does not need any Internet connection, which means most of the threats will disappear.



## LICENSE

Proudly be licensed under ![CC-BY-NC-ND](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-nd.svg)
