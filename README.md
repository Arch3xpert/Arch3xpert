
### About Me

```python
from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
    name: str = 'Manish Ranjan'
    location: str = 'India , Ranchi'


@dataclass(frozen=True)
class Skills:
    languages: Sequence[str] = 'python', 'shell', 'JavaScript', 'telethon', 'html', 'java', 'css', 'C++', 'c#', 'Visual Basic', 'ruby', 'many more'
    operation_systems: Sequence[str] = 'Linux', 'Windows', 'dragon focal'
   

@dataclass(frozen=True)
class Social:
    github: str = 'https://www.github.com/Arch3xpert'
    codewars: str = 'https://www.codewars.com/users/Arch3xpert'
    telegram: str = 'https://t.me/Arch3xpert'
    email: str = 'contact@sbexam.com' 
```



