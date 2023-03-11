# `ctags`

ctags enabled vim to support a jump to definition.
To enable it to a relative path, in the vim config set:
```
set tags=./tags;
```
To enable it in the current project run:
```
ctags -R *
```
To use it in vim, put the cursor over the value being called and run:
```
crtl shift ]
```
