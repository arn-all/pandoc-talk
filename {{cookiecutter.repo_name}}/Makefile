default: slides.pdf

slides.pdf: slides.md header.tex
	pandoc -t beamer -H header.tex --pdf-engine=xelatex  -V theme=metropolis $< -o $@

slides.html: slides.md header.tex
	pandoc -t revealjs -s -V revealjs-url=https://revealjs.com -V theme=white $< -o $@

report.pdf: slides.md header.tex
	pandoc -H header.tex --pdf-engine=xelatex $< -o $@
