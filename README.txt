How to use:
The script takes the video URL as the first args and then searches the sourcecode for "keywords":
> java -jar YT_Tags.jar https://www.youtube.com/watch?v=JGwWNGJdvx8

Shortened URLs will work as well, as long as it's a direkt link:
> java -jar YT_Tags.jar https://youtu.be/JGwWNGJdvx8

Special characters like Ä/Ü/etc. may be misinterpreted by your console thus resulting in weird outputs:
Î?Î½Ï? Î£Î·Ï?Î±Î½
Î?Î´ Î£Î·ÎµÎµÏ?Î±Î½
Î?Î½Ï? Î£Î¹Ï?Î±Î½
(from Shape of you)

Consoles are Ascii after all.

If you are using Windows you will find a "run.bat" with the code. This batch file generates the command for you.
If this batch script does not work you might have to copy the command and replace %i% with your URL.
