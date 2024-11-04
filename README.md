java c
CEG2136/CEG2536   Computer Architecture I
Architecture des ordinateurs I
MIDTERM
EXAMINATION
Instructions:
.   Answer ALL questions on the questionnaire.
.   This is a close-book examination.
.   Use the provided space to answer the following questions. For your calculations you can use pages 6-8.
.   Calculators are not allowed.
.   Read all the questions before you start.
Q1.      The range of signed integers N expressed in 2-s complement representation that can be
stored in a 10-bit register is:
(a) -1024≤N≤+1023     (b) -1023≤N≤+1024          (c) -512≤N≤+511           (d) -511≤N≤+512
(e) None of the above
Q2.      Identify the decimal number which is represented next in floating point with the IEEE
754 standard:               11000010100010101100000000000000
(a) (- 133.375)10    (b) (- 69.375)10       (c) (- 138.750)10     (d) (- 34.6875)10    (e) (- 8.671875)10
Q3)     Give the best binary approximation of A = (26.6)10  and B = - (23.4)10  employing signed
2’s-complement representation with 2 bits for the fractional part. A =                                                     B =
Q4)       1) Convert to decimal the following two numbers, 01010  10101, which are already
expressed in 2’s complement representation.
2) These numbers are stored in two 6-bit registers X and Y to calculate their sum
(S = X+Y) and their difference (D=X-Y) by using additions and 2’s complementation only. Convert to decimal and write each intermediate and final result, to check the correctness of
your assertions.
S = X+Y          2’s complement                   Base 10         D=X-Y             2’s complement                           Base 10
CY: X + Y
S

CY:  X + -Y    D

3) Since both S and D have to be represented with 6 bits, indicate if overflow occurs, and explain how a circuit can detect these situations.
Q5.      Which of the logic functions is implemented by the following circuit?
A'      B'     
f
C     D     
(a) f(A,B,C,D) = Σm(4,5,6,7,8,9,10)+X(12,13,14,15) (b) f(A,B,C,D) = Σm(4,5,6,8,9,10,14)
(c) f(A,B,C,D) = Σm(0,1,2,3,6,7,14,15)
(d) f(A,B,C,D) = Σm(0,1,2,3,7,11,15)
(e) f(A,B,C,D) = Σm(4,5,6,8,9,10,12,13,14)+X(7,11)
Q6.      Which of the following logic functions is implemented by the given circuit?

MUX 8x1 (1 bit)

0   1   2   3   4   5   6   7
D  0   0   D, D   1   D,代 写CEG2136/CEG2536 Computer Architecture I Architecture des ordinateurs I MIDTERM EXAMINATION
代做程序编程语言  1              (e) f(A,B,C,D) = Σm(1,6,9,10,11,12,14,15)
Q7.      What is the capacity of a ROM, capable to implement three functions of six variables?
(a) 8 words of 6 bits       (b) 16 words of 3 bits        (c) 32 words of 6 bits           (d) 64 words of 3 bits
(e) None of the above
Draw a block diagram of your memory with the major components, indicating its inputs and outputs.
Q8.
1)        - Draw the state diagram of the sequential circuit whose state table is given below
Present        Next                                                                               The State Diagram goes here:
State          state

A B C
A+B+C+
JA
KA
JB
KB
JC
KC
0 0 0
1 0 0






0 0 1
1 1 0






0 1 0
0 0 1






1 0 0
0 1 0






1 1 0
0 0 0






- Fill out the above table with the appropriate values for the JK flip-flops inputs such that the sequential circuit will observe the required transitions.
- Indicate the correct set of minimized equations of the JK flip-flops inputs from the following:
(a) J A = A,B,, (b) J A = A,B,, (c) J A = B,,
(d) J A = A,B,, (e) J A = B,,KA = C,, KA = 1,   KA = 1,   KA = A,  KA = A,
JB = AB’C’+ A’B’C,
JB = A+C, JB = A+C, JB = AC,   JB = AC,
KB = BC,, KB = 1,
KB = 1,   KB = C,, KB = C,,
JC = A’BC  JC = A,B,    JC = A,B,    JC = A,BC, JC = A,BC,
KC = A’B’C. KC = 1.
KC = 1.   KC = A,. KC = A,.
2)        - If your circuit reaches by mistake any of the 3 states that are not used, determine their corresponding next state.
Present state
Next State






- Is your circuit auto-corrective?        Reply just with YES or NODraw the time diagram and give the states of the flip-flops’ outputs through the first 6 clock pulses, assuming that their initial state (at t=0) is 000 and they are triggered on  the rising edge of the clock.
Clock
















t
C (20)
100 200
300
400
500
600
700
[ns]

t
B (21)

0     0


0







t
A (22)


0









t
1

States (encoded as base 10 numbers)
0             4









         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
