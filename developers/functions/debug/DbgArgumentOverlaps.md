# DbgArgumentOverlaps

This function checks whether a certain argument range already exist.

```c++
bool DbgArgumentOverlaps(duint start, duint end);
```

## Parameters

`start` first address of the argument range.

`end` last address of the argument range.

## Return Value

Returns TRUE if the given range overlaps an existing argument range or FALSE otherwise

## Example

```c++
if(DbgArgumentOverlaps(0x00401000, 0x00401013))
  GuiAddLogMessage("Argument range overlaps an existing one\r\n");
else
  GuiAddLogMessage("Argument range is not overlaping\r\n");
```

## Related functions

- DbgArgumentAdd
- DbgArgumentDel
- DbgArgumentGet
