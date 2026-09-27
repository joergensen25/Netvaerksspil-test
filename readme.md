Lavet af: Ali, Luca, Rasmus og Aksel

Noter: 

Der er en del udkommenteret kode fra tidligere implementeringer. 

Vi har flyttet en del ansvar fra klienterne over på serveren, så klienten kun sender en forespørgsel på MOVE
og serveren derefter afgør, om bevægelsen er lovlig og hvordan point skal fordeles.

Vi oprettede en fælles GameBoard-klasse, der indeholder banen og tjekker om et koordinatsæt på banen er en væg.

