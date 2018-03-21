# RGB Charliplexed 4x4x4 Led Cube
# Youtube link of working cube:
# https://www.youtube.com/watch?v=t1ANYMKwchA

CharlieCube with Arduino Nano

I Changed the following code in cubeplex.h because the original code was not looping through the effects :

bool continuePattern=false:
to:
volatile bool continuePattern = false;

Now EVERYTHING WORKS!!!
Hope it helps those having the same issue.

Original Asher Glick's project:
http://aglick.com/charliecube.html

Hari Wiguna's blog:
http://g33k.blogspot.com/2013/03/char...

More about charlieplexing:
http://en.wikipedia.org/wiki/Charliep...

Good information from:
https://www.instructables.com/id/Char...
https://www.instructables.com/id/Hack...

All 3 parts of RGB cube video:
https://youtu.be/n_CZL5dw-pY
https://youtu.be/zEIUTQOe7L8
https://youtu.be/hxSoQ93-bbg
