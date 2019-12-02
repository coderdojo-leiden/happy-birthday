# Extra uitdaging: Lang zullen we leven

De volgende 5 tabellen bevatten de noten voor de regels van *Lang zullen we leven*. Het interessante hieraan is dat er bijna altijd 2 noten tegelijk gespeeld moeten worden. Dan zou je dus 2 `play` commando’s direct na elkaar kunnen gebruiken en dan pas een `sleep` commando. Het begin van je melodie ziet er dan bijvoorbeeld als volgt uit:  
`play :f4`  
`play :c4`  
`sleep 1`

Een handiger optie is gebruik te maken van het `play_chord` commando. Hieraan geef je in plaats van een enkele noot een lijstje met de noten die tegelijk gespeeld moeten worden mee. Het begin van je melodie ziet er dan als volgt uit:  
`play_chord [:f4, :c4]`  
`sleep 1`  
Een lijst noten begint dus met een openblokhaak `[`, eindigt met een sluitblokhaak `]` en daartussen zet je de noten gescheiden door komma's.

Dit zijn de noten voor de eerste regel:

| **Noot 1** | **Noot 2** | **Lengte** |
|:---------- |:---------- |:---------- |
| :f4        | :c4        | 1 tel      |
| :f4        | :c4        | derde tel  |
| :f4        | :c4        | derde tel  |
| :f4        | :c4        | derde tel  |
| :f4        | :c4        | 1 tel      |
| :c4        |            | 1 tel      |  

<br/>
Dit zijn de noten voor de tweede regel:

| **Noot 1** | **Noot 2** | **Lengte** |
|:---------- |:---------- |:---------- |
| :a4        | :f4        | 1 tel      |
| :a4        | :f4        | derde tel  |
| :a4        | :f4        | derde tel  |
| :a4        | :f4        | derde tel  |
| :a4        | :f4        | 1 tel      |
| :f4        | :c4        | 1 tel      |  

<br/>
Dit zijn de noten voor de derde regel:

| **Noot 1** | **Noot 2** | **Lengte** |
|:---------- |:---------- |:---------- |
| :c5        | :a4        | 1 tel      |
| :c5        | :g4        | derde tel  |
| :c5        | :g4        | derde tel  |
| :c5        | :g4        | derde tel  |
| :d5        | :f4        | halve tel  |
| :c5        | :f4        | halve tel  |
| :bb4       | :f4        | halve tel  |
| :a4        | :f4        | halve tel  |
| :g4        | :e4        | 1 tel      |
| :g4        | :f4        | 1 tel      |
| :g4        | :e4        | 1 tel      |  

<br/>
Dit zijn de noten voor de vierde regel:

| **Noot 1** | **Noot 2** | **Lengte** |
|:---------- |:---------- |:---------- |
| :c5        | :d4        | halve tel  |
| :bb4       | :e4        | halve tel  |
| :a4        | :f4        | 2 tel      |
| :bb4       | :f4        | 2 tel      |
| :c5        | :a4        | 2 tel      |  

<br/>
En dit zijn de noten voor de vijfde (en laatste) regel:

| **Noot 1** | **Noot 2** | **Lengte** |
|:---------- |:---------- |:---------- |
| :d5        | :bb4       | 1 tel      |
| :bb4       | :g4        | 1 tel      |
| :a4        | :f4        | 2 tel      |
| :g4        | :e4        | 2 tel      |
| :f4        | :c4        | 2 tel      |  

<br/>
Veel plezier met het programmeren hiervan. Vergeet niet er ook een beat bij te componeren!

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons-Licentie" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Dit werk valt onder een <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/deed.nl">Creative Commons Naamsvermelding-NietCommercieel-GelijkDelen 4.0 Internationaal-licentie</a>.
