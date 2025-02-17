# RecyclableMemoryStreamManager.Events.MemoryStreamCreated method

Logged when a stream object is created.

```csharp
public void MemoryStreamCreated(Guid guid, string tag, long requestedSize, long actualSize)
```

| parameter | description |
| --- | --- |
| guid | A unique ID for this stream. |
| tag | A temporary ID for this stream, usually indicates current usage. |
| requestedSize | Requested size of the stream. |
| actualSize | Actual size given to the stream from the pool. |

## See Also

* class [Events](../RecyclableMemoryStreamManager.Events.md)
* namespace [Microsoft.IO](../../Microsoft.IO.RecyclableMemoryStream.md)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.IO.RecyclableMemoryStream.dll -->
