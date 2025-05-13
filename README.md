# csf211-lab-5-running-time-and-space-usage-insertion-sorting-file-i-o-and-build-tool-solved
**TO GET THIS SOLUTION VISIT:** [CSF211 Lab 5-Running Time and Space Usage, Insertion Sorting, File I/O, and Build Tool Solved](https://www.ankitcodinghub.com/product/csf211-lab-5-running-time-and-space-usage-insertion-sorting-file-i-o-and-build-tool-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91920&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSF211 Lab 5-Running Time and Space Usage, Insertion Sorting, File I\/O, and Build Tool Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Topics: Recursion, Measurements: Running Time and Space Usage, Insertion Sorting, File I/O, and Build Tool – Makefile

Exercise 1: [Expected Time: 40 minutes.]

Write a procedure to read a large file of records and store it in an array:

<ol>
<li>a) &nbsp;Assume that each record contains information about a credit card: &lt;Card_Number&gt;, &lt;Bank_Code&gt;, &lt;Expiry_Date&gt;, &lt;First_Name&gt;, &lt;Last_Name&gt; where &lt;Card_Number&gt; is a 16-digit integer, &lt;Bank_Code&gt; is made of 5 characters, &lt;Expiry_Date&gt; is in the form mm/yyyy.</li>
<li>b) &nbsp;Assume that each record is stored in one line of the file.</li>
<li>c) &nbsp;Assume an initial size for the array and allocate dynamically. Resize the array when it
is full. [Hint: Use realloc. End of Hint.]
</li>
<li>d) &nbsp;Measure the time taken for the entire read procedure for different file sizes – start
from 10,000 records and go up to 10,000,000 records. For initial testing, use given test files (10, 100, 1000, 10000) and then concatenate them repeatedly to generate requisite number of records.
</li>
<li>e) &nbsp;Write the measurements into an output file.</li>
</ol>
Exercise 2: [Expected Time: 60 minutes]

<ol>
<li>a) &nbsp;Write an insertInOrder procedure to insert a credit card record (see previous exercise) into an array of credit cards. Credit card number is the key.</li>
<li>b) &nbsp;Write a recursive procedure implementing Insertion Sort (that calls the insertInOrder procedure).</li>
<li>c) &nbsp;Measure the time taken by the insertionSort procedure from (b) for varying list sizes. Plot a curve using these measurements. Compare this curve against an estimated curve [i.e. O(n*n) curve for insertion sorting.]</li>
<li>d) &nbsp;Measure the stack space used by the insertionSort procedure for different list sizes. [i.e. Use the address of a variable in main as the bottom of the stack. Use the address of a variable in the current top-of-stack frame and find the difference in addresses. This gives a very good approximation of stack size.]</li>
<li>e) &nbsp;Write the measurements from (c) and (d) to an output file.</li>
</ol>
Assignment wrt Lab5: Solve Exercise 2 and upload the solution with all the graphs. Do not forget to rename the folder with your BITS ID.

Exercise 3: [Expected Time: 30 minutes]

Although you must have already grasped knowledge about make files during your assignment submission, following is a short introduction to it.

Write a Makefile with targets run, and compile for the program in Exercise 2:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li> &nbsp;compile: Compile files readRecords.c, insertionSort.c, and measureTimeAndSpace.c (with the appropriate header files) separately. Compile the object files (i.e. .o files) with the main .c file to produce an executable.</li>
<li> &nbsp;run: Run the executable produced by compile once with the input file.
Introduction to Makefiles:

Makefile is a linux utility to easily compile and link large programs, typically containing multiple source and header files. Whenever “make” command is run, it searches for a file named “makefile” in the current directory and executes it.

A makefile is a collection of rules, where each rule consists of following:

• target:keywordthatusercanpassasargumentto“make”.

• dependencies (prerequisites): all the files on which this target depends upon. If they are target themselves and have been modified since last execution then their corresponding rule is first executed

• commands(recipes):allthecommandswhichshouldbeexecutedifalldependencies of current target are met (i.e. unchanged from last execution)

Syntax: for writing a rule (there should be a tab (not spaces) before each command): target : dependency1 dependency2 dependencyn

command1 command2 commandm

Example:

Assume that there are two modules (with a source and header file each) and a driver file. In order to create a makefile with a single target “compileAll”, so that it can be executed with “make compileAll” command on terminal, a makefile can be created as follows: ***********************************************************

<pre>compileAll : module1.o module2.o driver.o
     gcc module1.o module2.o driver.o  -o myprogram
</pre>
<pre>module1.o : module1.c module1.h
     gcc  -c  module1.c
</pre>
<pre>module2.o : module2.c module2.h
     gcc  -c  module2.c
</pre>
<pre>driver.o : driver.c module1.h  module2.h
     gcc  -c  driver.c
</pre>
<pre>***********************************************************
</pre>
Exercise 4: [Expected Time: 45 minutes]

a) Modify the Makefile in Exercise 3 to add a target test with a parameter that specifies a test distribution. (see b)

b) Generate the following different input distributions and repeat Exercise 2 for each of them:
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li> &nbsp;Input list where several duplicate entries</li>
<li> &nbsp;Input list where a single entry is replicated a large number of times</li>
<li> &nbsp;Input list that is already in sorted order</li>
</ul>
 Input list that is sorted in reverse order

</div>
</div>
</div>
