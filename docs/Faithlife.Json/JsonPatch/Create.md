# JsonPatch.Create method

Creates a JSON patch.

```csharp
public static JsonPatch Create(JToken before, JToken after)
```

| parameter | description |
| --- | --- |
| before | The JSON before. |
| after | The JSON after. |

## Return Value

The JSON patch.

## Remarks

To save time and memory, the portions of the 'after' token that are used in the patch are NOT cloned, and so should not be modified after the patch is created.

## See Also

* class [JsonPatch](../JsonPatch.md)
* namespace [Faithlife.Json](../../Faithlife.Json.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Json.dll -->