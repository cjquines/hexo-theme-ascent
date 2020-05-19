# Ascent

An opinionated Hexo theme for blogs with long blocks of text. [Demo.](https://cjquines.github.io/hexo-theme-ascent/)

[![](sample.png)](https://cjquines.github.io/hexo-theme-ascent/)

It's best suited for blogs with a lot of longform writing, and it's designed to give the reader as smooth of a reading experience as possible. I wrote Ascent because it seemed that none of the Hexo themes available had this aim; unlike most Hexo themes, the focus of Ascent is to make posts that read like magazine articles or newspaper features.

Read more about Ascent design [on the demo](https://cjquines.github.io/hexo-theme-ascent/2020/05/18/Ascent/). See how Ascent formats Markdown [on the demo](https://cjquines.github.io/hexo-theme-ascent/2020/05/18/Demo/).

## Installation

```bash
npm install -g hexo-cli
hexo init <site>
cd <site>
git clone https://github.com/cjquines/hexo-theme-ascent themes/ascent
```

Then set your `theme` in `_config.yml` to `ascent`.

## Configuration

Here's what can be changed in `themes/ascent/_config.yml`:

* `menu`. Header links can be customized by adding more keys inside `menu`:

```yaml
menu:
  Home: /
  Archives: /archives
  Github: https://github.com/cjquines
```

* `rss`. Link to the generated RSS. You need to have `hexo-generator-feed` installed, which you can do with `npm install hexo-generator-feed`.

* `excerpt_link`. The text of the "read more" link in the home page.

* `favicon`. Path to the favicon.

* `settings`. Toggles whether the settings (sans-serif/serif, light/dark) appear in the lower-right corner of the screen.

* `highlight`. Toggles whether code blocks are styled. Changing this to `false` improves performance by a little bit.

* `word_count`. Toggles whether word counts appear before a post, and in the archives. You need to have `hexo-wordount` installed, which you can do with `npm install hexo-wordcount`.

* `google_analytics`. The `enable` key toggles whether Google Analytics is turned on. Replace `UA-000000000-0` with your Google Analytics tracking ID, which you can find in the Google Analytics code.

* `intensedebate`. The `enable` key toggles whether IntenseDebate comments are turned on. Replace `00000000000000000000000000000000` with the IntenseDebate site account, which you can find in Settings > Account > Site Key.
