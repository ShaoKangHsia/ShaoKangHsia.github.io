# Shao-Kang Hsia — Personal Website

An academic website based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template. Content was drafted from `CV.pdf` (dated November 20, 2026). The public CV is at `files/Shao-Kang_Hsia_CV.pdf`.

## GitHub Pages

This site is published from [ShaoKangHsia/ShaoKangHsia.github.io](https://github.com/ShaoKangHsia/ShaoKangHsia.github.io) on the `main` branch. The site URL is [https://shaokanghsia.github.io/](https://shaokanghsia.github.io/). The workflow at `.github/workflows/jekyll.yml` builds and deploys the site when `main` changes.

For later updates, push changes to `main` and check the **Actions** tab for `Deploy Academic Pages template site to Pages`. Under **Settings → Pages → Build and deployment**, set **Source** to **GitHub Actions**. GitHub's [publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) describe this setting.

## 修改內容

- `_pages/about.md`：首頁與聯絡資訊
- `_pages/research.md`：研究方向和專案
- `_pages/publications.md`：論文
- `_pages/teaching.md`：教學
- `_pages/cv.md`：網頁版履歷
- `_data/navigation.yml`：導覽列
- `_config.yml`：網站名稱、連結和側邊欄
- `images/sh-monogram.svg`：暫用的字母頭像，可換成新照片
- `files/Shao-Kang_Hsia_CV.pdf`：公開下載的 CV

上線前請核對公開的 CV PDF，特別是電子郵件、預期畢業時間、論文狀態和教學資訊。

若要在本機預覽，依照 [Academic Pages README](https://github.com/academicpages/academicpages.github.io#running-locally) 安裝 Ruby、Bundler 和 Node.js，執行 `bundle install`、`npm install`、`npm run build:js`，再執行 `bundle exec jekyll serve`。瀏覽 `http://localhost:4000`。

The original template is MIT licensed; see [LICENSE](LICENSE).
