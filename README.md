# 2DF30-Assignment-1
Question 3: Approximation of ruin probabilities. For the continuous time process U(t), several
methods exist to approximate the ruin probability ψ(u). One of these approximations, discussed in
[1], is the following:
ψ(u) ≈ ψ(0)e
−Ru
. (1)
We propose to use a similar approximation for our discrete time model:
ψ˜(u) ≈ ψ˜(0)e
−Ru˜
, (2)
where R˜ is the adjustment coefficient. It can be obtained by solving (either symbolically or numerically) the equation
mG(−R˜) = 1, with mG(t) = E[e
tGn
].
We will try the following:
• take the simulated values for ψ˜(0), obtained in Question 2,
• determine theoretically the adjustment coefficient R˜,
• plug these values in Equation (2),
• determine ψ˜(u) and compare it to the simulation results obtained in Question 2.
Use this method to obtain approximations for ψ˜(u) for as many of the model variations discussed in
Question 2 as possible. Comment on the accuracy of the approximations.
