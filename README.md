# Invoke-Upscale-Batcher-

This works along side invokeai. 

It automates all !fix commands allowing the user to input upscale commands. I made mainly for upscaling. 

Before running the script you must edit it. 

You must point it to where your invoke.bat file. Change to be made on line 50
and to point where your outputs folder is for invokeAI. change to made on line 15

The py file wont run without changing these path locations. 

Commands should be either
-U and number 1/2/4/8 seem to work fine
or 
-embiggen <scaling_factor> <esrgan_strength 0-1> <overlap_ratio OR overlap_pixels> 
