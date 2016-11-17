# ~/.git_template

```bash
git clone this/git_template.git ~/.git_template
git config --global init.templatedir ~/.git_template
```

## hooks/pre-commit

when `/!!$/` found, the commit fails
(`$` is a marker).

```ruby
KEY = 'PRIVATE_KEY'  #!!$
$
# debug print$
p KEY  #!!$
```
