# Quebec Print Felt Bold

A bold felt-tip handwriting font. You can use it for free, including in commercial work, under the
[SIL Open Font License 1.1](https://openfontlicense.org).

![A specimen of the font: "See you somewhere on the internet :)", then the lowercase and uppercase alphabets, figures and accented letters](specimen.png)

It has uppercase and lowercase letters, figures, punctuation and accented Latin letters, 319
characters in total.

## Files

| File | Use it for |
|---|---|
| `fonts/quebec-print-felt-bold.woff2` | Websites |
| `fonts/quebec-print-felt-bold.ttf` | Installing on your computer, for Figma, Keynote, Word and other apps |
| `LICENSE.txt` | The licence and copyright notice |
| `CREDITS.txt` | Every handwriting source, with links |

Both font files hold the same font; the TTF is simply uncompressed.

## Using the font on a website

Copy the WOFF2 file into your site, then load it with `@font-face`:

```css
@font-face {
  font-family: "Quebec Print Felt Bold";
  src: url("/fonts/quebec-print-felt-bold.woff2") format("woff2");
  font-weight: 400;
  font-display: swap;
}

h1 {
  font-family: "Quebec Print Felt Bold", "Bradley Hand", cursive;
}
```

The font reads best in capitals at large sizes, so try `text-transform: uppercase` on headings.

## Credits

- **Font:** The If This Finds You Project Authors, at
  [ifthisfindsyou.app](https://ifthisfindsyou.app), who create fictional writers' hands based on
  real handwriting traditions. Inside the font file it keeps its original name, "IfThisFindsYou
  Saymo quebec-print-felt-bold GY3E".
- **Handwriting:** the letters were traced from photographs of volunteers' handwritten copies made
  for Copiste d'un jour, a project of the Bibliothèque et Archives nationales du Québec (2024),
  published under the [Creative Commons Attribution 4.0 licence](https://creativecommons.org/licenses/by/4.0/).
  A generator then redrew, varied and outlined them. Neither the writers nor the project endorse
  this font.
- **Hershey fonts:** some symbols, punctuation and letter shapes come from the Hershey fonts,
  whose terms ask for this acknowledgement to travel with the data: *The Hershey Fonts were
  originally created by Dr. A. V. Hershey while working at the U. S. National Bureau of Standards.
  The format of the Font data in this distribution was originally created by James Hurt,
  Cognition, Inc., 900 Technology Park Drive, Billerica, MA 01821 (mit-eddie!ci-dandelion!hurt).*

[`CREDITS.txt`](CREDITS.txt) lists every source page by name, with a link to each.

## Sharing the font

- Keep `LICENSE.txt` and `CREDITS.txt` together with the font files.
- You can include the font in anything you make or sell, such as a website, an app or a template,
  but you can't sell the font on its own.
- If you modify the font, give your version a new name.
