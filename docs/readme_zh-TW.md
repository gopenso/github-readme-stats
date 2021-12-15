<p align="center">
 <img width="100px" src="https://res.cloudinary.com/anuraghazra/image/upload/v1594908242/logo_ccswme.svg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">GitHub Readme Stats</h2>
 <p align="center">在 README 文件中加入動態產生的 Github 統計卡片！</p>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

  <p align="center">
    <a href="#demo">看 Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Bug 回報</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">功能許願</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    .
    <a href="/docs/readme_zh-TW.md">繁體中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>
<p align="center">喜歡這個專案嗎？考慮 <a href="https://www.paypal.me/anuraghazra">捐款</a> 來讓這個專案變更好吧！


<p>
<a href="https://indiafightscorona.giveindia.org">
<img src="https://d2wvdrxmr8p0wf.cloudfront.net/static/giveindia.svg" alt="Give india logo" width="200" />
</a>

Are you considering to support the project by donating to me? Please DON'T!!  

Instead, Help India fight 2nd deadly wave of COVID,  
Thousands of people are dying in India for lack of Oxygen & COVID related necessary infrastructure.  

Visit [https://indiafightscorona.giveindia.org](https://indiafightscorona.giveindia.org) and make a small donation to help us fight covid and overcome this crisis.   
Your small help goes a long way. :heart:
</p>


# 特點

- [GitHub 統計卡片](#GitHub-統計卡片)
- [更多 github 釘選](#更多-github-釘選)
- [熱門語言統計卡](#熱門語言統計卡)
- [Wakatime 一周統計卡片](#Wakatime-一周統計卡片)
- [主題](#主題)
- [自定義](#自定義)
  - [常用選項](#常用選項)
  - [統計卡的相關選項](#統計卡的相關選項)
  - [Repo 卡的相關選項](#Repo-卡的相關選項)
  - [語言卡的相關選項](#語言卡的相關選項)
  - [Wakatime 卡的相關選項](#Wakatime-卡的相關選項)
- [自己部署伺服器](#自己部署伺服器)

# GitHub 統計卡片

只要將這段文字複製進你的 markdown 內容中，就完成了，就是這麼簡單！

將 `?username=` 的值換成你的 Github 用戶名稱。

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

_注：共有 S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone) 這幾個等級。
值是 用 [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) 用 commits、contributions、issues、stars、pull requests、followers，還有 擁有的 repositories 計算出的。
實際實作方法詳見 [src/calculateRank.js](./src/calculateRank.js)_

### 隱藏個別統計數據

要隱藏任何特定的統計數據，你可以加入篩選參數 `?hide=` 加上用半形逗號`,`隔開的值。

> 選項：`&hide=stars,commits,prs,issues,contribs`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,prs)
```

### 將私人專案的貢獻計數加到 commits 總計

你可以加入你所有的私人貢獻計數加入 commits 總計，加入參數 `?count_private=true`。

_Note: 如果你是自行部署這個專案的伺服器，那預設會加入私人貢獻計數，否則你就需要選擇分享你的私人貢獻計數。_

> 選項：`&count_private=true`

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true)
```

### 顯示 icons

要顯示 icons ，你可以在參數中加入 `show_icons=true` ，就像這樣：

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true)
```

### 主題

你可以通過現有的主題來自訂你的卡片，可以省去 [自己更改參數](#customization)的麻煩。

用 `&theme=THEME_NAME` 參數來選擇主題，就像這樣：

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

#### 所有現有的主題：

dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, highcontrast, dracula

<img src="https://res.cloudinary.com/anuraghazra/image/upload/v1595174536/grs-themes_l4ynja.png" alt="GitHub Readme Stats Themes" width="600px"/>

你可以到 [全部現有主題](./themes/README.md) 看看主題預覽，或查看 [主題設定檔](./themes/index.js) ，如果你想要的話 **也可以貢獻個新的主題** :D

### 自定義

You can customize the appearance of your `Stats Card` or `Repo Card` however you wish with URL params.

你可以通過給 URL 參數的方式，來自定義你的`Stats Card` 或者是 `Repo Card` 樣式。

#### 常用選項：

- `title_color` - 卡片的標題文字顏色 _(hex color)_
- `text_color` - 內文的文字顏色 _(hex color)_
- `icon_color` - Icons 的顏色（如果可用） _(hex color)_
- `border_color` - 卡片的邊框顏色 _(hex color)_. （如果`hide_border`沒有開啟，則不會有效果）
- `bg_color` - 卡片背景顏色 _(hex color)_ **或** 用 _angle,start,end_ 表示漸層色
- `hide_border` - 隱藏卡片的邊框 _(boolean)_
- `theme` - 從 [全部現有主題](./themes/README.md) 中選擇的主題名稱
- `cache_seconds` - 手動設定 cache header _(min: 1800, max: 86400)_
- `locale` - 設定卡片語言 _(e.g. cn, de, es, etc.)_
- `border_radius` - 卡片加圓角

##### bg_color 的漸層設定

你可以設定bg_color用多個半形逗號`,`隔開的值來產生漸層，漸層格式：-

```
&bg_color=DEG,COLOR1,COLOR2,COLOR3...COLOR10
```

> cache的注意事項：Repo 卡片的預設 cache 是 4 小時 (14400 秒) 如果 fork 數和 star 數少於1千的話，是 2 小時 (7200 秒)。還有，cache 被限制在最小 2 小時，最大 24 小時。

#### 統計卡的相關選項：

- `hide` - 個別統計數據 _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `hide_rank` - _(boolean)_ 隱藏等級，然後會自動調整卡片寬度。
- `show_icons` - _(boolean)_
- `include_all_commits` - 計算完整的 commits 總數，而不是只有當年的 commits _(boolean)_
- `count_private` - 計算私人專案的 commits _(boolean)_
- `line_height` - 設定文字行距 _(number)_
- `custom_title` - 自訂卡片標題
- `disable_animations` - 關閉所有卡片動畫 _(boolean)_

#### Repo 卡的相關選項：

- `show_owner` - 顯示 repo 的擁有者名稱 _(boolean)_

#### 語言卡的相關選項：

- `hide` - 卡片中隱藏特定語言 _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `layout` - 有兩種排列方式可以選擇， `default` 跟 `compact`
- `card_width` - 手動設定卡片的寬度 _(number)_
- `langs_count` - 在卡片上顯示更多語言，可選擇1-10，預設是5。 _(number)_
- `exclude_repo` - 排除特定的 repositories _(Comma-separated values)_
- `custom_title` - 自訂卡片標題

> :warning: **重要事項：**
> 語言名稱要按照 [百分號編碼 Percent Encoding](https://en.wikipedia.org/wiki/Percent-encoding) 指定的，語言名稱應使用 uri 轉譯。
> (例： `c++` 應該要轉成 `c%2B%2B`， `jupyter notebook` 要轉成 `jupyter%20notebook`，以此類推) 你可以用
> [urlencoder.org](https://www.urlencoder.org/) 來幫你自動轉。

#### Wakatime 卡的相關選項：

- `hide` - 卡片中隱藏特定語言 _(Comma-separated values)_
- `hide_title` - _(boolean)_
- `line_height` - 設定文字行距 _(number)_
- `hide_progress` - 隱藏進度列和百分比 _(boolean)_
- `custom_title` - 自訂卡片標題
- `layout` - 有兩種排列方式可以選擇， `default` 跟 `compact`
- `langs_count` - 限制要顯示在卡片上的最高語言數，預設是回報的所有語言。
- `api_domain` - 自訂卡片的 API domain ，例如要用 [Hakatime](https://github.com/mujx/hakatime) 或 [Wakapi](https://github.com/muety/wakapi) 服務。
- `range` – 自訂 WakaTime Request 的時間範圍，例如 `last_7_days`。看 [WakaTime API docs](https://wakatime.com/developers#stats) 了解可以用的選項。

---

# 更多 github 釘選

GitHub extra pins allow you to pin more than 6 repositories in your profile using a GitHub readme profile.

Yay! You are no longer limited to 6 pinned repositories.

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/pin?username=anuraghazra&repo=github-readme-stats`

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)

Use [show_owner](#customization) variable to include the repo's owner username

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats&show_owner=true)](https://github.com/anuraghazra/github-readme-stats)

# 熱門語言統計卡

The top languages card show a GitHub user's most frequently used top language.

_NOTE: Top Languages does not indicate my skill level or anything like that, it's a GitHub metric of which languages have the most code on GitHub. It's a new feature of github-readme-stats._

### Usage

Copy-paste this code into your readme and change the links.

Endpoint: `api/top-langs?username=anuraghazra`

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

### Exclude individual repositories

You can use `?exclude_repo=repo1,repo2` parameter to exclude individual repositories.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&exclude_repo=github-readme-stats,anuraghazra.github.io)](https://github.com/anuraghazra/github-readme-stats)
```

### Hide individual languages

You can use `?hide=language1,language2` parameter to hide individual languages.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&hide=javascript,html)](https://github.com/anuraghazra/github-readme-stats)
```

### Show more languages

You can use the `&langs_count=` option to increase or decrease the number of languages shown on the card. Valid values are integers between 1 and 10 (inclusive), and the default is 5.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
```

### Compact Language Card Layout

You can use the `&layout=compact` option to change the card design.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

- Compact layout

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

# Wakatime 一周統計卡片

Change the `?username=` value to your [Wakatime](https://wakatime.com) username.

```md
[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)
```

### Demo

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&hide_progress=true)](https://github.com/anuraghazra/github-readme-stats)

- Compact layout

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

---

### All Demos

- Default

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)

- Hiding specific stats

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=contribs,issues)

- Showing icons

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&hide=issues&show_icons=true)

- Customize Border Color

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&border_color=2e4058)

- Include All Commits

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&include_all_commits=true)

- Themes

Choose from any of the [default themes](#themes)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)

- Gradient

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

- Customizing stats card

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)

- Setting card locale

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api/?username=anuraghazra&locale=es)

- Customizing repo card

![Customized Card](https://github-readme-stats.vercel.app/api/pin?username=anuraghazra&repo=github-readme-stats&title_color=fff&icon_color=f9f9f9&text_color=9f9f9f&bg_color=151515)

- Top languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)

- Wakatime card

[![willianrod's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=willianrod)](https://github.com/anuraghazra/github-readme-stats)

---

### Quick Tip (Align The Repo Cards)

You usually won't be able to layout the images side by side. To do that you can use this approach:

```html
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats" />
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=convoychat" />
</a>
```

## 自己部署伺服器

#### [Check Out Step By Step Video Tutorial By @codeSTACKr](https://youtu.be/n6d4KHSKqGk?t=107)

Since the GitHub API only allows 5k requests per hour, my `https://github-readme-stats.vercel.app/api` could possibly hit the rate limiter. If you host it on your own Vercel server, then you don't have to worry about anything. Click on the deploy button to get started!

NOTE: Since [#58](https://github.com/anuraghazra/github-readme-stats/pull/58) we should be able to handle more than 5k requests and have no issues with downtime :D

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/anuraghazra/github-readme-stats)

<details>
 <summary><b> Guide on setting up Vercel  🔨 </b></summary>

1. Go to [vercel.com](https://vercel.com/)
1. Click on `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. Sign in with GitHub by pressing `Continue with GitHub`
   ![](https://files.catbox.moe/btd78j.jpeg)
1. Sign into GitHub and allow access to all repositories, if prompted
1. Fork this repo
1. After forking the repo, open the [`vercel.json`](https://github.com/anuraghazra/github-readme-stats/blob/master/vercel.json#L5) file and change the `maxDuration` field to `10`
1. Go back to your [Vercel dashboard](https://vercel.com/dashboard)
1. Select `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. Select `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. Select root and keep everything as is, just add your environment variable named PAT_1 (as shown), which will contain a personal access token (PAT), which you can easily create [here](https://github.com/settings/tokens/new) (leave everything as is, just name it something, it can be anything you want)
   ![](https://files.catbox.moe/0ez4g7.png)
1. Click deploy, and you're good to go. See your domains to use the API!

</details>

## :sparkling_heart: Support the project

I open-source almost everything I can, and I try to reply to everyone needing help using these projects. Obviously,
this takes time. You can use this service for free.

However, if you are using this project and are happy with it or just want to encourage me to continue creating stuff, there are few ways you can do it :-

- Giving proper credit when you use github-readme-stats on your readme, linking back to it :D
- Starring and sharing the project :rocket:
- [![paypal.me/anuraghazra](https://ionicabizau.github.io/badges/paypal.svg)](https://www.paypal.me/anuraghazra) - You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:

Thanks! :heart:

---

[![https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss](./powered-by-vercel.svg)](https://vercel.com?utm_source=github_readme_stats_team&utm_campaign=oss)


Contributions are welcome! <3

Made with :heart: and JavaScript.
