Yale CPSC 490 Thesis Project

Abstract: 
The video game design industry, particularly in franchises like Pokémon, has faced challenges in recent years with generating new and exciting characters. Designers often struggle with ``designer's block,'' limiting their ability to innovate and meet the evolving expectations of fans. As artificial intelligence technologies advance, it is worth exploring how these tools can assist in overcoming creative stagnation. This project aimed to develop a cross-platform mobile application that utilizes AI text-to-image models to generate new Pokémon-like characters. By employing these models, the app offers users a unique way to create imaginative designs that could serve as inspiration for future official Pokémon character designs. In addition to character design generation, this project investigated methods to increase user engagement with the application, focusing on the implementation of a multi-armed bandit algorithm and gamification techniques such as a head-to-head character design matchup voting system and leaderboard. Voting systems and leaderboards are widely used to motivate user engagement by introducing decision-making, competition, and achievement. Through a comprehensive literature review, the effectiveness of these gamification strategies was analyzed. Interestingly, the success of these gamification techniques in boosting engagement depended on various factors like the context they were applied in and user-specific characteristics, such as levels of extroversion and trait competitiveness. For instance, highly extroverted individuals or those with strong competitive tendencies may respond more positively to leaderboards, while others might find such features less engaging or even discouraging. These findings underscore the importance of tailoring gamification techniques to the target audience, highlighting the nuanced relationship between user psychology and engagement strategies. 

Make sure to install all of the dependencies in the package.json file before running the application!

To run Creature Canvas on iOS:
   - Open Simulator app
   - File > Open Simulator > iPhone 16 Pro
   - In VSCode terminal:
      - cd /Users/jasonlee/downloads/school/classes/f2024/cs490/creatureCanvas
      - npx react-native run-ios

To run Creature Canvas on Android:
   - Open Android Studio
   - More Actions > Virtual Device Manager
   - Click play button on "Medium Phone API 35" device
   - In VSCode terminal:
      - cd /Users/jasonlee/downloads/school/classes/f2024/cs490/creatureCanvas
      - npx react-native run-android

To launch database server:
   - In VSCode terminal:
      - cd /Users/jasonlee/downloads/school/classes/f2024/cs490/creatureCanvas/backend
      - node database.js

To access MySQL editor via terminal:
   - In VSCode terminal:
      - cd /Users/jasonlee/downloads/school/classes/f2024/cs490/creatureCanvas/backend
      - mysql -u root -p
      - password is Concord_11
