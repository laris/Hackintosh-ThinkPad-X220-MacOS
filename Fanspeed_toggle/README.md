# Fanspeed Hack - toggle normal max 4600RPM by ThinkVantage Button

https://www.reddit.com/r/hackintosh/comments/6zbwx5/x220_hackintosh_here_is_there_a_fan_controller/

McDonnellTech
If you used our X220 hackintosh guide then I have a solution that should work.
The standard dsdt.aml included with the guide reduces fan speeds in ways that most users prefer. An alternate dsdt.aml that does not implement this speed reduction can be downloaded here.
Just unzip and replace the existing dsdt.aml located on your EFI partition in EFI/CLOVER/ACPI/patched and then restart the computer.
Fan speeds will now run somewhat faster by default and you can use blue ThinkVantage button at the top of the keyboard to toggle between normal and maximum fan speed (about 4600 RPM).
Let me know if this doesn't work correctly for you.
