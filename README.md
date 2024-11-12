# goline

**goline** is a command-line interface (CLI) tool designed to automate installation workflows based on steps defined in a YAML or JSON file. It allows for seamless interaction, conditional execution, and user input, making it a flexible choice for customizable setups.

## Features

- **URL-based Configuration**: Accepts a URL to a YAML or JSON file that defines installation steps.
- **Multi-Step Workflow**: Supports a range of step types, including pure execution, user prompts, and conditional checks.
- **Conditional Logic**: Allows for dynamic installation flows based on user responses or previous step results.

## Requirements

- Go 1.18+
- Internet connection (to access configuration files via URL)

## Installation

TBD

## Usage

TBD

## Documentation

### Configuration File Structure

The configuration file can be in YAML or JSON format and should define a series of steps, each of which may include:

- **Execution Step**: Run commands with optional loading messages.
- **Prompt Step**: Ask the user a question and capture the answer.
- **Condition Check Step**: Perform actions based on previous answers, referencing values from earlier steps by ID.

#### Example Configuration

TBD

### Supported Step Types

1. **Execution** - Run commands with loading feedback.
2. **User Prompt** - Ask questions and store responses.
3. **Condition Check** - Make decisions based on previous inputs or command outcomes.

## Contributing

TBD

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
