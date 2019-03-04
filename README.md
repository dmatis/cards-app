# Cards Application

## Description
A simple cards application developed in conjunction with the following course:  
[Go: The Complete Developer Guide](https://www.udemy.com/go-the-complete-developers-guide)

## Interface
Create a new deck:  
`cards := newDeck()`

Deal out a set of cards of a specified size:  
*Note: returns a dealt set and the remaining deck of cards*  
`newHand, remainingDeck := deal(cards, handSize)`

Shuffle a deck:  
`cards.shuffle()`

Save a deck to disk:  
`cards.saveToFile(filename)`

Import deck from file:  
`cards := newDeckFromFile(filename)`

## To Start
`go run main.go deck.go`
