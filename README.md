# Octocat Quine :octocat:

It is **true** self-reproduction program (the so-called Quine).

Let's propagate it! :octocat: :octocat: :octocat: :octocat: .... :octocat:

## How to propagate

```console
$ git clone https://github.com/MakeNowJust/octocat-quine.git
$ cd octocat-quine
$ node octocat.js
```

and, please type your GitHub username and password.

Note that if you use 2FA for GitHub login, please input a personal access token with `gist` scope instead of a password.
It is known [GitHub limitation](https://docs.github.com/en/github/authenticating-to-github/accessing-github-using-two-factor-authentication#authenticating-on-the-command-line-using-https).

## What is Quine?

[Quine](http://en.wikipedia.org/wiki/Quine_%28computing%29) is self-reproduction program.

For example:

```js
eval(s='console.log("eval(s="+JSON.stringify(s)+")")')
```

This is the program to show the text, which is same the program.
It is the minimal example of Quine.

In the same way, [octocat.js](https://github.com/MakeNowJust/octocat-quine/blob/master/octocat.js) is the program to show self,
but also to **create a [Gist](https://gist.github.com/MakeNowJust/e2b6b142799a6a525add)**.
Som it is **true** self-reproduction program.

## License

[MIT License](http://makenowjust.mit-license.org/2014-2021)

2014-2021 (C) TSUYUSATO "MakeNowJust" Kitsune
