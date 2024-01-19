# HangFile

HangFile is a command-line game inspired by the concept of [Suicide Linux](https://qntm.org/suicide), where a random file is removed whenever the player makes a mistake. The game adds an element of risk to mundane tasks, creating an engaging and unpredictable experience.

## Features

- **Random File Removal:** Lose the game, and a randomly selected file in the specified directory will be permanently deleted.
- **Customizable Word List:** The game uses a word list containing 253,380 words, generously provided by [energizee](https://github.com/energizee). Check out the [gist with all the words](https://gist.github.com/energizee/02eafbc2e760c5cb0b816f780033b75e).
- **Cautionary Disclaimer:** A clear disclaimer is provided, urging users to exercise caution and emphasizing that the program may cause irreversible damage.

## How to Play

1. **Installation:**
   - Clone this repository to your local machine.

2. **Setup:**
   - Navigate to the directory where the repository is cloned.
   - Ensure you have Python installed (`python3`).
   - Customize the game by modifying command-line arguments (optional).

3. **Run the Game:**
   - Open a terminal and run the game using the command:
     ```bash
     python3 play.py
     ```
   - Follow the on-screen prompts to guess letters and try to avoid losing.

4. **Lose and Consequences:**
   - If you fail to guess the word and lose the game, a random file in the specified directory will be permanently deleted.

## Customization

- **Word File:** Specify a custom word file using the `-f/--file` option.
- **Punctuation Removal:** Include the `-p/--punctuation` flag to make the game more challenging by keeping punctuations in the chosen word.
- **Directory Selection:** Choose a different directory for file removal using the `-d/--directory` option. (defaults to User Home Directory)
- **File Removal:** Choose to either actually remove the file or not using `-r/--remove` flag. (defaults to no deletion)

## Disclaimer

Use this tool with extreme caution. The author takes no responsibility for any damage caused by the program. This game is not recommended for practical use and is intended for entertainment purposes only.

**Note:** This is a high-risk game, and users are advised not to play it if they are not comfortable with potential data loss.

Enjoy the thrill, but play responsibly (its your files after all)!

