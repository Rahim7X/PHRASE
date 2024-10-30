# Phrase CLI Password Manager

Welcome to the Phrase CLI Password Manager! This is a simple command-line tool for securely managing your passwords using AES encryption. It allows you to store and retrieve credentials in an encrypted format, ensuring your sensitive information is kept safe.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [License](#license)

## Features
- **Secure Password Management**: Uses AES encryption to keep your passwords safe.
- **Easy to Use**: Simple command-line interface with intuitive commands.
- **Add and Retrieve Credentials**: Store usernames and passwords with aliases for easy retrieval.
- **Show All Entries**: List all stored credentials.
- **Export and Import Vault**: Export your vault to a JSON file and import it with a new common password.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rahim7x/PHRASE.git
   cd PHRASE
   ```
2. Run the setup script to install dependencies and configure your shell:
```bash
chmod +x setup
./setup
```
## Usage
You can interact with the Phrase CLI Password Manager using the following commands:

## Commands
- Initialize a new vault:
```
phrase --init
```
- Add credentials:
  ```
  phrase --add <alias>
  ```
- Get credentials:
```
phrase --get <alias>
```
- Show all available entries:
```
phrase --show

```

- Export the vault:
```
phrase --export

```
- Import a vault:
```
phrase --import-vault

```
