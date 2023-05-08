Download Link: https://assignmentchef.com/product/solved-swen221-lab-1-java-programming-skills-using-eclipse
<br>
The purpose of this lab is to refresh your Java programming skills, to get started using Eclipse and to learn how to use the online submission system.

<strong>Activity 1: Diagnostic Test (approx 50mins)</strong>

(See separate test sheet)

<h1>Activity 2: Getting Started with Eclipse (approx 15mins)</h1>

To begin, download the calculator.jar program from the lecture schedule on the SWEN221 course website. Now, perform the following steps:

<ol>

 <li>Start Eclipse and create a project called “Calculator”:</li>

 <li>Import the jar file into your Calculator project. Do this by selecting <strong>“File</strong>→<strong>Import</strong>→ <strong>General</strong>→<strong>Archive File” </strong>from the menu:</li>

</ol>

Select the jar file in the “Import” dialog, and the set the <strong>“Into folder” </strong>field to be <strong>“Calculator/src” </strong>and click <strong>“Finished”</strong>.

<ol start="3">

 <li>Add JUnit library to your project. Do this by right-clicking on the project and selecting <strong>“Build Path</strong>→<strong>Add Libraries</strong>→ <strong>JUnit</strong>→<strong>JUnit 5/Jupiter” </strong>from the menu:</li>

</ol>

Your project should now compile without errors.

<strong>NOTE: </strong>if you cannot find the <strong>“Build Path” </strong>menu, then you should check that you are in the “Java” perspective, rather than the “Java EE” perspective:

<ol start="4">

 <li>Run the calculator program from Eclipse by creating a <strong>“Run Configuration”</strong>. One way to do this is by right-clicking on Main and selecting <strong>“Run As</strong>→<strong>Java Application”</strong>:</li>

</ol>

You should see the calculator running in the console window:

<ol start="5">

 <li>You can now perform simple calculations, like with a normal calculator. For example:</li>

</ol>

Welcome to the Calculator!

&gt; 1.0+1.23

= 2.23

&gt; 1+2.0

Found ’+’, expected ’.’: 1+2.0

^

java.lang.RuntimeException: Parse Error at swen221.lab1.Calculator.error(Calculator.java:144) at swen221.lab1.Calculator.match(Calculator.java:115) …

Spend some time using the calculator to get the hang of it; you might notice that there are several bugs in the system (as illustrated above).

<h1>Activity 3: Debugging the Calculator (approx 45min)</h1>

Your next task is to debug the program. To get started, run the JUnit tests provided (by right-clicking on CalculatorTests, and selecting <strong>“Run As</strong>→<strong>JUnit Test”</strong>):

Several of the tests will fail and you’ll need to fix the bugs to make them pass correctly.

<strong>HINT: </strong>Simply “eyeballing the code” (i.e. staring at it) will probably not help you find the bug! You must insert println statements to see what is actually going on, and to narrow down the problem.