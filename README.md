mappaeventigdocs
================

Mappatura eventi tramite spreadsheet Google e interfacciamento su OpenStreetMap

1) registrarsi su google (sigh)\n
2) creare sulla falsa riga di https://docs.google.com/spreadsheet/ccc?key=0AoZ9HGSxyqvydGI1M29qNU9XcUV6NThTd3RxLU5CcHc&usp=drive_web#gid=0\n
un proprio file eventi. è importante non inserire , (virgole), / o # nelle varie celle e incollare le coordinate nei campi LAT e LON nella forma 40.xxxx e 16.yyyy (esempio) in formato testo. per fare questo
consiglio di cliccare la cella, mettere nella sezione formula in alto a sinistra prima il carattere ' (apostrofo) e poi la coordinata. Es '40.444444 \n
3) sul gdocs fare File -> Pubblica sul web e copiarsi l'indirizzo del tipo https://docs.google.com/spreadsheet/pub?key=0AoZ9HGSxyqvydGI1M29qNU9XcUV6NThTd3RxLU5CcHc&single=true&gid=0&output=html \n
3) salvare sul proprio server il file php, il file js e i 4 files json mettendo questi ultimi con il permesso di scrittura
4) sostituire nel file php l'url del google docs nella forma https://docs.google.com/spreadsheet/pub?key=0AoZ9HGSxyqvydGI1M29qNU9XcUV6NThTd3RxLU5CcHc&single=true&gid=0&output=csv \n
cioè sostituendo il link del punto 3) con il finale =csv al posto di =html \n

Finito ;-) 
