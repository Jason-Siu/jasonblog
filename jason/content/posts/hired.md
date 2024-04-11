---
title: "How I got a role as an Application Security Analyst at Paycom"
date: 2024-04-11T16:28:52-05:00
draft: false
toc: true
images:
tags:
  - cybersecurity
  - hiring
  - penetration testing
  - job hunt
  - paycom
  - interview
---

## Introduction

Hey everyone.

Hope everyone is doing good.

The job hunt in this industry is absolutely brutal. Not just in cybersecurity, but all of tech.

Things like software engineers, developers, IT, and cybersecurity - the job market is horrific as of late 2023 and early 2024. It's so bad that even experienced veterans in the field are struggling too.

I recently accepted the role as an application security analyst at Paycom.

So, I am writing this in hopes that it helps someone who comes across this blog post, particularly anyone who is looking to be an application security analyst at Paycom.

## How I got the interview

First, I applied through the company website. A couple of days later I got an email inviting me to an interview.

My resume had my projects, internships and experience on it. It also had that I was a committee speaker in CSG, the cyberescurity club at UT Dallas and that I was CompTIA Security+ certified.

For Paycom, there are 3 interviews and 1 assessment.

## Interview 1
The first interview is with a recruiter. This interview was just basic questions about web application security (XSS, hashing vs encryption, SQLi, OWASP Top 10). 

Just make sure you explain well, it's mainly "explain xyz" questions. They also asked at the beginning "tell me about yourself", and this happened in all interviews.

Remember, the recruiter (though technical) just knows very basic information, so all you need to have to more information than them. I would intentionally sometimes go off into tangents about different technologies I would use and how they work just so that I would appear knowledgeable, smart and curious.

Because to the recruiter, I actually am.

Remember that this interview is only the first one, so you don't really need to be perfect, it's just a matter if you're knowledgable enough - which comes in both explaining things well enough and what things you know.

It really felt like I was teaching the interviewer, as opposed to just standard Q&A like a regular interview.

Once passed, they will send you an assessment after this. 

## The Assessment

The assessment is a 25 question standard test which has primarily multiple choice, but also a few "Select all that apply" questions.

This is slightly more difficult than the technical interview, and honestly a lot of the difficult questions are from here, since they were trickier as with a lot of multiple choice tests. These covered more topics on top of the basic web application security questions from the first interview, but still mainly surface level on those topics.

