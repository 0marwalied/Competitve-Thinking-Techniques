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

Although we read it fast, it is one of popular reason for **<ins>failure!</ins>**
The best way to avoid that is to be organized - to have a **<ins>DISIPLINE</ins>** during reading: a systematic way of reading

1. Read the problem **<ins>slowly</ins>** and think in each statement.
   1. Make sure every statement does not **<ins>conflict</ins>** what you overall understood
   2. Re-think in a statement, If it seems a **<ins>tricky</ins>** statement
   3. Number All important details

2. In some problems, constraints are clear (e.g. topcoder & IOI), somes times they are not.
   1. Each time you read a constraint in mid of description, write it beside.
   2. Never to avoid any constraints, especially unusual one `(e.g. 2 * (a+b) < c)`. Try to know why such constraints.
   3. Sometimes constraints make problem a special case of a general one. While general may not be solvable, **<ins>a specific one could be</ins>**.
   4. Ignoring constraints may push you approach problem trivially while it needs careful work `(n <= 10^18)`.
   5. Ignoring constraints may push you approach problem complicatedly while it could be solved trivially `(n <= 10)`.
   6. Sometimes constraints are not direct
      1. Find triangle angle with 2 precision -> `360 * 10^2    (angle * 2^precision)`.

   7. Sometimes more input space analysis is needed: `Given a string of (a, b, c) chars & length <= n -> we have 3^n possible string`.

3. Race samples as long as they are traceable
   1. Many times students write solutions and find samples **<ins>doesn't work</ins>**. They have to debug
      1. Sometimes they have code mistakes and original idea is correct.
      2. Sometimes they have code mistakes and original idea has some flaws.
      3. Sometimes they have code mistakes and **<ins>original idea is incorrect!</ins>**.

   2. Sometimes samples are trivial and mislead you.

4. If text is not small, Re-read the problem statement **<ins>once</ins>**. **<ins>Make sure you you have the full picture</ins>**.

5. Think in missed cases. Most of times authors don't put all basic cases. Think in them.

6. **<ins>Think in boundary & Especial cases</ins>**. They are big source of **<ins>WAs & RTEs</ins>**
   1. Think in the **<ins>smallest</ins>** boundaries `(e.g. n = 0, 1, 2 - R*C = {1*1, 1*2, 2*1, 2, 2} - str = "", str = "a", ...)`
   2. Think in the **<ins>largest</ins>** boundaries `(e.g. n = MAX, array is fully, string has max characters, ...)`
   3. Think in **<ins>especial</ins>** cases `(array filled with zeros, ...)`

7. Tips
   1. **<ins>NEVER to assume</ins>** something not mentioned.
      `(E.g. given a <= 100 - then a may be < 0 - Find count in range [a, b] - then b may be < a)`
   2. Make sure that you know exactly what is output and its "format"

---

# [Thinking - On papers Not on PC](https://youtu.be/olcmPKZNqnM?si=jivMMW8h7I_juog9)

- Remember the comofortable zone? When you move from **<ins>easy</ins>** to **<ins>meduim</ins>** to **<ins>hard</ins>** problem. you suffer more.
  - The more complex of problem, the MORE thinking you need about it.

- One of main problems is that **<ins>coders loves the PCs</ins>** and **<ins>loves solving over the machine</ins>**.
  - In many cases, this push them to write the solution, without doing all necessary steps first `(e.g. verifying idea/order)`
  - The mind will be **<ins>bounded on PC</ins>** and will keep doing "work arounds" to fix idea/code.

- It is much better to think on papers away of the PC. **<ins>Sketch FULL idea</ins>** and **<ins>verify</ins>** it.

- Same for implementation of a hard problem, you think more about code before writing it.
  `Write the code on the paper, make the paper compiling 😂`

- Yourself will tell you coding on PC is faster, **<ins>tell her NO</ins>**, this is not easy idea/code for me.

- If you sketched a code/idea and later discovered a mistake in it! **<ins>LEFT the machine</ins>**.
  - **<ins>Back to paper</ins>**, repeat your life cycle. **<ins>NEVER to think on PC</ins>**.

- Finally, In Real ICPC contest, Teams are of 3, with 1 pc. When you think on paper, **<ins>you save team time</ins>**.
  `The team that is good at thinking on paper has 15 hours during the contest, not only 5 hours.`

---

# [Thinking - Brainsotrm - Rank - Approach](https://youtu.be/7z1498LTCgg?si=5P5RPi9k3S9T6A9h)

