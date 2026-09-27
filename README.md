# Kun Feng's Academic Homepage

Personal website: [kkzsocute.github.io](https://kkzsocute.github.io/)

A bilingual academic homepage built with HTML, CSS, and JavaScript, featuring English and Chinese content, light and dark themes, and paper figures that expand within the page. No dependencies or build step are required.

## Content and Structure

- `index.html`: Biography, news, publications, internships, education, academic service, teaching, and selected honors, together with language switching, theme switching, and figure dialogs.
- `assets/styles.css`: Responsive layouts, typography, colors, and component styles.
- `assets/portrait.jpg`: Resized portrait with original metadata removed.
- `assets/ant-group-logo.png`: Ant Group logo.
- `assets/shanghaitech-logo.svg` and `assets/njupt-logo.png`: Official university emblems, displayed at consistent sizes with their original proportions and colors. Light backgrounds preserve visibility in dark mode.
- `assets/arise-intro.svg`, `assets/kairosagent-intro.svg`, and `assets/kairos-method.png`: Publication figures.
- `assets/favicon.svg`: Site icon.

Bilingual text uses adjacent `lang-en` and `lang-zh` elements. Shared publication titles, author lists, dates, and links are maintained once. Chinese text is stored as numeric character references in HTML and Unicode escapes in JavaScript. Update both language versions and their accessibility labels when editing content.

The page defaults to English and the light theme. Language and theme preferences are saved locally in the browser. Without JavaScript, the English content and publication thumbnails remain available.

Publication figures open in a native `dialog` with the paper title and publication status. Figures retain their complete composition, original colors, and white backgrounds in both themes. The Kairos bitmap is proportionally resized; the ARISE and KairosAgent figures retain their SVG format.

## Asset Sources and Attribution

University emblems:

- [ShanghaiTech University official vector logo](https://www.shanghaitech.edu.cn/_upload/tpl/00/20/32/template32/images/logo_red.svg): `assets/shanghaitech-logo.svg`. The complete circular emblem is extracted from the horizontal logo, preserving its original paths and colors.
- [Nanjing University of Posts and Telecommunications identity page](https://www.njupt.edu.cn/17223/list.htm), [emblem image](https://www.njupt.edu.cn/_upload/article/images/d9/3b/6b08b1d0409daf144ae91e96a324/1f4508a5-9ffe-4154-9160-1d217db63d85.png): `assets/njupt-logo.png`. Original proportions, colors, and transparency are preserved.

Publication figures:

- [ARISE introduction figure](https://mldi.group/ARISE/static/images/intro.svg): `assets/arise-intro.svg`. Provided by the ARISE authors through the [project website](https://mldi.group/ARISE/) under its stated [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license. The original figure is unmodified.
- [Kairos architecture figure](https://foundation-model-research.github.io/Kairos/static/images/method.png): `assets/kairos-method.png`.
- [KairosAgent introduction figure](https://mldi.group/KairosAgent/static/images/intro.svg): `assets/kairosagent-intro.svg`.

Images remain the property of their respective owners. Any license for the site code does not extend to publication figures.
