# Problem 1: Display student information
START
DECLARE name as string 
DECLARE age as integer
DECLARE grade as character 
DECLARE percentage as float

INPUT name 
INPUT age
INPUT percentage

DISPLAY name
DISPLAY age
DISPLAY GRADE
DISPLAY percentage
STOP
# PROBLEM 2: Read and display a character
START
DECLARE ch as character 

DISPLAY "enter a charcter"
INPUT ch using getchar()

DISPLAY "the character is:"
OUTPUT ch using putchar() 
STOP
# Problem 3: Display floating point value with different precision
START
DECLARE value as float

INPUT value 

DISPLAY value with default precision 
DISPLAY value with 2 decimal places 
DISPLAY value with 4 decimal places 

STOP
