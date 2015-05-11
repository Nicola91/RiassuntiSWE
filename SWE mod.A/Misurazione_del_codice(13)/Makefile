latex=pdflatex -synctex=1 -interaction=nonstopmode
# aspell=sudo aspell --mode=tex --lang=it check

compile: 
	$(latex) Misurazione_del_codice.tex && $(latex) Misurazione_del_codice.tex
	rm -rf *.aux 
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc 
	rm -rf *.synctex.gz
	rm -rf *.lof
	rm -rf *.lot

compilenoopen:
	$(latex) Misurazione_del_codice.tex && $(latex) Misurazione_del_codice.tex
	rm -rf *.aux 
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc 
	rm -rf *.synctex.gz
	rm -rf *.lof
	rm -rf *.lot


clean:
	rm -rf *.aux 
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc 
	rm -rf *.synctex.gz
	rm -rf *.pdf
	rm -rf *.lof
	rm -rf *.lot
