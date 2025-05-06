# How-to-Configure-.NET-MAUI-OTP-Input-Control-for-Alphanumeric-Values
This repository contains a sample explaining how to configure .NET MAUI OTP Input Control for alphanumeric values.

### Alphanumeric values support in .NET MAUI OtpInput

To accept alphanumeric input, set the [Type]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Type) property to `Text`.

The following code example illustrate how to Configure Alphanumeric values in SfOtpInput.

### XAML
```
<syncfusion:SfOtpInput Type="Text" Value="e3c7"/>

```
### C#

```
var otpInput = new SfOtpInput
{
    Type = OtpInputType.Text,
    Value = "e3c7"
};

```