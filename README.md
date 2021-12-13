# learningpython
#Randomize a password using list comprehension that starts with XXX### where X can be any english alphabet and # can be any digit

alphabet='abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'
digits='0123456789'

solution=[a+b+c+d+e+f for a in alphabet for b in alphabet for c in alphabet for d in digits for e in digits for f in digits]
