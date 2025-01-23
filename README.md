# zk-study

This repository contains zk-mathematics and will be following the curriculum below for building and learning

## ZK Physical Cohort Syllables
Milestone 1: 6th January - 2nd February 2025
Goal: Polynomials
Deliverables
Implementations
Univariate polynomial implementation
Multilinear polynomial implementation (evaluation form)
Composed polynomial implementation
fully recursive and generic over operation type

Milestone 2: 3rd February - 2nd March 2025
Goal: Sumcheck and GKR
Deliverables
Implementations
Fiat shamir transcript
Sumcheck prover and verifier over composed polynomial
GKR circuit representation with custom gates
GKR prover and verifier

Milestone 3: 3rd March - 31st March 2025
Goal: Polynomial commitment + Complete snark implementation
Deliverables
Implementations
FRI implementation
FRI-Binuis implementation
Complete snark implementation (GKR + FRI-Binius)





Breakdown
univariate polynomials
lagrange interpolation
shamir secret sharing


applying polynomials to zk


schwartz zippel lemma
introduce different types of polys
univariate, multivariate and multilinear
perform degree analysis from the schwartz zippel context
justifies multilinear polynomial in-depth
multilinear polynomial


co-efficient form implementation design session
lagrange interpolation
boolean hypercube [2HC] (graphical intuition)
briefly introduce higher dimensional hypercubes i.e 3HC, 4HC, …NHC
evaluation form design session
composed polynomials (generic over op)


representing multivariate polynomials as composition of multilinear polynomials
fully recursive composed polynomial representation i.e. composed that can hold composed
introduce higher dimensional hypercubes as an alternative representation method i.e 3HC, 4HC, … NHC
explore the tradeoff with both representations
sumcheck


application driven introduction to sumcheck (more complex applications to introduce more advanced sumcheck topics)
evaluation form sumcheck (abstracts over composed polynomials)
fiat shamir
sumcheck prover and verifier design session
GKR
GKR theory
GKR circuit representation design session
ability to add custom gates
GKR 2 to 1 trick
prover design session
verifier design session
Polynomial Commitment Scheme


FRI-Binius
Complete SNARK: GKR + Polynomial Commitment Scheme




