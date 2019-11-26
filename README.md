# FiraCode Retina Font with slant strikeout
FiraCode Retina is my favourite coding font. It has all beautifully
drawn ligatures, but I wanted my own customized strikeout Unicode character
so that it feels good.

Also when I was a child I used to strikeout slantly rather than a 
horizontal line. It reminded me of my mistakes. So why not implement 
the strikeout feature for your own good?

For any code to support strikeout it should have U+0336. Else
the font wont support strikeout like Inconsolata, which doesn't support it


FiraCode Retina has the unicode character U+0336, but it's a horizontal
line, not slanted line. So I copied the slanted line glyph from bptypewrite
to FiraCode to replace the character and now the results are something like 
this:

![](My%20Fira.png)

Don't forget to Star if you like the font.

Copyrights:  
I don't hold any code copyrights. All copyrights are same as that 
laid out by original authors whose information is retained in the font 
metadata

I have also added a python script which I use as keyboard shortcut
to add strikeout into sentences copied to clipboard. It's at: https://github.com/krishnachaitanya9/daily_scripts/blob/master/strikethrough_text_generator.py
