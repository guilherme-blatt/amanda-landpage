# Amanda Carvalho — brand guideline

Use this when changing the landing page. Keep the current layout. Match the identity, do not redesign it.

The source board and the Vanitas file live in `pictures-raw/` (gitignored). That folder is a high-resolution reference dump. Copy only what the site needs into `photos/` or `fonts/`.

## Personality

Moderna, delicada, atemporal, clean. The brand should feel light, subtle, and elegant. Avoid heavy contrast, loud color, and decorative clutter.

## Color

Use these hex values. Do not introduce a second palette.

| Role | Hex | Name |
| --- | --- | --- |
| Paper | `#F7F5F5` | Cool Gray 1 C |
| Stone | `#E5E3E2` | Cool Gray 2 C |
| Mist | `#C1D6E0` | Pantone 643 C |
| Mid blue | `#8DB1CB` | Pantone 4149 C |
| Blue | `#6083A7` | Pantone 2158 C |

`#6083A7` is the strongest brand color. Use it for buttons, kickers, and the wordmark. Body text can be darker than the palette so paragraphs stay readable. Light text on blue sections uses `#F7F5F5`.

## Type

The identity uses two families:

- **Vanitas Regular** for the name and headlines. Source file: `pictures-raw/Amanda Carvalho - ID VISUAL-20260909T171405Z-1-001 (1)/Amanda Carvalho - ID VISUAL/PALETA DE CORES E TIPOGRAFIA/Vanitas-Regular.otf`. A copy also sits in `fonts/`. Do not load this file on the site.
- **Poppins Regular** for labels such as "Odontologia estética" and for body text. Load Poppins from Google Fonts.

On the page, headlines use **Cormorant Garamond** (Google Fonts, weight 500). It is the stand-in for Vanitas because a self-hosted custom font is not the default for this site. Only swap a typeface for another font that is available online, such as Google Fonts.

The header uses the official transparent logo at `logo.png`, cropped from `Logo FUNDO TRANSPARENTE-06.png`. It is the blue lockup: script A, “Amanda Carvalho”, and “ODONTOLOGIA ESTÉTICA | CRO SP 136481”. Do not swap it for a plain “AG” circle or redraw the monogram. The registration on the logo is CRO SP 136481. Keep that value in the `CONTATO` block.

## Voice and page

Brazilian Portuguese. The practice name on the page is Dra. Amanda Guimarães Carvalho. The short brand name is Amanda Carvalho.

WhatsApp is the main action. Instagram is secondary. Edit only the `CONTATO` block in `index.html` for the number, Instagram handle, CRO, and city. Leave CRO and city empty rather than inventing them.

Do not add claims about results, prices, or years of practice that are not in the source material.
