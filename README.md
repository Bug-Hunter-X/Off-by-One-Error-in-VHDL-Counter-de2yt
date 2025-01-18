# VHDL Counter Bug
This repository demonstrates a common off-by-one error in VHDL code and its solution.

## Bug Description
The `buggy_counter.vhdl` file contains a counter that might not reset correctly, leading to unexpected behavior. This is a subtle issue often missed during testing.

## Solution
The `fixed_counter.vhdl` file presents the corrected code where the potential off-by-one error is addressed.  Proper handling of boundary conditions ensures correct counter functionality.