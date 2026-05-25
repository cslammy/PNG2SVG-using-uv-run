# PNG2SVG-using-uv-run
PURPOSE:

Turns PNG files to SVGs using python, with scaling; different algos return different SVGs per conversion, varying things like line thickness so you can choose the best file for your needs.

 HOW DO I RUN THIS?":

 in short:<br/><br/>
--Uses UV run, so no complex venv python setup. <br/>
--Requires potrace (not a Python module--the actual app) with PATH configured  <br/>

This cmdline worked for me on W11 just now. <br/><br/> uv run .\photo_to_outline_svg.py test-snoopy.png <br/><br/>
 

See "README photo to outline svg.txt" file in the repo for requirements, how to install, how to run using uv. I include a snoopy png file to experiment with.  

If the script works you should end up with a subfolder called OUTPUT with a bunch of SVG files in there--use whatever you think looks best.


How this was made
Vibe coded with claude 4.7 opus (who codes anymore--all hail stupid!) 
