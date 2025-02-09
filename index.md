# Lab Report 2 - Servers and Bugs (Week 3): Ruben A Gonzalez
---
# Part 1: Write a web server called StringServer
Below is the code used to run StringServer.
![Image](StringS.png)
After typing a String such as hello in /add-message?s=hello The website will refresh the text...

For this method we are checking to see if the path contains "/add" and "=". If so we can print what is typed after = .
![Image](hello.png)

If you were to type /add-message?s=how are you ... You'll see hello /n how are you ... in the website.

![Image](helloh.png)

---
# Part 2: Choosing one of the bugs from lab 3
- A failure-inducing input I found in Lab 3 would be inside the file LectureExamples.java. I noticed that method sumEvenIndices has a
bug that would not add the evens correctly.
![Image](ReverseTester.png)

The code below displays both methods( reversed and reversedInPlace ) after they have been fixed.
![Image](FixedCode.png)

- The method averageWithoutLowest did not seem to induce a failure. This method was tested with multiple numbers sorted in different ways and returned the correct value.

- An input that doesn't include a failure as a JUnit test can be seen in Tester ArrayTest.java. When the input in testReversed is null there is no way to detect if there's an error with the reverse method.
- A failure-inducing input I found in Lab 3 would be inside the file LectureExamples.java. I noticed that method sumEvebIndices prints out 19 instead of 15. The reason is due to it having a bug that would not add the evens correctly.
![Image](TestSum.png)
The bug in the code was it incrementing i+2 while grabbing [i+1] from the array. This was the bug in the code that caused it to not sum the even numbers.

---

# Part 3: What I've learned
After doing lab 2 and 3 I felt that I was able to learn more about how to start a web server using Github Desktop, and VSCode. My understanding of github has also improved. Another thing that I got a lot of experience doing during these two labs was to push my code using Github desktop. I enjoy knowing that these skills will help me a lot in the future.
