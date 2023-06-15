How to build this documentation:

1. Install Sphinx via pip3 `pip3 install Sphinx`
2. Build the documentation in the source language `make singlehtml`
3. Build the translated documentation `make SPHINXOPTS="-Dlanguage=en" singlehtml`

Update translation:
1. `make gettext`
2. `sphinx-intl update -l en`
3. Edit the translation .po files with an editor like Poedit.
4. Build if you want to see your changes.

Prebuild documentation:
You can look at this document without needing to build it yourself.
Updates are automatically built here:
German https://satzung.overte.org/de/
English https://satzung.overte.org/en/
