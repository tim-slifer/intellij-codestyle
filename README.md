# IntelliJ-Codestyle
This is my code style definition for IntelliJ IDEA.

General rules that are enforced are:

- 120 column line width.
- Tabs instead of spaces. Indents are 4 spaces, continuations are 8 spaces.
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

Copy the `codestyles` folder in this project into the `~/.IntelliJIdea/config/` folder and restart Idea.

## Supported Formats:

Syntax styling has been defined for:

CSS, Groovy, HTML, Java, JavaScript, JSON, Properties, Sass/SCSS, TypeScript, XML, YAML

## Code Styles

Code Styles are managed in Settings at Editor >> Code Style.

Click the "Manage" button and a default scheme can be set for all projects.  With a project open in Idea, click the "Manage" then "Copy to Project".  This will insert the XML file into the `.idea` directory of the project, allowing project-specific style definitions.

## Info

I tend to update this file on an as-needed basis, and have avoided any sort of formal versioning. That being the case, keeping up to date is as simple as running a quick `git pull`.
