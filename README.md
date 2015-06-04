I had this project in mind for quite a while now. There is a nice project
called "[Anki](https://ankiweb.net)", but I don't like much of the details
in the project. Especially sharing and collaboration has to be much better.

## Card format

* A JAML / JSON syntax should be used for each card
* Each card has the properties:
    * Question: Markdown+HTML (including LaTeX with MathJax?)
    * Answer: Markdown+HTML (including LaTeX with MathJax?)
    * Tags
    * Timestamp of last change
    * unique ID (hash of cards content?)
    * dependencies (for this card, you have to know another card)

Cards should also be able to reference an image. This makes everything
complicated...


## Deck format

* Title
* Description
* unique deck id


## State of learning format

The state of your studies should be stored in a defined format. This includes:

* For each card: A list when it was asked and how well the student performed


## User Interface

* Function to go back (to the last card)
* "Silence" a deck (meaning it will not be deleted, but not shown in the deck list / cards to learn)


## Sub projects

* Website ([responsive](https://en.wikipedia.org/wiki/Responsive_web_design))
* App (which has to work offline)
    * Android
    * iOs
    * Windows Phone
* Anki-Deck converter