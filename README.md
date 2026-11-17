<p align="center">
  <img src="assets/logo-dark-bg.png" alt="_You." width="360">
</p>

<p align="center"><b>Your space. Just yours.</b></p>

**_You._** is a personal space for your thoughts, in a window on your computer. A daily check-in on how
you are, a free space for notes and ideas, and your own profile. It's quiet, it's private, and it keeps
everything as plain text files that only you can see.

## Download

Go to **[Releases](../../releases/latest)** and download **`you-setup-x.y.z.exe`** (Windows 10 or 11).
Double-click it and follow the steps. No account and no internet needed to use it.

### Windows shows a warning? That's expected

You is new and its installer isn't code-signed yet (that costs money, and it's on the list). So
Windows and your browser may be careful with it. This doesn't mean anything is wrong. Here's how to
go ahead:

**1. Your browser says it's "not commonly downloaded" or blocks it**
- **Edge:** open the downloads list, click the **`...`** next to the file, choose **Keep**, then
  **Show more** and **Keep anyway**.
- **Chrome:** click the **`^`** next to the file, choose **Keep**.

**2. Windows says "Windows protected your PC" (SmartScreen)**
1. Click **More info**.
2. Click **Run anyway**.

**3. The file won't open at all (it says it's blocked)**
1. Right-click the downloaded `.exe` and choose **Properties**.
2. At the bottom of the General tab, tick **Unblock**, then **OK**.
3. Open it again.

**4. Windows says "Smart App Control blocked this app"**

Smart App Control is stricter and doesn't offer *Run anyway*. You can use the
**`you-windows.zip`** download instead: unzip it and open `you\you.exe`. If that is blocked too, the
only way is to turn Smart App Control off (**Windows Security > App & browser control > Smart App
Control settings**). It can't be turned back on without resetting Windows, so only do this if you're
comfortable with that.

### Want to be sure it's the real file?

Each release lists a fingerprint (SHA-256) next to the installer. To check yours, open
**PowerShell** in the folder with the download and run:

```
Get-FileHash .\you-setup-1.0.0.exe -Algorithm SHA256
```

The long code it prints must match the one shown for that file on the Releases page. If it doesn't,
don't open it.

## What you get

- **Journal**: a short daily check-in on your spirit, mind, emotions and body, with room to say more
- **Braindump**: pages and folders for anything on your mind
- **Stats**: how you've been, in plain numbers
- **Profile**: your name, a look you like, an avatar you design, and an optional password

## Your privacy

- Everything you write stays on your computer, in a folder called `you` in your user folder.
- Nothing is uploaded and there's nothing to sign in to.
- Once a day the app asks this page whether a newer version is out. Nothing about you is sent.
  You can turn that off in your Profile.

## Updates

When a newer version is ready, You tells you and shows what's new. Your writing is never touched
by an update or by uninstalling.
