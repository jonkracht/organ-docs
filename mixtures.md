# mixtures


## Introduction
What is a mixture?  Why does anyone care?


## How labial pipes make sound
* Air enters pipe toe and pass through flue
* Air stream impinges on the pipe's upper lip, creating vortex-like structures (eddies)
* These structures contain a broad spectrum of frequencies
* Only the pipe's natural frequencies are excited/amplified.


TODO:  Create diagram of labial pipe



## Deriving the resonance frequencies of a pipe

### Simplification to one-dimensional longitudinal waves

The acoustic pressure, that is the deviation from the ambient ($p \equiv P - p_0$), obeys the acoustic wave equation: 

\centerline{$\dfrac{d^2P}{dt^2} = \dfrac{1}{c^2}\dfrac{d^2P}{dt^2} $}

Since the boundary conditions of the organ pipe are that the pressure deviation goes to zero (i.e. $P(x=0,L) = 0$), solutions are sine waves.  In medium with sound speed $c$, the dispersion relation is:
$f=\dfrac{c}{\lambda}$

The resonant frequencies of this pipe is then given by:
$f_n = \dfrac{nc}{2L}$


## Full three-dimensional cylindrical solution


### Comparison of theoretical and experimental spectra

TODO:  Create/find some plots

The relative presence of each harmonic gives each sound its timbre.




| | Number of half steps  |
| --- | --- |
|Unison/octave| 1, 8, 15, 22, ...|
|$3^{rd}$| 3, 10, 17, 24, ...|
|$5^{rd}$| 5, 12, 19, 26, ...|

Get pitch class via modulo 7 (ex. $mod_7 (24) = 3$ so the 24th is a version of the third.)






## Related terminologies
A number of closely-related terms arise in the analysis of tuning.


### Pipe length
The effective physical length of the pipe.  For labial pipes (those with lips), this is the distance from the upper lip to the top of the pipe.

### Half-step distance
In music

### Diatonic distance
This is the distance in a major scale between two pitches.


### Partials or harmonics
These are the frequencies that appear in the harmonic series.  




## Mixture basics

### Contemporary American Organ (p. 67)

Mutation:  ranks sounding pitches other than a unison/octave
Mixture:  combination of unisons/octaves and mutations controlled via one drawknob

Mixture size range from two ranks (12th and 15th) to 8 ranks.

Smallest pipe has speaking length of less than three-eighths of an inch.  When a mutation voice is desired to be smallest than this length, instead made an octave lower.  This is deemed a break.  Happens one or multiple times across the span of the mixture.


Other factors in mixture design:
* Pipe types:  diapason/principal, flute, etc  (different harmonic contents produce varying mixture characters)
* Scaling (also affects harmonic content)
* Voicing (ex. soft, loud, aggressive, etc.)



### Mixture examples

#### Mixtures with no breaks

* Raushquinte or Grave Mixture
    * Only 12th and 15th
    * *Raush* in German, means intoxication, ecstasy, drunkeness 

* Cornet
    * 3 to 5 ranks with a versino of a third on top
    * Common pitch constituents are  (12-15-17) and (1-8-12-15-17)

