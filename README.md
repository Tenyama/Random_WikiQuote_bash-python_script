# Random_WikiQuote_bash_script-
Bash script that fetch a random quote of some person from WikiQuote
All code logic is based on [natetyler/wikiquotes-api](https://github.com/natetyler/wikiquotes-api)  

This was mostly converted to bash by AI to make a fun tool kinda like `fortune`

# Installation

```
cd
git clone https://github.com/Tenyama/Random_WikiQuote_bash_script.git
cd Random_WikiQuote_bash_script
chmod +x ./get_random_quote.sh
```
I did not care enough to make it an executable command so just make an alias for it in your .bashrc
```
alias random_quote='~/Random_WikiQuote_bash_script/get_random_quote.sh'
```

# Usage
```
random_quote "author or topic name" 
```
e.g: `random_quote "Terry A. Davis"`

>[!NOTE]
> The author/topic have to be exact, the example above would not work with `"Terry Davis"`

# Known issues
Sometimes it fetch the source if it was written as a line in the "Quotes" section

# Reference
[natetyler/wikiquotes-api](https://github.com/natetyler/wikiquotes-api)  
