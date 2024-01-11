### Keypack

Keypack is a unopiniated dynamic key-value JSON alternative.

- It has **human readable** format.
- Supports **custom types**.

```zig
.{ object=.{} }
.{ nullable=.nil }
.{ string="Hello, world." }
.{ enabled=true, disabled=false }
.{ number=3735928559, typed_number=.i32:3735928559 }
.{ float=3.14, typed_float=.f32:3.14 }
.{ array=.[], typed_array=.i32[] }
.{ enumerated_value=.[.first, .second, .third] }
```

#### Implementations

- [🦀 **Rust**](/) - Still in progress...

#### License

> [MIT](/LICENSE) &copy; Itallo Gabriel