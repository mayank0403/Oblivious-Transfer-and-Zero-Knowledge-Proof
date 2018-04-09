# Oblivious-Transfer-and-Zero-Knowledge-Proof

IPython notebooks for the code of the following cryptographic protocols :
1. Rabin Oblivious Transfer
2. 1-out-of-2 Oblivious Transfer
3. Feige Fiat Shamir ZKP

All the code has been written in SAGE MATH library in python. Install sage math first to run the codes on your machine.

Written as a part of course project for Network Security, Fall 2018, IIT BHU, Varanasi, India.

### Note
''In the code of Rabin Oblivious Transfer (filename - Oblivious Transfer), I have used a hardcoded seed which should never be used in cryptography. The purpose of using such a hardcoded PRNG seed was to ensure that I could give my professor an illustration of all the cases where x=y, x=-y or other cases. This led me into using a hardcoded seed. If you want to use it, then replace it with a better seed like taking it from the timestamp like I did in the other two codes.''


### All the codes have been written as a sequential code and don't employ sockets to transfer data across parties.
