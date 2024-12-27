# DLE
Diccionario de la Lengua Española (DLE) by Real Academia Española (RAE), available from the terminal, using a tiny bash script.

## Installation

```install -Dm755 dle ~/.local/bin```

## Usage

```dle [-f] [term]```

Use ```-f``` for full-ish results (everything but phrases). Using it without that option outputs just the first sense or senses for the term.

## Examples

```
> dle pinnípedo
1. adj. Zool. Dicho de un mamífero marino: Que tiene el cuerpo algo pisciforme, con las patas anteriores provistas de membranas interdigitales y las posteriores ensanchadas en forma de aletas, a propósito para la natación, pero con uñas, con tejido adiposo subcutáneo muy abundante y la piel revestida de un pelaje espeso, y que se alimenta exclusivamente de peces; p. ej., la foca. U. t. c. s. m., en pl. como taxón.
```

```
 > dle -f tromba
Del it. tromba 'trompa'.
1. f. manga (‖ columna de agua que se eleva desde el mar). Sin.: manga, tifón.
2. f. tromba de agua. Sin.: chaparrón, aguacero.
3. f. Irrupción tumultuosa de personas.
```
