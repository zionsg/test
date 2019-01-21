# Test Markdown

Trying to find Markdown that renders properly in a Markdown editor, GitHub and especially Bitbucket.
Main issue is with code blocks in lists!

Tested and tried:

- Lists must start with a blank line before it.
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
      <script>
        // Code block
        // for 1st item in list

        let a = 1;
      </script>
```

- 2nd item in list

    + 1st subitem for 2nd item in list

```
          <script>
            // Code block
            // for 1st subitem for 2nd item in list

            let b = 2.1;
          </script>
```

- 3rd item in list. Has no code blocks.
