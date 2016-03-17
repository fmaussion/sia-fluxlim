# sia-fluxlim
Implementation of a MUSCL flux limiter to a shallow ice approximation flow code based on finite differences.

For an overview of possible flux limiter functions $\phi$ to the MUSCL scheme, see [Wikipedia - flux limiter](https://en.wikipedia.org/wiki/Flux_limiter).
I have implemented now the Sweby (1984) limiter

For more details such as the scientific argument as to why this is a good idea, please consult the acompaning publication by **A. H. Jarosch**, C. G. Schoof, and F. S. Anslow, "[Restoring mass conservation to shallow ice flow models over complex terrain](http://www.the-cryosphere.net/7/229/2013/tc-7-229-2013.html),” *The Cryosphere*, Vol. 7, Iss. 1, pp. 229-240, 2013.
