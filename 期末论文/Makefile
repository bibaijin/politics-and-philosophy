filename=论义利观与中国政治

main.pdf:main.ltx ref.bib /home/bibaijin/share/format/xetex.tex
	xelatex main.ltx
	biber -l zh__pinyin main
	#xelatex main.tex
	xelatex main.ltx

rename:
	mv main.pdf "$(filename).pdf"

view:
	evince main.pdf &

clean:
	rm -f *.aux *.bbl *.blg *.idx *.ilg *.ind *.out *.toc *.nav *.snm main.pdf *.run.xml *-blx.bib *.bcf *.log
