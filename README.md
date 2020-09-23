<div align="center">

## \_ Open child window without toolbars, menues, buttons \.\.\.or all of them\.\.\.\.you decide \_


</div>

### Description

<br><b>Check this out!</b><br><ul>

<li><font face="Arial, Helvetica, sans-serif" size="2">This code is not only

REALLY simple, but has a lot of potential!</font></li>

<li>Fully commented, and

easy for you to customize.</li>

<li>You probably have seen

this function before, but it doesnt get any easier than this. Simply change

the URL, and size, and your off!.</li>

<li>It's like and 'a href',

so you can put the script anywhere you put one.</li>

</ul>

<p>Simple, yet effective....LOTS

more to come.</p><br><br> <CHECK OUT EXAMPLE</b> <a href="http://www.paul_cormie.homestead.com" target="_blank">Click on any of the sample URLs</a></font><br><br><br>
 
### More Info
 
All you need is to input your URL, and change the size of the popup window

all the code is here...even the HTML, so its as easy as cut and paste.

a child window with full control of the options of it. For example no menu, no scrollbar..etc


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[paul\_cormie](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/paul-cormie.md)
**Level**          |Intermediate
**User Rating**    |3.9 (27 globes from 7 users)
**Compatibility**  |
**Category**       |[Windows](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows__2-80.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/paul-cormie-open-child-window-without-toolbars-menues-buttons-or-all-of-them-you-decide__2-2014/archive/master.zip)





### Source Code

```
<html>
<head>
<title>Using JavaScript to open a child window</title>
</head>
<script>
<!-- JavaScript Start -
function openWin( windowURL, windowName, windowFeatures ) {
 return window.open( windowURL, windowName, windowFeatures ) ;
}
JavaScript End -->
</script>
<body>
<!--It's just like a regular 'href', but calls the script to open the new window.
If you also really want to go crazy, you could diable the right click....search for "a right click disabler" -->
<a href="javascript: newwindow = openWin( 'http://www.miata.net/garage/tirecalc.html', 'Title', 'width=450,height=550,toolbar=0,location=0,directories=0,status=0,menubar=0,scrollbars=0,resizable=0' ); newwindow.focus()">Click here for a child window to open using JavaScript!</a>
<!--anything you can do with a 'href' you can do with this. lots of potential! -->
</body>
</html>
```

