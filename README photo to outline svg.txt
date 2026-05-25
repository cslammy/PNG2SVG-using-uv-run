photo_to_outline_svg.py
 
Turn a photo into outline drawings and vectorize them to SVG.
 
Generates 5 outline variants using different edge-detection approaches,
then vectorizes each with potrace to produce SVG files.

 
Usage:
    uv run photo_to_outline_svg.py INPUT.png [-o OUTPUT_DIR] [--scale 4]
 
    # or make it executable and run directly:
    chmod +x photo_to_outline_svg.py
    ./photo_to_outline_svg.py INPUT.png
 
 
Requirements:
    - uv installed (https://docs.astral.sh/uv/)  TO TEST: cmd  then uv.  Should return a "basic UV commands" stdout

    - potrace installed and on PATH:  (NOTE! in windows, PATH changes only impact CMD, not TERMINAL)
        macOS:   brew install potrace
        Linux:   apt-get install potrace
        Windows: download from https://potrace.sourceforge.net/download/1.16/potrace-1.16.win64.zip:
        a) extract
	b) create new directory as local admin, C:\program files\potrace
        c) copy all potrace files in there.

For windows, add potrace to path:
win + r > sysdm.cpl  > advanced tab > environment variables 
under "user variables for [user] find the PATH entry
Add c:\program files\potrace as new PATH entry.
close and reopen CMD.  (PATH entries using sysdm only impact CMD, not PS terminal!)
OK

Did it work? Close and reopen CMD then issue 
potrace --version

You should see something like this.

C:\Users\cl>potrace --version
potrace 1.16. Copyright (C) 2001-2019 Peter Selinger.
Library version: potracelib 1.16
Default unit: inches
Default page size: letter





