# Russian-Regions-And-Cities-With-Time-Zone
Российские регионы и города с часовым поясом и координатами в json

Структура/Structure:

```C#
public class region
{
    public List<city> cities { get; set; }
    public string name { get; set; }
}

public class city
{
    public string name { get; set; }
    public int utc { get; set; }
    public string time_zons { get; set; }
    public string coordinates { get; set; }
}
```
