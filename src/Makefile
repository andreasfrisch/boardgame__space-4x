All: cards clean

cards:
	./latexdockercmd.sh pdflatex player_deck_cards.tex
	./latexdockercmd.sh pdflatex bureaucracy_cards.tex
	mv player_deck_cards.pdf ../
	mv bureaucracy_cards.pdf ../

clean:
	rm *.log *.aux
