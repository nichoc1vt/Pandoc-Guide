# Converting Word Files to Markdown Using Pandoc

Converting documents using Pandoc is a simple process, but it requires
paying close attention to a few key details. The instructions below
provide a guide for converting Word files to Markdown files via Pandoc.

## Steps

1.  Remove any title pages or tables of contents from the Word document
    that is to be converted; these elements will not appear properly in
    a Markdown document.

2.  Pandoc accepts commands through the computer's "Terminal" program.
    In Windows, this program is called "Command Prompt," while in Mac,
    it is simply called "Terminal."

3.  Before converting any file via Pandoc, you must specify the folder
    in which the file is located. This is achieved by typing "cd" in the
    Terminal, followed by the location of the folder. The location can
    be pasted by dragging the folder itself into the command line. Press
    Enter to specify the folder location.

4.  First, type "pandoc" into the command line, following by "-s" and
    the name of the Word file (e.g. "file.docx").

5.  Next, type "-t markdown" and, if your Word file contains images,
    "\--extract-media=images" into the command line.

6.  Finally, type "-o" followed by the intended Markdown file name (e.g.
    "file.md").

7.  Press Enter.
<figure>
<img src=images\media\image4.png>
<figcaption><b>Sample code for converting from Word to Markdown via Pandoc</b></figcaption>
</figure>
{% include footer.md %}