# LLM Tic Tac Toe V2
Docs 05-25-26 V1 (For questions or comments:  Stephen Witty switty@level500.com)  

### Project Overview:
This project is a revisit of an older project. The project provides a test harness for LLMs to study their ability to play Tic Tac Toe. The test harness provides a way to play a LLM against another LLM, the same LLM head to head, or a LLM against a perfect player. Win, loss, and draw stats are kept and can be saved. The player who goes first alternates between games. When a perfect player is selected and has the first move of the game, a random square is selected. This adds more game uniqueness across multiple games. The program uses Open Router to make LLM API requests across models the same. The software was written by Claude Code.

<img src="Pics/Game Board.png" width="500">

### Reports / Documentation:
- A presentation that covers the project can be found below:
- [Presentation Link](https://github.com/switty42/AI_Tic_Tac_Toe_V2/blob/main/Presentations/AI_Tic_Tac_Toe_V2_052426.pdf)
- Example run recorded:
- [Video](https://youtu.be/yAPSHvwvDJE)
- NWA AI meetup presentation (the last 10 minutes) 052826
- [Video](https://youtu.be/6PueLmj9fx4&t)
### Usage:

- The software is written in JavaScript
- The program should run in any browser, but has been tested in Chrome
- Provide an Open Router API key
- Select the perfect player check box in order to use a perfect game player
- Adjust the values you wish for the number of games, LLM temperature, API errors, and format errors
- Format errors occur any time the LLM returns an answer in the wrong format or an invalid square
