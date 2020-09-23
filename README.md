<div align="center">

## Base 64 Encoding/Decoding


</div>

### Description

This is an optimized version of the common Base 64 encode/decode. It eliminates the repeditive calls to chr$() and asc(), as well as the linear searches I've seen in some routines. It also avoid shifting each byte encoded using multiplication and division.

This method does use a bit more memory in permanent lookup tables than most do. However, this eliminates the need for using vb's rather slow method of bit shifting (multiplication and division). A method I've not seen elsewhere.

It doesn't make much difference in the IDE, but does make a huge difference in the exe. On my machine it's as fast as commercial packages such as Eudora on encoding if not faster.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2000-11-13 21:50:54
**By**             |[Tim Arheit](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tim-arheit.md)
**Level**          |Advanced
**User Rating**    |5.0 (25 globes from 5 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Encryption](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/encryption__1-48.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[Base\_64\_En1126297302002\.zip](https://github.com/Planet-Source-Code/tim-arheit-base-64-encoding-decoding__1-37414/archive/master.zip)








