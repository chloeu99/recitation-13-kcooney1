# CMPS 2200 Recitation 13

## Answers

**Name:**Annelise Bakewell, Kelly Romer, Kaitlyn Rene Cooney,Chloe Uhls

Place all written answers from `recitation-13.md` here for easier grading.

- **1)** The probability of removing v is 1 - the probability that v is not removed. The only case 
in which v is not removed occurs when v is the center vertex. The probability that v is 
the center vertex is the probability that both v flips head plus the probability that
all neighboring vertices flip tails. This in fact is (1/2 + 1/(2^d)). Thus, the probability 
that v IS removed is (1 - (1/2  + 1/(2^d))). 
This ultimately becomes P(v removed) = 1/2 - 1/(2^d)

- **2)** O (log_5 n) = O (logn)
