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
| **Full Name** | Rimas bint Khaled bin Ali Al-Dumaykhi |
| **Student ID** | 445052097 |
| **University Email** | 445052097@std.psau.edu.sa |
| **GitHub Username** | rimass26 |
| **Repository Link** | https://github.com/rimass26/OS-Assignment1-Rimas-AlDumaikhi |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - September 22, 2026, 2:30 PM
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

### Entry 1 - October 2, 2026, 7:00 PM

**What I did**:
Started the assignment setup and completed the first two code features.

**Details**:
- Created and prepared my GitHub repository from the starter project.
- Updated `SchedulerSimulation.java` with my student ID.
- Added the Process Priority feature using a random priority from 1 to 10.
- Added a getter for the priority and displayed the priority when a process enters the ready queue.
- Added the Context Switch Counter and incremented it before `currentThread.start()`.
- Printed the total number of context switches at the end of the simulation.
- Saved the work using separate GitHub commits.

**Challenges**:
I needed time to understand where each feature should be added in the existing code, especially the ready queue section and the thread execution part.

**Solution**:
I reviewed the relevant parts of `SchedulerSimulation.java` step by step and added each change separately. I checked the code after every small modification before continuing.

**Time spent**:
Approximately 1.5 hours.

---

### Entry 2 - October 5, 2026, 8:00 PM

**What I did**:
Completed the third feature, fixed the priority implementation, and tested the full program in VS Code.

**Details**:
- Fixed the Process Priority feature by restoring the `priority` field and its random initialization.
- Added `arrivalTime` and `completionTime` using `System.currentTimeMillis()`.
- Added methods to calculate waiting time and turnaround time.
- Created a final summary table showing Process Name, Burst Time, Waiting Time, and Turnaround Time.
- Added a separate map to keep each process only once in the final table.
- Installed the Java Extension Pack and JDK 17 to run the program in VS Code.
- Ran the complete simulation successfully and verified the final context switch count and timing table.

**Challenges**:
The main challenge was running the program because the first installed JDK version was Java 8, which did not support the `String.repeat()` method used in the starter code.

**Solution**:
I installed JDK 17, configured VS Code to use it, and ran the program again. After that, the simulation completed successfully without compilation errors.

**Time spent**:
Approximately 3 hours.

---

### Entry 3 - October 6, 2026, 12:00 PM
**What I did**:
Reviewed my completed program and started working on the assignment documentation and reflection section.
  
**Details**:
- Reviewed the three implemented features in `SchedulerSimulation.java`.
- Rechecked how the ready queue, threads, time quantum, and context switches work in the program.
- Reviewed the final output from the successful VS Code execution.
- Checked the waiting time and turnaround time results in the final table.
- Started preparing the reflection answers in `MY_WORK.md` based on my actual implementation and testing experience.

**Challenges**:
I reviewed the code and the program output again and used specific examples from my implementation instead of writing general explanations.

**Solution**:
I reviewed the code and the program output again and used specific examples from my implementation instead of writing general explanations.

**Time spent**:
Approximately 1 hour.

---

### Entry 4 - October 6, 2026, 1:00 PM
**What I did**:
Completed the reflection and technical answer sections in `MY_WORK.md`.

**Details**:
- Answered the four reflection questions using examples from my own work.
- Reviewed the differences between threads and processes.
- Explained the Round-Robin ready queue behavior using my program output.
- Described the thread lifecycle using `Thread.start()`, `Thread.join()`, and `Thread.sleep()`.
- Added real-world examples of Round-Robin scheduling.

**Challenges**:
The main challenge was making sure the answers were specific to my own code and output instead of being general explanations.

**Solution**:
I reviewed `SchedulerSimulation.java` and the output from my successful run, then used those details in each answer.

**Time spent**:
Approximately 1 hour.
---

### Entry 5 - October 7, 2026, 12:00 PM
**What I did**:
Performed a final review of the code, documentation, and GitHub repository before submission.

**Details**:
- Verified that the repository is public and correctly named.
- Checked that my student ID is correct in `SchedulerSimulation.java`.
- Confirmed that all three required features are working.
- Reviewed the commit history to make sure the work was saved in separate meaningful commits.
- Checked `MY_WORK.md` for missing placeholders or incomplete sections.
- Ran the program again to confirm that it compiles and completes successfully.

