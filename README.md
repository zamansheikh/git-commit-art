# Git Commit Art

This repository contains a Node.js script that demonstrates how to create artistic patterns on the GitHub contribution graph by manipulating commit dates. It's intended for educational purposes to understand Git's commit history mechanics and the contribution graph's behavior.

**Important:** This tool should not be used to artificially inflate contribution statistics or mislead others about your activity. Such actions are against GitHub's terms of service and can lead to account suspension.

## Features

- **Random Commits:** Generate a specified number of commits on random dates within the past year.
- **Custom Text Commits:** Create commits on specific dates to form text patterns (e.g., "HACK") on the contribution graph.

## How It Works

The script uses predefined 7x5 grid patterns for letters A-Z. For custom text commits, it calculates the dates corresponding to the cells needed to form the text on the contribution graph, starting from a user-specified date.

## Usage

1. **Prerequisites:**
   - Node.js installed
   - Git repository initialized and linked to GitHub

2. **Installation:**
   ```bash
   npm install jsonfile moment simple-git random readline
   ```

3. **Running the Script:**
   ```bash
   node git_commit_modifier.js
   ```
   - Choose option 1 for random commits or option 2 for custom text commits.
   - Follow the prompts to input the number of commits or the text and start date.

## Ethical Considerations

- Use this tool responsibly and for educational purposes only.
- Do not use it to misrepresent your contribution activity on GitHub.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements or bug fixes.

## License

This project is licensed under the MIT License.