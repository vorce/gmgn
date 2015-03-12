# GMGN #
[![](http://i35.tinypic.com/mrcug3.png)](http://code.google.com/p/gmgn/)

## Introduction ##
Python script that checks your Gmail account(s) for new mail. If it finds any, it will notify you with Growl.

## Dependencies ##
You will need libgmail and growl python bindings to run the script (links to the right). It is not end-user friendly yet.

---

## News ##
### 2008-10-20 ###
I'm currently battling py2app to bundle GMGN into a simple, end-user friendly native mac os x application. The show stopper at the moment i libgmail. The .app is generated properly by py2app but I will get this error when running it:
```
import libgmail
  File "libgmail.pyc", line 39, in <module>
  File "email/__init__.pyc", line 79, in __getattr__
ImportError: No module named base
```
Which I gather might have something to do with [this](http://www.mail-archive.com/pyinstaller@googlegroups.com/msg00801.html). Will post updates here and at my [blog](http://forvillelser.tumblr.com) when/if progress is made.

---

### 2008-10-19 ###
This google code project page up. Added download of 0.1.

---

