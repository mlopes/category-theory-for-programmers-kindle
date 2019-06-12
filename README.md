# Kindle / Epub generator for Category Theory for Programmers

This project let's you export the blog posts [Category Theory for Programmers](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/) by Bartosz Milewski to epub/mobi format.

A similar project that exports to pdf can be found here [https://github.com/hmemcpy/milewski-ctfp-pdf/](https://github.com/hmemcpy/milewski-ctfp-pdf/)

The book is available in paper format here [https://www.blurb.com/b/9008339-category-theory-for-programmers](https://www.blurb.com/b/9008339-category-theory-for-programmers)

Related content on Bartosz Milewski's [youtube channel](https://www.youtube.com/playlist?list=PLbgaMIhjbmEnaH_LTkxLI7FMa2HsnawM_)

## Generating the Kindle version

- Download and install [kindlegen](https://www.amazon.com/gp/feature.html?docId=1000765211)
- Execute kindlegen to generate the mobi:

```bash
kindlegen -verbose -o ctpf.mobi book.opf
```

## Epub

I don't own an epub reader, so I haven't attempted to generate an epub file.
Because the sources are in opf format, it's possible to generate an epub file that can be used in other e-readers. If you attempt to do this, please make a pull request with the instructions on how others can generate it themselves.