- In many times, contestants start to think in a problem, found an idea `(e.g. let's make it by DP)` and start to do **<ins>"DIVING"</ins>**
  - By Diving I mean, keep trying to solve the problem based on an idea, but time passes with no output!
    - In other words, you are **<ins>"STUCK in thinking"</ins>**.
    - Sometimes, Idea is correct, but they don't study enough algorithms to know how to continue
    - Sometimes, Idea is correct, but they don't do enough observations
    - Sometimes, approach is correct (e.g. it is DP), but the idea itself is wrong (you need to think in other reccurance)
    - Sometimes, approach is incorrect, and you need to think differently

## How to avoid stucking?

- It is very important to **<ins>BRAINSOTRM on different solutions</ins>** that may work, before focusing on one way.
  - E.g. Given ... Find the minium X? Think that **<ins>DP</ins>**, **<ins>greedy</ins>**, **<ins>Min Cut</ins>**, **<ins>B & B</ins>** or some **<ins>adhock</ins>** idea MAY do it.
    1. Try to **<ins>RANK your guesses</ins>** based on your analysis.
    2. APPROACH the problem using most probable idea to do it (which may be wrong).
    3. **<ins>Keep your eyes on TIME</ins>**. When you start to tackle it this way?
    4. After little analysis, **<ins>rethink about your ideas RANK</ins>**. Is current approach still the best?

- **<ins>No idea is a bad idea</ins>**
  - Even if think idea is ridiculous, or will never work, **<ins>give it a trial</ins>**.
    E.g. In many hard DPs one think this state is so big, we can't do it..and then an observation appears! sparce space is possible! problem is doable!

---

# [Thinking - Concretely, Symbolically, Pictorially](https://youtu.be/Tm_Vlkv4mOo?si=_Rcw3E-mAdwBEwMX)

- Think/solving **<ins>concretely</ins>** means **<ins>solving the problem using examples</ins>** `(e.g. Evlauting the series)`.
  - E.g. You are given some forumla F(n) for a Sequence: `3 * (n+5) * (n+6) / 2 + 4`.
  - You start to enmerate its values: 4 67 88, then work on its values
  - Typically easy and natural
  - Helps much in tough **<ins>pattern proplems</ins>**.
  - Bound your mind for given example. Need carefully considering other examples.
    ![Concerete](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Concerete.png?raw=true)

- Think/solving **<ins>Symbolically</ins>** means instead of working using actual objects is to represent every thing Symbolically.
  - E.g. You are given some forumla F(n) for a Sequence: `3 * (n+5) * (n+6) / 2 + 4`.
  - Let F1(n) = (F(n) - 4)/3, = (n+5)\*(n+6)/2
  - Let F2(n) = F1(n-5) ,  F2(n) = (n\*(n+1))/2 ... a popular sequence
  - In this one, we **<ins>work over symbols not the concerete values</ins>**. `E.g. X[i-1] + X[i+1] >= 2 X[i]` for every `1 <= i <= n-1`
  - The more you train over it, the better you recognize the solutions. Your abstractions ability improves too.
  - **<ins>Sometimes, you can't recognize the solution without it!</ins>**
    ![Symbolic.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Symbolic.jpg?raw=true)

