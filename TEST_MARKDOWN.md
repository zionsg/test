# Test Markdown

Trying to find Markdown that renders properly in a Markdown editor, GitHub and especially Bitbucket.
Main issue is with code blocks in lists!

Tested and tried:
- For nested lists, indent the subitems such that the bullet character of the subitem is 4 spaces in
  from the bullet character of the parent item.
- For code blocks in lists, indent the code block such that the 3 backticks are indented 4 spaces in
  from the bullet character of the list item.

### Test Section

```
Code block
for section
```

- 1st item in list

    ```
    Code block
    for 1st item in list
    ```

- 2nd item in list

    + 1st subitem for 2nd item in list

        ```
        Code block
        for 1st subitem for 2nd item in list
        ```

- 3rd item in list. Has no code blocks.
