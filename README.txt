What are tags?

Tags are a feature youtube added for content creators to give them the ability to optimise their videos for specific search terms.
So if you make a video in which you showcase your cake you would give the video the tag "baking" and if anybody then searched for "baking" your video would show up.
This sometimes leads to abuse as normally those tags are not shown to the end user and thus a false tagging is pretty much never reported. You want your cake video to go viral,
but muffins are more popular right now? Just throw a tag "muffin" into there. Nobody will notice.
Basically tags are, what youtubers do, when they think nobody's looking.



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