- Think/solving **<ins>pictorially</ins>** means **<ins>drawing the problem elements</ins>**, their relations and figuring properties from the **<ins>visualization</ins>**.
  - In this one, we try to do **<ins>visualization</ins>**.
  - You could visualize input elements, their relations.
  - You could visualize the nature of the output.
  - Many times, it appears with the **<ins>concrete or Symbolic</ins>**.
    ![Pictorial.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/Pictorial.jpg?raw=true)
    ![SymbolicPictorial.jpg](https://github.com/mostafa-saad/ArabicCompetitiveProgramming/blob/master/05%20Thinking%20Techniques/Algorithms_Practice_06_Thinking_Concretely_Symbolically_Pictorially/SymbolicPictorial.jpg?raw=true)

---

# [Thinking - Problem Constraints](https://youtu.be/6Fx8T_NBA7Q?si=Uj6o0cJ_bjTtpBkR)

- Sometimes Problem Constrains are the clue. Many times it is a guide of how algorithm should be complex! Rarely misleading.
  - N = 10, Not like N = 100, Not like N = 10^12, Not like 10^18

- Constraints may be traditional: `3 <= N <= 50` Sometimes they are problem domain specific: `max(2*a + b, c) < d`
  - This one is so critical, never ignore them if you don't understand why this constraint is important
    Many times, such constraints makes a special problem out of a general one. **<ins>Ignoring them is fatal mistake</ins>**.

- Do you remember the **<ins>complexity table</ins>**? Some estimations that may help

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
  - E.g. what is 1st most right digit in n! where n < 10^18? Simply starting from n = 5, answer is zero!
    Say you need to calculate F(n) where n < 10^9, by analysis you discovered that F(n > 20) is constant, and < 20 is brute forcable!

- As a trivial example for elimination is combination: Choose(1000, 997) = 1000! / (!997 _ 3!) = (998 _ 999 \* 1000) / 6
  Generally, your target calculations could be highly simplified

---

# [Thinking - Problem Abstraction](https://youtu.be/F0hmrbOW8nw?si=qyo0Y7M0-qOyTw-y)

- **<ins>"Problem Abstraction"</ins>** is a great tool to have a different view of the problem, where you **<ins>redefine the problem
  in very "general" terms AWAY from the problem Domain</ins>**.

- E.g. if the problem talks about set of words, and we could translate a word to another according to a cost function.
  What is minimal cost to convert string A to string B.
  - Problem abstraction: graph node = word, edge cost = cost function.
    What is "shortest path" to move from Node A to Node B.

- The Power of Abstraction is that it drops with problem domain (dictionary words in the example) and give you a general definition.
  The point, our mind is filled with the basic algorithms definition - hence recognizing the target algorithm FASTER.

- So when ever you got a problem, think in some ways to abstract it, you could reach correct algorithm faster than you imagine.

- But, never to drop the original problem, sometimes your abstraction drop some important domain consideration.
  E.g. Given set of points in Euclidean space, find a path with the given criteria.
  Abstracting the problem to a general graph representation, lose the Euclidean space, which was the **<ins>CLUE!</ins>**
  E.g. the given graph is bipartite and your abstraction dropped this feature.

---

# [Thinking - Problem Reverse](https://youtu.be/0wlc8Rhyybo?si=sjQL1Qsf9D4zRevs)

- Problem **<ins>Reverse</ins>** is to <ins>**think backward in the problem definition**</ins>.

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

# [Thinking - Problem Simplification ](https://youtu.be/x1rCxxKfFbM?si=DY1CkT6H-Cn1M5Yc)

- Sometimes, thinking in a simpler or a special version of the given problems, helps you to build up your intuition.

- ## Case 1: **<ins>Problem to Sub-Problems</ins>**
  - In many cases, especially hard problems, a problem may be **<ins>decomposed of other sub-problems</ins>**.
  - Realizing these sub-problems may be easy and may be hard. **<ins>Sometimes, a problem could be divided in may ways</ins>**.

  - Sometimes problems occurs:

    You keep trying in the sub-problem with no hope!
    **<ins>Always remember, you are JUST solving a sub-problem you invented.</ins>**

    If could not do it, may be you need to think in other sub-problem...or tackle it in a totally different way

- ## Case 2: **<ins>From simple to complex</ins>**

  Sometimes, you could think in a special problem/case, and then try to update the solution for general problem/case.
  - E.g. Problem mentioned 3 Constraints on the returned output. What if no constraints? What if 2nd constraint only?

  - E.g. Given R*C 2D array? what if 1*1? 1*2? 2*1? 2*2 ...increment to ... R*C

  - E.g. Given a polygon? What if it was just a triangle? What if was convex?

  - E.g. Game consist of N players? What if 1 player? 2? 3 .... N players?

  - E.g. Given a graph? What if A chain Graph? What if DAG? What if tree?

  - E.g. Given a 3D shape/array? What if 1D? What if 2D? 3D?

  - E.g. Given set of Rectangles covering Big Space? What if their coordinates are small?

  - E.g. Find answer in the given base? What if base only is 10? base is a prime number?

  - E.g. **<ins>In many cases, simplification is adhock - think how to start with simple state</ins>**

  Sometimes problems occurs:
  - E.g. you started to solve the polygon problem for convex case, BUT convex case couldn't be incremented!
  - E.g. you started to solve the graph problem for DAG case, BUT DAG case couldn't be incremented!

    **<ins>Always have a vision</ins>**, how a special case may be incremented? **<ins>Don't consume lot of time without return!</ins>**

- ## Case 3: **<ins>Simplification by Assumptions</ins>**

  **<ins>Idea is to make some assumptions that make problem easier, or special of general one.</ins>**
  - Say you have to find X, Y and Z and use them in evaluating F(X, Y, Z).
    You got confused due to trying to think in all of them together.
    Start to do temporary assumptions to have thoughts about the solution. E.g. What if we SOLVED X, how to find Y and Z?
    Found it harder? Think What if we SOLVED X & Y, how to find Z?

- Generally,
  **<ins>Problem simplification helps when you can't start with an idea and is stuck.</ins>**
  They open up our brains to think creatively and encourage solutions.

- Finally,
  The more experience you gain, the harder problems you can directly attack without simplifying them.

---

# [Thinking - Incrementally](https://youtu.be/5zILiqyQ2ts?si=znQ6NC-exUf9Vezh)

**<ins>Incremental algorithm is one that process input step by step, in each step it finds its way to update the old state with new item.</ins>**

- E.g. Given N unordered Numbers, find a sorting algorithm. To think incrementally, you do the following:

  [Say we have sorted the first m items], how to add the m+1 item and update array to be again sorted?
  If we managed to do that, we found an algorithm.

  Let say array is `10 2 7 4 15`

  Let's say we have sorted the first 3 elements (then we have 2 7 10), could we add 4th element (4)?

  YES, move backward tell find an element 4th element is greater than it
  Intially

  `2 7 10 4 NO`

  `2 7 4 10 NO`

  `2 4 7 10 YES`

  This is called **<ins>Insertion Sort</ins>** Algorithm.

- E.g. Given an array, we perform K swap operations selected randomly, what is expected array?

  [Say we have the answer array after m swaps], how to update the m+1 swap?

  Let say we have array a b c d .. a position is prop1 to be selected in a swap, prop2 to not.

  Now, let's build answer incrementally, that step by step we update the array.

  For each position, it is either swapped with one of n-1 var, or not swapped. Using normal Expectation Equ

  E.g, for first position : `a' = a*prop2 + b*prop1 + c*prop1 + d*prop1`

  E.g, for second position: `b' = a*prop1 + b*prop2 + c*prop1 + d*prop1`

  Repeat for k times. SRM575-1-2

  In Many cases, **<ins>Incremental Thinking needs data sorting</ins>**, as its idea is based on growing up the solution.

- E.g. Given N points in 2D space, find a convex hull of them

  [If we have the convex hull of the first m points], how to add the m+1 point, and update to the next convex hull?

  CAN'T!

  Let's sort the points relative to a corner point, could we do the update?

  YES

- E.g. Given set of squares, {(-R, -R), (R, R)}, a random bomb is put inside each square.

  Power of a Point is X^2 (X number of bombs in point). Total power is sum of points power. What is expected power?

  Sort the rectanges based on R. Say we have expected power of first m rectanges, how to update for next? SRM526.5-1-2

- Sometimes, the incremental algorithm order is big, as update operation is costive.
  In case order doesn't affect, consider input randomization, somtimes help.

- Sometimes update from state to another is systematic, that we could model it in a matrix,
  and perfrom matrix power to get all incremental steps zipped in one matrix.

---

# [Thinking - Problem Domain re-interpretation](https://youtu.be/9fwHOeebIgc?si=5aK2KcJEg-XOslUO)

- A problem may have a domain: E.g. given N cities find a path from A to B?

  This problem lies in graph theory domain.

  What if the cities are in Euclidean space? Then we have 2 involved domains: Graphical and Geometrical.

  Sometimes, the solution requires you to **<ins>re-interpret the problem</ins>** in another domain. This is not always do-able, but may be the clue.

- E.g. Say we have teams in ICPC competitions. Each team has strength (a, b). Team beat another if both `a1 > a2` and `b1 > b2`.

  The problem solution in its internals requires knowing how many teams I could beat. This is doable in O(n^2). What if n so big?

  Could you reinterpret this problem domain?

  Yes, Geometricallly!

  Imagine plane where points are strength (a, b).

  Now, Team with (a, b) beats the teams in rectangle (a+1, b+1) - (MAX_A, MAX_B). Find fast way to count them FAST.

- E.g. Given a sequence S of integers, and operation to minimize an item by 1, what is minimum operations applied to

  let this sequence convex `(e.g. S[i-1] + S[i+1] >= 2 \* S[i], for each i)`

  Imagine plane where points are (idx, S[idx])...start to draw lines from ith point to....and do.... (don't care with details)

- E.g. You are given set of states, each one is represented in terms of other sub-states, evaluate value for a given state.

  Let's reinterpret it Mathematically. Let each state is variable. Then we have N variables.

  Construct a matrix of the variables relations, Guassian Elimination is the solution .... (don't care with details)

- E.g. Given set of boxes, each box has a key and is opened by certain key. Given a starting key, could you open all of them?

  Let's reinterpret it Graphically. Think in keys as graph nodes. We start from certain node(key). We move from key to another, by opening a box.

  Solution now is Eulerian Path.

  What about thinking in boxes as nodes, and form box to box an edge if it has its key.

  An extra source node for the starting key.
