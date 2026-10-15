# Whalesong Studio · 鲸歌工坊 — website

The project page of [Whalesong Studio](https://github.com/xuhao1/whalesong-studio) (鲸歌工坊), the long-form fiction plugin for DeepSeek Harness: one static page in two languages, served by GitHub Pages from the root of `main` at <https://whalesong.xuhao1.me> (`CNAME`).

- `index.html` — the page; Chinese and English side by side (`lang="zh"` / `lang="en"`), the language switch keeps the choice in `localStorage`; `?lang=en` or `?lang=zh` picks one.
- `style.css` — light theme, no web fonts, no scripts beyond the language switch.
- `img/` — the cover (drawn with GPT Image through Codex), the icon, `og.jpg` for link previews, the screenshots (`shots/en` is *Alice's Adventures in Wonderland* in the English interface, `shots/zh` is 《红楼梦》 in the Chinese one) and portraits drawn in the Studio (`people/`).

Preview locally: `python3 -m http.server` in this folder, then open <http://localhost:8000>.

The screenshots and pictures come from the plugin's repository (`docs/images/readme/`, and the Studio's own pictures of the two demonstration books). The books are in the public domain.
