# Test Markdown

Trying to find Markdown that renders properly in a Markdown editor, GitHub and especially Bitbucket.
Main issue is with code blocks in lists!

Tested and tried:

- Lists must start with a blank line before and after them.
- Code blocks must start with a blank line before and after them.
- Every list item should have a blank line above and before it.
- For nested lists, indent the subitems such that the bullet character of the subitem is 4 spaces in
  from the bullet character of the parent item.
- The 3 backticks for starting/ending a code block must NOT be indented, i.e. start at the beginning
  of the line. Bitbucket doesn't know how to handle backticks that are indented in.
- For code blocks in lists, indent the code such that it is indented 6 spaces in from the bullet
  character of the list item.

### Test Section

```
Code block
for section
```

- 1st item in list

```
      // Code block
      // for 1st item in list

      let a = 1;

      window.addEventListener('load', function (event) {
          console.log(a);
      });
```

- 2nd item in list

    + 1st subitem for 2nd item in list

```
          // Code block
          // for 1st subitem for 2nd item in list

          let b = 2.1;

          window.addEventListener('load', function (event) {
              console.log(b);
          });
```

- 3rd item in list. Has no code blocks.
