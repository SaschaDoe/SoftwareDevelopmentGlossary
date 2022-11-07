
# Coding Style best practises
This is language independently list of best practises in coding styles.  
Using these tipps improves the code quality of changeability.

## Syntax
<details>
  <summary>Call things by real name</summary>

 **Bad**

```c#
public class Orders
{
    private List<int> _ns;

    public void GetNums(List<int> number)
    {
        _ns = number;
    }
}
```
**Good**

```c#
public class Order
{
    private List<int> _numbers;
    
    public void SetNumbers(List<int> numbers)
    {
        _numbers = numbers;
    }
}
```
</details>
