# SaltyGet
A small Jupyter Notebook of a Python scrapping script to retrieve every possible informations from Salty Bet matches for illuminatis accounts.
It can be a precious tool for anyone willing to make an optimal betting algorithm.

# The Concept
The basic idea comes from here : https://codereview.stackexchange.com/questions/211017/a-bot-for-saltybet-that-watches-and-records-matches?rq=1
Though, you can see in the script that it evolved a lot.

Every existing scripts I found so far were only recording which fighter won or lost. Though, I have two problems with this approach:
- Knowing who won and who lost doesn't give informations on why
- Going for the one with the highest chances of winning isn't the optimal way of betting

So I wrote this script to get all the informations from the characters, but also the odds for each match.

# Requirements
Most of the informations can't be retrieved when not Illuminati ("premium" Salty Bet users).
I erased my account ids from the script for obvious reasons.
I won't share the data I retrieved so far, as it would allow anyone to access these informations without paying. 
They are not essential to enjoy Salty bet's greatness, and I think its creator deserves some income for his work.

# How to use
When password and email have been given in the appropriate variables, you can basically just run all cells, and the script will do the rest.
This is based on a "while True" loop, so it won't stop as long as the kernel is not shut down. 
The only thing to do is to do nothing. Don't close the browsers or visit other websites while the script is running, and it will be ok (if you do, it won't record matches anymore, but that's all). You can open new tabs on these browsers and do wathever you want, that won't cause any problem, though I would advise to just open a new browser to avoid mistakes).

# Future updates
I plan to make a few updates in the future, such as "dumb" automatic betting (betting a fixed value for the highest or lowest winrate) to mine automatically while scrapping (this won't make anyone rich though) and try to get the informations without opening browsers.
