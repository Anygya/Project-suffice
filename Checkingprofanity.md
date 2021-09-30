# Project-suffice
from better_profanity import profanity 

# text to be censored 

text = "Fuck the world!"
# start censoring 

censored = profanity.censor(text, '$') 
 
# view output 

print(censored)
