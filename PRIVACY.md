# Coffer privacy policy

*Effective 28 October 2026. Coffer is made by Sleeping Shield Studio.*

## In short

Coffer keeps your files on your own PC. It has no accounts, no ads, no analytics and no tracking, and it never sends
your files, their names or anything about your vault to anyone — including us.

## What Coffer stores, and where

- **Your vault**: the files you add, encrypted, together with their folders, categories, tags and descriptions.
- **Your settings**: things like the theme, the design and the animations.
- **Watched folders**, if you use them: which folders on your PC Coffer watches, and which files in them it has
  already added. This is kept inside the vault, encrypted, like everything else in it.

Both stay on your PC: in the Microsoft Store version in the `Coffer` folder in your user folder
(`C:\Users\<you>\Coffer`), in the version from GitHub in `%LOCALAPPDATA%\Coffer`, and on Linux in
`~/.local/share/Coffer`. If you make a backup, it goes to the
folder you pick.

Features that look at your files — finding duplicates, sorting by similarity, reading text in images, recognising
tags and categories, describing documents — all run on your PC. Nothing is uploaded for them. Three of them use
machine learning ("AI"), with models that come with Coffer: **Sort by Similar** (a small image model), **reading
watermarks** (Tesseract's text-recognition model) and **recognising tags and categories** (which learns from the tags
you gave, on your PC). They only sort or suggest — they never change your files or tags by themselves — and your files
are never sent anywhere or used to train anything outside your PC.

When you open a file in another program, Coffer puts a temporary unencrypted copy in a private folder on your PC so
that program can read it, and wipes it again when it's no longer needed (at the latest when Coffer closes).

## Deleting your data

- **Removing a file** moves it to *Recently removed*, still encrypted, for as long as you chose in Settings → Backup.
  After that, or when you use *Delete for good*, its encrypted copy, its thumbnail and the details Coffer read from it
  are deleted, and its key is removed, so it can't be read again.
- **Backups** drop removed files the next time they run. *Settings → Backup → Remove…* can also delete a backup
  completely.
- **Originals**: when you let Coffer delete the original files you added, it first checks its own copy, then
  overwrites each original before deleting it. (On SSDs, old copies of overwritten data can remain on the drive.)
- **Uninstalling Coffer keeps your vault**, so your files aren't lost by accident. To remove everything, delete the
  folders named above (and any backups you made).

## When Coffer goes online

- **Microsoft Store version**: never. The Microsoft Store takes care of updates.
- **Version from GitHub**: when it starts, it asks GitHub whether a newer version exists (you can turn this off in
  Settings → General), and downloads the installer from GitHub if you choose to update. Only the request itself is
  sent: GitHub sees your IP address and Coffer's version number, as with any web request. Nothing about your vault is
  sent.

## Bug reports and suggestions

**Report a bug or issue** and **Send a suggestion** open a form on Coffer's GitHub page in your web browser, with your
Coffer version filled in. A bug report can also be filled in with details about your PC and Coffer if you choose to:
the Windows or Linux version, the processor, graphics card and memory, the screens, roughly how many files the vault holds and
how big it is, the settings you changed, and errors Coffer noticed since it started — never file, folder, category or
tag names, keys or paths. You see the exact text before the form opens, can leave it out, and can still change it in
the form. Nothing is sent unless you submit the form yourself. What you write there is public and
handled by GitHub under [GitHub's privacy statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## The Microsoft Store and Windows

If you install Coffer from the Microsoft Store, Microsoft handles the download, updates and any crash or usage data
Windows collects, under the [Microsoft Privacy Statement](https://privacy.microsoft.com/privacystatement). Sleeping
Shield Studio may see the summary statistics Microsoft provides to app publishers (such as number of installs), which
don't identify you.

## Children

Coffer doesn't collect personal information from anyone, children included.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about this policy: open an issue at <https://github.com/ItIsMrDanish/Coffer/issues>.
