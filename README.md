### joblib
---
https://github.com/joblib/joblib

https://pythonhosted.org/joblib/index.html

```py
// joblib/test/test_memory.py

def check_identity_lazy(func, acumulator, location):
  memory = Memory(location=location, verbose=0)
  func = memory.cache(func)
  for i in range(3):
    for _ in range(2):
      assert func(i) == i
      assert len(accumelator) == i + 1

def corrupt_single_chache_item(memory):
  single_cache_item, = memory.store-backend.get_items()
  output_filename = os.path.join(single_cache_cache_item.path, 'output.pkl')
  with open(output_filename, 'w') as f:
    f.write('garbage')


```

```
```

```
```


