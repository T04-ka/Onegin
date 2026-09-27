<h1 align="center">
  How to use my Onegin
</h1>

## My lore
Hey, I'm T04-ka, First-year student at MIPT (FRKT). This is my first university project after summer "kvadratka", 
completed as part of an educational semester course, prodused under direction of Ilya Rudolfovich Dedinski (aka DED, aka SARODIP).

A special, big thank you to my mentor, Yasha [Bolda] (also SARODIP and CHMO(d +x)).

## Synopsis
This is the program for sorting content from text files in different orders. For example: if you have file "hol_ded.txt", 
you can put it in program and get output file with sorted "hol_ded.txt" in direct alphabetical order and reverse order, comparing from the end.

P.S. You can use your own text file, or see sorted "Evgeniy Onegin" by Aleksandr Sergeevich Pushkin. "Evgeniy Onegin" already included to the release (see file <kbd>ASPushkinEvgeniyOnegin.txt</kbd>).

## Usage
1. Download the archive from [the last page of the release](https://github.com/T04-ka/Onegin/releases/tag/v1.0).
2. Extract the contents of the archive to a path that does not contain Russian characters or special symbols.
3. Run executable file with command
```text
PATH/Onegin input.txt output.txt
```
replacing "PATH" with the path to the work directory (FE <kbd>~/Desktop/sarodiPahsaY/Onegin</kbd>), "input.txt"
with the path to your file, "output.txt" with the path to file that you want to sorted data be written.
## Notes
1. You may not to write "output.txt", then output will be printed in terminal.
2. To use given "Evgeniy Onegin" text, use command 
```text
PATH/Onegin ASPushkinEvgeniyOnegin.txt output.txt
```
replacing "PATH" with the path to the work directory, "output.txt" with the path to file that you want to sorted data be written.

3. **This program is intended only for Linux users.**
4. **If you use your own file, make sure there exist only English letter and special symbols(NO UTF-8 BLYAT!!!)**

## Fun facts
* Sorting algorithm is implemented using 2 different methods. The program uses quicksort from the standard library and my own quicksort algorithm.
* When comparing strings, non-alphabetical character are ignored, uppercase letters are treated the same as lowercase letters.
* Reading from a file is implemented using the fopen, fread, fclose functions.

* To see Linux manual pages for my own functions, use command
```text
PATH/man/man3/filename
```
replacing "PATH" with the path to the work directory, filename with name of file which Linux man you want to see.

* To see full project documentation, use command 

```text
BROWSER PATH/html/index.html
```
replacing "PATH" with the path to the work directory, "BROWSER" with the command you use to open the browser you want to open documentation in.

Here are examples for some browsers from my lovely Ubuntu (ВСТАВИТЬ СЕРДЕЧКО):

Google Chrome
``` 
google-chrome PATH/html/index.html
```
Firefox
``` 
firefox PATH/html/index.html
```
* Yasha is loh.
<p align="center">
  <img width="954" height="474" alt="image" src="https://github.com/user-attachments/assets/e69305ba-582a-44a9-bdbd-27cdb2260609" />
</p>

<h1 align="center">
  🆁🅰🅳🅸 🅽🅴🅴......
</h1>


