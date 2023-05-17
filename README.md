# Unic
The closed-source C# library for everything coding.

## Installation
### Windows
Head to our releases tab on the GitHub repo and download the "unic-setup.win64.exe" file. Run it and it will guide you through the process of installing Unic.
### Linux
Head to our releases tab on the GitHub repo and download the "unic-setup.deb" file. Run it and it will guide you through the process of installing Unic.
### MacOS
Head to our releases tab on the GitHub repo and download the "unic-setup.mac.app" file. Run it and it will guide you through the process of installing Unic.
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
