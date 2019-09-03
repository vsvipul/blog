---
layout: post
title: Microsoft Internship Interview Experience 2020
---
I recently participated in on-campus internship interviews for Microsoft and got selected. I am sharing the interview experience for the same here.

![microsoft_logo]({{ site.baseurl }}/images/microsoft.png){: .center-image }

## Online Round

Online round was conducted on mettl.com. It was a weird platform as it had no support for C++ 11. Only C++ 5 was supported. Also, instead of strings, the parameters were passed as char* , which took some time to get used to. Practicing on this platform before hand will be benefecial for anyone new. 

About 73 students participated in this round.

Questions were framed differently, with a story. I am only adding the implementation part here for 1 and 2.

### Questions-
1. Checking for balanced parantheses. Solution [here](https://www.geeksforgeeks.org/check-for-balanced-parentheses-in-an-expression/).
2. Minimum number of bracket reversals needed to make and expression balanced. Solution  [here](https://www.geeksforgeeks.org/minimum-number-of-bracket-reversals-needed-to-make-an-expression-balanced/).
3. Your Pikachu is fighting Mewtwo in a pokemon battle. Your Pikachu has a set of attacks which have been provided to you as an array of strings and another string describing the entire battle. Pikachu can win only if it performs all the attacks one after the other in any sequence. Write a function which returns the index at which its winning move starts, else return -1. O(N) solution was expected.
Eg. Input: [thunderbolt, slam, agility, growl]
kickpunchthunderboltgrowlslamagilityheadbutttackle
Output: 9

About 46 students passed the Online round and made it to group fly round.

## Group Fly Round
In this round, we were asked two questions for which were aked to write code on paper, which were then checked and evaluated. 

### Questions-
1. A 2d matrix was given and some obstacles in between. We were supposed to find the shorted path from first column to last column avoiding the obstacles. 
2. We were given some numbers and were asked to join them to form the largest number. Solution [here](https://www.geeksforgeeks.org/given-an-array-of-numbers-arrange-the-numbers-to-form-the-biggest-number/). 

About 19 students made it to the interview stage. 

## Technical Round 1

1. Minimum Characters to add to a string at the front to make it a palindrome. O(N) solution expected. Solution [here](https://www.geeksforgeeks.org/minimum-characters-added-front-make-string-palindrome/).
2. What mobile apps do you use? Do you use WhatsApp? How will you write tests for the home screen of Whatsapp? What things will you test? Why is testing important in development?
3. Get a mirror tree from a given binary tree. Solution [here](https://www.geeksforgeeks.org/write-an-efficient-c-function-to-convert-a-tree-into-its-mirror-tree/).
4. What are the different HTTP methods used to send request and get a response? What is the difference between GET and POST?
5. Given an array, find the first pair with a given sum K. Return -1 if not found. Solution [here](https://www.geeksforgeeks.org/given-an-array-a-and-a-number-x-check-for-pair-in-a-with-sum-as-x/).
6. Then, he went on to ask about my GSoC project and why those changes were required and how were they implemented.

## Technical Round 2

1. How will you design a service like Github (with only Push and Pull features)? How will you address performace, scalability, failures, fail-safe mechanisms, data loss, data availability? Given users info from some countries, where in the world would you place your servers to get max performance? How else can you increase the performance, so that load on the servers is less?
2. Print all nodes at distance K from a given node. Solution [here](https://www.geeksforgeeks.org/print-nodes-distance-k-given-node-binary-tree/).
3. Given start and end time for some number of jobs. Find the maximum number of jobs that can be completed. 
4. Find union and intersection of a Linked List. How is a set and unordered_set implemented internally in C++ ?
5. Explain ACID properties. 

## Technical Round 3 / HR

1. What is the difference between authorization and authentication?
2. How will you implement these in the database if you are building an e-commerce website ? Design the database for the same. How will the features and front-end differ for each type of user?
3. Why have i not done any AI/ML projects?
4. What are my areas of interests in Computer Science? Why a particular interest in these areas?

8 students were selected by Microsoft for this internship, and i was one of them. I am thankful to everyone who played a role in this, especially the Career and Placement Cell of my college. 

## Some tips -
1. Carry your own pen to the interviews. This creates a good impression.
2. Wear ironed formals. No need to wear ties. Just a formal shirt and pants with clean shoes will do.
3. Try to read something about System Design before hand. Don't say that you haven't studied a particular topic during the interview. This creates a negative impression.
4. Stay calm even if you are not able to solve a problem. Ask for hints from the interviewer. They are there to help you.
5. It's generally better to say that you don't know an answer if you don't have any idea about it, than to speak anything.
6. Smile and show interest. Ask good questions at the end of the interview.
7. Get a good sleep before the interview. 
8. Build a good resume by doing some good projects (try for GSoC and ICPC, if possible). 
9. Practice a lot in the summer vacations before the interviews.
10. Also work on your communication skills, if you lack in those.