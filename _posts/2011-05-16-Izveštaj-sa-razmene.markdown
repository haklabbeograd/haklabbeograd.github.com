---
title: Izveštaj sa Razmene, 15. Maj 2011
layout: post
---
Druga razmena u CZKD-u:

- Za razmenu je dovoljno troje.
- Probali smo **netrw** (Vim) i **tramp** (Emacs), koji omogućavaju transparentno editovanje fajlova
  i kretanje kroz fajl sistem na udaljenom računaru.
- Igrali smo se sa raznim prečicama u Zsh-u i Bash-u:
   - `Alt-.` ubacuje poslednji argument prethodne komande
   - `=program` == `` `which program` ``
   - `Ctrl-Alt-_` ponavlja prethodnu reč
   - `Alt-q` za pokretanje bilo čega usred editovanja komande
   - `Alt-'` za quoting cele linije
   - `Ctrl-X Ctrl-E` za editovanje komandne linije u $EDITOR-u
- Pogledali načine da se asinhrono startuje više monitora sa različitim
  periodima osvežavanja -- **xmobar** ovo ima ugrađeno, "domaći" Bourne shell skript radi ovo za **Wmii**.
- Probali smo (bezuspešno) da aktiviramo wireless adhoc mode na SL510 Thinkpad-u.
- Pametovali smo o bazama podataka: "Real life" RDBMS-ovi ne implementiraju
  čistu relacionu algebru -- rezultat SELECT-a ne može imati više identičnih
  redova jer je tabela ("relvar") *skup* redova.
- Probali smo da instaliramo 32-bitni Debian i podignemo 64-bitni Ubuntu
  u VirtualBox-u na Visti, i obrukali se.
- Prozori u Ubuntuu imaju zaobljene ivice da se čovek ne bi posekao.
