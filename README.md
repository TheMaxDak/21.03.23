# Задание 1
```

import re 
result = re.search(r'TYTY','HA$','SGO TO HA$')
print(result.group(0))
```

# Задание 2
```

import re 
result = re.sub(r'TYTY','HA$','SGO TO HA$')
print(result)
```

# Задание 3
```

import re 
result = re.findall(r'bread','bread s chesse and bread s hunny')
print(result)
```

# Задание 4
```

import re
result = re.match(r'Gag','Gag Ton')
print(result.group(0))
```

# Задание 5
```

import re
result = re.split(r'a','Tytyshka pepedos', maxsplit = 2) 
print(result)
```
