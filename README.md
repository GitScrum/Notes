# Notes

## Git

### Remove remote tag
```console
git tag -d 12345
git push origin :refs/tags/12345
```

## Test spies
- [sinon](https://github.com/sinonjs/sinon)
- [descartes](https://github.com/mariusGundersen/descartes)

## css flex
- [flexgrid](http://flexboxgrid.com/)
- [flexpattern](http://www.flexboxpatterns.com/home)


## dotFiles
### .editorconfig
```
root = true

[*]
indent_style = tab
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[{package.json,*.yml,*.scss, *.jade}]
indent_style = space
indent_size = 2

[*.md]
trim_trailing_whitespace = false
```
