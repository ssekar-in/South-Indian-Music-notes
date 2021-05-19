# South-Indian-Music-notes
The code calculates cent values for the notes of South Indian Music based on known ratios of notes.
Further another code calculates the notes from the fifths and fourths and calculates the cent values as below:
Microtones calculation in South Indian carnatic music:
Calculation procedure:This is based on the book by Prof P Sambamoorthy, South Indian Music, Book:IV, Fourth edition, 1975, Chapter V on 22 srutis.
The calculation is based on perfect 5ths( ratio 3/2) and perfect 4ths ( ratio 4/3). The srutis are said to be derived from calculation fifth of fifth of fifth .. 3/2 x 3/2 x 3/2 ..reduced to octave one and fourth of fourth of fourth.. reduced to octave one.
The number of cycles taken is 11 for the fifths. As perfect fifth is 701.955 cents ( 1200 x log base2 (3/2)), the 11th cycle yields 7721.5 cents, which reduces to 7721.5 - 6 x 1200 = 521.5 cents in the first octave. In other words, upto 7th octave the calculation is proceeded.¶
Similarly fourth of fourth of fourth .. 4/3 x 4/3 x 4/3.. In this case the number of cycles considered is ten. As perfect fourth is 498.045 cents ( 1200 logbase2(4/3)), the 10th cycles yields 4980.5 cents, which is in the fifth octave.
Once the above srutis that is, note value in cents are calculated, they are arranged in ascending order to get the 22 srutis including microtones.
It is also observed that when calculation up to 5 cycles for fifths and 6 cycles for fourths are only considered, that is only up to third octave for both fifths and fourths, the semitones are got.
