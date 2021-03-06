---
title: Policy CSP - Bitlocker
description: Policy CSP - Bitlocker
ms.author: maricia
ms.topic: article
ms.prod: w10
ms.technology: windows
author: nickbrower
ms.date: 03/12/2018
---

# Policy CSP - Bitlocker



<hr/>

<!--Policies-->
## Bitlocker policies  

<dl>
  <dd>
    <a href="#bitlocker-encryptionmethod">Bitlocker/EncryptionMethod</a>
  </dd>
</dl>


<hr/>

<!--Policy-->
<a href="" id="bitlocker-encryptionmethod"></a>**Bitlocker/EncryptionMethod**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Specifies the BitLocker Drive Encryption method and cipher strength.

> [!NOTE]
> XTS-AES 128-bit and XTS-AES 256-bit values are only supported on Windows 10 for desktop.

You can find the following policies in BitLocker CSP:
<dl>
  <dd>
    <a href="./bitlocker-csp.md#encryptionmethodbydrivetype" id="encryptionmethodbydrivetype">BitLocker/EncryptionMethodByDriveType</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#fixeddrivesrecoveryoptions" id="fixeddrivesrecoveryoptions">BitLocker/FixedDrivesRecoveryOptions</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#fixeddrivesrequireencryption" id="fixeddrivesrequireencryption">BitLocker/FixedDrivesRequireEncryption</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#removabledrivesrequireencryption" id="removabledrivesrequireencryption">BitLocker/RemovableDrivesRequireEncryption</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#systemdrivesminimumpinlength" id="systemdrivesminimumpinlength">BitLocker/SystemDrivesMinimumPINLength</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#systemdrivesrecoverymessage" id="systemdrivesrecoverymessage">BitLocker/SystemDrivesRecoveryMessage</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#systemdrivesrecoveryoptions" id="systemdrivesrecoveryoptions">BitLocker/SystemDrivesRecoveryOptions</a>
  </dd>
  <dd>
    <a href="./bitlocker-csp.md#systemdrivesrequirestartupauthentication" id="systemdrivesrequirestartupauthentication">BitLocker/SystemDrivesRequireStartupAuthentication</a>
  </dd>
</dl>

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   3 - AES-CBC 128-bit
-   4 - AES-CBC 256-bit
-   6 - XTS-AES 128-bit (Desktop only)
-   7 - XTS-AES 256-bit (Desktop only)

<!--/SupportedValues-->
<!--/Policy-->
<hr/>

Footnote:

-   1 - Added in Windows 10, version 1607.
-   2 - Added in Windows 10, version 1703.
-   3 - Added in Windows 10, version 1709.
-   4 - Added in Windows 10, version 1803.

<!--/Policies-->

