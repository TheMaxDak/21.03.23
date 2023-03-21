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
# Задание 6
```

import re
result = re.findall(r'\w','Tatashka Pepedos') 
print(result)
```

# Задание 7
```
import re
result = re.findall(r'\w','Tatashka Pepedos') 
print(result)
```

# Задание 8
```

import re
result = re.findall(r'^\w','Tatashka Pepedos') 
result1 = re.findall(r'\w+$','Tatashka Pepedos')
print(result, result1)
```

# Задание 9 
```

import re
result = re.findall(r'Tatashka|Pepedos','Tatashka Pepedos antyty') 
print(result)
```

# Задание 10
```

import re
result = re.findall(r'Tatashka|Pepedos','Tatashka Pepedos antyty') 
result1 = re.findall(r'\w+$','Antikrizis Merer')
print(result, result1) 
```

# Задание 11
```

```

