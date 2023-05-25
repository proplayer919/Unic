# Unic
The C# library for everything coding.

## Installation
### Just use
```cs
using Unic;
```
## Using Unic
### Message boxes
You can show your user a message mox with
```cs
using Unic.Interaction;

class YourClass
{
  public static void Main()
  {
    InteractiveMessages.ShowMessageBox("title", "message");
  }
}
```
### Windows
You can open a window with:
```cs
using Unic.Xero;

class YourClass
{
  public static void Main()
  {
    XeroRenderer.OpenWindow("Test Window", 500, 500);
  }
}
```
