filename=论政治中的道德

main.pdf:main.tex ref.bib /home/bibaijin/share/format/xetex.tex
	xelatex main.tex
	biber -l zh__pinyin main
	#xelatex main.tex
	xelatex main.tex

rename:
	mv main.pdf "$(filename).pdf"

view:
	evince main.pdf &

clean:
	rm -f *.aux *.bbl *.blg *.idx *.ilg *.ind *.out *.toc *.nav *.snm main.pdf *.run.xml *-blx.bib *.bcf *.log
