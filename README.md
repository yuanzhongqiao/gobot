[![Gobot](https://raw.githubusercontent.com/hybridgroup/gobot-site/master/source/images/elements/gobot-logo-small.png)](http://gobot.io/)

[![GoDoc](https://godoc.org/gobot.io/x/gobot/v2?status.svg)](https://godoc.org/gobot.io/x/gobot/v2)
[![CircleCI Build status](https://circleci.com/gh/hybridgroup/gobot/tree/dev.svg?style=svg)](https://circleci.com/gh/hybridgroup/gobot/tree/dev)
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/ix29evnbdrhkr7ud/branch/dev?svg=true)](https://ci.appveyor.com/project/deadprogram/gobot/branch/dev)
[![codecov](https://codecov.io/gh/hybridgroup/gobot/branch/dev/graph/badge.svg)](https://codecov.io/gh/hybridgroup/gobot)
[![Go Report Card](https://goreportcard.com/badge/hybridgroup/gobot)](https://goreportcard.com/report/hybridgroup/gobot)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/hybridgroup/gobot/blob/master/LICENSE.txt)

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="http://gobot.io/" rel="nofollow"><img src="https://raw.githubusercontent.com/hybridgroup/gobot-site/master/source/images/elements/gobot-logo-small.png" alt="戈博特" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://godoc.org/gobot.io/x/gobot/v2" rel="nofollow"><img src="https://camo.githubusercontent.com/9561e646cf844dda6379755027013e8dc8ced9dc815602db3cea17c6f15832e8/68747470733a2f2f676f646f632e6f72672f676f626f742e696f2f782f676f626f742f76323f7374617475732e737667" alt="戈多克" data-canonical-src="https://godoc.org/gobot.io/x/gobot/v2?status.svg" style="max-width: 100%;"></a>
<a href="https://circleci.com/gh/hybridgroup/gobot/tree/dev" rel="nofollow"><img src="https://camo.githubusercontent.com/7b8a2beab9adc8152cc966f662445763d2b562663fb6cfac91eb44d03b20ef34/68747470733a2f2f636972636c6563692e636f6d2f67682f68796272696467726f75702f676f626f742f747265652f6465762e7376673f7374796c653d737667" alt="CircleCI 构建状态" data-canonical-src="https://circleci.com/gh/hybridgroup/gobot/tree/dev.svg?style=svg" style="max-width: 100%;"></a>
<a href="https://ci.appveyor.com/project/deadprogram/gobot/branch/dev" rel="nofollow"><img src="https://camo.githubusercontent.com/29eda0f64f38427e9363bcec3158c2fabbfce790953281bbb5db858d3fbdb0ab/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f6978323965766e626472686b723775642f6272616e63682f6465763f7376673d74727565" alt="Appveyor构建状态" data-canonical-src="https://ci.appveyor.com/api/projects/status/ix29evnbdrhkr7ud/branch/dev?svg=true" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/hybridgroup/gobot" rel="nofollow"><img src="https://camo.githubusercontent.com/67a6c9bd10901ca72546496c1bb06f94593368879c05faf96a863b5d0f75ece0/68747470733a2f2f636f6465636f762e696f2f67682f68796272696467726f75702f676f626f742f6272616e63682f6465762f67726170682f62616467652e737667" alt="代码科夫" data-canonical-src="https://codecov.io/gh/hybridgroup/gobot/branch/dev/graph/badge.svg" style="max-width: 100%;"></a>
<a href="https://goreportcard.com/report/hybridgroup/gobot" rel="nofollow"><img src="https://camo.githubusercontent.com/88c0f72140473e7c30625881e50894f8cd328a395962bbecbeb4b3d41d7f305b/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f68796272696467726f75702f676f626f74" alt="去报告卡" data-canonical-src="https://goreportcard.com/badge/hybridgroup/gobot" style="max-width: 100%;"></a>
<a href="https://github.com/hybridgroup/gobot/blob/master/LICENSE.txt"><img src="https://camo.githubusercontent.com/db9dfde8049c5d66ba62fde707d2cfb30e26f9f26ff274c3442c0aec1ec410a4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d417061636865253230322e302d626c75652e737667" alt="执照" data-canonical-src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot ( </font></font><a href="https://gobot.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://gobot.io/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 是一个使用 Go 编程语言 ( </font></font><a href="https://golang.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://golang.org/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 的框架，用于机器人、物理计算和物联网。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它提供了一种简单而强大的方法来创建同时包含多个不同硬件设备的解决方案。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">想直接在微控制器上运行 Go 吗？查看我们的姐妹项目 TinyGo ( </font></font><a href="https://tinygo.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://tinygo.org/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> )</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-get-in-touch" class="anchor" aria-hidden="true" tabindex="-1" href="#get-in-touch"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持联系</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过运行以下命令获取 Gobot 源代码：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/hybridgroup/gobot.git
git checkout release</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/hybridgroup/gobot.git
git checkout release" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后看一下</font></font><a href="/hybridgroup/gobot/blob/release/examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例目录</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。您需要找到一个与您的平台相匹配的示例来进行第一次测试（例如“raspi_blink.go”）。然后构建二进制文件（交叉编译），将其传输到您的目标并运行它。</font></font></p>
<p dir="auto"><code>env GOOS=linux GOARCH=arm GOARM=5 go build -o ./output/my_raspi_bink examples/raspi_blink.go</code></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用上面的示例代码在本地计算机上构建代码将为 ARMv5 创建二进制文件。这可能不是您的特定目标平台所需要的。另请阅读平台子文件夹中的平台特定文档。</font></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-create-your-first-project" class="anchor" aria-hidden="true" tabindex="-1" href="#create-your-first-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建您的第一个项目</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建一个新文件夹和一个新的 Go 模块项目。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>mkdir <span class="pl-k">~</span>/my_gobot_example
<span class="pl-c1">cd</span> <span class="pl-k">~</span>/my_gobot_example
go mod init my.gobot.example.com</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="mkdir ~/my_gobot_example
cd ~/my_gobot_example
go mod init my.gobot.example.com" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了 go.mod 文件之外，复制示例文件，导入需求并构建。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>cp /<span class="pl-k">&lt;</span>path to gobot folder<span class="pl-k">&gt;</span>/examples/raspi_blink.go <span class="pl-k">~</span>/my_gobot_example/
go mod tidy
env GOOS=linux GOARCH=arm GOARM=5 go build -o ./output/my_raspi_bink raspi_blink.go</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cp /<path to gobot folder>/examples/raspi_blink.go ~/my_gobot_example/
go mod tidy
env GOOS=linux GOARCH=arm GOARM=5 go build -o ./output/my_raspi_bink raspi_blink.go" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在您已准备好修改示例并测试您的更改。首先删除文件开头的构建指令。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-examples" class="anchor" aria-hidden="true" tabindex="-1" href="#examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-gobot-with-arduino" class="anchor" aria-hidden="true" tabindex="-1" href="#gobot-with-arduino"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot 与 Arduino</font></font></h3>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
  <span class="pl-s">"time"</span>

  <span class="pl-s">"gobot.io/x/gobot/v2"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/drivers/gpio"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/platforms/firmata"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
  <span class="pl-s1">firmataAdaptor</span> <span class="pl-c1">:=</span> <span class="pl-s1">firmata</span>.<span class="pl-en">NewAdaptor</span>(<span class="pl-s">"/dev/ttyACM0"</span>)
  <span class="pl-s1">led</span> <span class="pl-c1">:=</span> <span class="pl-s1">gpio</span>.<span class="pl-en">NewLedDriver</span>(<span class="pl-s1">firmataAdaptor</span>, <span class="pl-s">"13"</span>)

  <span class="pl-s1">work</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>() {
    <span class="pl-s1">gobot</span>.<span class="pl-en">Every</span>(<span class="pl-c1">1</span><span class="pl-c1">*</span><span class="pl-s1">time</span>.<span class="pl-c1">Second</span>, <span class="pl-k">func</span>() {
      <span class="pl-s1">led</span>.<span class="pl-en">Toggle</span>()
    })
  }

  <span class="pl-s1">robot</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewRobot</span>(<span class="pl-s">"bot"</span>,
    []gobot.<span class="pl-smi">Connection</span>{<span class="pl-s1">firmataAdaptor</span>},
    []gobot.<span class="pl-smi">Device</span>{<span class="pl-s1">led</span>},
    <span class="pl-s1">work</span>,
  )

  <span class="pl-s1">robot</span>.<span class="pl-en">Start</span>()
}</pre><div class="zeroclipboard-container">
  
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-gobot-with-sphero" class="anchor" aria-hidden="true" tabindex="-1" href="#gobot-with-sphero"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot 与 Sphero</font></font></h3>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
  <span class="pl-s">"fmt"</span>
  <span class="pl-s">"time"</span>

  <span class="pl-s">"gobot.io/x/gobot/v2"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/platforms/sphero"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
  <span class="pl-s1">adaptor</span> <span class="pl-c1">:=</span> <span class="pl-s1">sphero</span>.<span class="pl-en">NewAdaptor</span>(<span class="pl-s">"/dev/rfcomm0"</span>)
  <span class="pl-s1">driver</span> <span class="pl-c1">:=</span> <span class="pl-s1">sphero</span>.<span class="pl-en">NewSpheroDriver</span>(<span class="pl-s1">adaptor</span>)

  <span class="pl-s1">work</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>() {
    <span class="pl-s1">gobot</span>.<span class="pl-en">Every</span>(<span class="pl-c1">3</span><span class="pl-c1">*</span><span class="pl-s1">time</span>.<span class="pl-c1">Second</span>, <span class="pl-k">func</span>() {
      <span class="pl-s1">driver</span>.<span class="pl-en">Roll</span>(<span class="pl-c1">30</span>, <span class="pl-en">uint16</span>(<span class="pl-s1">gobot</span>.<span class="pl-en">Rand</span>(<span class="pl-c1">360</span>)))
    })
  }

  <span class="pl-s1">robot</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewRobot</span>(<span class="pl-s">"sphero"</span>,
    []gobot.<span class="pl-smi">Connection</span>{<span class="pl-s1">adaptor</span>},
    []gobot.<span class="pl-smi">Device</span>{<span class="pl-s1">driver</span>},
    <span class="pl-s1">work</span>,
  )

  <span class="pl-s1">robot</span>.<span class="pl-en">Start</span>()
}</pre><div class="zeroclipboard-container">
    iver(adaptor)


  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-metal-gobot" class="anchor" aria-hidden="true" tabindex="-1" href="#metal-gobot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“金属”戈博特</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用上面示例中所示的整个 Gobot 框架（“经典”Gobot），也可以从各种 Gobot 软件包中进行挑选，仅使用纯惯用的 Golang 代码（“金属”Gobot）来控制硬件。例如：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
  <span class="pl-s">"gobot.io/x/gobot/v2/drivers/gpio"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/platforms/intel-iot/edison"</span>
  <span class="pl-s">"time"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
  <span class="pl-s1">e</span> <span class="pl-c1">:=</span> <span class="pl-s1">edison</span>.<span class="pl-en">NewAdaptor</span>()
  <span class="pl-s1">e</span>.<span class="pl-en">Connect</span>()

  <span class="pl-s1">led</span> <span class="pl-c1">:=</span> <span class="pl-s1">gpio</span>.<span class="pl-en">NewLedDriver</span>(<span class="pl-s1">e</span>, <span class="pl-s">"13"</span>)
  <span class="pl-s1">led</span>.<span class="pl-en">Start</span>()

  <span class="pl-k">for</span> {
    <span class="pl-s1">led</span>.<span class="pl-en">Toggle</span>()
    <span class="pl-s1">time</span>.<span class="pl-en">Sleep</span>(<span class="pl-c1">1000</span> <span class="pl-c1">*</span> <span class="pl-s1">time</span>.<span class="pl-c1">Millisecond</span>)
  }
}</pre><div class="zeroclipboard-container">

  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-master-gobot" class="anchor" aria-hidden="true" tabindex="-1" href="#master-gobot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“大师”戈博特</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用该框架（又名“Master Gobot”）的全部功能来控制机器人群或其他功能，例如内置 API 服务器。例如：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
  <span class="pl-s">"fmt"</span>
  <span class="pl-s">"time"</span>

  <span class="pl-s">"gobot.io/x/gobot/v2"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/api"</span>
  <span class="pl-s">"gobot.io/x/gobot/v2/platforms/sphero"</span>
)

<span class="pl-k">func</span> <span class="pl-en">NewSwarmBot</span>(<span class="pl-s1">port</span> <span class="pl-smi">string</span>) <span class="pl-c1">*</span>gobot.<span class="pl-smi">Robot</span> {
  <span class="pl-s1">spheroAdaptor</span> <span class="pl-c1">:=</span> <span class="pl-s1">sphero</span>.<span class="pl-en">NewAdaptor</span>(<span class="pl-s1">port</span>)
  <span class="pl-s1">spheroDriver</span> <span class="pl-c1">:=</span> <span class="pl-s1">sphero</span>.<span class="pl-en">NewSpheroDriver</span>(<span class="pl-s1">spheroAdaptor</span>)
  <span class="pl-s1">spheroDriver</span>.<span class="pl-en">SetName</span>(<span class="pl-s">"Sphero"</span> <span class="pl-c1">+</span> <span class="pl-s1">port</span>)

  <span class="pl-s1">work</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>() {
    <span class="pl-s1">spheroDriver</span>.<span class="pl-en">Stop</span>()

    <span class="pl-s1">spheroDriver</span>.<span class="pl-en">On</span>(<span class="pl-s1">sphero</span>.<span class="pl-c1">Collision</span>, <span class="pl-k">func</span>(<span class="pl-s1">data</span> <span class="pl-k">interface</span>{}) {
      <span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"Collision Detected!"</span>)
    })

    <span class="pl-s1">gobot</span>.<span class="pl-en">Every</span>(<span class="pl-c1">1</span><span class="pl-c1">*</span><span class="pl-s1">time</span>.<span class="pl-c1">Second</span>, <span class="pl-k">func</span>() {
      <span class="pl-s1">spheroDriver</span>.<span class="pl-en">Roll</span>(<span class="pl-c1">100</span>, <span class="pl-en">uint16</span>(<span class="pl-s1">gobot</span>.<span class="pl-en">Rand</span>(<span class="pl-c1">360</span>)))
    })
    <span class="pl-s1">gobot</span>.<span class="pl-en">Every</span>(<span class="pl-c1">3</span><span class="pl-c1">*</span><span class="pl-s1">time</span>.<span class="pl-c1">Second</span>, <span class="pl-k">func</span>() {
      <span class="pl-s1">spheroDriver</span>.<span class="pl-en">SetRGB</span>(<span class="pl-en">uint8</span>(<span class="pl-s1">gobot</span>.<span class="pl-en">Rand</span>(<span class="pl-c1">255</span>)),
        <span class="pl-en">uint8</span>(<span class="pl-s1">gobot</span>.<span class="pl-en">Rand</span>(<span class="pl-c1">255</span>)),
        <span class="pl-en">uint8</span>(<span class="pl-s1">gobot</span>.<span class="pl-en">Rand</span>(<span class="pl-c1">255</span>)),
      )
    })
  }

  <span class="pl-s1">robot</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewRobot</span>(<span class="pl-s">"sphero"</span>,
    []gobot.<span class="pl-smi">Connection</span>{<span class="pl-s1">spheroAdaptor</span>},
    []gobot.<span class="pl-smi">Device</span>{<span class="pl-s1">spheroDriver</span>},
    <span class="pl-s1">work</span>,
  )

  <span class="pl-k">return</span> <span class="pl-s1">robot</span>
}

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
  <span class="pl-s1">master</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewMaster</span>()
  <span class="pl-s1">api</span>.<span class="pl-en">NewAPI</span>(<span class="pl-s1">master</span>).<span class="pl-en">Start</span>()

  <span class="pl-s1">spheros</span> <span class="pl-c1">:=</span> []<span class="pl-smi">string</span>{
    <span class="pl-s">"/dev/rfcomm0"</span>,
    <span class="pl-s">"/dev/rfcomm1"</span>,
    <span class="pl-s">"/dev/rfcomm2"</span>,
    <span class="pl-s">"/dev/rfcomm3"</span>,
  }

  <span class="pl-k">for</span> <span class="pl-s1">_</span>, <span class="pl-s1">port</span> <span class="pl-c1">:=</span> <span class="pl-k">range</span> <span class="pl-s1">spheros</span> {
    <span class="pl-s1">master</span>.<span class="pl-en">AddRobot</span>(<span class="pl-en">NewSwarmBot</span>(<span class="pl-s1">port</span>))
  }

  <span class="pl-s1">master</span>.<span class="pl-en">Start</span>()
}</pre><div class="zeroclipboard-container">

  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-hardware-support" class="anchor" aria-hidden="true" tabindex="-1" href="#hardware-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">硬件支持</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot有一个可扩展的系统用于连接硬件设备。目前支持以下机器人和物理计算平台：</font></font></p>
<ul dir="auto">
<li><a href="http://www.arduino.cc/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Arduino</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/firmata"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">音频 &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/audio"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://beagleboard.org/boards" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Beaglebone 黑色</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/beaglebone"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://beagleboard.org/pocket/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Beaglebone PocketBeagle</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/beaglebone"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="https://www.bluetooth.com/what-is-bluetooth-technology/bluetooth-technology-basics/low-energy" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝牙 LE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/ble"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://www.nextthing.co/pages/chip" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">芯片</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/chip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="https://docs.getchip.com/chip_pro.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CHIP Pro</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/chip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://digistump.com/products/1" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Digispark</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/digispark"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="https://www.ryzerobotics.com/tello" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DJI Tello</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/dji/tello"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="https://developer.qualcomm.com/hardware/dragonboard-410c" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DragonBoard</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/dragonboard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://esp8266.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ESP8266</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/firmata"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="https://www.dexterindustries.com/gopigo3/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GoPiGo 3</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/dexter/gopigo3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="https://www.intel.com/content/www/us/en/products/boards-kits/curie.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英特尔居里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/intel-iot/curie"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://www.intel.com/content/www/us/en/do-it-yourself/edison.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英特尔爱迪生</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/intel-iot/edison"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://intel.com/joule/getstarted" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">英特尔焦耳</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/intel-iot/joule"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="https://developer.nvidia.com/embedded/jetson-nano/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jetson Nano</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/jetson"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://en.wikipedia.org/wiki/Joystick" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">操纵杆</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/joystick"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包装</font></font></a></li>
<li><a href="https://en.wikipedia.org/wiki/Computer_keyboard" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键盘</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/keyboard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="https://www.leapmotion.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Leap Motion</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/leap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://qgroundcontrol.org/mavlink/start" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MavLink</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/mavlink"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://www.makeblock.com/megapi" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MegaPi</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/megapi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://microbit.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Microbit</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/microbit"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://mqtt.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MQTT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/mqtt"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="https://wiki.friendlyelec.com/wiki/index.php/NanoPi_NEO" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NanoPi NEO</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/nanopi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://nats.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">NATS</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/nats"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://neurosky.com/products-markets/eeg-biosensors/hardware/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Neurosky</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/neurosky"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="http://opencv.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenCV</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/opencv"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="https://www.particle.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">粒子</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/particle"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://ardrone2.parrot.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Parrot ARDrone 2.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/parrot/ardrone"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="http://www.parrot.com/usa/products/bebop-drone/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">星际鹦鹉</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/parrot/bebop"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套装</font></font></a></li>
<li><a href="https://www.parrot.com/us/minidrones" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Parrot 迷你无人机</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/parrot/minidrone"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套装</font></font></a></li>
<li><a href="https://www.getpebble.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卵石</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/pebble"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="https://wiki.radxa.com/Rock4/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Radxa Rock Pi 4</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/rockpi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套件</font></font></a></li>
<li><a href="http://www.raspberrypi.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树莓派</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/raspi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="http://www.sphero.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphero</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/sphero"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://www.sphero.com/bb8" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphero BB-8</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/sphero/bb8"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包装</font></font></a></li>
<li><a href="http://www.sphero.com/ollie" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphero Ollie</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/sphero/ollie"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套餐</font></font></a></li>
<li><a href="http://www.sphero.com/sprk-plus" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sphero SPRK+</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/sphero/sprkplus"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
<li><a href="https://www.asus.com/us/Single-Board-Computer/Tinker-Board/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tinker Board</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/tinkerboard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包</font></font></a></li>
<li><a href="http://www.up-board.org/upsquared/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UP2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/platforms/upboard/up2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">封装</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对许多使用通用输入/输出 (GPIO) 的设备的支持具有使用该</font></font><code>gobot/drivers/gpio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包提供的一组共享驱动程序：</font></font></p>
<ul dir="auto">
<li><a href="https://en.wikipedia.org/wiki/General_Purpose_Input/Output" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GPIO</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/drivers/gpio"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">驱动程序</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AIP1640 LED点阵/7段控制器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按钮</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蜂鸣器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接插针</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">易驱动</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove Button（通过使用 Button 的驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove Buzzer（通过使用蜂鸣器驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove LED（通过使用 LED 驱动器）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove 磁性开关（通过使用按钮驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove Relay（通过使用 Relay 驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove 触摸传感器（通过使用按钮驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HC-SR04 超声波测距模块</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HD44780液晶控制器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引领</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Makey 按钮（通过使用按钮驱动程序）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MAX7219 LED点阵</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发动机</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接近红外 (PIR) 运动传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中继</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RGB LED</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伺服</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">步进电机</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TM1638 LED控制器</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对许多使用模拟输入/输出 (AIO) 的设备的支持具有使用该</font></font><code>gobot/drivers/aio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包提供的一组共享驱动程序：</font></font></p>
<ul dir="auto">
<li><a href="https://en.wikipedia.org/wiki/Analog-to-digital_converter" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一体机</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/drivers/aio"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">驱动程序</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模拟执行器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模拟传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格罗夫光传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove 压电振动传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格罗夫旋转表盘</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove 声音传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格罗夫温度传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">温度传感器（支持正向和反向模式下的线性和NTC热敏电阻）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">热区温度传感器</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对使用内部集成电路 (I2C) 的设备的支持具有使用该</font></font><code>gobot/drivers/i2c</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包提供的一组共享驱动程序：</font></font></p>
<ul dir="auto">
<li><a href="https://en.wikipedia.org/wiki/I%C2%B2C" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">I2C</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/drivers/i2c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">驱动程序</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adafruit 1109 2x16 RGB-LCD，带 5 个按键</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adafruit 2327 16 通道 PWM/伺服 HAT 帽子</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adafruit 2348 直流和步进电机帽</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADS1015 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADS1115 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ADXL345 数字加速度计</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BH1750 数字亮度/勒克斯/光传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">闪烁 LED</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BME280 气压/温度/高度/湿度传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BMP180 气压/温度/高度传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BMP280 气压/温度/高度传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BMP388 气压/温度/高度传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DRV2605L 触觉控制器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于从寄存器地址读取和写入值的通用驱动程序</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Grove 数字加速度计</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GrovePi 扩展板</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格罗夫 RGB 液晶显示屏</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HMC6352 指南针</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HMC5883L 3轴数字罗盘</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">INA3221 电压监视器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JHD1313M1 LCD 显示屏，带 RGB 背光</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">L3GD20H 三轴陀螺仪</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">激光雷达-Lite</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP23017 端口扩展器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MMA7660 3 轴加速度计</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MPL115A2 气压/温度</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MPU6050 加速度计/陀螺仪</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCA9501 带中断的 8 位 I/O 端口、2 kbit EEPROM</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCA953x LED 调光器，适用于 PCA9530（2 位）、PCA9533（4 位）、PCA9531（8 位）、PCA9532（16 位）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCA9685 16通道12位PWM/伺服驱动器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCF8583 时钟和日历或事件计数器，240 x 8 位 RAM</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PCF8591 8 位 4xA/D 和 1xD/A 转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SHT2x 温度/湿度</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SHT3x-D 温度/湿度</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSD1306 OLED显示控制器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TSL2561 数字亮度/勒克斯/光传感器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Wii 双节棍控制器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YL-40亮度/温度传感器、电位器、模拟输入、模拟输出驱动器</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对使用串行外设接口 (SPI) 的设备的支持具有使用该包提供的一组共享驱动程序</font></font><code>gobot/drivers/spi</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><a href="https://en.wikipedia.org/wiki/Serial_Peripheral_Interface_Bus" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SPI</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> &lt;=&gt;</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/drivers/spi"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">驱动程序</font></font></a>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">APA102 可编程 LED</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3002 模拟/数字转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3004 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3008 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3202 模拟/数字转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3204 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3208 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MCP3304 模数转换器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MFRC522 RFID 读卡器</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSD1306 OLED显示控制器</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多平台和驱动程序即将推出...</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-api" class="anchor" aria-hidden="true" tabindex="-1" href="#api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序编程接口</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot 包含一个 RESTful API，用于查询组内运行的任何机器人的状态，包括连接和设备状态，并执行设备命令。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要激活 API，请导入</font></font><code>gobot.io/x/gobot/v2/api</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包并实例化，</font></font><code>API</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如下所示：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-s1">master</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewMaster</span>()
  <span class="pl-s1">api</span>.<span class="pl-en">NewAPI</span>(<span class="pl-s1">master</span>).<span class="pl-en">Start</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  master := gobot.NewMaster()
  api.NewAPI(master).Start()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以指定 api 主机和端口，并开启身份验证：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre>  <span class="pl-s1">master</span> <span class="pl-c1">:=</span> <span class="pl-s1">gobot</span>.<span class="pl-en">NewMaster</span>()
  <span class="pl-s1">server</span> <span class="pl-c1">:=</span> <span class="pl-s1">api</span>.<span class="pl-en">NewAPI</span>(<span class="pl-s1">master</span>)
  <span class="pl-s1">server</span>.<span class="pl-c1">Port</span> <span class="pl-c1">=</span> <span class="pl-s">"4000"</span>
  <span class="pl-s1">server</span>.<span class="pl-en">AddHandler</span>(<span class="pl-s1">api</span>.<span class="pl-en">BasicAuth</span>(<span class="pl-s">"gort"</span>, <span class="pl-s">"klatuu"</span>))
  <span class="pl-s1">server</span>.<span class="pl-en">Start</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  master := gobot.NewMaster()
  server := api.NewAPI(master)
  server.Port = &quot;4000&quot;
  server.AddHandler(api.BasicAuth(&quot;gort&quot;, &quot;klatuu&quot;))
  server.Start()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以</font><font style="vertical-align: inherit;">通过导航到 Gobot 来访问</font></font><a href="https://github.com/hybridgroup/robeaux"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">robeaux</font></font></a><font style="vertical-align: inherit;"></font><code>http://localhost:3000/index.html</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> React.js 界面。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-cli" class="anchor" aria-hidden="true" tabindex="-1" href="#cli"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令行界面</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot 使用 Gort </font></font><a href="http://gort.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://gort.io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令行界面 (CLI)，因此您可以直接从命令行访问重要功能。我们称之为“RobotOps”，又名“机器人开发运营”。您可以扫描、连接、更新设备固件等等！</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们总是在我们的网站</font></font><a href="https://gobot.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://gobot.io/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上添加文档，请在我们继续开发 Gobot 时查看该网站</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">谢谢你！</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-need-help" class="anchor" aria-hidden="true" tabindex="-1" href="#need-help"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">需要帮忙？</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题： https: </font></font><a href="https://github.com/hybridgroup/gobot/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//github.com/hybridgroup/gobot/issues</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推特：</font></font><a href="https://twitter.com/gobotio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">@gobotio</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">松弛： https: </font></font><a href="https://gophers.slack.com/messages/C0N5HDB08" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//gophers.slack.com/messages/C0N5HDB08</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">邮件列表：</font></font><a href="https://groups.google.com/forum/#!forum/gobotio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://groups.google.com/forum/#!forum /gobotio</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关我们的贡献指南，请访问</font></font><a href="https://github.com/hybridgroup/gobot/blob/master/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/hybridgroup/gobot/blob/master/CONTRIBUTING.md
</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gobot 随贡献者行为准则一起发布。参与该项目即表示您同意遵守其条款。
</font></font><a href="https://github.com/hybridgroup/gobot/tree/master/CODE_OF_CONDUCT.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你可以在这里读到它</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版权所有 (c) 2013-2020 混合集团。根据 Apache 2.0 许可证获得许可。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献者契约是根据知识共享署名 4.0 国际公共许可证发布的，该许可证要求包含署名。</font></font></p>
</article></div>
