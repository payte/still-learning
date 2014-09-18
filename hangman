def isWordGuessed(secretWord, lettersGuessed):
    '''
    secretWord: string, the word the user is guessing
    lettersGuessed: list, what letters have been guessed so far
    returns: boolean, True if all the letters of secretWord are in lettersGuessed;
      False otherwise
    '''
    # FILL IN YOUR CODE HERE...
    
    listy = []
    for i in secretWord:
        if i in lettersGuessed:
            listy.append(i)
    return len(listy) == len(secretWord)
    
def getGuessedWord(secretWord, lettersGuessed):
    '''
    secretWord: string, the word the user is guessing
    lettersGuessed: list, what letters have been guessed so far
    returns: string, comprised of letters and underscores that represents
      what letters in secretWord have been guessed so far.
    '''
    # FILL IN YOUR CODE HERE...
    secretWord2 = secretWord
    alphabet = 'abcdefghijklmnopqrstuvwxyz'
    listy = []
    result = ''
    for ch in secretWord2:
        result = result + ch + ' '
    
    
    for i in lettersGuessed:
        if i in secretWord:
            listy.append(i)

    for i in alphabet:
        if i not in listy:
            result = result.replace(i,"_")
    return result
    
def getAvailableLetters(lettersGuessed):
    '''
    lettersGuessed: list, what letters have been guessed so far
    returns: string, comprised of letters that represents what letters have not
      yet been guessed.
    '''
    # FILL IN YOUR CODE HERE...
    
    availableLetters=""
    for i in "abcdefghijklmnopqrstuvwxyz":
        if i not in lettersGuessed:
            availableLetters += i
 
    return availableLetters


    
