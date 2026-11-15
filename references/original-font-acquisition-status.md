# Original font acquisition status (2026-11-15)

This index documents **original font sources**, not replacement fonts, and distinguishes legal use from permission to republish the font file in this public repository.

| Reference | Original source | Font file published here? | License assessment |
| --- | --- | --- | --- |
| Detstvo (Детство) | https://www.behance.net/asset/739825/Detstvo-font (Dasha Kuchnova, ZIP on Behance) | No | Free personal/commercial use advertised, but redistribution not established |
| Gossip (Deborah Khodanovich) | https://gossip.cargo.site/font ; https://type.lab.joshwel.co/fonts/gossip/ | Pending Actions import | SIL Open Font License 1.1; Latin only |
| Wayward (Katerina Volokitina) | https://teletype.in/@finegan/CNdtHOlAIyU | No | Free font advertised, permission to redistribute unconfirmed |
| Arial Narrow | https://learn.microsoft.com/en-us/typography/font-list/arial-narrow | No | Proprietary; cannot republish |
| Black Diamond (Set Sail Studios) | https://setsailstudios.com/downloads/blackdiamond/ | No | Paid $18; cannot republish |
| Gilroy (Radomir Tinkov) | https://www.myfonts.com/collections/gilroy-font-radomir-tinkov | No | Light + ExtraBold are free to use, but 2018 EULA prohibits distribution to third parties |
| Eskal (Font4You) | https://localfonts.eu/freefonts/handwritten-cyrillic-free-fonts/eskal/ | No | Free for personal use; redistribution permission unconfirmed |
| Balsara | Font name also appears in https://ooo-rakurs.ru/upload/iblock/ed4/ap5orji632uuuko3gory2u70v935nzoc.pdf | No | Original font package/redistribution license not established |
| Betro | Reference image only | No | Reliable original source not established |
| Шелест | Reference image only | No | Reliable original source not established |
| Stylization | Reference image only | No | May describe lettering technique instead of an actual font |

## Intended use: private project library

The owner needs these original fonts for their own websites, branding, design and visual works, **not** as a font download collection. However this repository is currently public. Do not commit restricted TTF/OTF binaries here. A private repository is preferable for licensed local font storage, but private storage does not override individual EULA rules about copying, team access, web embedding, or commercial usage. For a public-facing website, check a webfont license before uploading WOFF/WOFF2. For personal-use-only fonts, do not use them in commercial projects without an appropriate license.

For the original files **not permitted to be redistributed**, use the author's download link and install directly on the owner's device, rather than uploading binaries to this public GitHub repository. A published font file and an image specimen are different assets.

## Import automation

The workflow at `.github/workflows/import-gossip-fonts.yml` attempts to fetch the original Gossip archive on GitHub Actions and commits the font binaries **only if it finds a bundled OFL license**. A workflow file being committed does **not** prove that an import succeeded. Verify `imported/gossip/` for OTF/TTF files before reporting installation complete.
