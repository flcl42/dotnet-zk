
Compile with

```powershell
csc Class1.cs .\System\Attribute.cs System\Object.cs System\Primitives.cs .\System\ValueType.cs .\System\Enum.cs /nostdlib+ -out:.\Class1.dll /noconfig /nowarn:1701,1702 /errorreport:prompt /warn:4 /noconfig /unsafe /target:library
```