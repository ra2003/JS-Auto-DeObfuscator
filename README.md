JS Auto DeObfuscator v.5 by Luciano Giuseppe: http://sites.google.com/site/lucianogiuseppeprogrammi/
========================


##About
This tool helps security researches to speed up their work: it's useful when a js uses eval or some other function, one or more time, to de-obfuscat it-self.
It uses to work as default browser Firefox, but at last line of the source you can change firefox with an other browser as Chrome, obviously.


##How to use
python jsado.py file.html function_to_hack [n_execution=0] 

You can call this script with: "python jsado.py obf.html eval" to don't let's execute eval in obf.html and get into the browser all js code executed with eval.
You can use the increment to let execute eval one time , for example: the first time with eval there are some variables declaration.

##How JSADO works
JSADO injects into the webpage a js script, that hook the function. Once the function hooked is executed, the js script injected shows a pannel with the code catched.
