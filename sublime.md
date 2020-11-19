# Sublime

## Plugins

- Lang Format
- PyYapf Python Formatter
- SublimeLinter
- SublimeLinter-cppcheck
- SublimeLinter-cpplint
- SublimeLinter-golint
- SublimeLinter-mdl
- SublimeLinter-pylint
- SublimeLinter-shellcheck

## Installing dependencies

```
brew install clang-format cppcheck pylint shellcheck yapf
[sudo] gem install mdl
go get -u github.com/golang/lint/golint
pip install cpplint
```

## Sublime settings

```
{
    "ignored_packages":
    [
        "Vintage"
    ],
    "rulers":
    [
        120
    ],
    "tab_size": 4,
    "trim_trailing_white_space_on_save": true,
    "ensure_newline_at_eof_on_save": true,
    "translate_tabs_to_spaces": true
}
```
