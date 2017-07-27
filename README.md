## TWRP device tree for Galaxy Note 7 (China Qualcomm)

Add to `.repo/local_manifests/graceqltechn.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/graceqltechn" name="android_device_samsung_graceqltechn" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/android_kernel_samsung_msm8996/tree/twrp-6.0

