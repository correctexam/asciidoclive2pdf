# AsciiDocLive 2 correctExam PDF

If you enjoy using [AsciiDocLive](https://asciidoclive.com/) to build your exam. Just use it, next download your exam as a *html*. Upload the resulting html file on this [form](https://correctexam.github.io/asciidoclive2pdf/). 

Next, you can ask to print 2 pdf using Ctrl + P or Cmd +P.

In your asciidoc, you can directly include svg like the following to create your box for the answer. The width of a page is 600px. The height is max at 800px. 

```txt
pass:[<div align="center"><svg height="200" width="600"><rect style="fill:rgb(255,255,255);stroke-width:1;stroke:rgb(0,0,0)" height="200" width="600"></rect></svg></div>]
```

You can use task to create your QCM:

```txt
* [ ] good
* [ ] bad
* [ ] ...
```

And you can use all the [great feature of AsciiDocLive](https://asciidoclive.com/)

