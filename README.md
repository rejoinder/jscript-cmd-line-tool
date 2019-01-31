# Jscript cmd line tool
Port of a tool used to decode MS JScript. Useful for some Malware reverse engineering or decoding of obfuscated Javascript. I have seen JScript.Encode used recently and thought this tool could be useful for folks working on security research. JScript was introduced by MS in 1996. I did not write the original implementation of this.

Credit goes to: MrBrownstone, mrbrownstone@virtualconspiracy.com



------------------

<b>Usage (single command line): </b>
<br />

./srcdec < infile > < outfile > < -urldec | -htmldec > < -verbose > < -dumb >

<b>Options:</b>
<br />

Use -urldec to unescape %xx style encoding on the fly, or -htmldec to unescape & style encoding.

Use -dumb to bypass HTMLGuardian defeation mechanism.

Use -verbose for verbose output.

Hit enter. Then check the < outfile > you set. 

Simple app.
