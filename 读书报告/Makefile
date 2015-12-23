filename=读《君主论》有感

main.pdf:main.tex /home/bibaijin/.config/LaTeX/xelatex.ltx
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
