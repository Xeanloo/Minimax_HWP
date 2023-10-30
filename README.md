# Minimax_HWP
to debug/run:
    1. Load Sbox at address "000000"
    2. Load key at address "000040"

Key-scheduling algorithm (KSA)/ SBox permutation 
    Line 0-3    : init register and load key from memory
    Line 4      : Check condition of SBox permutation loop
    Line 5      : Start Sbox permutation loop
    Line 6-16   : Calculate j
    Line 17-23  : Null memory cells to write later
    line 24-30  : get S[j]
    line 31-43  : swap S[i] with S[j]