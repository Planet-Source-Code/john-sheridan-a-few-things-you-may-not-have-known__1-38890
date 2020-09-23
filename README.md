<div align="center">

## A few things you may not have known


</div>

### Description

Just a few things about vb that will probably be helpful to you once in a while.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[john sheridan](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/john-sheridan.md)
**Level**          |Beginner
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/john-sheridan-a-few-things-you-may-not-have-known__1-38890/archive/master.zip)





### Source Code

Did you know you can set boolean variables to mathematical equations? For example: <br>
<br><font face="Courier New"><b>
Dim blnMyBoolean As Boolean <br>
<br>
blnMyBoolean = (1 + 1 = 2) <br>
<br></font></b>
This would assign the variable a <i>True</i> value. On the other hand, this...<br>
<br><font face="Courier New"><b>
blnMyBoolean = (1 + 1 = 3) <br>
<br></font></b>
...would give the variable a <i>False</i> value. <br>You can also use greater than or less than:<br><br><font face="Courier New"><b>
blnMyBoolean = (1 < 2) 'true<br><br></font></b>
This is useful if you're making a math quiz program or something or you use boolean variables that test numbers.<br><br><br>Another good tip I know that saves time is a quick way to reverse boolean variables. For example, say you have a Command Button that Enables or Disables a timer. Instead of using an if, just do this:<br><br><font face="Courier New"><b>
Private Sub Command1_Click()<br>
Timer1.Enabled = Not Timer1.Enabled<br>
End Sub<br></font></b><br>You can also use this with <i>Visible</i>, or any other boolean variable.<br><br>I hope these two quick tips helped you. No need to vote, I just felt like uploading this.

