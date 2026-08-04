# [Tackling a problem](https://youtu.be/fd0Ebfa_mJ0?si=FMHr71z8_ftqEkfb)

## Before tackling a problem you should be:

- Ready / Relax

- Active as if you are in a conest

- Challenge Spirit

- Don't rush / Don't panic

- Check your watch - Monitor your progress

## We could think in Solving a problem as stages:

1. Reading and correctly "understanding" problem statement

2. "Thinking" in a solution -> Verifying it

3. Coding

4. Debugging if necessary

5. Testing

## Hence your overall performance depends on performance in every stage.

- The more better in one of stages, the better overall performance.

- Then, your practice plans must care with all the stages.

- Always measure time you do for every phase, this will help you know your problems

- The training must be varied and you should focus on your weaknesses.

- Another dimension for performance is your speed.

# Reading problem statement

Although we read it fast, it is one of popular reason for **failure!**
    The best way to avoid that is to be organized - to have a **<u>DISIPLINE</u>** during reading: a systematic way of reading

1. Read the problem **<u>slowly</u>** and think in each statement.
   
   1. Make sure every statement does not **<u>conflict</u>** what you overall understood
   
   2. Re-think in a statement, If it seems a **<u>tricky</u>** statement
   
   3. Number All important details

2. In some problems, constraints are clear (e.g. topcoder & IOI), somes times they are not.
   
   1. Each time you read a constraint in mid of description, write it beside.
   
   2. Never to avoid any constraints, especially unusual one `(e.g. 2 * (a+b) < c)`. Try to know why such constraints.
   
   3. Sometimes constraints make problem a special case of a general one. While general may not be solvable, **<u>a specific one could be</u>**.
   
   4. Ignoring constraints may push you approach problem trivially while it needs careful work `(n <= 10^18)`.
   
   5. Ignoring constraints may push you approach problem complicatedly while it could be solved trivially `(n <= 10)`.
   
   6. Sometimes constraints are not direct
      
      1. Find triangle angle with 2 precision -> `360 * 10^2    (angle * 2^precision)`.
   
   7. Sometimes more input space analysis is needed: `Given a string of (a, b, c) chars & length <= n -> we have 3^n possible string`.

3. Race samples as long as they are traceable
   
   1. Many times students write solutions and find samples **<u>doesn't work</u>**. They have to debug
      
      1. Sometimes they have code mistakes and original idea is correct.
      2. Sometimes they have code mistakes and original idea has some flaws.
      3. Sometimes they have code mistakes and **<u>original idea is incorrect!</u>**.
   
   2. Sometimes samples are trivial and mislead you.

4. If text is not small, Re-read the problem statement **<u>once</u>**. **<u>Make sure you you have the full picture</u>**.

5. Think in missed cases. Most of times authors don't put all basic cases. Think in them.

6. **<u>Think in boundary & Especial cases</u>**. They are big source of **<u>WAs & RTEs</u>**
   
   1. Think in the **<u>smallest</u>** boundaries `(e.g. n = 0, 1, 2 - R*C = {1*1, 1*2, 2*1, 2, 2} - str = "", str = "a", ...)`
   
   2. Think in the **<u>largest</u>** boundaries `(e.g. n = MAX, array is fully, string has max characters, ...)`
   
   3. Think in **<u>especial</u>** cases `(array filled with zeros, ...)`

7. Tips
   
   1. **<u>NEVER to assume</u>** something not mentioned.
      `(E.g. given a <= 100 - then a may be < 0 - Find count in range [a, b] - then b may be < a)`
   
   2. Make sure that you know exactly what is output and its "format"

---

# [Thinking - On papers Not on PC](https://youtu.be/olcmPKZNqnM?si=jivMMW8h7I_juog9)

- Remember the comofortable zone? When you move from **<u>easy</u>** to **<u>meduim</u>** to **<u>hard</u>** problem. you suffer more.
  
  - The more complex of problem, the MORE thinking you need about it.

- One of main problems is that **<u>coders loves the PCs</u>** and **<u>loves solving over the machine</u>**. 
  
  - In many cases, this push them to write the solution, without doing all necessary steps first `(e.g. verifying idea/order)`
  
  - The mind will be **bounded on PC** and will keep doing "work arounds" to fix idea/code.

- It is much better to think on papers away of the PC. **<u>Sketch FULL idea</u>** and **<u>verify</u>** it.

- Same for implementation of a hard problem, you think more about code before writing it. 
  `Write the code on the paper, make the paper compiling 😂`

