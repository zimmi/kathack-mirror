# What?

This is an unofficial mirror of the excellent [http://kathack.com](http://kathack.com) created by Alex Leone, David Nufer and David Truong.  
More specifically, the files making up the bookmarklet itself were copied and modified to load from this github repo.

# Why?

The original bookmarklet doesn't support sites using HTTPS, which now is practically all of them.

# Wherewith?

Try it out by copying this to your bookmarks:
```
javascript:var i,s,ss=['https://zimmi.github.io/kathack-mirror/kh.js','https://code.jquery.com/jquery-1.5.1.min.js'];for(i=0;i!=ss.length;i++){s=document.createElement('script');s.src=ss[i];document.body.appendChild(s);}void(0);
```
Activate it on any site you wish.

# Attribution

All credit goes to the original authors!


Copyright Alex Leone, David Nufer, David Truong, 2011-03-11. kathack.com
