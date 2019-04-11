resultados.pdf: resultados.tex plot1.pdf

plot1.pdf: plotdatos1.py datos1.dat
	python plotdatos1.py

datos1.dat: a.out
	./a.out>>datos1.dat

a.out: makedatos1.cpp
	g++ makedatos1.cpp	


resultados.pdf: resultados.tex plot.pdf

plot.pdf: plotdatos.py datos.dat
	python plotdatos.py

datos.dat: makedatos.py 
	python makedatos.py>>datos.dat