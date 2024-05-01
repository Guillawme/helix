# Configuration for helix

## Why this?

I really wanted to like Emacs. I had fun at the beginning, making [my own
configuration](https://github.com/Guillawme/emacs.d). Later, [I tried using
doom-emacs](https://github.com/Guillawme/doom.d) instead: it simplified a few
things, solved some problems I wasn't able to figure out, but for some reason
it wasn't as enjoyable to use. When native compilation of elisp files became
available, I got excited about it and turned it on. A good idea in principle,
not so much in practice: every doom update now required recompilation of all
packages, which took quite some time. Then it dawned on me: Emacs is a fun hobby
(sometimes), but I didn't need one more hobby. I needed a tool that doesn't
distract me from the things I am actually trying to do. I remembered why I tried
Emacs in the first place: it was when I started writing [my PhD thesis](https://
github.com/Guillawme/these), then I chose it for its movement and text editing
commands that could operate on words, sentences and paragraphs in addition to
lines and characters. This was very helpful, and is still the main way I need to
interact with text.

I like the idea of Emacs a lot, but in practice there are simply too many moving
parts.

For some time I used Vim without any configuration other than turning on syntax
coloring. It's pretty good, and has the advantage of being available everywhere.
I discovered kakoune and found that commands in the form `noun-verb` are much
easier to use, but for some reason kakoune never really clicked. Maybe I didn't
try long enough.

Finally, I found helix. It has the same `noun-verb` commands, and offers a
balance between features out of the box and configurability that suits me
well. A lot of useful things work right away and are on by default, it's very
refreshing! So here we go, maybe my last text editor?

## Practical details

To use the language configuration for Julia, there needs to be a global
Julia environment called `@dev` with the packages `LanguageServer` and
`JuliaFormatter` installed.

To use the formatter for shell scripts, `shfmt` needs to be installed on the
system.

