=============================================================================================================================================
Name : Prasad Kshirsagar / Ankan Bal
Entry no : 2016csb1041 / 2016csb1031
Subject : SIMD CO-PROCESSOR (PROJECT)

==============================================================================================================================================

Instructions added : 
==========================================================================================================================================

1. VMOV1 Vn, Rn
2. VMOV2 Rn, Vn
3. VADD Vd, Vr, Vs
4. VSUB Vd, Vr, Vs
5. VMUL Vd, Vr, Vs
6. VDIV Vd, Vr, Vs
7. VMOD Vd, Vr, Vs
8. VAND Vd, Vr, Vs
9. VLD Vd, Imm[Rs]
10. VST Vd, Imm[Rs]

=============================================================================================================================================

HOW TO COMPILE & RUN :

As given in the read_me file of main Simple Risc structure.

============================================================================================================================================
About the Project :

============================================================================================================================================

- We have added all the instructions keeping in mind , the 64 bit structure of vector registers as compared to 32 bit structure of normal registers and also followed the "Project Proposal document".

- Proper changes in memory, pipelining & other files were done accordingly.

- NOTE : There is slight change as while using Vst instruction. In Vst we need to give immediate at a distance of 8 rather than 4.
         We can do it while writing assembly program.
         ex; Vst v1,0[r1]
             Vst v2,8[r2]

- Attached are the required test files to test addition,multiplication & subtraction of short numbers .

==========================================================================================================================================


