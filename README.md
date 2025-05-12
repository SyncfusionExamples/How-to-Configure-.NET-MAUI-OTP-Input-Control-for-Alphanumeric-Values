# How-to-Configure-.NET-MAUI-OTP-Input-Control-for-Alphanumeric-Values
This repository contains a comprehensive sample explaining how to configure the .NET MAUI OTP Input Control specifically for accepting alphanumeric values. This configuration is essential for scenarios where the input needs to include a mix of letters and numbers, enhancing the versatility of your application's OTP field.

### Alphanumeric values support in .NET MAUI OtpInput

In order to accept alphanumeric input effectively, you must set the [Type]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Type) property of the OTP input to `Text.` This setting enables the control to handle not just numbers, but also letters, making it highly suitable for application data that might require mixed input.

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