# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Layan Radi Alonazi |
| **Student ID** | [446052091] |
| **University Email** | 446052091@std.psau.edu.sa |
| **GitHub Username** | [Layan-alonazi] |
| **Repository Link** | https://github.com/Layan-alonazi/OS-Assignment1-Layan-alonazi |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1mdbstVqpV7q710_sK3Z_C1EvBDZptUMo/view?usp=drivesdk]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 5, 2026 ,9:45 PM]
**What I did**:
Updated my Student ID in SchedulerSimulation.java
**Details**:
I changed the Student ID to 446052091 then ran the program to make sure it still worked correctly Since the Student ID is used as the seed for the random values I also checked that the program produced my own process information and output.
**Challenges**:
The main thing I needed to make sure of was that I changed the correct Student ID value without changing the rest of the original code.
**Solution**:
I checked the Student ID in SchedulerSimulation.java and ran the program to make sure everything worked correctly.
**Time spent**:
1 hour
---

### Entry 2 - [October 6, 2026, 9:25 PM]
**What I did**:
Implemented Feature 1: Process Priority.
**Details**:
I added a priority value to the Process class. The priority is randomly generated from 1 to 10, where 10 is the highest priority I also changed the ready queue message so the priority is shown when a process is added to the queue I kept the queue as FIFO because the assignment says the priority is only for display and should not change the scheduling order.
**Challenges**:
I first needed to understand where the process is added to the ready queue and where the information about the process is printed
**Solution**:
I followed the addProcessToQueue() method and added the priority there without changing how the queue works. I ran the program and checked that every process showed a priority between 1 and 10
**Time spent**:
2 hours
---

### Entry 3 - [October 7, 2026. 6:52 PM]
**What I did**:
Implemented Feature 2: Context Switch Counter
**Details**:
I added a static counter to SchedulerSimulation The counter is increased each time a process starts running by placing the increment before currentThread.start(). At the end of the program, I printed the total number of context switches In my output, the final number was 26.
**Challenges**:
I needed to decide exactly where the counter should be increased so that it counts every time a process is started.
**Solution**:
I placed the counter increment immediately before currentThread.start() in the scheduler loop Then I ran the program and checked the final output.
**Time spent**:
1.5 hours
---

### Entry 4 - [October 8, 2026, 1:30 AM]
**What I did**:
Implemented Feature 3: Waiting Time Tracking.
**Details**:
I used System.currentTimeMillis() to record when a process enters the ready queue Before the process starts running I calculate how long it has been waiting and add that time to its total waiting time I also added a final table showing the process name, burst time, waiting time, and turnaround time The turnaround time is calculated using the assignment formula: waiting time plus burst time.
**Challenges**:
The main part I had to understand was that a process can wait more than once because it can be added back to the ready queue after its time quantum
**Solution**:
I stored the time when the process enters the queue and recorded the waiting time every time it is selected to run This allows the waiting times from different rounds to be added together.
**Time spent**:
2 hours
---

### Entry 5 - [October 8, 2026, 10 PM]
**What I did**:
Completed MY_WORK.md and reviewed the assignment before submission.
**Details**:
I reviewed the code and checked that the three features were still working I also checked the final output, development log, reflection, technical answers, and the required video information I made sure that the final statistics table was included and that the output showed the context switch count.
**Challenges**:
There were several parts to check, so it was easy to forget a small requirement from the assignment.
**Solution**:
I went through the assignment checklist and checked the code, output, documentation, commits, and video requirements one by one.
**Time spent**:
2 hours
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [8 hours 30 minutes]

**Most challenging part**:
The most challenging part was the waiting time feature because the process can enter the ready queue more than once I had to understand how to measure each waiting period and add them together instead of recording only one value.
**Most interesting learning**:
The most interesting thing I learned was how the ready queue and time quantum work together. I could see this directly in my output when a process did not finish and was added back to the ready queue.
**What I would do differently next time**:
Next time, I would start the documentation earlier instead of leaving most of it until the end I would also write down important output examples while testing each feature because it would make the technical questions easier to answer later.
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*
This assignment helped me understand how threads are created and used in Java The Process class implements Runnable and a Thread is created using the process object The scheduler uses Thread.start() to start the process, while Thread.join() makes the main thread wait until that process finishes its current execution I also saw how Thread.sleep() is used inside run() to simulate the process doing work for a period of time. The ready queue and time quantum helped me understand how a process can run for a while and then continue later Before this assignment, I understood threads mostly as a concept, but seeing the output made the idea clearer to me.


## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*
The waiting time feature was the most challenging part for me I needed to understand when a process actually starts waiting and when that waiting period ends A process can be placed in the ready queue more than once, so one waiting period is not always enough I used System.currentTimeMillis() to record the time when the process enters the queue and then calculated the waiting time before it starts running I also had to make sure that the waiting times from different rounds were added together Testing the output helped me check that the final waiting time and turnaround time were being calculated.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I worked on one feature at a time instead of changing everything at once After each change I ran the program and checked the output to make sure the new feature worked For the waiting time feature I followed the process through the scheduler and looked at where it was removed from and added back to the ready queue. I also used the existing methods such as addProcessToQueue() and the scheduler loop to understand where the new code should go When I was not sure about a calculation, I compared the values in the final table with the formula required by the assignment. This made it easier to find where a change needed to be made before moving to the next feature.
## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading can be used in many applications where different tasks need to make progress at the same time For example, an operating system can use scheduling techniques to give CPU time to different running programs so that one program does not use the CPU forever. Another example is a web server, where different client requests can be handled by different threads This is similar to my assignment because each simulated process is executed by a Java thread Using threads can make applications more responsive because work can be divided between different execution paths.
### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is a program that is running and has its own resources while a thread is an execution path inside a process.
Processes normally have separate memory spaces, while threads of the same process can share memory and are generally cheaper to create. In this assignment, Process is actually a class that simulates an operating-system process, not a real OS process. The actual execution is done by a Java thread using new Thread(process) inside addProcessToQueue().

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process does not finish during its time quantum, it is placed back into the ready queue. For example, my output shows that P4 has a burst time of 12318 ms, while the time quantum is 5000 ms, so it cannot finish in one turn. P4 runs for a quantum, has remaining time, and is added back to the ready queue before it eventually finishes during a later turn. Re-queueing allows the other processes in the FIFO queue to get CPU time instead of letting P4 keep the CPU until it finishes.

Example from my output:
```
P4 executing quantum [5000ms]
P4 remaining time: 7318ms
P4 yields

P4 added to ready queue | Burst time: 12318ms Priority: 7/10

```

**Explanation of example:**
P4 didn't finish during its 5000 ms time quantum because it still had 7318 ms remaining. The scheduler therefore returned P4 to the ready queue so that other processes could run. Later, P4 received CPU time again and completed its remaining execution.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: : P1 is in the New state after the scheduler creates a Thread for the Process object in addProcessToQueue(), before start() is called.

2. **Runnable**: P1 becomes runnable when the scheduler calls currentThread.start().

3. **Running**: P1 runs the code inside its run() method after the thread is started

4. **Waiting**:During Thread.sleep(), P1's thread temporarily stops executing while simulating its work while the main scheduler thread waits for P1 using join(). More precisely, Java reports sleep() as TIMED_WAITING, while join() can put the main thread into a waiting state.

5. **Terminated**: P1 reaches the terminated state after its run() method finishes and the thread has completed its execution.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
An operating system can use scheduling to give CPU time to different processes that are ready to run Each process can receive a time quantum before another process gets a chance to run This is similar to my simulation, where each process has a burst time and the scheduler uses a time quantum of 5000 ms.

**Why Round-Robin works well here**:
Round-Robin is useful when fairness and responsiveness are important because a process cannot keep the CPU forever. Processes that still have work remaining are returned to the ready queue This gives other processes a chance to run before the first process continues.

### Example 2: [Web Server]

**Description**:
A web server may use multiple threads to handle requests from different users Each request can be treated as a separate unit of work, similar to the simulated processes in my program. Threads allow the server to work on different requests without making every request wait for one long task to finish.

**Why Round-Robin works well here**:
A Round-Robin style of scheduling can help give different tasks a fair amount of processing time. This can improve responsiveness when there are many requests The time quantum in the simulation is similar to the limited amount of CPU time given to a task before another task gets a chance.

## Summary

**Key concepts I understood through these questions:**
1.	How Runnable, Thread.start(), Thread.join(), and Thread.sleep() work together.
2.	How a ready queue and time quantum are used in Round-Robin scheduling.
3. How waiting time can be measured when a process enters the ready queue more than once.

**Concepts I need to study more:**
1.	The differences between all Java thread states and how they are handled by the JVM.
2. How real operating systems implement scheduling and context switching at a lower level.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
