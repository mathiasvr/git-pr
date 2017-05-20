# git pr

Create GitHub pull requests from the command line!

## usage
    git pr [options] ["title"] ["description"]

Omitting title and description will open the default editor, similar to `git commit`.

### options
    -b, --base [base]       Base branch for the pull request
    -y, --yes               Don't show confirmation prompt
    -c, --commit-message    Use the last commit message as title
    -o, --browse            Open created pull request url in browser.

## install

### homebrew
    brew install mathiasvr/repo/git-pr

### manual
Place the [git-pr](https://github.com/mathiasvr/git-pr/blob/master/git-pr) script in your `$PATH`, and make it executable. Example:

    chmod +x git-pr
    cp git-pr /usr/local/bin

## authentication
To avoid entering your password every time, set up [password caching](https://help.github.com/articles/caching-your-github-password-in-git/).

Optionally create a [personal access token](https://github.com/settings/tokens
) and use that instead of your password.


[![license](http://img.shields.io/:license-MIT-blue.svg?style=flat-square)](http://mvr.mit-license.org)
