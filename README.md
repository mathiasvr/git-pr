# git pr [![license](http://img.shields.io/:license-MIT-blue.svg)](http://mvr.mit-license.org)

Create GitHub pull requests from the command line!

## usage
```
git pr [title] [description]
```

## install

Place the `git-pr` script in your `$PATH`, and make it executable. Example:
```
chmod +x git-pr
cp git-pr /usr/local/bin
```

## authentication

To avoid entering your password every time, set up [password caching](https://help.github.com/articles/caching-your-github-password-in-git/).

Optionally create a [personal access token](https://github.com/settings/tokens
) and use that instead of your password.
