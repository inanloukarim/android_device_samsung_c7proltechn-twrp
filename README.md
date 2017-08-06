## TWRP device tree for Galaxy c7proltechn (China Qualcomm)

Add to `.repo/local_manifests/c7proltechn.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/c7proltechn" name="android_device_samsung_c7proltechn" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/inanloukarim/kernel_samsung_msm8953.git