- Yourself will tell you coding on PC is faster, **<u>tell her NO</u>**, this is not easy idea/code for me.

- If you sketched a code/idea and later discovered a mistake in it! **<u>LEFT the machine</u>**.
  
  - **<u>Back to paper</u>**, repeat your life cycle. **<u>NEVER to think on PC</u>**.

- Finally, In Real ICPC contest, Teams are of 3, with 1 pc. When you think on paper, **<u>you save team time</u>**. 
  `The team that is good at thinking on paper has 15 hours during the contest, not only 5 hours.`

---

# [Thinking - Brainsotrm - Rank - Approach](https://youtu.be/7z1498LTCgg?si=5P5RPi9k3S9T6A9h)

- In many times, contestants start to think in a problem, found an idea `(e.g. let's make it by DP)` and start to do **<u>"DIVING"</u>**
  
  - By Diving I mean, keep trying to solve the problem based on an idea, but time passes with no output! 
    
    - In other words, you are **<u>"STUCK in thinking"</u>**.
    
    - Sometimes, Idea is correct, but they don't study enough algorithms to know how to continue
    
    - Sometimes, Idea is correct, but they don't do enough observations
    
    - Sometimes, approach is correct (e.g. it is DP), but the idea itself is wrong (you need to think in other reccurance)
    
    - Sometimes, approach is incorrect, and you need to think differently 

## How to avoid stucking?

- It is very important to **<u>BRAINSOTRM on different solutions</u>** that may work, before focusing on one way.
  
  - E.g. Given ... Find the minium X? Think that **<u>DP</u>**, **<u>greedy</u>**, **<u>Min Cut</u>**, **<u>B & B</u>** or some **<u>adhock</u>** idea MAY do it.
    
    1. Try to **<u>RANK your guesses</u>** based on your analysis.
    
    2. APPROACH the problem using most probable idea to do it (which may be wrong).
    
    3. **<u>Keep your eyes on TIME</u>**. When you start to tackle it this way?
    
    4. After little analysis, **<u>rethink about your ideas RANK</u>**. Is current approach still the best?

- **<u>No idea is a bad idea</u>**
  
  - Even if think idea is ridiculous, or will never work, **<u>give it a trial</u>**.
    E.g. In many hard DPs one think this state is so big, we can't do it..and then an observation appears! sparce space is possible! problem is doable!

---

# [Thinking - Concretely, Symbolically, Pictorially](https://youtu.be/Tm_Vlkv4mOo?si=_Rcw3E-mAdwBEwMX)

- Think/solving **<u>concretely</u>** means **<u>solving the problem using examples</u>** `(e.g. Evlauting the series)`.
  
  - E.g. You are given some forumla F(n) for a Sequence: `3 * (n+5) * (n+6) / 2 + 4`.
  
  - You start to enmerate its values: 4 67 88, then work on its values
  
  - Typically easy and natural
  
  - Helps much in tough **<u>pattern proplems</u>**.
  
  - Bound your mind for given example. Need carefully considering other examples.
    ![Concerete](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Concerete.png?raw=true)

- Think/solving **<u>Symbolically</u>** means instead of working using actual objects is to represent every thing Symbolically.
  
  - E.g. You are given some forumla F(n) for a Sequence: `3 * (n+5) * (n+6) / 2 + 4`.
  
  - Let F1(n) = (F(n) - 4)/3, = (n+5)*(n+6)/2
  
  - Let F2(n) = F1(n-5) ,  F2(n) = (n*(n+1))/2        ... a popular sequence
  
  - In this one, we **<u>work over symbols not the concerete values</u>**. `E.g. X[i-1] + X[i+1] >= 2 X[i]` for every `1 <= i <= n-1`
  
  - The more you train over it, the better you recognize the solutions. Your abstractions ability improves too.
  
  - **<u>Sometimes, you can't recognize the solution without it!</u>**
    ![Symbolic.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Symbolic.jpg?raw=true)

- Think/solving **<u>pictorially</u>** means **<u>drawing the problem elements</u>**, their relations and figuring properties from the **<u>visualization</u>**.
  
  - In this one, we try to do **<u>visualization</u>**.
  
  - You could visualize input elements, their relations.
  
  - You could visualize the nature of the output.
  
  - Many times, it appears with the **<u>concrete or Symbolic</u>**.
    ![Pictorial.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Pictorial.jpg?raw=true)
    ![SymbolicPictorial.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/SymbolicPictorial.jpg?raw=true)

