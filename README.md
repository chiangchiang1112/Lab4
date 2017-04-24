問題A
Use g++ to compile the following program, and then use nm to list symbols of the executable file. 
What encoded identifiers are used for the functions?
Ans:
000000000040052d T _Z7averageif
00000000004004ed T _Z7averagePdRd
問題B
What is the output of the following program? Why?
Ans:
1 8
4 8
4 8
8 8
首先char是字元儲存，總共佔記憶體空間1；int與float是單精度數字儲存，總共佔記憶體空間4；double是雙精度數字儲存，總共佔記憶體空間8。
接著是指標(pointer)，指標指的是一個記憶體區段，在32位元電腦上為4bytes，在64位元電腦上為8bytes。
