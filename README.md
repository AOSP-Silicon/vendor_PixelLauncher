# ![Pixel Launcher Mod v7.1 (Khonsu)](https://telegra.ph/file/5d395b129080e060bdfb4.jpg)<br/>
**Support only for Android 12L/12.1**<br/>
**Current version: v7.3**<br/>
**Variant: Khonsu**<br/>

**What is Khonsu variant?**<br/>
-&nbsp;It consists all the mod features mentioned in [documentation](https://telegra.ph/Pixel-Launcher-MOD-Features-Version-Details-Instructions--Troubleshooting-02-07) with Seamless Double Tap To Sleep. On this variant double tap to sleep feature will work as soon as you enable it from settings.

However, This Seamless Dt2s feature doesn't work on every rom & on some roms when you double tap then laucher crashes. Why it crashed for you? Because some roms have their own signature key and this variant is using aosp signature & dt2s require same signature in rom. That's the reason it works perfectly in unofficial EvoX & EvoX Official Unsigned Build but it crashes in EvoX Signed Build.<br/>

Add these line in device.mk or romname_devicename.mk:
>**_$(call inherit-product, vendor/PixelLauncher/PixelLauncher.mk)_**
<br/>

**Credits:**<br/>
[Team Files™](https://t.me/modulesrepo)<br/>
[Magisk module](https://t.me/modulesrepo/3166)<br/>
