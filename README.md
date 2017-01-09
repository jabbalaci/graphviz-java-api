**New (Jan 9, 2017):** This project is not maintained anymore. If you want
to add something to it, make a fork. Thanks.

GraphViz Java API
=================

* Author:     Laszlo Szathmary (jabba.laci@gmail.com)
* Date:       2003--2016
* License:    GPL 2 or Apache 2

GitHub:     https://github.com/jabbalaci/graphviz-java-api


With this Java class you can simply call dot from your Java programs.
It is made to facilitate the usage of [GraphViz](http://www.graphviz.org/)
in your Java programs.

Example
-------
Check out the file `Proba.java` to see how to use this simple API.

How to compile the sources in command-line
------------------------------------------
You can use maven. The output will appear in the `target/` folder.

    $ mvn package

Or, you can use SCons. The output will appear in the `bin/` folder.

    $ scons

How to launch the example from command-line
-------------------------------------------
If you used SCons for instance, then

    $ java -cp bin/ com/github/jabbalaci/graphviz/Proba

It prints a dot source to the stdout, and creates its corresponding GIF
representation in your temp folder.


History
-------
small changes are not listed...

    0.6.1   Apr. 10, 2016   The eclipse project configuration was extended with the maven nature.
                            (patch of Markus Keunecke)
    0.6     Nov. 28, 2013   Representation type can be specified (dot, neato, fdp, sfdp, twopi, circo)
                            (patch of Olivier Duplouy)
    0.5.1   Mar. 18, 2013   Mac support (patch of Juan Hoyos)
    0.5     Apr. 24, 2012   OS detection, start subgraph, read config file
                            (patch of Abdur Rahman)
    0.4.5   Apr. 16, 2011   Image dpi can be changed (patch of Peter Mueller).
            Apr. 10, 2011   Moving to GitHub.
    0.4     Feb. 5, 2011    Patch of Keheliya Gallaba is added. Now you can
                            specify the type of the output file:
                            gif, dot, fig, pdf, ps, svg, png, etc.
    0.3     Nov. 29, 2010   Windows support (only took 7 years :))
                            + ability to read DOT source from a file
    0.2     July 22, 2010   simple bug fix
    0.1     Dec. 4, 2003    first release


Contributors
------------
Thanks to these people for their contributions:

* Daniel Khashabi
* Mike Chenault
* Keheliya Gallaba
* Peter Mueller
* Abdur Rahman
* Juan Hoyos
* Olivier Duplouy
* Markus Keunecke
