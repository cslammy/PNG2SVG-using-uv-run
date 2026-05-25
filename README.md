# PNG2SVG-using-uv-run
PURPOSE:

Turns PNG files to SVGs using python, with scaling; variable algos throw back different things like line thickness..  

BASIC "HOW DO I RUN THIS?":

See "README photo to outline svg.txt" for requirements, how to install, how to run using uv.  I am not going to maintain that twice, and I don't want to use github every time I need to remember how to run the damn thing, so I am not putting that into this readme.

I include a snoopy png file to experiment with.  If the script works you should have a subfolder called OUTPUT with a bunch of SVG files in there--use whatever you think looks best.

But in short:
--Uses UV run, so no complex venv python setup. <br/>
--Requires potrace (not a Python module--the actual app) with PATH configured  <br/>
This cmdline worked for me on W11 just now.  uv run .\photo_to_outline_svg.py test-snoopy.png <br/><br/>
 
How this was made
Vibe coded with claude 4.7 opus (who codes anymore--all hail stupid!) 
