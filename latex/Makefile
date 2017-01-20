all:
	pdflatex --shell-escape report.tex
	bibtex report
	pdflatex --shell-escape report.tex
	pdflatex --shell-escape report.tex

clean:
	find . -type l -delete
	rm -f *.log
	rm -rf _minted-*-report
	rm -f *-report.aux
	rm -f *-report.bbl
	rm -f *-report.blg
	rm -f *-report-blx.bib
	rm -f *-report.log
	rm -f *-report.out
	rm -f *-report.pdf
	rm -f *-report.run.xml
	rm -f *-report.toc