* Sesquialtera
    * 12th and 17th for which series they support (ex. to support an 8' stop, pitches $2 \dfrac{2}{3}$ and $1\dfrac{3}{5}$ are played)   



#### Mixtures with breaks

* Mixture/Fourniture/Plein Jeu
* Scharf/Acuta
* Carillon/Glockenspiel
* Harmonics


#### Resultants
Provides some of the overtone series to give the illusion of a non-existent, lower fundamental tone.


##### Compton Harmonics

##### (Arthur) Harrison Harmonics



Page 303 of Barnes:  
32' Grand Cornet on Pedal CCC plays:
* Bourdon 16':  16 $10\frac{2}{3}$ 
* Gemshorn:  $10\frac{2}{3}$ $5\frac{1}{3}$ 4 $3\frac{1}{5}$

(All octaves and fifths.)




| Description | Diatonic number | Chromatic distance | Pipe length (ft) | Common Names |
|--- | :---: | :---: | :---: | --- |
|Root, unison| 1| 0| 8| Unison|
|Octave| 8| 12| 4| Super octave|
|Oct + 5th| 12| 17| $2\frac{2}{3}$| Nazard, quint|
|2 octaves| 17| 24| 2| Fifteenth|
|2 oct + major 3rd| 17| 28|$1\frac{3}{5}$| Tierce|
|2 oct + 5th| 19| 31| $1\frac{1}{3}$| Larigot|
|2 oct + min 7th | Flatted 21st | 34 | $1\frac{1}{7}$| Septime |
|3 oct | 22 | 38 | 1 | None |

Table:  Description of this table





Labial (lip) pipe:  Synonym for flue pipe



    


## Temperament

A temperament is a system of tuning that adjusts intermediate interval sizes while retaining pure octaves.


### Just Intonation

### Pythagorean

### Meantone

### Well-temperament







### Equal temperament

Uses a single ratio between adjacent notes.  Let this ratio be $R$.  Let the first note in a scale be $f_0$, the second be $f_1$, and so on.

\centerline{$R = \frac{f_1}{f_0} = \frac{f_2}{f_1} = ... = \frac{f_{12}}{f_{11}}$}


\centerline{$R^{12} = \frac{f_{12}}{f_0}$}

Since we want octaves to be equally spaced, adjacent octaves will have a frequency ratio of two.
Therefore:
\centerline{$R = \sqrt[\leftroot{-2}\uproot{2}12]{2} = 1.0594630943592953$}
We may equivalently write the twelfth root of two as $2^{\frac{1}{12}}$.  This notation will be a bit more compact in the following section.


Now that the ratio $R$ has been solved for, we can write out the first few frequencies.  

$f_1 = 2 ^ {\frac{1}{12}} f_0$

$f_2 = 2 ^ {\frac{1}{12}} f_1 = \left( 2 ^ {\frac{1}{12}}\right) ^ 2 f_0 = 2 ^ {\frac{1}{6}} f_0$

$f_3 = 2 ^ {\frac{1}{12}} f_2 = 2 ^ {\frac{1}{12}} 2^{\frac{1}{6}} f_0 = 2 ^ {\frac{1}{4}} f_0$


And so on.

A typical value for reference frequency is 440 Hertz at 70 degrees Fahrenheit.

|Scale degree | Fraction  | Decimal approx.|
| :---: | :---: |:---|
|0   |1  | 1.000|
|1  | $2^{\frac{1}{12}}$  |      1.059|
|2  | $2^{\frac{1}{6}}$  |      1.112|
|3  | $2^{\frac{1}{4}}$  |      1.189|
|4  | $2^{\frac{1}{3}}$  |      1.260|
|5  | $2^{\frac{5}{12}}$  |      1.334|
|6  | $2^{\frac{1}{2}}$  |      1.414|
|7  | $2^{\frac{7}{12}}$  |      1.498|
|8  | $2^{\frac{2}{3}}$  |      1.587|
|9  | $2^{\frac{3}{4}}$  |      1.682|
|10  | $2^{\frac{5}{6}}$  |      1.782|
|11  | $2^{\frac{11}{12}}$  |      1.888|
|12  | $2$  |      2.000|



So, any pitch's frequency may be computed via:
\centerline{f_n = f_0 2 ^ {\frac{n}{12}}}
where $n$ is the number of half-steps separating the desired and reference pitches.  Note this equation holds for pitches that are both higher and lower by choosing the sign of $n$ (i.e. positive or negative) appropriately.  







## TODO
* Mouth tone versus body tone
* Boundary condition of pipe body resonance solution:  air column starts at lower lip so both ends are at ambient pressure ($\Delta P = 0$) 
* End correction?  Pipe appears (sounds) a bit longer than it is
* Derivation and utility of sum and difference tones
* Introduce cent notation for 


