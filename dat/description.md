# File description

Data file `wtc.csv` contains a summary of the fugues in 
*The Well Tempered Clavier* by J.S. Bach. Fields are separated by 
a semi-colon.

## Columns

- `book`: Book number (1 or 2)
- `key`: Key signature
- `meter`: Time signature
- `startDegree`: the scale degree on which the fugue subject starts
- `endDegree`: the scale degree on which the fugue subject ends
- `numVoices`: number of voices in the fugue
- `isDoubleFugue`: whether the piece is a double fugue (Y/N)
- `hasCS1`: whether the fugue has a counter subject (Y/N)
- `hasCS2`: whether the fugue has a second counter subject (Y/N)
- `hasStretto`: whether the fugue uses a stretto at any time (Y/N)
- `realAns`: whether the fugue answer is real instead of tonal (Y/N)
- `ansDomCad`: whether the fugue answer cadences strongly in the dominant (Y/N)
- `epsAfterAns`: whether the answer is followed by a short episode (Y/N)
- `expoProg`: list of chord progression of exposition (comma separated)
- `subject`: list of scale degrees in fugue subject (comma seperated)