---

# [Thinking - Problem Constraints](https://youtu.be/6Fx8T_NBA7Q?si=Uj6o0cJ_bjTtpBkR)

- Sometimes Problem Constrains are the clue. Many times it is a guide of how algorithm should be complex! Rarely misleading.
  
  - N = 10, Not like N = 100, Not like N = 10^12, Not like 10^18

- Constraints may be traditional: `3 <= N <= 50` Sometimes they are problem domain specific: `max(2*a + b, c) < d`
  
  - This one is so critical, never ignore them if you don't understand why this constraint is important
    Many times, such constraints makes a special problem out of a general one. **<u>Ignoring them is fatal mistake</u>**.

- Do you remember the **<u>complexity table</u>**? Some estimations that may help

```latex
N                           Complexity            Possible Algorithms & Techniques

10^18                       O(log(N))             Binary & Ternary Search / Matrix Power / Cycle Tricks / Big Simulation Steps / Values ReRank
100 000 000                 O(N)                  A Linear Solution - May be a greedy algorithm
40 000 000                  O(N log N)            linear # calls to Binary & Ternary Search / Pre-processing & Querying / D & C
10 000                      O(N2)                 adhock / DP / Greedy / D & C / B & B
500                         O(N3)                 adhock / DP / Greedy / ..
90                          O(N4)                 adhock / DP / Greedy / ...
30-50                                             Search with pruning - branch and bound
40                          O(2^N/2)              Meet in Middle
20                          O(2^N)                Backtracking / Generating 2^N Subsets
11                          O(N!)                 Factorial / Permutations / Combination Algorithm
```

- Sometimes the constraint is misleading and it is a "fake" limit:
  
  - E.g. what is 1st most right digit in n! where n < 10^18?    Simply starting from n = 5, answer is zero!
    Say you need to calculate F(n) where n < 10^9, by analysis you discovered that F(n > 20) is constant, and < 20 is brute forcable!

- As a trivial example for elimination is combination: Choose(1000, 997) = 1000! / (!997 * 3!) = (998 * 999 * 1000) / 6
  Generally, your target calculations could be highly simplified

---

# [Thinking - Problem Abstraction](https://youtu.be/F0hmrbOW8nw?si=qyo0Y7M0-qOyTw-y)

- **<u>"Problem Abstraction"</u>** is a great tool to have a different view of the problem, where you **<u>redefine the problem
  in very "general" terms AWAY from the problem Domain</u>**.

- E.g. if the problem talks about set of words, and we could translate a word to another according to a cost function.
  What is minimal cost to convert string A to string B.
  
  - Problem abstraction: graph node = word, edge cost = cost function.
    What is "shortest path" to move from Node A to Node B.

- The Power of Abstraction is that it drops with problem domain (dictionary words in the example) and give you a general definition.
  The point, our mind is filled with the basic algorithms definition - hence recognizing the target algorithm FASTER.

- So when ever you got a problem, think in some ways to abstract it, you could reach correct algorithm faster than you imagine.

- But, never to drop the original problem, sometimes your abstraction drop some important domain consideration.
  E.g. Given set of points in Euclidean space, find a path with the given criteria.
    Abstracting the problem to a general graph representation, lose the Euclidean space, which was the **<u>CLUE!</u>**
    E.g. the given graph is bipartite and your abstraction dropped this feature.

---

# [Thinking - Problem Reverse](https://youtu.be/0wlc8Rhyybo?si=sjQL1Qsf9D4zRevs)

- Problem **<u>Reverse</u>** is to <u>**think backward in the problem definition**</u>.

- E.g. What is probability of event X occurs.
  Reverse: What is probability of event ~X. Answer is 1 - ~X. Sometimes Calculating ~X is extremely easier than X.

- E.g. We have 2^N subset, find subset with property X (e.g. # 1s are 5).
  Reverse: Find subsets with property ~X (e.g. # 1s != 5). Answer = 2^N - Count ~X

- E.g. Find Minimum Summation. (many times min/max are interchangeable)
  Reverse: Total - Maximum Summation

- E.g. Given An "inc/decreasing" generating Sequence (Say Fibonacci), Given a value, what is its index in the sequence?
  Reverse: Given an index, could you get its value? If so, Binary Search on X tell finding vlaue index

- Sometimes, problem is solvable through its main definition or reversed one.
  Sometimes, the ONLY way to solve it is its reverse.

---
