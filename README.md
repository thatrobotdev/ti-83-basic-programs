# ti-basic-83-programs

## About

This is a collection of programs that I've written throughout high school math courses to solve problems faster on my TI-84 Plus CE.

These are written in [TI-BASIC_83](https://en.wikipedia.org/wiki/TI-BASIC_83), a programming language for TI-83/84/+/SE/CSE/CE calculators. These programs are uncompiled, as .txt files. You will need to convert them to .8xp files for them to work on your calculator. For more information on how to download these onto your calculator, see [Downloading](##Downloading)

If you would like to add some helpful programs, or improve these, [please create a pull request]([https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request))!

| Program Name | Source Code | Compiled | Description | Equation | Configuration |
| --- | --- | --- | --- | --- | --- |
| QUADFORM     | [QUADFORM.txt](QUADFORM/QUADFORM.txt) | [QUADFORM.8xp](QUADFORM/QUADFORM.8xp) | Finds quadratic formula for both possibilities, and rounds to answer to 2 decimal points. | b±√((b²-4ac)÷(2a)) | `mode → NUMBER TYPE → a+bi`

## Downloading

### Requirements

You need

* A Windows/Mac Computer ([For full system requirements, see TI's official page](https://education.ti.com/en/products/computer-software/ti-connect-sw#lightbox=ti-connect-ce-get-the-right-version))
* A TI-83/84/+/SE/CSE/CE calculator. ([For full system requirements, see TI's official page](https://education.ti.com/en/products/computer-software/ti-connect-sw#lightbox=ti-connect-ce-get-the-right-version))
* [TI Connect™ Software](https://education.ti.com/en/products/computer-software/ti-connect-sw)
* A USB 2.0 A to Mini B cable.

### How to download a program onto your calculator

1. Connect your calculator to your computer with the cable.
2. Open the TI Connect™ Software.
3. Click the 3 blocks icon on the left bar.

---

#### Compile the program yourself

1. Click `New Program`
2. Copy the source code (`.txt file`) of the program that you want to download and paste it into the TI Connect™ Software.

#### Use the pre-compiled program.

1. Download the `.8xp` file of the program that you want to put on your calculator.
2. Click `Open Program`
3. Navigate to where you stored the downloaded `.8xp` file.

---

4. On the top toolbar, click the icon of a calculator with an arrow.
5. Change `NAME ON CALCULATOR` to desired name.
6. Change `LOCATION` to RAM or Archive, depending on where you want to save the program. [Which should I choose?](####Should-I-download-to-RAM-or-Archive?)
7. Ensure you calculator is selected.
8. Click `SEND`

## FAQ

### Should I download to RAM or Archive?

[RAM, or Random-access memory](https://en.wikipedia.org/wiki/Random-access_memory), is volatile memory on your calculator, which means that if your calculator crashes or you change your calculator battery, your programs on the calculator will be deleted.

Your calculator archive, or [ROM (Read-Only Memory)](https://en.wikipedia.org/wiki/Read-only_memory) is much more stable, and there is more storage in this part of the calculator than RAM, meaning that you can store more programs. However, as the name suggests, you cannot edit programs in this part of the calculator.

**You should download your calculator programs to the archive, rather than the RAM.**

Later, if you want to unarchive a program, you can do

`2nd → mem(+) → 6 → prgm → (the name of the archived program) → enter`

# [License](LICENSE)

This repository is licensed under the Unlicense, which means that these programs are released into the [public domain](https://en.wikipedia.org/wiki/Public_domain).