The topics included: 
 - IDOR
 - OWASP Top 10 (Make sure you know all of them)
 - PHP insecure code review
 - Mitigating and preventing attacks
 - CSP (Content Security Policy) and output encoding
 - JWT (JSON web token)
 - identifying examples from the OWASP Top 10, (ie: which one of these is security and data integrity failure)
 - interception proxies and needing a new browser certificate
 - SQLi vs XSS and knowing the different types of SQLi and XSS
 - HTTP Status codes (100-199, 200-299, 300-399, 400-499, 500-599)
 - what is robots.txt, what's it used for?
 - Thinking like an attacker (2 questions give you a screenshot, and they ask what attacks would you do)
 - clickjacking, mass assignment, content spoofing
 - MD5 (just know that it's a weak hashing algorithm)
 
I didn't have questions about WAF, OSI model, DNS, or networking stuff.

I had at times where I was stuck between 2 choices, which is where I found it tricky.

Anywho, after that they will let you know that you passed.

## Interview 2

This interview with 2 team leads and it was ALL technical questions related to the basics of cybersecurity (CIA Triad, authentication, I dont remember the rest) and some application security questions like OWASP top 10, SQLi, XSS, encryption, hashing. But also on how to apply those concepts to a real scenario. Examples are:
 - How should you store passwords? (Strong hashing algorithm with work factor and salting, but also the users having strong passwords will help too)
 - How would you implement secure authentication? (Can use a third party authentication, OAuth, or implement secure password checking, with password policies, lockouts, etc - alot of answers work here)
 - Explain broken authentication from OWASP Top 10 (super simple but also give multiple ways to mitigate)
 - Hashing vs Encryption, and how does it related to CIA Triad? (confidentiality for encryption, and hashing for integrity, then explain the differences between hashing and encryption)
 - Explain SQL Injection (I explained it briefly but then I went on about different types of SQLi and how you would actually attack a system)
 - I can't remember the rest.

Aside from the "Walk me through your resume" and they also dug deeper on a project that I mentioned related to penetration testing.

For the technical questions, some of these were repeat questions from the first interview (basically "explain xyz" questions). They will probe deeper questions based on your response for clarification, which is good if you know what you're talking about since it makes you look smart on a topic that you're already familiar with.

They gave me example PHP code and I listed the vulnerabilities in that code (it's a super basic 10 line ish program, nothing complex).

There was no behavioral questions.

This interview that I had seemed like she knew more than the interview.

I wanted to make it seem like a conversation, so when I was explaining things to her when giving my thought process, I would intentionally ask, "Are you familiar with this?", "Have you heard of that?". And sometimes she would say no, which made me feel WAY more confident that I knew more than the interviewer (who is a team leader).

So it was basically another teaching interview and a back and forth conversation. I would also look for if she nodded to see if she approved of my answer.

One question she gave was a super obvious question ("Should you always have a strong password for an admin user?"). 

I said at first yes because an admin user has more permissions than a regular user and can make changes to a system. I paused and thought about the question itself more and why she was asking it. 

I then said, it just depends though, like if it's for an application that doesn't have sensitive information, can't really be changed (static website), then in those rare cases, then no. 

She then nodded.

I continued with in general, yes an admin user should have a strong password.

Basically, I think she wanted to know if I would give a naive answer, but in my opinion the question was just "too obvious", so I had to give more clarity.

I had already passed the Security+, so basic in general cybersecurity questions I was familiar with.

At the end, I asked her, "How did I do?"

She said I did good, and I would have the recruiter contact me if I made it to the next stage.

And that's what happened.

Basically this interview is the same as the first, just show off your knowledge and approach from a teaching perspective. Check in with them if they are following, just like a teacher.

I went deep in explanation just because it gives you more time of talking (so that the interviewer doesn't ask many questions to trick you) but also that you look smart and it also gives you more opportunity to check if they know what you're talking about.

And if they don't, that makes you look like an expert.

Always give more than 1 way to mitigate an attack.

For super obvious scenario questions, give an "it depends" response to make you look smart, then explain.

## Interview 3

This interview was with another 2 team leads, but they have been in the company longer.

This interview, I wasn't able to teach as much since they knew way more than the previous 2 interviews, but I still explained my deep thought process.

They gave me a lot more scenario questions, which I didn't really prepare for (it's harder to since they can come up with any hypothetical scenario). 

There was no programming questions, unlike what the recruiter told me.

Examples were:
 - How would you deal with a 0 day exploit? (hard to prevent, but make your detection is solid, and explain an example incident response) 
 - Explain buffer overflow to a nontechnical person (just give an analogy, and use basic words. I also that this before I gave my answer "I would make it as simple and brief as possible")
 - How would you attack a login page (nmap, gobuster, LFI, XSS, SQLi, insecure javascript code, etc - go off on your rant here)

When you are done explaining, they might probe deeper questions of what your response included. For example, if I said nmap, they would've asked after "What's in an nmap output?".

I would then explain the output but also what it's used for when attacking a system.

Notice how I always give an explanation on top of the answer. Keep in mind in this interview, sometimes I felt like my answers were taking too long so I would address it on the spot "I know this answer is a little long, but I feel the need that it's necessary and part of the thought process when you're attacking a system". 

If you say that multiple times, just make sure to reword it. You can say the same thing multiple times just reworded since it will sound more natural and less robotic.

I was also asked 1 behavioral question "How would you deal with a conflict with a coworker?"

Super simple response if you've prepared for it already beforehand (which I did)

I asked some questions at the end, but my final one was "How did I do?"

They asked it was basically all good, with exception of my nmap explanation and that it was a little ranty.

After that I got a call a day after saying that I got it and for onboarding steps.

## Tips and Tricks

Aside from the obvious tips like
 - prepare beforehand
 - dress nice
 
You want to
 - speak slowly but loud (like a presenter on stage)
 - give in depth explanations (buys you more time, you look smart, and less questions from interviewers)
 - check in with them while explaining ("Are you familiar with that", "Do you know what that is?", "Have you heard of that?")
 
Also, I personally had my degree and my Security+ certification hanging in the background, similar to a doctor. It makes you look smart on first impression.

Anywho, this is by far my longest blog post, I hope it was helpful.

Jason
