# pdfmake-mini

> the essence of pdfmake

# note: this is work in progress

## Scope

`pdfmake-mini` is a fork of [pdfmake](http://pdfmake.org/), with the goal
to slim it down as much as possible. Basically, I'd like to create a
[pdfkit](https://github.com/devongovett/pdfkit/) plugin that is compatible
with pdfmake's content declaration.

## Demo / Playground

```
git clone git@github.com:gr2m/pdf-editor.git
cd pdf-editor
git checkout pdfmake-mini
npm install
npm start
```

Current issue is, that no text is showing up at all. Other things
like borders and backgrounds are being rendered. My guess is that
the problem is the font embedding, but I couldn't figure it out.
Any help would be much appreciated
