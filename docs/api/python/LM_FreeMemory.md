# LM_FreeMemory

```python
def LM_FreeMemory(alloc : int, size : int)
```

# Description

Frees `size` bytes of allocated memory in the calling process.

# Parameters

- alloc: virtual address of the allocated memory.
- size: the size of the region to deallocate.

# Return Value

On success, it returns `true`. On failure, it returns `false`.

