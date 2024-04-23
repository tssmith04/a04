## Clash of Clans/Clash Royale clan Comparison

# Setup
To effecitvely setup the program you will need to clone the repository and run 'npm install' to install all of the package dependencies. You will also need to navigate to https://developer.clashroyale.com/ and https://developer.clashofclans.com/ to get your own API keys. Although my API keys are still in this pushed code, they will not work because they require a user to be on the same IP. So when you navigate to these links you can signup and retrieve your own API keys, replace the two I have in server.js and use the application as you wish.

# Background
The inspiration of this very small web application is that my friends and I are in a clan in Clash of Clans and Clash Royale. It would be nice to know, going into the war, the comparisons between our clan and another clan. This could also be extended to simply compare one clan to another out of curiosity.

# Testing Data Tags
Some basic tags you can use for Clash of Clans are: #28C0J9L9L and #2QRPYGCC0
Some basic tags you can use for Clash Royale are: #LGLJLUV9 and #LU8OQLUG

# How it Works
The program works by retrieving each clans war log (all previous wars within the past year) and computing aggregate values for each clan.

These values for Clash of Clans include current win streak, average destruction percentage, and overall win percentage. These can be useful to know because Average Destruction and Overall Win percentage tell you how good of a clan you are against and the win streak/lose streak may indicate the activity of the clans players currently. 

These values for Clash Royal are very similar and include win streak, average trophies gained, and overall win percentage. These can be useful to know because Average Trophies gained indicates how much a clan is winning in the 1v1v1v1v1v1 among 6 clans. If there is a large Average Trophy gain then they are consistently beating the other 5 clans. Similarly to Clash of Clans, the current win/loss streak may indicate the current activity of the players. Lastly, the overall win percentage indicates the general level of expertise of a clan.

Hope this is helpful, have a nice day!
