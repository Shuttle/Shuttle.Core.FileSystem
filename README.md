# Shuttle.Core.FileSystem

```
PM> Install-Package Shuttle.Core.FileSystem
```

Provides abstractions/interfaces for relevant static types in the `System.IO` namespace.

The interfaces have the exact signatures as found in the `System.IO` namespace.  There is also always a default implementation that delegates to to the `System.IO` type.

|Interface|Default implementation|
|---|---|
|`IDirectory`|`DefaultDirectory`|
|`IFile`|`DefaultFile`|