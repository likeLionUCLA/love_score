## Your goal is to

- 1) Use your full name
- 2) Use another full name where we will check their percentage match
- 3) Create a method `nameMixer` that takes (1) and (2) as arguments, and combines the two names above in a single string

(example) inputs : 'Jeehae Jessica Song', 'Justin Drew Bieber'
          output: 'Jeehae Justin Jessica Drew Song Bieber'

- 4) Using the pre-made method called `charToNum`, return the total sum of each word in the name as string

(example)  'Jeehae' -> 74+69+69+72+65+69 = 418
           'Justin' -> 74+85+83+84+73+78 = 477
           'Jessica' -> 74+69+83+83+73+69+65 = 516
           'Drew' -> 68+82+69+87 = 306
           'Song' -> 83+79+78+71 = 311
           'Bieber' -> 66+73+69+66+69+82 = 425

input : 'Jeehae Justin Jessica Drew Song Bieber'
output: '418 477 516 306 311 425'

- 5) Create a method called loveScore that take one argument as a string, return the last sum as number between 0-99.

 - the first step should make number between 0-99
 - Sum up the first and second, second and third, third and fourth, fourth and fifth, fifth and six. Take off hundreds if you need to. keep your number between 0-99
 - Repeat same thing until you get only one number.
 (see the PDF on page 233 for your understanding)

(example)

input: '418 477 516 306 311 425'

step1:   18  77  16  6  11 25
step2:     95  93  22  17  36
             88  15  39  53
               3  54  92
                 57  46
                   3

output : 3






input:

charToNum('B') # you'll get 66
