# beyond_rabbit (an MPC `SCALE-MAMBA` Implementation)
__Batches removed to comply with anonymous submission__. 

A __Through the mirror__ full implementation. eprint to be added, shortly. This repository includes:

* Basic random sampling using dabits in MAMBA. 
* VHDL Circuits and Bristol Fashion Files.
* Constant Round implementations of Rabbit and Catrina comparison protocols from Through the Mirror.  
* A `relu` implementation, and a complementing library.
* Easy to use test files, to verify your installation/configuration is correct.
* __Repo will be deanonymized once sumbission is accepted__.

This is to the best of our knowledge the first implementation of any support for the `dabits` instruction in `mamba.`


## Pre-requisites
* `SCALE-MAMBA` 1.11 or above. 
* `numpy` 1.16 or above. (exclusively to __test__, which in this context means, execute [`test_relu.mpc`](beyond_rabbit/test_relu/test_relu.mpc)).

## Installation and Configuration
1. Download and configure `SCALE-MAMBA`:

2. **Append** the contents of [`library.py`](beyond_rabbit/Compiler/library.py), on the namesake original file in your installation of `SCALE-MAMBA`, __accordinly__. That is add the imports on top of the file, and the additional functions at the bottom. 
3. Do the same with the [`comparisons.py`](beyond_rabbit/Compiler/library.py). In this case, just append the contetent at the end of the namesake file in `SCALE-MAMBA`.  No importas are needed here. 
4. Copy both remaining `.py` files __as is__ directly in the `Compiler` folder in `SCALE-MAMBA`. 
5. Copy the tests folders in the `Programs` folder of your `SCALE-MAMBA` installation. 
6.Copy the contents of the Bristol folder, into its namesake, in your local `SCALE-MAMBA` installation. 
7. You can now run them and check all tests are in <span style='color:green'>green.</span> (NOT in <span style='color:red'>red.</span>)

## Contact Information:
__removed to comply with anonymous submission__ (code has a team of mantainers)
 
## License
### Authors: 

__removed to comply with anonymous submission__. 

Licensed under the MIT license.
