# Keepsake for Windows: downloads

This repository holds the public Windows downloads of **Keepsake**. It does not hold any source code.

Get Keepsake from the Keepsake page on [analyticalants.com](https://analyticalants.com), or from the latest release here.

## Before you open it

1. Download `Keepsake-<version>-windows-x64.zip` from the latest release.
2. Optionally, check that the download is complete and unchanged. In PowerShell, run:

   ```powershell
   Get-FileHash .\Keepsake-0.1.0-windows-x64.zip -Algorithm SHA256
   ```

   The result must match the line for that file in the release's `SHA256SUMS.txt`, and the SHA-256 shown on the download page.
3. Right-click the ZIP, choose **Extract All…**, then **Extract**.
4. Double-click **Keepsake**.
5. This early version is not yet signed, so Windows may show **"Windows protected your PC"** the first time. Click **More info**, then **Run anyway**.

Keepsake installs itself for your Windows user and keeps your memories on your own computer.
