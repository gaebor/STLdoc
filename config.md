## Usage
Copy every implementation to `XYZ/inc`
Where XYZ is your preferred STL implementation

And edit the configure file as

    STRIP_FROM_INC_PATH    = XYZ/inc
    HTML_OUTPUT            = XYZ/html
    INPUT                  = XYZ/inc

then run the following from this directory:

    doxygen XYZ/config

## Implementation

Find the implementation of STL, it depends on your compiler and OS.
* VS2017: `C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.10.25017\include`
* `gcc` on linux: `/usr/include/c++/9.9.9`
* VS2013: `C:\Program Files (x86)\Microsoft Visual Studio 12.0\VC\include`
