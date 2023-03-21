## Задание 1
```

import re 
result = re.search(r'Alabama','Sweet home Alabama')
print(result.group(0))
```

# Задание 2
```
import re 
result = re.sub(r'TYTY','HA$','SGO TO HA$')
print(result)
