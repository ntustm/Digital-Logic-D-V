How to avoid race condition between TB and DUT
1. clock stimulus for dut and tb should have phase diff
2. tb work on clock negedge when dut on posedge
3. ensure noblock ouput iin tb and dut
4. sv use clocking block and program block
