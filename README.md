# NLP Spell Checker App

## Brief Description
App runs a basic spell checking program (Run the SpellCorrector.py file). 
- A user inputs a sentence, the program checks all words entred, highlights the misspelled works when one clicks the "Submit" button.
- Upon clicking submit, the same sentence is replicated as an output at the very bottom text widget.
- If a word appears in the corpus attached as "514-8.txt", no suggestion will be present.
- Suggestions only appear if a word is misspelled.
- A drop down menu is automaticaally enabled when there are suggestions. 
- From the drop down menu, the misspelled words are reflected there.
- A user selects their misspelled word individually, depending on the number of misspelled words.
- Once selected, a user then clicks on the next button, "Suggestions." 
- This then displays a list of suggestions for the misspelled word, ranked according to the highest probability.
- Depending on the corpus, the minimum edit distance & the error model, a misspelled word may have 3 max suggestions (this can be edited on the code as per a user's needs)
- From the suggestions displayed, a user can select the word they intended to type then click "Replace" button to replace the misspelled word.
- Take not of the changes happening at the bottom text widget. The initial sentence input gets changed/replaced with the new words replacing the mispelled words.

## Setup/Installation
1. Clone this repo from Github to your local machine.
2. Preferred IDE is Spyder or Jupyter Notebooks.
3. You need Python >3 installed in your local machine.


## Technologies Used
1. Python 3.7
2. NLP libraries e.g., NLTK
3. Tkinter library

## Support & Contact Details
karari.alexander@gmail.com or TP056742@mail.apu.edu.my

### Project year
2020 

### Contributors
1. TP038434@mail.apu.edu.my
2. TP032076@mail.apu.edu.my
3. TP057392@mail.apu.edu.my
