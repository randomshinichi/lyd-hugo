This is a Hugo single page landing site.

docs/hugo.txt includes basic knowledge of how to do things in Hugo.

themes/hugo-scroll is the theme, and I have copied themes/hugo-scroll/exampleSite/content into content/ to start with. This theme is for landing pages, and supports i18n, and the exampleSite content explains how to setup localization.

This is a dual language site - content/en and content/zh-tw (Traditional Chinese). Each section should have its equivalent in both languages.

- Theme is still `hugo-scroll`; hero/headline set via `content/en/_index.md` and multilingual mirrors in `content/zh-tw/`.
- Homepage sections live in `content/<lang>/homepage/` with weights controlling order; new sections include `Contact & Booking`/`聯絡與報名` and `Community Links`/`社群連結`.
- Traditional Chinese copy should stay in `content/zh-tw/`; English translations belong in `content/en/`.

Refer to themes/hugo-scroll/exampleSite for how to use the features in this theme.