All: cards board extraboards technology clean

cards:
	./latexdockercmd.sh pdflatex player_deck_cards.tex
	./latexdockercmd.sh pdflatex bureaucracy_cards.tex
	mv player_deck_cards.pdf ../
	mv bureaucracy_cards.pdf ../

board:
	./latexdockercmd.sh pdflatex game_board.tex
	./latexdockercmd.sh pdflatex anomaly_hexes.tex
	mv game_board.pdf ../
	mv anomaly_hexes.pdf ../

extraboards:
	./latexdockercmd.sh pdflatex market_boards.tex
	./latexdockercmd.sh pdflatex shuffle_track.tex
	mv market_boards.pdf ../
	mv shuffle_track.pdf ../

technology:
	./latexdockercmd.sh pdflatex technology_boards.tex
	./latexdockercmd.sh pdflatex technology_tiles.tex
	mv technology_boards.pdf ../
	mv technology_tiles.pdf ../
	
clean:
	rm *.log *.aux
