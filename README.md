# tinyscheme

A fork of
[TinySCHEME 1.42 (2020-05-30)](https://tinyscheme.sourceforge.net/home.html).

## TinySCHEME notes

This section contains notes on the upstream source,
[TinySCHEME](https://tinyscheme.sourceforge.net/home.html)


### Copying

TinySCHEME 1.42 was released with the following license:

    Copyright (c) 2000, Dimitrios Souflis. All rights reserved.
    
    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are
    met:
    
        Redistributions of source code must retain the above copyright notice,
        this list of conditions and the following disclaimer.
    
        Redistributions in binary form must reproduce the above copyright
        notice, this list of conditions and the following disclaimer in the
        documentation and/or other materials provided with the distribution.
    
        Neither the name of Dimitrios Souflis nor the names of the
        contributors may be used to endorse or promote products derived from
        this software without specific prior written permission.
    
    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR
    CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
    EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
    PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
    PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
    LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
    NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

### MiniSCHEME Tribute

TinyScheme would not exist if it wasn't for MiniScheme.
I had just written the HTTP server for Ovrimos SQL Server, and I was lamenting the lack of a scripting language.
Server-side Javascript would have been the preferred solution, had there been a Javascript interpreter I could lay my hands on.
But there weren't.
Perl would have been another solution, but it was probably ten times bigger that the program it was supposed to be embedded in.
There would also be thorny licencing issues.

So, the obvious thing to do was find a truly small interpreter.
Forth was a language I had once quasi-implemented, but the difficulty of handling dynamic data and the weirdness of the language put me off.
I then looked around for a LISP interpreter, the next thing I knew was easy to implement.
Alas, the LeLisp I knew from my days in UPMC (Universite Pierre et Marie Curie) had given way to Common Lisp, a megalith of a language!
Then my search lead me to Scheme, a language I knew was very orthogonal and clean.
When I found Mini-Scheme, a single C file of some 2400 loc, I fell in love with it!
What if it lacked floating-point numbers and strings!
The rest, as they say, is history.

### MiniSCHEME Credits

     ---------- Mini-Scheme Interpreter Version 0.85 ----------

                coded by Atsushi Moriwaki (11/5/1989)

            E-MAIL :  moriwaki@kurims.kurims.kyoto-u.ac.jp

               THIS SOFTWARE IS IN THE PUBLIC DOMAIN
               ------------------------------------

This software is completely free to copy, modify and/or re-distribute.
But I would appreciate it if you left my name on the code as the author.

This version has been modified by R.C. Secrist.

Mini-Scheme is now maintained by Akira KIDA.
