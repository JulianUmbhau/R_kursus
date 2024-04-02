# R aftenskole
2 undervisningsgange af 3 timer inklusive pauser \
30 minutter før og efter hver undervisningsgang, til Q&A \
Øvelser som frivilligt hjemmearbejde.

### Nødvendigt for kursister
- Egen computer med R installeret og RStudio installeret
- https://cran.r-project.org/bin/windows/base/ (Gratis R download)
- https://www.rstudio.com/products/rstudio/download/#download (Gratis Rstudio download)

### Online gratis lærings materiale
Gode R kurser og hjemmesider
- R oversigt - https://www.tutorialspoint.com/r/index.htm

- Data analyse basics i R - [Data Analysis with R Programming](https://www.coursera.org/learn/data-analysis-r#syllabus)

- [R ggplot2 visualiserings cheat sheet](http://zevross.com/blog/2014/08/04/beautiful-plotting-in-r-a-ggplot2-cheatsheet-3/)

- Visualisering i R - [Data Visualization & Dashboarding with R Specialization](https://www.coursera.org/specializations/jhu-data-visualization-dashboarding-with-r#courses)

- Gode øvelser i en interaktiv R pakke - https://swirlstats.com/

- Statistik i R - [Introduction to Probability and Data with R](https://www.coursera.org/learn/probability-intro)

# Undervisningsplan
Vil du gerne lære at arbejde med data, lave data analyser og data visualiseringer? \
Dette kursus er for dig, der vil lære fundamentet for data analyser i programmeringssproget R - Det første skridt på vejen mod data science og data analysis på professionelt niveau. 
Du kommer til at få indsigt i
- Opsætning af programmeringssproget R og kode editoren RStudio
- Brug af basis funktionalitet I Rstudio
- Grundlæggende data typer I R
- Brugbare pakker til brug I R
- Grundlæggende funktioner til data indlæsning og data manipulation
- Grundlæggende funktioner til data analyse
- Kort gennemgang af data visualisering i R
- Øvelser og online kurser til videre læring

OBS: Dette er tilregnet den som er helt ny indenfor programmeringssprog. 
Pga. Kursets varighed og fokus, kommer vi ikke til at beskæftige os med dybere emner såsom statistiske analyser, machine learning, kode versionering, kodning best practice og lignende emner

#### Se et grundlæggende eksempel på interaktiv data visualisering udført i R
https://julian-johannes-umbhau-jensen.shinyapps.io/workspace/ \
(Det kan tage op til 1 minut at loade, da det kører på en gratis server som er i dvaletilstand)

# Kursusgennemgang

## 1. Introduktion til R, Rstudio og data analyse

Geting to know each other
- Mine erfaringer med R
- Kursisters udgangspunkt, interesseniveau, erfaring

Data analyse i R - baggrund
- Baggrund bag R
- Muligheder med data analyse i R (eller andre sprog)
- R Pros and Cons

Show off af muligheder i R
- Data cleaning og træning med efterfølgende visualisering

Introduktion til R og Rstudio
- Installation og opsætning af R og Rstudio

## 2. Datatyper og open source
Objekter i R
- Variabler og variabelnavne

Hvad er en funktion?
- reuseable code
- arguments
- output/action
- Lær mere om funktionen ?print

Datatyper
- Logical (logisk)
    - true/false
- Integer (hele tal)
- Numeric (numerisk)
    - decimaltal
- Character (Karakterer)
- Complex (komplekse)
    - imaginære betegnelser (5i)
- Raw (systemsprog)

Datastructurer
- Vector (vektor)
    - samling af data af én type
- List (liste)
    - vektor med forskellige typer
- Matrix (matrice)
    - to dimensioner
- Array (sekvens)
    - flere dimensioner
- Factor (faktor)
    - vektor med oversigt over unikke værdier
- Dataframe (dataframe)
    - matrix med forskellige typer data

Manglende data
- NA, NaN, None
- Håndtering af NA

Særlige typer data
- JSON, XML, Yaml, mv.

Øvelser

## 3. Data manipulation

Forstå en dataframe
- rækker
- kolonner

Indlæsning af data
- forskellige typer data
- csv, excel, JSON, mv.
- print

Operatorer
- assignment
- minus, addition, multiplikation, division
- <, >
- &, |, !

Konditionelle operatorer
- if
- else
- if else

Workflow funktioner
- For loops
- While loops
- repeat, next, break

Filtrering
- Ved index `[`
- Ved tekst `[`
- `$`
- `[[]]`

Øvelser

## 4. Grundlæggende kodning i R
Hvad er pakker i R?
- Ideen bag open source og code

Kode igennem scripts
- Ideen bag reproducerbare analyser
- Kommentarer i kode

Brugbare funktioner
- table
- summary

Dataframe funktioner
- cbind
- rbind
- merge

Scopes i R
- Environments - search()

Hvordan laver man en funktion i R?
- definition
- scope - funktion foregår i undermiljø
- input
- output

Best practice
- Brug editor
- Indentation
- 80 karakterer
- Variabelnavne/funktionsnavne
- Minimale og Generiske funktioner

Øvelser

## 5. Data udforskning og visualisering 
Udforskning af data
- Mean, median, mode
- Unique, max, min
- type, str

Visualisering i R basic
- Diverse plot funktioner
    - Pie, Bar, Scatter
- Plot manipulering

Avanceret visualisering i R
- ggplot2 pakken

Øvelser

## 6. Pipes og Tidyverse
Tidyverse
- Forstå pipes
- tibbles dataframe
- tidyverse pakker
- nyttige funktioner til data manipulation

Visualisering i ggplot2
- multiple variable i et plot
- forskellige plot muligheder

Øvelser

## + Ekstra emner
#### Versionering
- Hvorfor er versionering vigtig?
- Hvordan sørger man for god versionering?
- Git repositories

#### R Markdown 
- Markdown til dokumentation

