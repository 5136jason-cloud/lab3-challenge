This is the total setup and test code of lab3 challenge.

Two extra structure are added: SPMOD and INT_STACK.

SPMOD:![image](SPMOD.png)

INT_STACK:![image](INTSTACK.png)

SPMOD modifies the Stack Pointer(SP) and INT_STACK stores the values.

Please remind that after a set of MOVC2 we need to add a line of meaningless codeto let MOVC2.Q to be low due to the one cycle delay.

assem copy.txt is the test code for the structure
