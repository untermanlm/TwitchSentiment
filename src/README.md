# Subfolder Contents

The files in this folder contain the various experiments that I have conducted (and am planning to conduct) in performing sentiment analysis on Twitch emotes.
The first program, `experiment1.ipynb`, uses the Llama-2 LLM to label different Twitch chat messages. I used three labels: negative, neutral, and positive.
Why might this be useful? Well, for example, you can provide audience reaction metrics on different product releases that are streamed live. Many streamers
react to game-announcement streams, and providing a concrete analysis on the reactions of the people in Twitch chat can allow for a company to gauge consumer interest in their product. 

The next goal I have for the repository is to create code that labels the sentiment of different Twitch emoticons. There are already papers which use textual emoticons, such as :), :(, and >:(, and 
smartphone emoticons, such as "😂", but there is still an untapped repository of Twitch emoticons whose sentiments have not yet been thoroughly analyzed. There have been introductory forays into the 
analysis of "global" emoticons on Twitch, but new emotes are made every day.
Here is a paper that uses deep-learning to decode the meanings of different emotes:
[twitch-emote-sentiment-analysis](https://www.researchgate.net/publication/353988143_Finding_epic_moments_in_live_content_through_deep_learning_on_collective_decisions)

I think it would be cool to make an application which automatically labels new emotes by 1) scraping all of the enabled 7TV emotes on a given channel and 2) collecting information on the words 
that are associated with the valid emotes. 
