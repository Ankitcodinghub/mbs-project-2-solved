# mbs-project-2-solved
**TO GET THIS SOLUTION VISIT:** [MBS Project 2 Solved](https://www.ankitcodinghub.com/product/mbs-project-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94266&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MBS Project 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This laboratory practice will be devoted to small matrixes. You will develop a programme which

allows the user to calculate the determinant of 3×3 matrixes. The student must perform the requirement analysis and its implementation. To successfully complete this assignment, you will have to use a significant part of the instructions of 8086 microprocessor.

Task 1. Lab2.asm

Write a programme in assembler which calculates the determinant of a 3×3 matrixes of integer values. The initial values of the matrix might be pre-defined in memory (recommended for an initial version) or typed. For that purpose, the program will show the user a menu with the next options:

<ol>
<li>1) &nbsp;Calculate the determinant using the default values.</li>
<li>2) &nbsp;Calculate the determinant by Typing the new values</li>
</ol>
In case the user selects the second choice, a message will be printed with the instructions on how to input the data to be properly read by the application. To make it simpler, it is recom- mended to use only one interruption to take all the inputs from keyboard.

No matter which option is selected, the programme must print the matrix on the screen, calcu- late its determinant and store it into a variable named B, and then print it with the next format:

</div>
</div>
<div class="layoutArea">
<div class="column">
| a11 a12 |A|= | a21 a22 | a31 a32

</div>
<div class="column">
a13| a23 | = B a33 |

</div>
</div>
<div class="layoutArea">
<div class="column">
To succeed in this task, you will have to implement an auxiliar subroutine which converts an integer number into a ASCII String to print the results as decimal notation number.

i.e.: the number 0122h must be convert in to the ASCII String “274” (32h, 37h and 34h). Laboratory – Microprocessor Based Systems. Laboratory Assignment 2. Academic Course 2021-2022. Pg. 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Important:

<ul>
<li>▪ &nbsp;To access the numbers of the A matrix, the based indexed addressing must be used.</li>
<li>▪ &nbsp;The A values are 8 bits while B values are 16 bits.</li>
<li>▪ &nbsp;The subroutine that converts from binary to ASCII must receive the number that needs to be converted in the register BX, and then it returns in DX:AX the memory address where the ASCII String begins (DX contains the segment while AX contains the offset). The String must be ended with ‘$’ to ease the printing process by using the function 9 of the INT 21h of MS-DOS (read ANEX of Lab0 and Alumno.ASM).</li>
<li>▪ &nbsp;Keep in mind that A values can be negatives. In this case, the values must be stored in memory using 2 complement formatting.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Laboratory – Microprocessor Based Systems. Laboratory Assignment 2. Academic Course 2021-2022. Pg. 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
ANEX I: Functions of the operating system to print text and end the execution.

The operating system MS-DOS provides most of its services through the interruption INT 21h. Firstly, the function number must be loaded into the AH register. Moreover, individual functions can require some other input parameters whose value must be stored in other registers. Three functions for programmes developed in these laboratory assignments are detailed below.

Function 2H: Send an ASCII code to the screen peripheral. Description: Print a single character into the screen.

Input parameters: ➢ AH=2h

DL = ASCII code to be printed.

Output parameters: none. Involved registers: none. Example:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>MOV AH, 2h
MOV DL, ‘A’
INT 21h
</pre>
</div>
<div class="column">
; Function number

; Character to be printed

<pre>    ; Software interruption
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Function 9H: Send an ASCII string to the screen peripheral. Description: Print a string ended with character ‘$’ into the screen.

Input parameters: ➢ AH=9h

DX = Memory offset of the data segment where the first character of the string is stored.

Output parameters: none. Involved registers: none. Example:

.DATA

TextPrint DB “Hello world, 13, 10, $” ; String ended with the characters CR, LF and ‘$’

.CODE

; If DS is the segment where the text to print is stored

MOV DX, OFFSET TextPrint ; DX: Offset at the beginning of the text to print string MOV AH, 9h ; Printing String function

INT 21h ; Software interruption

</div>
</div>
<div class="layoutArea">
<div class="column">
Laboratory – Microprocessor Based Systems. Laboratory Assignment 2. Academic Course 2021-2022. Pg. 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Function 0AH: Reading characters introduced by the keyboard peripheral.

Description: It captures the characters introduced using the keyboard and prints them into the screen in a local echo mode and transfers them to the application. The function ends when the users introduce the ASCII 13 (car- riage return). The operating system allows the character’s input up to the maximum numbers of characters previ- ously defined. Otherwise, these overflow characters won’t be printed and stored.

Input parameters:

➢ DX = Memory offset of the data segment where the space to store the captured characters is defined. In the first byte of that reserved memory space the maximum number of characters desired must be de- fined.

Output parameters: In the second byte of the reserved memory space pointed by DX the operating system stores the number of characters stored.

Involved registers: none.

Example:

MOV AX, 0Ah ; Capture keyboard function.

MOV DX, OFFSET NAME ; Memory space reserved named NAME MOV NAME[0], 60 ; Maximum number of characters is 60 INT 21h ; Software interruption

In NAME[1] the operating system will store the number of registered characters.

Function 4C00h: End of programme.

Description: This function indicates to the operating system that the process (programme) has ended correctly. Input parameters: none.

Output parameters: none

Involved registers: none.

Example:

MOV AX, 4C00h ; End of programme.

<pre>INT 21h          ; Software interruption
</pre>
</div>
</div>
</div>
