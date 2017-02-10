## LoveScore

- 1) Use your full name
- 2) Use another full name where we will check their love score
- 3) Create a method `nameMixer` that takes (1) and (2) as arguments, and combines the two names above in a single string

(example)

        inputs : 'Jeehae Jessica Song', 'Justin Drew Bieber'
        output: 'Jeehae Justin Jessica Drew Song Bieber'

- 4) With the help of the pre-made method called `charToNum` in file, create a method that returns the total sum of all words in the name as a string

(example)

           'Jeehae' -> 74+69+69+72+65+69 = 418
           'Justin' -> 74+85+83+84+73+78 = 477
           'Jessica' -> 74+69+83+83+73+67+65 = 514
           'Drew' -> 68+82+69+87 = 306
           'Song' -> 83+79+78+71 = 311
           'Bieber' -> 66+73+69+66+69+82 = 425

        input : 'Jeehae Justin Jessica Drew Song Bieber'
        output: '418 477 514 306 311 425'

- 5) Create a method called loveScore that take one argument as a string, and returns a final score as a number between 0-99.

 - The first step should lose any place at hundreds and above
 - Sum the first and second, second and third, third and fourth, etc. Apply the first step to each intermediate result
 - Repeat until you end up with one number, this is your love score
 (see the diagram in the PDF on page 233 )

(example)

    input: '418 477 514 306 311 425'

    step1:   18  77  14  6  11  25
    step2:     95  91  20  17  36
                 86  11  37  53
                   97  48  90
                     45  38
                       83

    output : 83
