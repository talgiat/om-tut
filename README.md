##om-tut

IE8 Issues with om tutorial.

####How to replicate IE8 errors

```
lein cljsbuild once om-tut
python -m SimpleHTTPServer
```
Navigate to http://box_ip_address:8000 from windows7/IE8 browser. Click on the add contact input field, errors will show. 
Enter a name (e.g. David Nolen) and click 'Add Contact' button, more errors show, as can be seen in the screenshot below.

![screenshot of the errors on IE8](https://raw.githubusercontent.com/talgiat/om-tut/master/IE8_om_error.png)
