# Sublime ɴsɪ Syntax

[Nsɪ](https://nsi.readthedocs.io/) syntax support for [Sublime Text](www.sublimetext.com).

## Caveat

I'm not a Sublime user. Only tested with `bat`. See below.

# Installation For BAT

[`BAT`](https://github.com/sharkdp/bat) is a `cat` replacement that
supports syntax highlighting.

Assuming you have `bat` & `git` installed:

```
mkdir -p "$(bat --config-dir)/syntaxes"
cd "$(bat --config-dir)/syntaxes"
git clone https://github.com/virtualritz/sublime-nsi-syntax
bat cache --build
```
