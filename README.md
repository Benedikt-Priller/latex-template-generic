# latex-template-generic

## Usage

Import into your project as a submodule.

```shell
git submodule add git@github.com:Benedikt-Priller/latex-template-generic.git
```

In your main .tex-file setup the following commands:

```shell
\newcommand{\templatedir}{../latex-template-generic/}

% Import template
\input{\templatedir packages}
\input{\templatedir pagestyles/basic_transcript}
\input{\templatedir macros}
\input{\templatedir elements}
\input{\templatedir letterfonts}
```

Now you can utulize all included packages, elements and other configruations defined in the template.
