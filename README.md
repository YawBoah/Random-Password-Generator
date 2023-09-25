# Random Password Generator

This is a simple web-based Random Password Generator that allows users to create random passwords with a combination of uppercase letters, lowercase letters, numbers, and symbols. The generated password can be copied to the clipboard for easy use.

![image](https://github.com/YawBoah/Random-Password-Generator/assets/126890146/cfdf693c-e3bd-4721-92e8-aaebf8fa2952)


## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Password Generation**: Users can generate random passwords by clicking the "Generate Password" button. The generated password includes a mix of uppercase letters, lowercase letters, numbers, and symbols.

- **Copy to Clipboard**: Users can easily copy the generated password to their clipboard by clicking the copy icon.

## Usage

1. Open the `index.html` file in a web browser.

2. Click the "Generate Password" button to create a random password.

3. The generated password will be displayed in the input field.

4. Click the copy icon to copy the password to your clipboard for use in other applications.

## How It Works

The password generation process is as follows:

1. Initialize an empty `password` variable to store the generated password.

2. Add one character from each of the character sets (uppercase letters, lowercase letters, numbers, and symbols) to the password to ensure that at least one character from each set is included.

3. While the length of the password is less than the desired length (12 characters in this case), randomly select characters from the combined character set (allChars) and append them to the password.

4. Display the generated password in the input field.

5. Users can click the copy icon to copy the password to their clipboard.

## Contributing

Contributions to this project are welcome. If you have any suggestions for improvements or would like to add new features, please feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to use this README for your Random Password Generator project. If you have any further questions or need additional information, please let me know!
