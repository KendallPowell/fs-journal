# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It's used to organize code into groups to prevent names from overlapping each other when you use multiple.. repositories (projects)?
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Default accessibility of variables and methods.
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
class
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It's hiding certain details and only showing information the user might "need"
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It's used to override the base class member based on requirement
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public Private Protected Internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
anything within the same class
```