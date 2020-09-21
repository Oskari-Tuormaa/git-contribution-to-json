# git-contribution-to-json

This is a little script that outputs a json file containing the amount lines each contributor has commited to each file in the repo.

Blank lines are not counted in the tally.


## Requirements

```
GitPython
```

## How to use

1. cd to root of git repo
2. Run `git-contribution-to-json`
3. ...
4. Profit from the generated `git_contributions.json`

## Output structure

The output json is structured as in the following example:

```json
{
    "path/of/file1": {
        "contributor1": number_of_lines,
        "contributor2": number_of_lines
    },
    "path/of/file2": {
        "contributor1": number_of_lines,
        "contributor2": number_of_lines
    }
}
```
