latex=pdflatex -synctex=1 -interaction=nonstopmode
# aspell=sudo aspell --mode=tex --lang=it check

compile: 
	$(latex) Qualità_del_software.tex && $(latex) Qualità_del_software.tex
	rm -rf *.aux 
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc 
	rm -rf *.synctex.gz
	rm -rf *.lof
	rm -rf *.lot

compilenoopen:
	$(latex) Qualità_del_software.tex && $(latex) Qualità_del_software.tex
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
