### doublex
---
https://pypi.org/project/doublex/

```py
import unittest
from doublex import Spy, assert_that, called

class SpyUseExample(unittest.TestCase):
  def test_spy_example(self):
    spy = Spy(SomeCollaboratorClass)
    cut = YourClassunderTest(spy)
    
    cut.a_method_that_call_the_collaborator()
    
    assert_that(spy.some_method, called())
```

```
```

```
```


