# OrgMode

Forked repo of [OrgMode](https://github.com/JurajKubelka/OrgMode) parser, developed by JurajKubelka.

## Status

Tests pass as of Pharo 13.0.

## Loading instructions

### Starting from a Pharo image

Open a playground window (`Ctrl+O+W`) and evaluate:

```smalltalk
Metacello new
    baseline: #OrgMode;
    repository: 'github://capsulecorplab/OrgMode:main';
    load.
```

Note: Evaluate by highlighting the text, then either right-click on the highlighted text and click `Do it` or press `Ctrl+D`.
