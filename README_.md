#  chat-bot-choix-distribution-linux
  
Bot de conversation de choix de Distribution Linux
  
  
### FlowChart
  
  
Premier Jet de l'organigramme  
  
```flow
st=>start: Début du questionnaire
cond1=>condition: Êtes vous débutant ?
cond2=>condition: Sur GNU/Linux ?
cond3=>condition: Capacité de la machine ?
cond4=>condition: en informatique ?
cond6=>condition: Capacité de la machine ?
cond7=>condition: Capacité de la machine ?
cond8=>condition: peur des lignes de commande ?
cond9=>condition: peur des lignes de commande ?
U=>end: Ubuntu
M=>end: Mint
D=>end: DFLinux
A=>end: ArchLinux
B=>end: Debian
  
st->cond1
cond1(yes)->cond2
cond1(no)->cond3
cond2(yes)->cond4
cond4(yes)->cond7
cond4(no)->cond6
cond6(yes)->U
cond6(no)->D
cond7(yes)->M
cond7(no)->D
cond3(yes)->cond8
cond3(no)->cond9
cond8(yes)->U
cond8(no)->A
cond9(yes)->B
cond9(no)->A
```
  