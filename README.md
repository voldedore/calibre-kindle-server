# Simple python script to deliver news using calibre

## Prerequisites

- `python2`
- `calibre`

## How to

- Edit the `process-recipe.py` with SMTP credentials.
- Update corresponding recipe in the `recipe` folder.
- (Optional but recommended) Edit your crontab.

## Command

Since this is executable, 2 options to run

```
$ ./process-recipe.py <name-of-recipe>

E.g:

$ ./process-recipe.py lemonde
Sending lemonde.mobi over email
```

Or

```
$ python2 process-recipe.py lemonde
Sending lemonde.mobi over email
```

## TODO

- Separate credential file and gitignore it.
