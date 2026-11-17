<p><img src="tesra-mark.svg" width="64" height="64" alt=""></p>

# Tesra beta

**A spreadsheet that remembers every revision.** Instead of saving "Quote final v2.xlsx", you
commit each version with a short comment. Later you can see who changed what, compare any two
versions side by side, go back, or try a variant, all in one file. It opens and saves ordinary
Excel files.

This is an early beta for invited testers. Some things will be rough.

## Download (Windows 10 or 11)

Get the installer (**Tesra_<version>_x64-setup.exe**) and the testers' guide (PDF) from the
[latest release](../../releases/latest).

- A new beta installs over the old one; your workbooks carry over.
- It installs for your user only; no administrator rights are needed.
- The beta is not yet signed with a publisher certificate, so Windows may say **"Windows protected
  your PC"**. Click **More info**, then **Run anyway**.
- Excel stays your default for .xlsx files; Tesra only appears under **Open with**.
- To check the download, compare its SHA-256 with `SHA256.txt` in the release
  (PowerShell: `Get-FileHash .\Tesra_<version>_x64-setup.exe`).

## Your data

Your workbooks stay on your computer. Nothing is uploaded and the app does not report usage. The
optional AI assistant only sees the cells you choose to share.

## Feedback

In the app, click **Feedback** on the left rail. You see exactly what will be sent and can edit it,
then send it to **blw@saptasati.com**.

## Licences

Tesra is closed-source software, free to use during the beta. It is built with open-source
components; their licence texts are in `THIRD_PARTY_LICENSES.txt` in the release and are installed
next to the app.
