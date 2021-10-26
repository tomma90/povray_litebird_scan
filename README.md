# POV-Ray scene file

This repository contains the POV-Ray files used to create the
following video:

[![Link to YouTube video](https://img.youtube.com/vi/C0xdvI1rNzg/0.jpg)](https://www.youtube.com/watch?v=C0xdvI1rNzg)

To re-create the animation, you need to have:

-  GNU Make
-  [POV-Ray 3.7](http://povray.org/)
-  [ffmpeg](https://ffmpeg.org/)

If you have all the programs available on your path, just run

    povray litebird-scanning-strategy.ini
    
(For those not proficient with POV-Ray, the `.ini` file describes how
images should be created, but the juicy parts with the geometry are in
the `.pov` file.)
