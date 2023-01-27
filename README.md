"Invoke-Upscale-Batcher" is a script that works alongside "invokeai". It automates all "!fix" commands, allowing the user to input upscale commands. It is primarily designed for upscaling.

Before running the script, it must be edited. The user must change the "invokePath" variable to the location of their "invoke.bat" file and the "invokeOutputs" variable to the location of their "Outputs" folder for "invokeAI". 

The script will not run without these path locations being correctly specified.

Commands for the script should be in the following format:

    "-U" followed by a number (1, 2, 4, or 8)
    or "-embiggen" followed by a scaling factor, an "esrgan" strength value between 0 and 1, and either an "overlap ratio" or "overlap pixels" value.

https://invoke-ai.github.io/InvokeAI/features/EMBIGGEN/#embiggen_1
