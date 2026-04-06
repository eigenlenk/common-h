# Common-H
Includes a few common C headers in my projects. Basic macros like min, max and clamp; annotations for optional and discardable types as well as a macro for counting the number of macro arguments. Templated vec2 type is for declaring custom `vec2<T>` types.

```c
#include "vec2.h"
DECLARE_VEC2_T(int32_t, vec2i)
DECLARE_VEC2_T(float, vec2f)
```
You now have types `vec2i` and `vec2f`, and functions like `vec2f_make(5.1f, 0.3f)` and `vec2i_length(v)`.
