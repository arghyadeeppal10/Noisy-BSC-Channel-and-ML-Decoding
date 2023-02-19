# Noisy-BSC-Channel-and-ML-Decoding
A codeword $x \in C$  is transmitted over a communication channel, and the received vector is $y = x + e$ $\vert$ $\forall e \in \mathbb{F}^{n}_{2}$. Given $y$, we would like to recover an estimate of x. The channel is memoryless binary symmetric channel,i.e. each element of the random vector e is generated independently according to the following probability distribution:
```math
 P(e_{i}=1)=p 
```
where 0 < $p$ < 1/2. Given y, the Maximum Likelihood (ML) decoding (a widely-used technique) performs decoding by maximizing the following probability:
```math
x^{*} =  \underset{x \in C} {argmax} P(y;x)
```
```math
  e^{*} =  \underset{\hat{e} \in C'} {argmin} \lVert e \rVert_1\;\text{where}\;C' = {\hat{e} \in \mathbb{F}^{n}_{2} \vert y - \hat{e} \in C}
```

A test problem for an arbitrary codeword $x \in C$, which has been corrupted with a random error $e$ to receive the message $y=x+e$ has been taken into consideration and ML decoding has been performed. For a specific Message Vector $x$, the Error Rate for a particular value of $p$ and the variation of Error Rate versus Crossover Probability $p$ has been plotted. 
