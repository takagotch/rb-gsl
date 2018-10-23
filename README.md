### rb-gsl
---
https://github.com/SciRuby/rb-gsl


```

```

```ruby
require 'gsl'
nm = NMatrix.new([5], [1,2,3,4,5], dtype: :float64)
nm.to_gslv

require 'gsl'
nm = NMatrix.new([3, 3], [2]*9, dtype: :int32)
nm.to_gslm

g = GSL::Vector.alloc(1,2,3,4)
g.to_nm
```

```

```


