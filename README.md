# Random_WikiQuote_bash_script
Bash script that fetch a random quote of some person from WikiQuote then use Python to clean them up for outputting

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

# Dependencies

This script requires the following tools to be installed:

## Required
- **bash** — shell interpreter
- **curl** — for HTTP requests
- **jq** — for JSON parsing
- **python** — for HTML parsing
    - Uses only the Python standard library:
      `sys`, `re`, `html.parser`
- **shuf** — for random selection (GNU coreutils)

## Optional
- **cowsay** or `python-cowsay` if piping the quote into a cowsay-style program. (My favorite usage)

# Reference
[natetyler/wikiquotes-api](https://github.com/natetyler/wikiquotes-api)  
