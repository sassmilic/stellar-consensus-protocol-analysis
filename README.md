# stellar-consensus-protocol-analysis
Analyzing various assumptions of the Stellar Consensus Protocol

Preliminary notes: 
* The Stellar Consensus Protocol entirely rests on the assumption of "Quorum Intersection"
* Testing for Quorum Intersection is NP-complete; see: https://arxiv.org/pdf/1902.06493.pdf
  * Why would you rest your entire consensus algorithm on an assumption you can't tractably test? ...
* Some analysis of the network dynamics of the Stellar Network has already been done; see: [TODO, can't find the paper now...]

TODO:
* Simulate networks with realistic parameters based on actual Stellar network activity.
* Compute how often Quorum Intersection *actually holds*. Note: this will need to be a lower bound due to intractability mentioned above.

References:
* http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.696.93&amp=&rep=rep1&amp=&type=pdf
* https://arxiv.org/pdf/1902.06493.pdf
* https://arxiv.org/pdf/1707.01873.pdf
* https://arxiv.org/pdf/2002.08101.pdf
* https://arxiv.org/pdf/2002.08101.pdf
* https://arxiv.org/pdf/1904.09839.pdf
