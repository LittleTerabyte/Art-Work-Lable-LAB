# Art-Work-Lable-LAB
(classes/constructors)

Define the Artist class with a constructor to initialize an artist's information and a print_info() method. The constructor should by default initialize the artist's name to "None" and the years of birth and death to 0. print_info() should display Artist Name, born XXXX if the year of death is -1 or Artist Name (XXXX-YYYY) otherwise.

Define the Artwork class with a constructor to initialize an artwork's information and a print_info() method. The constructor should by default initialize the title to "None", the year created to 0, and the artist to use the Artist default constructor parameter values.

Ex: If the input is:

Pablo Picasso
1881
1973
Three Musicians
1921

The output is:

Artist: Pablo Picasso (1881-1973)
Title: Three Musicians, 1921

If the input is:

Brice Marden
1938
-1
Distant Muses 
2000

the output is:

Artist: Brice Marden, born 1938
Title: Distant Muses, 2000
