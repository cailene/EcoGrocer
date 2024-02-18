EcoGrocer
---
*founded by: Cailene Magat, Carmen Lam, Francesca Ysabelle Galang, and Sarah Mathew*

## Mission Statement
"Imagine a world where managing your groceries is effortless, sustainable, and community-driven. That's EcoGrocer. Our AI-powered app tracks expiration dates, suggests recipes based on your ingredients and even helps you donate surplus items to local food banks. Join us in revolutionizing grocery management, minimizing waste, and building a more sustainable future, one fridge at a time."

## Inspiration
We know how high food prices are right now so we discussed when overconsumption and food waste would occur the most throughout the year. We realized that during the Holiday season, many families prepare more lavish meals for the festivities. However, during the hectic time of parties, gatherings, and other events,  many food items can be forgotten and sadly, eventually go bad and go to waste.

## What it does
EcoGrocer helps combat the overall goal of reducing food wastage while also providing a secondary solution of helping the homeless by directing app users to possible food bank locations nearby (in hopes of donating non-perishable foods). 

Some functionalities that we've implemented/planned to implement are:
- [ ] Use Google ML Kit to convert receipts captured by camera to text
- [ ] Generate a list of groceries by parsing the converted image to text
- [ ] Users can manually add expiration dates otherwise the app generates estimated dates (through a database list)
- [ ] Users have access to mark Groceries as "done" as per usage
- [ ] App gererates alerts on when food items expire
- [ ] User also has the flexibility of possible recipes to finish certain grocery items (planned to implement this with web scraping) 
- [ ] Users also have the option to manually search through the app for recipes of their liking
- [ ] Possible options for donating food to food banks using Google Maps
- [ ] Use Auth0 for login and signout options
- [ ] Use of MongoDB to store information regarding user profile info and recipe lists

## How we built it
As originally planned we started off using Android Studio however due to errors we did switch the React to come up with a presentable demo. However, as we plan for this app's future we'll be learning more about Android Studio and combat the issues we've faced and build our App there instead. 

## Challenges we ran into
As the Challenge had started we initially opted to code with Android Studio using Java as our main programming language. However, shortly after this decision we quickly ran into errors with the implementation of Auth0 (as it was written in Kotlin) and the implementation of MongoDB. To combat this obstacle we split into two teams one working on Figma to have a visual representation of our project in case of failure of potential code, and the other working on debugging. After numerous attempts, asking mentors, and researching possible solutions online we decided to scratch the idea entirely and use React with Visual Studio Code instead. This transition had happened so close to the submission deadline however as a team we were determined to push through. Keeping the same organization of tasks as before we embarked once again with two teams, one working on presentational resources while the other team working with coding different aspects of the project rather than the project as a whole. We believe rather than showing a finished project, showing the various aspects of what we aim to build in the future of this App is more important than rushing through the finished project. 

## Accomplishments that we're proud of
As a team, we've collectively collaborated although we're from different backgrounds within coding. As this is the first hackathon for most of our members we're proud to have attempted to create an impressive app that can change the future of how much food wastage occurs during the holiday times. Another accomplishment that we've collectively been proud of is our ability to problem-solve and eagerness to learn new concepts. Java was a language that over half of us hadn't had experience with and if we did have experience it was minimal, this made it incredibly difficult to get a grasp on the concepts that followed with it. However, with the help of online resources, we've been able to learn a new language and possibly also learn a bit of React due to the challenge we faced as mentioned before *(as mentioned before in the section, "Challenges we ran into") *. However, at the end of the day, the most important aspect of attending this hackathon was to have fun, network, and socialize which we as a group collectively accomplished. 

## What we learned
Some skillsets that we have learned or are in the process of learning are:
- [ ] Java
- [ ] React
- [ ] Implementing Auth0 
- [ ] Implementing MongoDB

## What's next for EcoGrocer
Although EcoGrocer started as a hackathon idea for the prompt "4 seasons" we plan to expand EcoGrocer to a fully functional app as we see a future where this app can be successful in reducing food wastage, over consumption/overbuying of groceries and helping the homeless in terms of food bank donations. We plan to continue developing this app for the possibility of launching it one day and plan to follow the above to-do list (as seen in the section *"What it does"*). Although most of the to-do list has skills that most of us do not possess we plan to learn more about the skill set we need to develop this and bring this project to life. 
Once this project is at a possible stage where development is complete, we'll bring this app to possible investors who are willing to hear our pitch and help us bring this app to life. 

## Try it out
[Protoype](https://www.figma.com/proto/mO7io1dZh9R5XXLbx7xAOW/Byte-me?type=design&node-id=58-4937&t=QRtxC173aEAx2Atn-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=58%3A4937&show-proto-sidebar=1&mode=design)

[1st Take!](https://github.com/NightingaleX03/ByteMe)

[Slides](EcoGrocer/Byte_Me.pdf)
