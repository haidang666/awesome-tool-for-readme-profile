# Things you can add to your GitHub profile README

Cards, badges, feeds and GitHub Actions you can drop into your [GitHub profile README](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme), each with a live demo.

Every entry is tagged by how it runs:

- `Hosted API`: you paste an image URL and someone else's server renders it. Easiest to set up, but these are the entries that break when a free host shuts down.
- `GitHub Action`: a workflow in your profile repo generates the image or text on a schedule. More setup, but it doesn't depend on someone else's server staying up.
- `Self-host`: you deploy your own copy, usually to Vercel.
- `Website`: a site you visit, not something you embed.

## Contents

- [Stats and metrics](#stats-and-metrics)
- [Activity feeds](#activity-feeds)
- [Music](#music)
- [Headers and decoration](#headers-and-decoration)
- [Badges and counters](#badges-and-counters)
- [Fun](#fun)
- [Generators and related tools](#generators-and-related-tools)
- [Contributing](#contributing)

## Stats and metrics

### [profile-summary-cards](https://github.com/vn7n24fzkq/github-profile-summary-cards) - [vn7n24fzkq](https://github.com/vn7n24fzkq/)
`GitHub Action` Summary cards for your profile details, top languages, commit times and more.

[![Profile details card](https://raw.githubusercontent.com/vn7n24fzkq/github-profile-summary-cards-example/master/profile-summary-card-output/default/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)  
![Productive time card](https://raw.githubusercontent.com/vn7n24fzkq/vn7n24fzkq/master/profile-summary-card-output/solarized/4-productive-time.svg)

### [All GitHub metrics](https://github.com/lowlighter/metrics) - [lowlighter](https://github.com/lowlighter)
`GitHub Action` An infographics generator with 30+ plugins and 300+ options to display stats about your account or organization.

<table>
  <tr>
    <th align="center">For user accounts</th>
    <th align="center">For organization accounts</th>
  </tr>
  <tr>
    <td align="center">
      <img alt="metrics for a user account" width="400" src="https://raw.githubusercontent.com/lowlighter/metrics/examples/metrics.classic.svg">
    </td>
    <td align="center">
      <img alt="metrics for an organization account" width="400" src="https://raw.githubusercontent.com/lowlighter/metrics/examples/metrics.organization.svg">
    </td>
  </tr>
</table>

### [GitHub Stats Visualization](https://github.com/jstrieb/github-stats) - [jstrieb](https://github.com/jstrieb)
`GitHub Action` Overview and language cards that can include stats from your private repos.

[![GitHub stats overview](https://raw.githubusercontent.com/jstrieb/github-stats/generated/overview.svg)](https://github.com/jstrieb/github-stats)
[![GitHub stats languages](https://raw.githubusercontent.com/jstrieb/github-stats/generated/languages.svg)](https://github.com/jstrieb/github-stats)

### [GitHub Stats Extended](https://github.com/stats-organization/github-stats-extended) - [stats-organization](https://github.com/stats-organization)
`Hosted API` The maintained successor to [github-readme-stats](https://github.com/anuraghazra/github-readme-stats): stats, top languages, WakaTime and other cards, with themes.

> [!IMPORTANT]
> [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) is no longer maintained, and its public instance at `github-readme-stats.vercel.app` is best-effort. Its README now points to GitHub Stats Extended. To migrate, change the domain to `github-stats-extended.vercel.app`. If you don't want to depend on a public instance at all, use [github-readme-stats-action](https://github.com/stats-organization/github-readme-stats-action).

[![Anurag's GitHub stats](https://github-stats-extended.vercel.app/api?username=anuraghazra)](https://github.com/stats-organization/github-stats-extended)

### [gh-stats](https://github.com/ShayManor/github-readme-stats) - [ShayManor](https://github.com/ShayManor/)
`Hosted API` Configurable README widgets for your GitHub stats.

[![gh-stats card](https://gh-stats.com/?username=ShayManor)](https://github.com/ShayManor/github-readme-stats)

### [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats) - [DenverCoder1](https://github.com/DenverCoder1/)
`Hosted API` Your total contributions, current streak and longest streak.

[![GitHub Streak](https://streak-stats.demolab.com/?user=DenverCoder1&theme=dark)](https://github.com/DenverCoder1/github-readme-streak-stats)

### [Profile trophy](https://github.com/ryo-ma/github-profile-trophy) - [ryo-ma](https://github.com/ryo-ma/)
`Hosted API` `Self-host` Trophies for your GitHub stats.

> [!WARNING]
> The maintainer warns that the public instance may shut down because of hosting costs, and it was returning HTTP 402 when this list was last checked (November 2026). Self-hosting (fork it and deploy to Vercel) is recommended. The upstream README also lists volunteer mirrors.

[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)

### [Wakatime Weekly Metrics](https://github.com/athul/waka-readme) - [athul](https://github.com/athul/)
`GitHub Action` Your weekly WakaTime coding stats as a text block in your README.

![preview](https://user-images.githubusercontent.com/8397274/87243943-e6b45c00-c457-11ea-94c9-2aa0bf241be8.png)

### [Wakatime-stats](https://github.com/anmol098/waka-readme-stats) - [anmol098](https://github.com/anmol098)
`GitHub Action` Dev metrics from WakaTime and GitHub: when you code, languages, editors, projects and more.

![preview](https://user-images.githubusercontent.com/25841814/79395484-5081ae80-7fac-11ea-9e27-ac91472e31dd.png)

### [GitHub README Insight Terminal ASCII](https://github.com/seuthootDev/github-readme-insight-terminal-ascii) - [seuthootDev](https://github.com/seuthootDev/)
`Hosted API` Your contribution graph as a terminal-style ASCII SVG.

[![Contribution graph](https://github-readme-insight-terminal-asci.vercel.app/svg?user=seuthootDev&theme=mac&scale=0.6)](https://github.com/seuthootDev/github-readme-insight-terminal-ascii)

### [Repository Star History Graph](https://github.com/lucabubi/star-history) - [luca](https://github.com/lucabubi)
`Hosted API` A star history chart for any repository.

> [!WARNING]
> The hosted endpoint (`api.lucabubi.me`) didn't resolve when this list was last checked (November 2026).

![star-history](https://api.lucabubi.me/chart?username=mdn&repository=js-examples&color=violet)

### [Stackoverflow badge](https://github.com/omidnikrah/github-readme-stackoverflow) - [omidnikrah](https://github.com/omidnikrah/)
`Hosted API` Your Stack Overflow reputation and badges as a card.

![Omid Nikrah StackOverflow](https://github-readme-stackoverflow.vercel.app/?userID=6558042)

### [Stack Overflow flair](https://stackoverflow.com/users/flair)
`Hosted API` Stack Exchange's own profile flair image. [More about flair](https://stackoverflow.blog/2010/09/23/flair-now-even-flairier/).

<a href="https://stackexchange.com/users/7551592"><img src="https://stackexchange.com/users/flair/7551592.png" width="208" height="58" alt="profile for Felix on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for Felix on Stack Exchange, a network of free, community-driven Q&amp;A sites"></a>

## Activity feeds

### [Blog post workflow](https://github.com/gautamkrishnar/blog-post-workflow) - [gautamkrishnar](https://github.com/gautamkrishnar/)
`GitHub Action` Your latest blog posts from any RSS feed, plus Stack Overflow activity or YouTube videos.

![preview](https://user-images.githubusercontent.com/8397274/88047382-29b8b280-cb6f-11ea-9efb-2af2b10f3e0c.png)

### [Medium](https://github.com/bxcodec/github-readme-medium-recent-article) - [bxcodec](https://github.com/bxcodec/)
`Hosted API` Your most recent Medium articles as cards.

<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@imantumorang/2"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@imantumorang/2" alt="Recent Article 2"></a>
<a target="_blank" href="https://github-readme-medium-recent-article.vercel.app/medium/@imantumorang/0"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@imantumorang/0" alt="Recent Article 0"></a>

### [readme-scribe](https://github.com/muesli/readme-scribe) - [muesli](https://github.com/muesli)
`GitHub Action` Fills a [markscribe](https://github.com/muesli/markscribe) template with your recent work, releases, sponsors, followers or blog posts. [crazy-max's profile](https://github.com/crazy-max) is a live example built with markscribe.

<img src="https://raw.githubusercontent.com/muesli/readme-scribe/master/assets/template_example.png" width="600" alt="readme-scribe example output">

### [YouTube Cards](https://github.com/DenverCoder1/github-readme-youtube-cards) - [DenverCoder1](https://github.com/DenverCoder1)
`GitHub Action` Your latest YouTube videos as cards that update automatically.

<a href="https://www.youtube.com/watch?v=1lXaKEy97qE">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ytcards.demolab.com/?id=1lXaKEy97qE&title=GitHub+Star+Swag+Unboxing+and+Giveaways&lang=en&timestamp=1696868769&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=250&border_radius=5&duration=172">
    <img src="https://ytcards.demolab.com/?id=1lXaKEy97qE&title=GitHub+Star+Swag+Unboxing+and+Giveaways&lang=en&timestamp=1696868769&background_color=%23ffffff&title_color=%2324292f&stats_color=%2357606a&max_title_lines=2&width=250&border_radius=5&duration=172" alt="GitHub Star Swag Unboxing and Giveaways" title="GitHub Star Swag Unboxing and Giveaways">
  </picture>
</a>
<a href="https://www.youtube.com/watch?v=maoXtlb8t44">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ytcards.demolab.com/?id=maoXtlb8t44&title=How+To+Self-Host+GitHub+Readme+Streak+Stats+on+Vercel&lang=en&timestamp=1693523015&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=250&border_radius=5&duration=257">
    <img src="https://ytcards.demolab.com/?id=maoXtlb8t44&title=How+To+Self-Host+GitHub+Readme+Streak+Stats+on+Vercel&lang=en&timestamp=1693523015&background_color=%23ffffff&title_color=%2324292f&stats_color=%2357606a&max_title_lines=2&width=250&border_radius=5&duration=257" alt="How To Self-Host GitHub Readme Streak Stats on Vercel" title="How To Self-Host GitHub Readme Streak Stats on Vercel">
  </picture>
</a>
<a href="https://www.youtube.com/watch?v=6u9BrDaSHJc">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ytcards.demolab.com/?id=6u9BrDaSHJc&title=Automatically+Deploy+to+Fly.io+with+GitHub+Actions&lang=en&timestamp=1661864404&background_color=%230d1117&title_color=%23ffffff&stats_color=%23dedede&max_title_lines=2&width=250&border_radius=5&duration=312">
    <img src="https://ytcards.demolab.com/?id=6u9BrDaSHJc&title=Automatically+Deploy+to+Fly.io+with+GitHub+Actions&lang=en&timestamp=1661864404&background_color=%23ffffff&title_color=%2324292f&stats_color=%2357606a&max_title_lines=2&width=250&border_radius=5&duration=312" alt="Automatically Deploy to Fly.io with GitHub Actions" title="Automatically Deploy to Fly.io with GitHub Actions">
  </picture>
</a>

### [Readme X Cards](https://github.com/seuthootDev/readme-x-cards) - [seuthootDev](https://github.com/seuthootDev/)
`Hosted API` Your X (Twitter) profile or a post as a card.

[![X profile card](https://readme-x-cards.vercel.app/api/profile?user=Seuthoot&theme=aurora)](https://github.com/seuthootDev/readme-x-cards)

### [GitHub Readme Testimonials](https://github.com/smashah/github-readme-testimonials) - [smashah](https://github.com/smashah/)
`Hosted API` Quote GitHub comments that praise your work as testimonial cards.

<div align="center">
  <img src="https://github-readme-testimonials.vercel.app/api?comments=WwogICAgICAnaHR0cHM6Ly9naXRodWIuY29tL29wZW4td2Evd2EtYXV0b21hdGUtbm9kZWpzL2lzc3Vlcy83NDcjaXNzdWVjb21tZW50LTY4MjExNjE3MScsCiAgICAgICJodHRwczovL2dpdGh1Yi5jb20vb3Blbi13YS93YS1hdXRvbWF0ZS1ub2RlanMvaXNzdWVzLzMyNSNpc3N1ZWNvbW1lbnQtNjE0NzQ3NDA5IiwKICAgICAgImh0dHBzOi8vZ2l0aHViLmNvbS9vcGVuLXdhL3dhLWF1dG9tYXRlLW5vZGVqcy9pc3N1ZXMvMjk3I2lzc3VlY29tbWVudC02MTIxODM4NDkiLAogICAgICAiaHR0cHM6Ly9naXRodWIuY29tL29wZW4td2Evd2EtYXV0b21hdGUtbm9kZWpzL2lzc3Vlcy8zMDQjaXNzdWVjb21tZW50LTYxMjk3NTAwMyIsCiAgICAgICJodHRwczovL2dpdGh1Yi5jb20vb3Blbi13YS93YS1hdXRvbWF0ZS1ub2RlanMvaXNzdWVzLzk4I2lzc3VlY29tbWVudC01ODMyMzcxMTUiLAogICAgICAiaHR0cHM6Ly9naXRodWIuY29tL29wZW4td2Evd2EtYXV0b21hdGUtbm9kZWpzL2lzc3Vlcy80MDcjaXNzdWVjb21tZW50LTYyNTA1MjMwNCIsCiAgICAgICJodHRwczovL2dpdGh1Yi5jb20vb3Blbi13YS93YS1hdXRvbWF0ZS1ub2RlanMvaXNzdWVzLzI3NyNpc3N1ZWNvbW1lbnQtNjA5NTM4NzI0IiwKICAgICAgImh0dHBzOi8vZ2l0aHViLmNvbS9vcGVuLXdhL3dhLWF1dG9tYXRlLW5vZGVqcy9pc3N1ZXMvMjYxI2lzc3VlY29tbWVudC02MDk0MDM0MDQiLAogICAgICAiaHR0cHM6Ly9naXRodWIuY29tL29wZW4td2Evd2EtYXV0b21hdGUtbm9kZWpzL2lzc3Vlcy8yNjAjaXNzdWVjb21tZW50LTYwOTU1MDA2NyIsCiAgICAgICJodHRwczovL2dpdGh1Yi5jb20vb3Blbi13YS93YS1hdXRvbWF0ZS1ub2RlanMvaXNzdWVzLzgyI2lzc3VlY29tbWVudC01ODYxMzY5OTIiCiAgICBd"/>
</div>

## Music

### [Show your Spotify activity](https://github.com/magic-ike/spotify-data-card) - [magic-ike](https://github.com/magic-ike/)
`Hosted API` A card with your Spotify listening data. Log in on the project's website to generate it.

![preview](https://raw.githubusercontent.com/magic-ike/spotify-data-card/master/docs/basic.svg)

### [Show your Spotify playing](https://github.com/kittinan/spotify-github-profile) - [kittinan](https://github.com/kittinan/)
`Hosted API` `Self-host` The song you're playing on Spotify right now.

![review](https://raw.githubusercontent.com/kittinan/spotify-github-profile/716a50d2d70dc32f034d30c3e544141a4f1ddec0/img/example.svg)

### [Music playing](https://github.com/natemoo-re/natemoo-re) - [natemoo-re](https://github.com/natemoo-re/)
`Self-host` A Spotify now-playing card served from Nate Moore's own profile repo. Fork it and deploy your own copy to Vercel.

| Now Playing                                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------------------- |
| <a href="https://status.nmoo.dev/api/now-playing?open"><img src="https://status.nmoo.dev/api/now-playing" width="540" height="64"></a> |

## Headers and decoration

### [Capsule render](https://github.com/kyechan99/capsule-render) - [kyechan99](https://github.com/kyechan99)
`Hosted API` Animated header and footer banners with your own text.

![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=300&section=header&text=capsule%20render&fontSize=90&animation=fadeIn&fontAlignY=38&desc=Decorate%20GitHub%20Profile%20or%20any%20Repo%20like%20me!&descAlignY=51&descAlign=62)

### [Cardivo card name](https://github.com/satyawikananda/cardivo) - [satyawikananda](https://github.com/satyawikananda/)
`Hosted API` A business-card style intro with your name, a short bio and social links.

![Satya wikananda's card name](https://cardivo.vercel.app/api?name=Satya%20Wikananda&description=Hi,%20i%27m%20a%20front%20end%20web%20developer%20and%20i%27m%2019%20y.o.%20Nice%20to%20meet%20you%20%F0%9F%91%8B&image=https://pbs.twimg.com/profile_images/1295263306731536385/lSqa7QG7_400x400.jpg&backgroundColor=%23ecf0f1&instagram=satyawikananda&linkedin=I%20Gusti%20Ngurah%20Satya%20%20Wikananda&github=satyawikananda&twitter=satya_wikananda&pattern=leaf&colorPattern=%23eaeaea)

### [profile_stack](https://github.com/gleich/profile_stack) - [gleich](https://github.com/gleich/)
`GitHub Action` A table of the technologies you use and the projects that use them.

| 💻 **Technology**                                                                                                                     | 🚀 **Projects**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [![Dart](https://img.shields.io/static/v1?label=&message=Dart&color=52C0F2&logo=dart&logoColor=white)](https://dart.dev/)             | [![import_sorter](https://img.shields.io/static/v1?label=&message=import_sorter&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/fluttercommunity/import_sorter) [![Personal-Site](https://img.shields.io/static/v1?label=&message=Personal-Site&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/gleich/beta-website) [![auralite-mobile](https://img.shields.io/static/v1?label=&message=auralite-mobile%20%28WIP%29&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/gleich/auralite-mobile) |
| [![Flutter](https://img.shields.io/static/v1?label=&message=Flutter&color=52C0F2&logo=flutter&logoColor=white)](https://flutter.dev/) | [![Personal-Site](https://img.shields.io/static/v1?label=&message=Personal-Site&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/gleich/beta-website) [![auralite-mobile](https://img.shields.io/static/v1?label=&message=auralite-mobile%20%28WIP%29&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/gleich/auralite-mobile)                                                                                                                                                                                                 |

## Badges and counters

### [Profile views counter](https://github.com/antonkomarev/github-profile-views-counter) - [antonkomarev](https://github.com/antonkomarev/)
`Hosted API` Counts how many times your profile has been viewed.

![Profile views](https://komarev.com/ghpvc/?username=haidang666&color=blue)

### [Badge generator](https://github.com/badges/shields) - [Shields.io](https://shields.io/)
`Hosted API` Badges for almost anything, in several styles.

![badge](https://shields.io/badge/style-plastic-green?logo=appveyor&style=plastic) ![badge](https://img.shields.io/badge/rating-%E2%98%85%E2%98%85%E2%98%85%E2%98%85%E2%98%85-brightgreen)     
![badge](https://shields.io/badge/-yellowgreen-yellowgreen) ![badge](https://shields.io/badge/-orange-orange) ![badge](https://shields.io/badge/-blueviolet-blueviolet)

### [Markdown badge list from shields.io](https://github.com/Ileriayo/markdown-badges) - [Ileriayo](https://github.com/Ileriayo)
`Hosted API` A large collection of ready-made Shields.io badges for languages, tools and social links, ready to copy.

<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />  <img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />  <img alt="Udemy" src="https://img.shields.io/badge/Udemy%20-%23EA5252.svg?&style=for-the-badge&logo=Udemy&logoColor=white"/>  <img alt="Jest" src="https://img.shields.io/badge/-jest-%23C21325?&style=for-the-badge&logo=jest&logoColor=white"/>

### [terminal-shields](https://github.com/seuthootDev/terminal-shields) - [seuthootDev](https://github.com/seuthootDev/)
`Hosted API` A terminal-style alternative to Shields.io badges.

![build](https://terminal-shields.vercel.app/badge/build-passing-brightgreen)
![qt](https://terminal-shields.vercel.app/badge/qml-41CD52?logo=qt&theme=amber)
![stars](https://terminal-shields.vercel.app/github/stars/seuthootDev/terminal-shields)

### [My Badges](https://github.com/my-badges/my-badges) - [antonmedv](https://github.com/antonmedv)
`GitHub Action` Achievement badges (commit hashes, stars and more) that update daily.

> [!WARNING]
> The upstream repository is archived and no longer maintained.

<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/abc-commit/a-commit.png?raw=true" alt="One of my commit sha starts with &quot;a&quot;." title="One of my commit sha starts with &quot;a&quot;." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/abc-commit/ab-commit.png?raw=true" alt="One of my commit sha starts with &quot;ab&quot;." title="One of my commit sha starts with &quot;ab&quot;." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/stars/stars-100.png?raw=true" alt="I collected 100 stars." title="I collected 100 stars." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/stars/stars-500.png?raw=true" alt="I collected 500 stars." title="I collected 500 stars." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/stars/stars-1000.png?raw=true" alt="I collected 1000 stars." title="I collected 1000 stars." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/stars/stars-2000.png?raw=true" alt="I collected 2000 stars." title="I collected 2000 stars." width="64"></a>
<a href="https://github.com/my-badges/my-badges"><img src="https://github.com/my-badges/my-badges/blob/master/src/all-badges/stars/stars-5000.png?raw=true" alt="I collected 5000 stars." title="I collected 5000 stars." width="64"></a>

### [Show npm packages downloads](https://github.com/dhruvjainin/github-readme-npm-downloads) - [dhruvjainin](https://github.com/dhruvjainin/)
`GitHub Action` Total downloads of your npm packages as a badge.

> [!WARNING]
> The upstream repository (formerly `maddhruv/github-readme-npm-downloads`) is archived and no longer maintained.

![NPM Stats](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdhruvjainin%2Fgithub-readme-npm-downloads%2Fmaster%2Fstats.json)

### [Get gist count](https://github.com/lifeparticle/Gist-Count) - [lifeparticle](https://github.com/lifeparticle/)
`Hosted API` Your number of public gists as a badge.

[![Github gists](https://gist-count.vercel.app/api?username=lifeparticle)](https://gist.github.com/lifeparticle)

## Fun

### [Snake game from github user contributions graph](https://github.com/Platane/snk) - [Platane](https://github.com/Platane/)
`GitHub Action` A snake that eats your contribution graph, as an animated SVG or GIF.

![preview](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.gif)

### [Git Ship](https://github.com/PingPongPlus/git-ship) - [PingPongPlus](https://github.com/PingPongPlus/)
`GitHub Action` Turn your commits into animated pixel-art ships that automatically update in your profile README.

<a href="https://github.com/PingPongPlus/git-ship">
  <img src="https://raw.githubusercontent.com/PingPongPlus/git-ship/ecaa7c29f691c6952a870446f52b36ada00fc374/examples/huge-demo/git-ship.gif" width="800" height="320" alt="Git Ship demo with language logos and rain">
</a>

### [Readme Jokes](https://github.com/ABSphreak/readme-jokes) - [ABSphreak](https://github.com/ABSphreak)
`Hosted API` A random programming joke.

<img src="https://readme-jokes.vercel.app/api" alt="Jokes Card" />

### [Dynamic quote generator for your GitHub readmes](https://github.com/zhravan/github-readme-quotes) - [zhravan](https://github.com/zhravan/)
`Hosted API` A random quote card, with themes. The service moved from Heroku to Vercel, so old `herokuapp.com` URLs no longer work.

![Quote](https://github-readme-quotes-bay.vercel.app/quote?theme=dark)

### [GitHub Readme Zodiac](https://github.com/seuthootDev/github-readme-zodiac) - [seuthootDev](https://github.com/seuthootDev/)
`Hosted API` A zodiac-style card generated from your GitHub activity.

[![Zodiac card](https://github-readme-zodiac.vercel.app/api/card?username=seuthootDev&width=360)](https://github.com/seuthootDev/github-readme-zodiac)

### [GitHub Readme Chinese Zodiac](https://github.com/seuthootDev/github-readme-chinese-zodiac) - [seuthootDev](https://github.com/seuthootDev/)
`Hosted API` A Chinese zodiac (十二生肖) card generated from your GitHub activity.

[![Chinese Zodiac card](https://github-readme-chinese-zodiac.vercel.app/api/card?username=seuthootDev&birthdate=1995-04-24&width=360&glow=1)](https://github.com/seuthootDev/github-readme-chinese-zodiac)

## Generators and related tools

These help you build or explore a profile, but you can't embed them in a README.

### [simple profile generator](https://github.com/arturssmirnovs/github-profile-readme-generator) - [arturssmirnovs](https://github.com/arturssmirnovs/)
`Website` Fill in a form and get a profile README to copy.

![Github readme generator](https://arturssmirnovs.github.io/github-profile-readme-generator/images/gif.gif?v=123)

### [Profile Summary](https://github.com/tipsy/profile-summary-for-github) - [tipsy](https://github.com/tipsy/)
`Website` Visualizes any GitHub profile: languages, commits per repo, stars and more. It renders a page on [profile-summary-for-github.com](https://profile-summary-for-github.com/search), not an image.

![Profile Summary screenshot](https://user-images.githubusercontent.com/1521451/34072014-4451dbf6-e280-11e7-90a7-32ad1f313541.PNG)

## Contributing

Suggestions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first: it covers what gets added and how to format an entry. A GitHub Action checks every link in this list once a week.
