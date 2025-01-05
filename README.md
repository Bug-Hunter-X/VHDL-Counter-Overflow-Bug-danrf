# VHDL Counter Overflow Bug
This repository demonstrates a common error in VHDL code and its solution.  The `buggy_counter.vhd` file contains a counter that exhibits unexpected behavior due to an incorrect handling of overflow conditions.  The `fixed_counter.vhd` file presents a corrected version of the counter.

**Problem:** The original counter does not wrap around when reaching the maximum count correctly. This causes issues with the intended functionality.

**Solution:** The corrected counter explicitly handles the overflow case.  The solution demonstrates best practices for handling counter overflow in VHDL.  This will prevent unintended behavior in the counter.