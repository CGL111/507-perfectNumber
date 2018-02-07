# 507-perfectNumber
Mersenne primes 2^p-1    For 2p−1 to be prime, it is necessary that p itself be prime.
However, not all numbers of the form 2p−1 with a prime pp are prime; for example, 211−1=2047=23×89 is not a prime number.

Euclid proved that 2^(p-1)(2^p-1) is an even perfect number where (2^p-1) is a prime;
so we just evaluated the perfect number for primes {2,3,5,7,13,17,19,31};
  ((1 << p) - 1)  
	 (1 << p - 1) 会先算p-1
