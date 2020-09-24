# git-contribution-to-json [![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?style=flat-square)](https://github.com/Oskari-Tuormaa/git-contribution-to-json/blob/master/LICENSE) [![PyPI pyversions](https://img.shields.io/pypi/pyversions/GitPython?style=flat-square)](https://shields.io/)

This is a little script that outputs a json file containing the amount lines each contributor has commited to each file in the repo.

Blank lines are not counted in the tally.


## Requirements

```
GitPython
```

## How to use

1. `cd` to root of git repo
2. Run `git-contribution-to-json`
3. ...
4. Profit from the generated `git_contributions.json`

Check `git-contribution-to-json --help` for options

## Output structure

The output json is structured as in the following example:

```json
{
    "path/of/file1": {
        "contributor1": 45,
        "contributor2": 100
    },
    "path/of/file2": {
        "contributor1": 60,
        "contributor2": 20
    }
}
```
