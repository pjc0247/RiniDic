RiniDictionary
====

No more `KeyNotFoundException`.<br>
The only dictionary which knows what you wants.

```cs

RiniDictionary rdic = new RiniDictionary();

rdic["rini"] = "genius";
rdic["jwvg"] = "genius";

Console.WriteLine(rdic["roni"]); // genius
```

```cs
rdic["han minsoo"] = "genius";
rdic["park min-soo"] = "real genius";

// a dash(`-`) makes him more geniusrousous
Console.WriteLine(rdic["nam min-soo"]); // real genius. 
```
