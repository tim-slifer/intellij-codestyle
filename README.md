# IntelliJ-Codestyle
This is my code style definition for IntelliJ IDEA.

General rules that are enforced are:

- 120 column line width.
- Spaces instead of tabs. Indents are 4 spaces, continuations are 8 spaces.
- Spaces:
    - Add spaces before parentheses, except for method/function declarations and calls.
    - Add spaces around operators, except unary operators.
    - Add spaces before left braces
    - No spaces before keywords.
    - No spaces within parentheses, braces, or brackets.
- Force line wraps when running long, and after constants and annotations.
- Force braces on all blocks, even if only contains one line.
- Blank lines generally limited to 1, one blank line inserted at end of file.
- No wildcard imports.

I've forced very little line wrapping, opting instead to wrap if long. I felt this would provide some flexibility in how line breaks could be styled depending on either the situation at hand, or individual preferences.

## Installation

Copy the `codestyles` folders in this project into the IntelliJ config folder and restart Idea.

For Linux users: `~/.config/JetBrains/IntelliJIdea<version>`

For Mac users: `~/Library/Application Support/JetBrains/IntelliJIdea<version>`

For Windows users: `%APPDATA%\Roaming\JetBrains\IntelliJIdea<version>`

## Supported Formats:

Syntax styling has been defined for:

Java, Groovy, HTML, HTTP Request, JavaScript, JSON, Markdown, Properties, Style Sheets (CSS, Less, Sass, SCSS), TOML, TypeScript, XML, YAML

## Code Styles

Code Styles are managed in Settings at Editor >> Code Style.

Click the "Manage" button and a default scheme can be set for all projects.  With a project open in Idea, click the "Manage" then "Copy to Project".  This will insert the XML file into the `.idea` directory of the project, allowing project-specific style definitions.

## Info

I tend to update this file on an as-needed basis, and have avoided any sort of formal versioning. That being the case, keeping up to date is as simple as running a quick `git pull`.

The latest changes are known to work in IntelliJ Idea 2025.2.
