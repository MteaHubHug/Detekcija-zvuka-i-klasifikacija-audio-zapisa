# Detekcija-zvuka-i-klasifikacija-audio-zapisa

tagovi : umjetna inteligencija, strojno učenje, računarni vid ,konvolucijske neuronske mreže

Croduino nova32 pločicu - mikrokontroler. Kako sam kući imala komadić pametne LED- trake,
jedan USB-kabal koji mi je poslužio kao napajanje i prozirnu kutijicu od posnog sira... 
-> Sastavila sam primitivnu "lampu" koja je povezana na laptop preko kojeg šaljem instrukcije lampi kojom bojom da svijetli. Ulaz su naredbe "crvena", "plava"... 
koje govorim laptopu. Dakle, u kod je integriran model koji klasificira te naredbe.
Kada je tišina, lampa svijetlu u bijeloj boji...
Uz to sam napravila i neku jako jadnu "aplikaciju" koja kada se pusti pjesma "Rebel, rebel" prikazuje slike moje prijateljice, 
a kada se pusti Can't hold us, prikazuje sliku moje druge prijateljice. Ne radi baš najbolje zbog toga što mikrofon konstantno prima naredbe,
a i model nije treniran na dovoljno podataka. 
Preuzela sam i neku igricu s interneta i popravila ju tako da player puca u balone kada okinem G-dur akord na gitari. 
Za teorijski dio sam pripremila Colab bilježnicu u kojoj je objašnjeno na koji način računalo obrađuje
audio-zapise te kako pripremamo i popravljamo zvučne zapise da budu prikladni ulazi za konvolucijsku neuronsku mrežu. 
Zatim, imam kod u JS-u koji prikljuplja podatke kroz mikrofon klikom na gumb, trenira model te nakon treniranja,
klikom na gumb "slušaj" prima ulaze kroz mikrofon i klasificira ono što je računalo "čulo" što je vizualizirano 
pomicanjem slidera lijevo (ako je prva klasa) te desno (ako se radilo o drugoj klasi) .
