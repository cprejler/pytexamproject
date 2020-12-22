# Mikkel, Casper, Aske - Tough Sympathy

## Python Eksamensprojekt


### Problemstilling

Vi bruger dette dataset: https://www.kaggle.com/datasnaek/mbti-type  til at lave en machine learning model, man kan bruge til at analysere personligheds træk igennem tekst.

Til at starte med, vil vi tage udgangspunkt i alle personlighedstyper og se hvor nøjagtig en model vi kan lave på den måde.

Bagefter, vil vi træne en mere specifik model ved kun at dele det op i ekstroverte og introverte

 - Introversion (I) – Extroversion (E)
 - Intuition (N) – Sensing (S)
 - Thinking (T) – Feeling (F)
 - Judging (J) – Perceiving (P)

På den måde kan vi sammenligne modellerne. Vores hypotese er, at hvis man tager den simple model får man en meget mere nøjagtig model, grundet størrelsen på vores dataset
### Valg af teknologi
Vi har brugt Tensorflow med keras til at lave vores model og træne vores neurale netværk. Vi har brugt pandas, numpy, matplotlib, samt seaborn til data visualisering
Vi har brugt ntlk.korpus stopwords til vores træning for a ignorere en liste af ord. 
Vi har brugt sklearn til at dele vores dataset op i "training og test"

### Instruktion til at køre projektet

Vores projekt er en google collab notebook. "Link"

Projektet er sat op til at downloade datasættet, samt filerne til at genskabe modellerne igen, fra et google drive, så man ikke behøves at køre modellen igen. 

### OBS: Hver model tager et par timer at køre.

