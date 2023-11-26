# CUCU-Compiler-Design

CUCU (A Compiler U Can Understand) is a toy compiler for a toy language.
As writing a compiler for the whole ANSI C standards is very difficult, CUCU is a very small subset of the C language.

i) to run and compile,use commands : 
#bison -d cucu.y \n
#flex cucu.l 
#gcc cucu.tab.c lex.yy.c -lfl -o cucu ./cucu micro.txt ,if micro.txt is the input file then input file should be given as command line arguments.

ii) i have not included brackets in parser output.

iii) Sample1.txt Sample2.txt are input file. Sample1.txt contains correct C code, Sample2.txt contains incorrect C code.
