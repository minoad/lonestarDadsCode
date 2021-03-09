# Lonestar Dads Coding

## Layout

I am trying to keep the layout pretty simple for the moment.  

* Code: Includes coding examples that are a bit more in depth than what is on the weekly syllabus.  Used primarily for reference and examples.  This will be broken up into specific sections.
* Data: Will contain data for analysis.  Im going to add some fun stuff here.  Maybe some baseball data for us to chunk through.  Anything you guys would like to see here?  Maybe housing data for our local area?
* Math: Covers that math we will need.  Will also cover notations for different segments of math.  I absolutely promise you that this will not make it difficult for anyone.
* Schedule: As expected this will cover the when and the where.
* Setup: A single file on each thing to setup with all the details and troubleshooting we come up with.
* Syllabus: This is a single file per session and will include all of the data covered for that session.  This will change a good deal especially over these initial sessions.
* .gitignore: You will become intimately familiar with this file.  It will include a listing for all items that you do not want included in `git add/commit/push`.
* License: This is generally included in all git repos and covers the legality of how the data contained can be used.  In this case it is the MIT license. The MIT License gives users express permission to reuse code for any purpose, sometimes even if code is part of proprietary software. As long as users include the original copy of the MIT license in their distribution, they can make any changes or modifications to the code to suit their own needs.  Basically this is Open Source (OSS) and anyone can use anything they want as long as the result remains open source.  It is a way to combat people taking others work and then monetizing it.
* markdown.md: Markdown is small language supported by most tech tools.  It allows you to format text inline as you type it.  This file is formatted in such a way.  It is supported by git and most pull requests include Markdown in their description.  It is a tiny language and only really requires a few minutes to get it straight.  Markdown is incredible for coding discussions as it allows you to embed code directly in your document.  Mathematical notation is also supported in markdown.  Some examples below

LaTeX (Currently github does not render LaTeX)

$\sum_{n=1}^{\infty} 2^{-n} = 1$

Shell

```shell
cat test.txt | egrep 'Hel[a-zA-Z]{1,4}'
```

Go

```golang
fmt.PrintLn("Here is a go formatted code segment")
```

Python

```python
[i for i in [1,2,3,4,5]]
```

Image of markdown and resulting document.  The markdown is on the left and resulting parsed document is on the right.
![Markdown](data/images/markdown.png)
