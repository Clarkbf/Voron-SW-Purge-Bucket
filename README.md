# Voron-SW-Purge-Bucket
I was having trouble getting a Purge Tower to stay in place on my build plate and was having great success with Edwardyeeks Nozzle Scrubber/Purge Bucket on my Trident so wanted one for my Switchwire.

This adaptation will require replacing the Y-axis extrusion with a 360mm long extrusion and replacing the Y_idler_lower with a shorter one I adapted from the original.

The Purge Bucket works but I have been having trouble with the code working with the ERCF. I am posting the files and My code in hopes that the community can help solve the issues and give us Switchwire users a working Purge bucket. (The nozzle scrubber does work, so if someone wants to use this on a non-ERCF unit it will still be of benefit.

The problem I have been having is that after the second tool change... T0 - T1 -T0 the toolhead returns to the model in the proper XY position but not the proper Z height, almost 8mm to high.
