# DouDizhu - Racket

A compact Racket implementation of the Chinese card game **Dou Dizhu** (*Fight the Landlord*).

### What this project does (high level)
- Represents cards and Dou Dizhu order (3 … Ace, 2, Black Joker, Red Joker)
- Detects common hand types (e.g., solos, pairs, trios, straights, straight-pairs, airplanes), plus bombs and the rocket
- Compares hands according to Dou Dizhu rules
- Includes a minimal turn engine and a few simple bot policies for experimentation
- Uses many small, testable helpers with `check-expect` style tests

> **Source availability**  
> Since this project was developed during a University of Waterloo course, the full source code is only available **privately upon request**.  
> 📩 **Contact:** ratiu17filip@gmail.com
