# myfirstpython
I have leant python before but I wanted to create a solid documentation of what I will be doing from now on SO DEPOSITING MY CODES AND WOKRS IN GIT-HUB let's gooo!!!!
Python 3.9.6 (tags/v3.9.6:db3ff76, Jun 28 2021, 15:26:21) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> string='error'
>>> len(string)
5
>>> a='mommy'
>>> a.index('m')
0
>>> a.count("m")
3
>>> a.find("sco")
-1
>>> a.lower
<built-in method lower of str object at 0x000001F1AB0F07F0>
>>> a.lower()
'mommy'
>>> a.upper()
'MOMMY'
>>> a.startswith("m")
True
>>> b= " hello "
>>> b.replace(" ","")
'hello'
>>> "_".join(a)
'm_o_m_m_y'
>>> "-".join(a)
'm-o-m-m-y'
>>> "3".join(a)
'm3o3m3m3y'
>>> m in a
Traceback (most recent call last):
  File "<pyshell#17>", line 1, in <module>
    m in a
NameError: name 'm' is not defined
>>> "m" in a
True
>>> "model: %s, %d slots, ios %f" % ("777RM",7,7.77)
'model: 777RM, 7 slots, ios 7.770000'
>>> "model: %s, %d slots, ios %f" % ("7745RM",11,7.69)
'model: 7745RM, 11 slots, ios 7.690000'
>>> "model: {}, {} slots, ios {}" .format ("4657RM",7,9.77)
'model: 4657RM, 7 slots, ios 9.77'
>>> "model: {1}, {1} slots, ios {1}" .format ("4657RM",7,9.77)
'model: 7, 7 slots, ios 7'
>>> "model: {0}, {2} slots, ios {1}" .format ("4657RM",7,9.77)
'model: 4657RM, 9.77 slots, ios 7'
>>> perfect
Traceback (most recent call last):
  File "<pyshell#24>", line 1, in <module>
    perfect
NameError: name 'perfect' is not defined
>>> "perfect"
'perfect'
>>> model = "7999RM"
>>> slots = 7
>>> ios = 7.99
>>> f"(model: {model}, {slots} slots, ios {ios})
SyntaxError: EOL while scanning string literal
>>> f"model: {model}, {slots} slots, ios {ios}
SyntaxError: EOL while scanning string literal
>>>  f"model: {model}, {slots} slots, ios {ios}"
 
SyntaxError: unexpected indent
>>> f"model: {model}, {slots} slots, ios {ios}"
'model: 7999RM, 7 slots, ios 7.99'
>>> 
