# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```

You can use a namespace to organize code elements and to create globally unique types.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```

A structure is a value type so it is stored on the stack, but a class is a reference type and is stored on the heap.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```

void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```

public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```

it designates the class of the object
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```

An abstract class allows you to create functionality that subclasses can implement or override.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```

 It is used when a method's basic functionality is the same but sometimes more functionality is needed in the derived class

```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```

public private internal and protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```

the code in the same class or struct
```