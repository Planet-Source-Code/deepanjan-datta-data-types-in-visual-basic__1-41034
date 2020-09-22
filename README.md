<div align="center">

## Data types in Visual Basic


</div>

### Description

Learn everything about data types supported by Visual Basic!!!(Don't look at the ratings because this article has been updated to make it as complete as possible!!!)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Deepanjan Datta](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/deepanjan-datta.md)
**Level**          |Intermediate
**User Rating**    |1.8 (14 globes from 8 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Data Structures](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/data-structures__1-33.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/deepanjan-datta-data-types-in-visual-basic__1-41034/archive/master.zip)





### Source Code

<CENTER><B><H1><U><I>Data types in Visual Basic</I></U></H1></B></CENTER><BR>
Just as ice-creams come in different flavors,<BR> data comes in diffrent types.<BR>
<P>
Visual Basic handles 14 standard data types(it is also possible to define your data types).<BR>
</P>
<H3>String</H3><BR>
<PRE>
The string data type holds characters. Avariable holding a string is called, naturally enough, a string variable.
Here is a declaration of string variable:
</PRE>
Dim strVariableName as String<BR>
<PRE>
String variables can theoritically hold about 2 billion characters. On a specific computer, though, the variable may hold less due to memory constraints, overhead requirements for Windows or the number of strings used in the form.
 One of the commonest uses of string variables is to pick up information contained in a text box.
Here is how:
</PRE>
strVariableName=Text1.Text<BR>
<H3>Integer</H3><BR>
<PRE>
Integer variables hold relatively small integer values (between -32,768 to +32,767). Integer arithmetic is very fast but is restricted to these ranges or you will get an error message.
Here is a declaration :
</PRE>
Dim intVariableName as Integer<BR>
<CENTER><H3>Long integer</H3></CENTER><BR>
<PRE>
Long integer variables hold integers between -2,147,483,648 and +2,147,483,647. Long integer arithmetic is also fast and there is very little (if any) performance penalty on modern machines.
Here is a declaration :
</PRE>
Dim intALongInteger=123456789<BR>
<H3>Single precision</H3><BR>
<PRE>
Single precision variables have a decimal point but one can be sure of accuracy of seven digits. For example if an answer comes as 12,345,678.97 then the 8.97 may not be correct.
The range of these numbers is upto 38 digits.
Calculations will always be approximate for these types of variables; exact answers are impossible to guarantee.
</PRE>
<H3>Double precision</H3><BR>
<PRE>
The answers with this data type have 16 places of accuracy. This data type allows you more than 300 digits.
</PRE>
<H3>Currency</H3><BR>
<PRE>
Variables of this data type are designed to avoid certain problems inherent in switching from binary fractions to decimal fractions.
 The currency type can have four digits to the right of the decimal place and upto fifteen digits to the left of the decimal point.
Arithmetic will be exact within this range.
</PRE>
<H3>Date</H3><BR>
<PRE>
Date data type gives you convenient way to store both date and time information for any time between midnight on January 1, 100 to midnight on December 31, 9999.
</PRE>
<H3>Byte</H3><BR>
<PRE>
Byte type was added to Visual Basic 5. It can hold integers between o and 255. This is a great convenience when you need to save space and it makes certain arrays much smaller than they would have been in earlier versions of Visual Basic.
</PRE>
<H3>Boolean</H3><BR>
<PRE>
Use boolean data type when you need data to be either true or false.
</PRE>
<H3>Variant</H3><BR>
<PRE>
The variant data type is designed to store all the different possible Visual Basic data received in one place. If Visual Basic is not told what data type a variable belongs to, Visual Basic puts the variable in this data type. Using variant type rather than using a specific type is slower because of the conversions needed. It takes up more memory.
</PRE>
Those are the data types supported by Visual Basic.
Happy programming!!!

