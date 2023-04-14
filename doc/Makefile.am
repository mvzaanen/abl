info_TEXINFOS = abl_refguide.texi
TEXINFO_TEX = ../doc/texinfo.tex

SUFFIXES = .html
html_docs = abl_refguide.html

EXTRA_DIST = ovis_exectime.eps ovis_exectime_merge.eps treebank.eps editd.eps

.texi.html:
	$(MAKEINFO) --html $<

.PHONY: html
html: abl_refguide.texi $(html_docs)))
