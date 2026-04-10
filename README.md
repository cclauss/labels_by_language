# labels_by_language
A GitHub Action that adds language labels to pull requests.

Example pull request: [#1](https://github.com/cclauss/labels_by_language/pull/1)

<img width="826" height="142" alt="image" src="https://github.com/user-attachments/assets/8471f2d3-1817-4de3-91dd-b92f97994341" />

```javascript
// Map programming languages to their file extensions.
const languageMap = {
  C: ['.c', '.h'],
  'C++': ['.cpp', '.cc', '.cxx', '.hpp', '.hh', '.hxx'],
  Go: ['.go'],
  JavaScript: ['.js', '.jsx'],
  TypeScript: ['.ts', '.tsx'],
  Lua_: ['.lua'],
  Python_: ['.py', '.pyi'],
  Cython: ['.pyx', '.pxd', '.pxi'],
  Rust: ['.rs'],
};
```
To try it out, create a pull request that adds files with one of the file extensions above.

The corresponding labels will automatically be added to that pull request.

Two alternative GitHub Actions:
* https://github.com/cclauss/labels_by_language/blob/main/.github/workflows/labels_by_language.yml
