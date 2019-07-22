# Cards With Go
 Using golang to create a deal,get new deck,,shuffle,save to file
 
# Functions Used
  > newDeck() - this function provides a set of new cards(16) when ever called into a slice "cards" by using append() and joining
  cardSuits,cardValues.............
  > deal() - this returns the cards based on handsize and theb remaing cards from the slice of the cards from new deck...........
  > print() & toString() - print() fuction prints the deck form the slice,toString() coverts the data stored in the in the slice in a single string seperated by commas.......
  > shuffle()/randomIntn()- take the deck as input and shuffle the deck
  > saveToFile()-store the data in a text file
  > newDeckFromFile()- read the file created by saveToFile() and convert into output
