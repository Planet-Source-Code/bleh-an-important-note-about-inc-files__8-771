<div align="center">

## An Important Note About \.inc Files


</div>

### Description

Security issues using ".inc" include files.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[bleh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bleh.md)
**Level**          |Beginner
**User Rating**    |3.7 (55 globes from 15 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Security](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/security__8-14.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bleh-an-important-note-about-inc-files__8-771/archive/master.zip)





### Source Code

<font face="Verdana" size="2">
<b>An Important Note About .inc Files</b>
<p>This is just a quick note about using include files with the ".inc" file extension. This doesn't apply to <b>JUST</b> PHP, but the web in general. I am posting this here in the PHP section because that is the server side language that I use, and I have noticed an abundance of ".inc" files in various projects throughout PSC.</p>
<p>For those who don't know, ".inc" files are nothing more than a file that generally contains information that you would need to access from various scripts on a site. Most often, they are a time saving way of storing certain variables. A primary example is Login/Passwords for database connections. This way, if you change the login/pass for the database, you only need to update one file.</p>
<p>The problem is, however, that the contents of ".inc" can be viewed in a browser by simply typing in the path. So anyone who knew the path of your include file could easily find out information that you probably didn't want them to know. Now, to those who aren't all that concerned with security, this may not seem a big issue. However, for the more paranoid among us, it is an issue.</p>
<p>I'm not sure if this applies to all platforms. The server I use runs Apache on Slackware, and the SysOp is a pretty security conscious person. Also, it could vary well be just an IE6 thing, as I have not had a chance to test this in any other browser. However, I thought I would make the uninformed among you aware of this.</p>
<p>The best way to get around this is to simply change the file extension to ".php" (or whatever language your using). It's that easy. Don't let your information be compromised.</p>
</font>

