Meu portfólio, montado como se fosse um editor de código. Um arquivo HTML, sem build, sem dependência.
```
.-----------------------------------------------------------------------------.
|                                                                             |
| .-------------------------------------------------------------------------. |
| |  ______________________________________________________________________ | |
| | |igor-portfolio                                                 |F]|!"| | |
| | |""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""|"| | |
| | |~/igordev-exe $ whoami                                             | | | |
| | |Igor Alves - Engenharia de Software, UnB/FGA                       | | | |
| | |                                                                   | | | |
| | |~/igordev-exe $ _                                                  |_| | |
| | |___________________________________________________________________|/| | |
| `-------------------------------------------------------------------------' |
|                                                                             |
|  (o) PWR   (o) BRT                                      C= COMMODORE 1084S  |
`-----------------------------------------------------------------------------'
                             \___________________/
                       .-------------------------------.
                       `-------------------------------'
```
```
.-----------------------------------------------------------------------------.
||Es| |F1 |F2 |F3 |F4 |F5 | |F6 |F7 |F8 |F9 |F10|                  C= AMIGA   |
||__| |___|___|___|___|___| |___|___|___|___|___|                             |
| _____________________________________________     ________    ___________   |
||~  |! |" |§ |$ |% |& |/ |( |) |= |? |` || |<-|   |Del|Help|  |{ |} |/ |* |  |
||`__|1_|2_|3_|4_|5_|6_|7_|8_|9_|0_|ß_|´_|\_|__|   |___|____|  |[ |]_|__|__|  |
||<-  |Q |W |E |R |T |Z |U |I |O |P |Ü |* |   ||               |7 |8 |9 |- |  |
||->__|__|__|__|__|__|__|__|__|__|__|__|+_|_  ||               |__|__|__|__|  |
||Ctr|oC|A |S |D |F |G |H |J |K |L |Ö |Ä |^ |<'|               |4 |5 |6 |+ |  |
||___|_L|__|__|__|__|__|__|__|__|__|__|__|#_|__|       __      |__|__|__|__|  |
||^    |> |Y |X |C |V |B |N |M |; |: |_ |^     |      |A |     |1 |2 |3 |E |  |
||_____|<_|__|__|__|__|__|__|__|,_|._|-_|______|    __||_|__   |__|__|__|n |  |
|   |Alt|A  |                       |A  |Alt|      |<-|| |->|  |0    |. |t |  |
|   |___|___|_______________________|___|___|      |__|V_|__|  |_____|__|e_|  |
|                                                                             |
`-----------------------------------------------------------------------------'
```

## Como foi feito

O desenho veio primeiro. Montei a interface inteira no Figma antes de escrever qualquer linha: layout, paleta, hierarquia dos painéis, como cada estado deveria parecer. (Tudo baseado no design já existente do Vscode)

A exportação para HTML dá conta do que é estático. As caixas, as cores, o tipo, o espaçamento. O que ela não entrega é comportamento, o terminal que interpreta comandos, a busca fuzzy do command palette, o dobramento de código, o sticky scroll, a troca de tema, a busca em todos os arquivos. Nada disso sai de um export.

Essa camada eu escrevi com apoio do Claude Code, revisando e refazendo o que não servia. O desenho continua sendo meu, utilizei dele para entender o funcionamento do código e como ferramenta de auxilio.

## Comandos

O terminal do painel inferior é de verdade.

```
ls                lista os arquivos
cat <arquivo>     abre um arquivo
open <nome>       abre pelo nome curto (open projects)
grep <termo>      busca em todos os arquivos
theme <nome>      dark | light | monokai
whoami            sobre mim
status            disponibilidade
help              lista os comandos
clear             limpa o terminal
```

## Atalhos

```
Ctrl+P            abrir arquivo
Ctrl+Shift+P      command palette
Ctrl+G            ir para a linha
Ctrl+B            barra lateral
Ctrl+`            terminal
```

## Stack

HTML, CSS e JavaScript puros. Arquivo único, ~100 KB, sem framework e sem etapa de build, a única coisa externa é a fonte JetBrains Mono.

No celular o código quebra em vez de rolar para o lado, a numeração das linhas acompanha e os menus se agrupam num botão só.

## Rodar

Baixe e abra o `index.html` no navegador. É isso.

```
 _______________________________________________________________________
|contato                                                          |F]|!"|
|"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""|"|
|github    github.com/igordev-exe                                     | |
|linkedin  linkedin.com/in/igordev-exe                                | |
|email     igoralvesrodrigues12@gmail.com                             | |
|                                                                     |_|
|_____________________________________________________________________|/|
```
