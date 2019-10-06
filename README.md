# DIGITAL-ROTAMETER
In order to measure oil flowing through a pipeline, a digital rotameter was installed which sends our 
system a single pulse for every 6.3 gallons of oil that flow past it.  This is referred to as the digital 
rotameter’s “k‐factor.”  We have the rotameter on a bit address instead of an actual input so that we 
can control it with a timer.  Create timer logic which pulses the bit every 12 seconds and store the flow 
to the given float address.  We also want to update the flow rate every 12 seconds.  How fast is the oil 
flowing? 
## IO / ASSIGNED MEMORY
B3:0/0 ‐ Rotameter 
F8:0 ‐ Flow (gpm)
### Test Criteria
To start, run your program on Emulate.  F8:0 should be equal to 0 at first, but after a minute or so it 
should settle down at 31.5. 
Lastly, change your pulse timer preset from 12 seconds to 2 seconds.  After a minute or so F8:0 should 
settle down at 189. 
