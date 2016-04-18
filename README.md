# nucleo-jlink

ST Nucleo + SEGGER Jlink SWD adapter 

Format is EagleCAD schematic and board layout

Adapts Jlink 2x10 connector to the 6-pin ARM SWD connector on the larger ST Nucleo development boards.

### Notes

Target Vref is connected to JP1 on the Nucleo PCB, which is normally left open. JP1 controls the max current requested during USB enumeration. You may need to short it if you are powering the board via USB without enumeration. If you wish to short this jumper, use extended-length header pins or simply bridge the pins on the adapter PCB. 

### PCB on OSH Park

You can order a PCB for this adapter [on OSH Park](https://oshpark.com/shared_projects/m3tkYXXR).

### More Information

* https://www.segger.com/admin/uploads/productDocs/UM08001_JLink.pdf
* https://wiki.segger.com/index.php?title=Connecting_to_STM32_Nucleo_boards
* http://www2.st.com/content/ccc/resource/technical/document/user_manual/98/2e/fa/4b/e0/82/43/b7/DM00105823.pdf/files/DM00105823.pdf/jcr:content/translations/en.DM00105823.pdf

### License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>