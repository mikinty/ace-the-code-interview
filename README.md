# Ace the Code Interview

Technical code interviews are integral to company hiring standards, but also
scary to any candidate. Depending on the company, there are standards for how
candidates are evaluated. The nuance is that doing well in a coding interview
doesn't just mean having a 100% right solution, or being able to code something
up fast. So e.g., some people think they did well in an interview and have no
idea why they got rejected, when in reality they were maybe too rash in their
coding, had poor style, or was hard to work with during the problem.

I'll discuss a few main types of of interviews, and what companies are generally
looking for in them.

## Signal

The interviewer can evaluate you in a variety of ways, but generally we call
this "signal," meaning certain things you do correspond to a rubric (sometimes
literally) they are grading you against.

Depending on what type of interview you have, there are different signals, but
some general signals are

1. You are a pleasant person to talk to. Don't annoy them, which can go both ways in terms of annoying them by being too suck-up, or by being rude to them.
2. You are able to effectively communicate your ideas to your interviewer.
3. Your code is readable and efficient. This can mean a variety of things, including:
    - **Formatting and style**: it may not matter to compile code, but I guarantee you that if you format your code while writing, have good spacing, and follow some sort of styling code, your interviewer will at least subconsciously feel better
    - **Good variable names**: If you just use random variable names it can confuse the interviewer
    - **Modular code**: Your code should not be this magical black box of code
    - **It is understandable**: You have to remember that interviewers probably don't think about interviewing all the time. So if you come up with a solution that might throw them off or is hard for them to understand, they will get frustrated and not want to read your solution.
4. You are familiar with the programming language. This should go without saying, but there are quite a bit of people I have interviewed where it's very clear they have not used the language very much, and don't understand it beyond as a way to write their solution. Having a deeper understanding of how the language works will prove useful when you are explaining things to your interviewer, and also give your interviewer more confidence in your abilities.

## Algorithms (General Questions, Leetcode Style Questions)

These are very straightforward questions, and there are 2 ways to do well on these

1. Be a coding god and just code it in one go: this is fine, but unlikely unless you've seen the question before (luck) or you're just really good at coding
2. Work with the interviewer to come up with a reasonable algorithm, translate thoughts into code effectively, and demonstrate that the code works, with the expected runtime and space complexity.

If doing approach 1. is pretty straightforward, either you don't really need this guide, or you just memorized a huge bank of problems. I think the general principle is that if you've done around 300 random Leetcode problems, you should be pretty set here. Of course, you need to also have solid CS foundations, but with that, plus seeing a ton of questions, this category should be all set for you.

### If you're a normal person

This is not to downplay your intelligence -- doing 1. is a valid approach -- but it's not very "organic" and may be hard for the interviewer to follow, or the interviewer may get suspicious.
The more normal approach to do these problems is

**Prep:**

1. Review data structures
2. Do a healthy amount of Leetcode or problem practice
  - When you do these problems, you should strive to actually spend time thinking about the problems and solving them, not just looking up solutions. It may be surprising, but spending time exercising your brain _does_ help with your problem solving skills.
  - You should try to write test cases yourself, so you can practice verifying that your solution is right. This will also force you to do some debugging on your solution, which is a vital part of your coding skills.

**During the Interview:**

1. Clarify with the interviewer assumptions about the problem
2. Come up with a solution that is reasonable. It doesn't have to work in all cases yet here in general. Definitely clarify if your solution is ok to proceed coding. It doesn't make sense to start coding until the interviewer
  a. Follows what you're trying to do
  b. Wants to see you code a particular solution
3. When you code, adhere to general good coding principles, such as naming variables properly, re-using code where appropriate, and writing legible code
4. After you are done coding (hopefully you make it to this step), you should run trough the code with the interviewer, and show them it works. Here is where you should show that the edge cases work, and then do a general case.
5. You should conclude with the runtime and space complexity of your algorithm.
6. If there are improvements to your algorithm, you should mention what could be improved. Note that you shouldn't annoy your interviewer by pointing out improvements that are trivial and don't really help.

## Systems Questions (OS, Distributed, Lower Level)

Correctness is VERY important here. Never start coding a question until you are sure you've covered most edge cases (the obvious ones) and the general case of course.

**Prep:**

1. Strict correctness in complicated systems is usually something you do at the systems level, like Operating Systems, Distributed, etc. If you were really good at these topics, then you'll do well for these type of topics.
2. Learning how to prove functions are correct can be very beneficial. Think pre condition, invariants, and post condition

**During the Interview:**

NOTE: A pitfall is that you code something really quickly, but it doesn't work, and you have to get through many iterations before it works. This frustrates the interviewer, as they
1. Have to find your mistake, this can be excruciating, and you should've done it
2. Point it out to you, even though you should've done it
   - (Optional) wait for you to realize it, and be frustrated that you don't see the mistake

Therefore, it is a good idea to
1. Discuss your solution conceptually first, and even if it makes sense at that level, just try some edge cases so you know it can handle them. Note that although this means you might have to keep a lot of information in your head, this can be a plus if it is well-organized.
  - A good way to do this systematically is to do a "mini design doc" with your interviewer, clarify edge cases and operation, before you try to start coding
2. While you code your solution, mention any difficult spots that you run into, and why you are doing certain things.
3. Also prefer **correctness** and **readability** over efficiency at first. If the interviewer asks you to optimize, they will, and this is generally easier to do with a working solution than a broken one.

## System Design

There's a great book called [System Design Interview: A great overview on what questions to expect on system design interviews](https://amzn.to/3jpApQd) which gives over this process in more detail.

### Design

TBD

### Coding

TBD
