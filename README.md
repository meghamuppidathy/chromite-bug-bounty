# Chromite-Bug-Bounty
<h2> 1. List all the ratified extensions of the unprivileged spec </h2> 
 
  1. M : Integer Multiplication and Division </br>
  2. A : Atomic Instructions </br>
  3. F : Single Precision Floating Point </br>
  4. D : Double Precision Floating Point </br>
  5. Q : Quad Precision Floating Point  </br>
  6. Ziscr : Control and Status Registers </br>
  7. Zifencei : Instruction-Fetch Fence </br>
  8. C : Compressed Instructions </br>
 
<h2> 2. List at least 4 unratified extensions of the unprivileged spec </h2>
  1. L : Decimal floating point </br>
  2. B : Bit manipulation </br>
  3. J : Dynamic Languages </br>
  4. T : Transactional memory </br>

<h2> 3. Why do immediates have such a weird encodings? </h2>
  The reason immediates have such a "weird" encodings in some instruction formats is to ensure that the other fields namely the register fields(rs1,rs2) in the same position as the two source register fields in R-type instructions.
