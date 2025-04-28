# cs3305a-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS3305A Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs-3305a-operating-systems-solved-4/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119599&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3305A Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

Purpose

The goals of this assignment are the following:

• Get experience with the fork(), wait() and pipe() system functions.

• Learn how to use pipe for bi-directional communication between parent and child process.

• Gain more experience with the C programming language from an OS perspective.

Inter-Processes Communications (100 points)

Write a C program that will accept three strings from the user as command-line arguments (for example, X, Y, and Z). Your parent process will create a child process. The parent process will read the first command-line argument into variable X while the child process will read second and third command-line argument into variable Y and Z, respectively. The parent process will write X to the pipe and wait for the child process to finish. The child process will read X from the pipe written by the parent process. After that, the child process concatenates Y and Z to generate Y’ and then concatenates X and Y’ to generate Z’. The child process will write Z’ into the pipe (i.e., shared memory). The parent process will read Z’ from the pipe and output the resulting string. The expected output from your program should look like the following for the arguments “CS”,”3305″, and “is fun!”:

1. parent (PID 2209) created a child (PID 2213)

2. parent (PID 2209) receives X = “CS” from the user

3. parent (PID 2209) writes X = “CS” to the pipe

4. child (PID 2213) receives Y = “3305” and Z = “is fun!” from the user

5. child (PID 2213) concatenates Y and Z to generate Y’ = ” 3305 is fun!”

6. child (PID 2213) reads X from pipe = “CS”

7. child (PID 2213) concatenates X and Y’ to generate Z’ = “CS 3305 is fun!”

8. child (PID 2213) writes Z’ into the pipe

9. parent (PID 2209) reads concatenated result from the pipe (Z’ = “CS 3305 is fun!”)

Hints: fork(), wait(), pipe(), write(), read()

1

Mark Distribution

• Inter-Processes Communications (100 points)

a) Parent reads X from user: 10 points

b) Child reads Y &amp; Z from user: 12 points

c) A pipe is created for communication between parent and child: 20 points

d) Parent writes X into the pipe: 12 points

e) Child reads X from the pipe: 12 points

f) Child writes Z’ into the pipe: 12 points

g) Parent reads Z’ from the pipe: 12 points

h) Output the correct string: 10 point

Computing Platform for Assignments

• Students have virtual access to the MC 244 lab, which contains 30 Fedora 28 systems. Linux machines available to you are: linux01.gaul.csd.uwo.ca through linux30.gaul.csd.uwo.ca.

• It is your responsibility to ensure that your code compiles and runs on the above systems. You can SSH into MC 244 machines (please see the Assignment 1 file transfer tutorial).

• If you are off campus, you have to SSH to compute.gaul.csd.uwo.ca first (this server is also known as sylvia.gaul.csd.uwo.ca, in honour of Dr. Sylvia Osborn), and then to one of the MC 244 systems (linux01.gaul.csd.uwo.ca through linux30.gaul.csd.uwo.ca) (please see the Assignment 1 file transfer tutorial).

• https://wiki.sci.uwo.ca/sts/computer-science/gaul

Assignment Submission

2
