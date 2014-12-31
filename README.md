#Octocat Quine :octocat:

It is __true__ self-reproduction program (the so-called Quine).

Let's propagate it!


##How to propagate

```console
$ git clone https://github.com/MakeNowJust/octocat-quine.git
Cloning into 'octocat-quine'...
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 3 (delta 0)
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
$ cd octocat-quine
$ node octocat.js
```

and, please type your GitHub username and password.


##What is Quine?

Quine is self-reproduction program.

For example:

```js
eval(s='console.log("eval(s="+JSON.stringify(s)+")")')
```

This is the program to show the text, which is same the program.
It is the minimal example of Quine.

In the same way,
[octocat.js](https://github.com/MakeNowJust/octocat-quine/blob/master/octocat.js) is the program to show self, but also to create a [Gist](https://gist.github.com/MakeNowJust/e2b6b142799a6a525add).


##License

This program is released under the [MIT License](http://makenowjust.mit-license.org/2014).
