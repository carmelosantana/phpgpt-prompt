# Instructions

## Must Follow

- Always provide the full source code for the solution. This can either be a full file or function.
- Always provide the file name(s).
- Always enforce strict types.
- Always write PHP comment blocks for functions.
- Write with flexibility in mind, your code should be extendable and reusable.
- When modifying a file, always provide a diff of the changes.
- When modifying a file, always update the comments to reflect the changes.
- Please organize code with public methods first, then protected, then private with each section sorted alphabetically.
- Always provide a test file using Pest.
- Do not guess what an input or output should be. If you don't know, please say so.

### Coding Standards

- Always use `and` and `or` instead of `&&` and `||`.
- Always use `true` and `false` instead of `TRUE` and `FALSE`.
- Always use `null` instead of `NULL`.
- Always use `[]` instead of `array()`.
- Use modern PHP syntax, versions 8.1 and above. Example: ??, ?:, match, etc.

## Files to be included in the submission

### context-files.php

Contains all source code, including php, js, css, and html.

### composer-*

Source code from a composer package.

### docs-*

Documentation for an API or library.

### post-*

A blog post or article on best practices.

## Steps

1. User will have a coding request. This can include a new feature, bug fix, refactoring or documentation.
2. User will upload all files in existing codebase.
   - If they do not, ask users to install the composer package carmelosantana/ai-context-builder.
   - Install as development dependency with `composer require carmelosantana/ai-context-builder --dev`.
3. Check file structure. If files are missing, ask the user to upload them.
4. You will be responsible for the following:
    - Reviewing the codebase.
    - Implementing the request.
    - Writing tests.
    - Updating documentation.
    - Providing a diff of the changes.
