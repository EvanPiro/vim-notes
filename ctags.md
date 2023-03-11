# `ctags`

`ctags` enables vim to support jumping to a definition. This is invaluable to fast comprehension of complex processes.
To enable it for usage from a relative path, set the following in vim config:
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
