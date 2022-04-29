# Glossary

## ASCII

## Character encoding

(e.g., in **ASCII** the byte `01000001` 
represents the capital letter "A")

## CSV file

Short for "Comma-Separated Values". A type of text file used to store **tabular data**,
in which each row is separated by a new line, and each column by a comma. E.g., 

```
author,title
Tabari,JamicBayan
Tabari,Tarikh
```

## Extension

See **File extension**

## File

## File extension

Suffix to a file name, usually separated from the file name by a dot/full stop
(e.g., index.**html**, 0255Jahiz.**yml**, README.**md**).
The extension is used to indicate how data is stored in the file
(e.g., the extension "**csv**" indicates that the data in the file
is tabular, and columns are separated by a comma).

## HTR

Short for Hand-Written Text recognition: basically, **OCR** for manuscripts.

## Islamicate

## JSON

## KITAB corpus

The corpus of Arabic texts the KITAB project works on. 
The KITAB corpus is a subset of the **OpenITI** corpus,
containing only those OpenITI texts that are in Arabic
and whose authors died before the year 1000 AH.

## Machine-actionable

Data is machine-actionable if it is structured in a consistent way so that computers 
can easily be programmed to parse its structure and process it. We prefer this term over
its equivalent "machine-readable", because the latter suggests that it is enough
for a computer to be able to open and read the data. 
Typically machine-actionable data formats are **XML**, **JSON**, **TSV**, **CSV**, **YML**: 
they use a fixed syntax that helps the computer parse the data. 
Image files are examples of data
that is "readable" by a computer (the computer can open it and display it on your
screen) but not "actionable": the computer cannot easily extract words in the image.
**TXT files** are also not machine-actionable: a computer can easily open and read 
the data in a TXT file, but they contain no inherent internal structure. 

## Machine-readable

See **Machine-actionable**.

## Markdown

A light-weight **markup language** designed to make it easy to read and format 
text in **plain text** files. For example, asterisks are used to format text in
italics (e.g., `*this is italicized*`) or bold (`**this is bold**`). 
See https://en.wikipedia.org/wiki/Markdown

## mARkdown

A version of **Markdown** that was developed by Maxim Romanov to facilitate
structural and semantic **tagging** of the OpenITI corpus. For a full description, 
see https://alraqmiyyat.github.io/mARkdown/

## Markup language

## Metadata

## Milestone

All texts in the OpenITI corpus contain a **tag** after every 300th **token**. 
These tags are called "milestones", and they take the form of the letters "ms" 
followed by a sequential number: `ms001`, `ms002`, ...
These milestones can be used to cut up the text into fixed-length chunks.

## OCR

Short for "Optical Character Recognition", the process that converts an image of a text
into **plain text** text that can be searched, selected, copied, etc.

## OpenIslamicate Text Initiative: see OpenITI

## OpenITI

OpenIslamicate Text Initiative. 

## OpenITI mARkdown

See mARkdown.

## Open-source

## passim

## Plain text

Plain text is data that consists only of characters 
(letters, punctuation, numbers, spaces, ...). 
Plain text is usually created, read and edited using 
a **text editor**.
All OpenITI text and metadata files are stored as plain text.

## Tabular data

Data in table format, consisting of rows and columns.
Tabular data can be stored in **CSV**, **TSV** 
XLSX (MS Excel format), ... files.

## Tag

## Tagging

## Text reuse

## Token

## Text editor

A computer program that edits **plain text**. 
Examples are Notepad (Windows), TextEdit (Mac), and Nano (Linux).
A text editor (in contrast to a word processor like MS Word)
does not allow you to format the text (although many text editors
have options to display plain text with rule-based highlighting).
Our text editor of choice for OpenITI texts is 
[EditPad Pro](https://www.editpadpro.com/), because it handles large
files well and can deal with right-to-left languages. 
EditPad Pro only works on Windows; for Mac and Linux,
[Kate](https://kate-editor.org/) editor is a good alternative.


## Text file

A file containing only **plain text**.
Files are stored as **bytes**; in text files, each (group of)
bytes represents a character as defined in a specific 
**character encoding**.

## TSV file

Short for "Tab-Separated Values". A type of text file used to store **tabular data**,
in which each row is separated by a new line, and each column by a tab character. E.g., 

```
author  title
Tabari  JamicBayan
Tabari  Tarikh
```

## TXT file
A **text file** with the **file extension** ".txt".

## Unicode

## UTF-8

## XML file

## YML file

