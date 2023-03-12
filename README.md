# training
hi I'm Ahmad i just to this for fun and improve my skills in the computer sicens 
#Write a for loop the prints out all the element between -5 and 5 using the range function.
for i in range(-4, 5):
    print(i)
 -4'rock'
-3 'R&B'
-2 'soundtrack'
-1'soul

1
2
3
4

#Print the elements of the following list: Genres=[ 'rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop'] 
#Make sure you follow Python conventions.
Genres=[ 'rock', 'R&B', 'Soundtrack', 'R&B', 'soul', 'pop']

for Genre in Genres:
    print(Genre)
rock
R&B
Soundtrack
R&B
soul
pop

#Write a for loop that prints out the following list: squares=['red', 'yellow', 'green', 'purple', 'blue']
squares=['red', 'yellow', 'green', 'purple', 'blue']
for square in squares:
    print (square)
red
yellow
green
purple
blue

#Write a while loop to display the values of the Rating of an album playlist stored in the list PlayListRatings.
#If the score is less than 6, exit the loop.
#The list PlayListRatings is given by: PlayListRatings = [10, 9.5, 10, 8, 7.5, 5, 10, 10]
PlayListRatings = [10, 9.5, 10, 8, 7.5, 5, 10, 10]
i = 0
Rating = PlayListRatings[0]
while(i < len(PlayListRatings) and Rating >= 6):
    Rating = PlayListRatings[i]
    print(Rating)
    i = i + 1
    
 #Write a while loop to copy the strings 'orange' of the list squares to the list new_squares
 #Stop and exit the loop if the value on the list is not 'orange':
 
 squares = ['orange', 'orange', 'purple', 'blue ', 'orange']
new_squares = []
i = 0
while(i < len(squares) and squares[i] == 'orange'):
    new_squares.append(squares[i])
    i = i + 1
print (new_squares)
