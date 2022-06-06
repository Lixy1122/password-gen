# password-gen
python password gen!
-----------------------------------
import random

lower = "qwertyuiopasdfghjklzxcvbnm"
upper = "QWERTYUIOPLKJHGFDSAZXCVBNM"
numbers = "1234567890"
symbols = "!@#$%^&*()[]}{;:'<>?."

string = lower + upper + numbers + symbols
length = 20
password = "".join(random.sample(string, length))

print(password)
