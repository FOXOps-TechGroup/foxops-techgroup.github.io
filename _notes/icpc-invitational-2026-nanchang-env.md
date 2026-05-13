## Software

The software configuration will consist of the following:

* OS:
  * Ubuntu 24.04.3 LTS with Linux kernel 6.14.0-29-generic.

* Desktop:
  * Xfce

* Editors:
  * vi/vim
  * gvim
  * emacs
  * gedit
  * geany
  * kate
  * Visual Studio Code

* Languages:
  * C: GCC version 13.3.0 with compiler flags: 
  * C++ version 13.3.0 with 
  * Java: OpenJDK 21.0.8
  * Kotlin: 1.9.24

  * C: GCC 13.3.0 with compiler flags:
    `-x c -Wall -O2 -static -pipe -o "$DEST" {files} -lm`
  * C++: GCC 13.3.0 with compiler flags:
    `-x c++ -std=gnu++20 -Wall -O2 -static -pipe -o "$DEST" {files}`
  * Java: OpenJDK 21.0.8 with compiler flags:
    `-encoding UTF-8 -sourcepath . -d . {files} 2> "$TMPFILE"`
  * Python 3: PyPy3 3.11.11
  * Kotlin: 1.9.24 with compiler flags:
    `-d . -Djava.io.tmpdir=/ {files}`

* IDEs:
  * Eclipse 4.33.0 (2024-09), configured with:

    * JDT (Java Development Tools) version 3.19.600.v20240903-0240 using Java as listed above)
    * CDT (C/C++ Development Tools) version 11.6.1 202407022008 using C/C++ as listed above)
    * PyDev (Python Development Environment) version 13.0.0.202502031104 using Python 3 as listed above)

  * IntelliJ (IDEA Community Edition version 2024.2.3), configured with:

    * Java as listed above
    * Kotlin as listed above

  * CLion (version 2024.2.2), configured with:

    * C/C++ as listed above

  * Pycharm Community Edition Python IDE (version 2024.2.3), configured with:

    * Python 3 as listed above

  * Code::Blocks (version 20.03+svn13046-0.3build2), configured with:

    * C/C++ as listed above

  * Visual Studio Code (version 1.93.1), configured with:

    * Microsoft C/C++ . (Note that the Judges will compile C/C++ programs with GCC as listed above, not with Microsoft C/C++.)


