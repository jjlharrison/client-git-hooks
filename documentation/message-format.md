# message-format

By default this hook will insist that all commit messages include at least 4 words. You can turn this feature off using the following configuration,

```sh
git config hooks.message-format.disabled true
```

Alternatively, for more control of your commit messages you can specify a regular expression that must match all commit messages.

```sh
git config hooks.message-format.regex "$x"
```

Where `$x` is a Perl compatible regular expression. You can also customise the error message.

```sh
git config hooks.message-format.message "Your message here"
```