**Challenges**:
The main challenge was making sure no required item was missed before the final submission.

**Solution**:
I used the final checklist in `MY_WORK.md` and reviewed each requirement one by one.

**Time spent**:
Approximately 45 minutes.
---

### Entry 6 - Optional - Date and Time
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

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

**Your Answer:** 

I learned that threads allow different tasks to run in an organized way. In this assignment, each simulated process was executed using a Java thread. I learned that `Thread.start()` starts the thread and `Thread.join()` makes the main program wait for it. I also saw how `Thread.sleep()` was used to simulate execution time. The Round-Robin scheduler gave each process a limited time quantum. This helped me understand how threads and CPU scheduling work together.

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** 

The most challenging part was understanding where to add the required features in the existing code. At first, I was not sure where the priority, context switch counter, and waiting time should be added. I also had a problem running the program because Java 8 did not support one method used in the code. This caused compilation errors in VS Code. I needed to review the code carefully and test each change separately. After installing JDK 17, the program worked correctly.

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** 

I solved the problems by working on the assignment step by step. I reviewed the code before making each change. I tested each feature separately instead of changing everything at once. When the program did not run, I checked the error message in VS Code. I found that the Java version was the problem and installed JDK 17. After that, I ran the program again and checked the final output. 

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:**  
Multithreading can be used in applications that need to perform several tasks at the same time. For example, a web browser can load a page while also responding to user actions. A music application can play audio while the user searches for another song. Operating systems also use scheduling to share CPU time between different tasks. The Round-Robin method can help give each task a fair chance to run. This assignment helped me understand how these ideas can be applied in real programs.

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

**Your Answer:** 

A process is an independent program with its own memory, while a thread is a smaller unit of execution inside a program. Threads are usually faster to create and can share memory more easily than separate processes. In this assignment, the `Process` class represents a simulated process, but it is actually executed using a Java thread. The code creates the thread using `new Thread(process)` inside `addProcessToQueue()`. Threads were used because they are simple and suitable for simulating CPU scheduling in one Java program. 

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** 

When a process does not finish within its time quantum, it is added back to the ready queue. In my run, P1 had a burst time of 4432 ms, so it needed more than one CPU turn. It was re-queued once before it finished. Re-queueing gives other processes a chance to use the CPU. This makes Round-Robin scheduling fair. 
<img width="1508" height="1006" alt="p1" src="https://github.com/user-attachments/assets/cc99a5c5-b905-49c0-bcb5-ebf01ae866d5" />
Example from my output:
P1 completed quantum 4000ms
Remaining time: 432ms
P1 yields CPU for context switch
P1 added to ready queue | Burst time: 4432ms | Priority: 2



**Explanation of example:** 
P1 could not finish during its first 4000 ms time quantum because its burst time was 4432 ms. It had 432 ms remaining, so it was added back to the ready queue once before completing.

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 is in the New state when the thread is created using new Thread(process).

2. **Runnable**: P1 becomes Runnable after Thread.start() is called.

3. **Running**: P1 is Running when the CPU starts executing the run() method.

4. **Waiting**: P1 goes into a waiting state when Thread.sleep() is used during execution. The main thread also waits for P1 using Thread.join().

5. **Terminated**: P1 is Terminated when its run() method finishes and there is no remaining execution time.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): CPU scheduling

**Description**:
An operating system can use Round-Robin to give each running program a small amount of CPU time.

**Why Round-Robin works well here**:
Each program gets a fair turn. The time quantum is the amount of CPU time each program receives. A context switch happens when the CPU moves from one program to another. This keeps the system responsive.

### Example 2: Web server

**Description**:
A web server can handle many user requests using different threads.

**Why Round-Robin works well here**:
Each request can get a small amount of processing time. This prevents one request from using all the CPU. It helps the server stay fair and responsive for many users.

## Summary

**Key concepts I understood through these questions:**
1.The difference between threads and processes.
2.How Round-Robin scheduling works.
3.How thread states change during execution.

**Concepts I need to study more:**
1.Thread synchronization.
2.More advanced CPU scheduling algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [x] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
