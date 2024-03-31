# Python-password-
import random
lower="abcdefghijklmnopqrstuvwxyz"
upper="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
numners="1234567890"
symbols="@#$_&-+(){}/?!;;'"*<>"
all=lower+upper+numbers+symbols
length=18
password="".join(random.sample(all,length))
print(password)
