# PROJECT-NAND2TETRIS-PART-1-project-06
project-06

# **Project 6: The Assembler**

## **Overview**

Project 6 is the final project in the *Nand to Tetris* course. The goal of this project is to build an **assembler** that translates Hack assembly language (`.asm`) programs into machine language (`.hack`) binary code. This project allows students to understand how high-level instructions are converted into low-level binary commands that a computer can execute.

---

## **Features**

* Translates **A-instructions** (`@value`) into 16-bit binary.
* Translates **C-instructions** (`dest=comp;jump`) into 16-bit binary using the Hack specification.
* Handles **labels** `(LABEL)` and **symbol resolution** automatically.
* Supports **programming option** (automatic translation using the assembler) and **manual option** (hand translation for selected programs).
* Generates `.hack` files compatible with the Hack CPU emulator.

---

## **Files Included**

### Programming Option

* `Add.asm` → `Add.hack`
* `Max.asm` → `Max.hack`
* `Rect.asm` → `Rect.hack`
* `Pong.asm` → `Pong.hack`
* `prog.txt` (indicator file for programming option)

### Manual Option

* `MaxL.asm` → `MaxL.hack`
* `Rect.asm` → `Rect_manual.hack`
* `hand.txt` (indicator file for manual option)

> **Note:** `Rect_manual.hack` is renamed to avoid conflict with the programming version.

---

## **How to Use**

1. **Programming Option:**

   * Run the assembler program and load the `.asm` files.
   * The assembler will automatically generate the `.hack` binary files.
   * Use the Hack CPU emulator to test the generated `.hack` programs.

2. **Manual Option:**

   * Translate assembly code into 16-bit binary manually.
   * Save the binary as `.hack` files.
   * Test using the Hack CPU emulator.

---

## **Submission Instructions**

1. Place all `.hack` files and indicator text files (`prog.txt` or `hand.txt`) in a folder.
2. Compress the folder into `project6.zip`.
3. Upload the zip file to the course submission portal before **Dec 22, 11:59 PM PST**.

---

## **References**

* [Nand2Tetris Official Website](https://www.nand2tetris.org/)
* *The Elements of Computing Systems* – Nisan & Schocken, 2005
