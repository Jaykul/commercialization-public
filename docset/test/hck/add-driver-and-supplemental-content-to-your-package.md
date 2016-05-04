---
author: joshbax-msft
title: Add driver and supplemental content to your package
description: Add driver and supplemental content to your package
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 44772187-6a8d-4208-85f1-9b6adbf94a01
---

# Add driver and supplemental content to your package


## Adding a driver package


For device submissions, the driver(s) being used must be added. The purpose of adding the driver accomplishes two objectives, if the submission passes:

-   The driver(s) called the Driver Package are catalog-signed and returned. These are now the **certified** set of drivers.

-   The driver package can be posted on Windows Update, for broad distribution (as applicable).

Some device submissions (for example, devices which are certified for Server systems) also require the debug symbols to be attached.

These requirements are explicitly called out in documentation. Unless specifically stated, it is not necessary to submit driver symbols.

**To add a driver**

1.  On the **Package** tab, click **Add Driver Folder**.

2.  Select folder where driver package is located.

3.  Click **OK**.

4.  When **Driver Properties** dialog appears, select appropriate **Products** and **Locales** for your package.

5.  Click **OK** to close **Driver Properties** dialog.

**To add symbols**

1.  Right-click selected driver.

2.  Select **Add Symbols**.

## Adding supplemental content


Depending on the Device or System to be certified, additional information may be required.   For example, devices being certified for SERVER systems must include the Static Driver Verifier (SDV) logs.

The requirements for these are covered in the necessary documentation.  Unless explicitly called out, it is not necessary to add supplemental content.

**To add supplemental content**

1.  On the **Package** tab, click **Add Supplemental Folder**.

2.  Select folder where supplemental content is located.

3.  Click **OK**.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20Add%20driver%20and%20supplemental%20content%20to%20your%20package%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



