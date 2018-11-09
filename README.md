lll-function-signature
==

A utility to calculate ABI compatible LLL function signatures for the
EVM (Ethereum Virutal Machine).


Usage:

```
$ ./lll-function-signature 'name()'
name()
0x06fdde03
```

This can then be used in an LLL def statement:

```
(def 'get-name 0x06fdde03)
```

--
Burton Samograd
BusFactor1 Inc.
2018