# XSD_Converter
Call the XmlDocTransform function with the paths to your XML file and XDT file:

```
# Call the XmlDocTransform function
$xmlPath = "input.xml"
$xdtPath = "transform.xdt"
XmlDocTransform $xmlPath $xdtPath
```

Replace "input.xml" and "transform.xdt" with the actual paths to your XML file and XDT file respectively.

Ensure that the Microsoft.Web.XmlTransform.dll is located in the same directory as the PowerShell script or provide the correct path to it if it's located elsewhere.
