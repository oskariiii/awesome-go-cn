# Awesome Go

[Gold]: ./docs/Gold.svg "star > 5000"
[Silver]: ./docs/Silver.svg "star > 1000"
[Bronze]: ./docs/Bronze.svg "star > 100"
[Green]: ./docs/Green.svg "最近一周有更新"
[Yellow]: ./docs/Yellow.svg "最近一年没有更新"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-07-04 15:11:42(每隔1天同步一次)**

**:star:项目地址 : [yinggaozhen/awesome-go-cn](https://github.com/yinggaozhen/awesome-go-cn):star:**

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) 为Awesome Go打赏~

精选了一系列很棒的Go框架、库和软件。灵感来自于[awesome-python](https://github.com/vinta/awesome-python)。

**小图标说明** :


小图标 | 说明  
:-:|-
![star > 5000][Gold] | star数量 > 5000 的项目
![star > 1000][Silver] | star数量 > 1000 的项目
![star > 100][Bronze] | star数量 > 100 的项目
![最近一个周有更新][Green] | 最近一周有更新。可以基本判断当前库处于积极维护状态。
![最近一年未更新][Yellow] | 最近一年没有更新。反应了此库的维护积极性不高，使用时需谨慎。
 

### 贡献

你可以快速浏览贡献者名单[contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md). 感觉所有为此项目付出的同学[contributors](https://github.com/avelino/awesome-go/graphs/contributors); 你真棒!

如果您在看到一个包或项目不再维护或不适合，请往awesome-go提交[Pull Request](https://github.com/avelino/awesome-go/pulls)，本项目每隔一天与英文文档同步。感谢!

### 内容

- [Awesome Go](#awesome-go)
    - [音频和音乐](#音频和音乐)
    - [身份验证和OAuth](#身份验证和oauth)
    - [Bot建设](#bot建设)
    - [命令行](#命令行)
    - [配置](#配置)
    - [持续集成](#持续集成)
    - [CSS预处理器](#css预处理器)
    - [数据结构](#数据结构)
    - [数据库](#数据库)
    - [数据库驱动程序](#数据库驱动程序)
    - [日期和时间](#日期和时间)
    - [分布式系统](#分布式系统)
    - [电子邮件](#电子邮件)
    - [可嵌入的脚本语言](#可嵌入的脚本语言)
    - [错误处理](#错误处理)
    - [文件](#文件)
    - [金融](#金融)
    - [表单](#表单)
    - [方法](#方法)
    - [游戏开发](#游戏开发)
    - [代码生成与泛型](#代码生成与泛型)
    - [地理](#地理)
    - [Go 编译器](#go-编译器)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [硬件](#硬件)
    - [图片](#图片)
    - [物联网](#物联网)
    - [作业调度器](#作业调度器)
    - [JSON](#json)
    - [日志记录](#日志记录)
    - [机器学习](#机器学习)
    - [消息](#消息)
    - [微软办公软件](#微软办公软件)
        - [Microsoft Excel](#microsoft-excel)
    - [杂项](#杂项)
        - [依赖注入](#依赖注入)
        - [项目布局](#项目布局)
        - [字符串](#字符串)
    - [自然语言处理](#自然语言处理)
    - [网络](#网络)
        - [HTTP客户端](#http客户端)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [包管理](#包管理)
    - [查询语言](#查询语言)
    - [嵌入的资源](#嵌入的资源)
    - [科学与数据分析](#科学与数据分析)
    - [安全](#安全)
    - [序列化](#序列化)
    - [模板引擎](#模板引擎)
    - [测试](#测试)
    - [文本处理](#文本处理)
    - [Third-party APIs](#third-party-apis)
    - [公用事业公司](#公用事业公司)
    - [UUID](#uuid)
    - [验证](#验证)
    - [版本控制](#版本控制)
    - [视频](#视频)
    - [Web框架](#web框架)
        - [中间件](#中间件)
            - [仿真中间件](#仿真中间件)
            - [用于创建HTTP中间件的库](#用于创建http中间件的库)
        - [路由器](#路由器)
    - [Windows](#windows)
    - [XML](#xml)

- [工具](#工具)
    - [代码分析](#代码分析)
    - [编辑器插件](#编辑器插件)
    - [Go 生成工具](#go-生成工具)
    - [Go 工具](#go-工具)
    - [软件包](#软件包)
        - [DevOps 工具](#devops-工具)
        - [其他软件](#其他软件)

- [服务器应用程序](#服务器应用程序)

- [资源](#资源)
    - [基准](#基准)
    - [会议](#会议)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [聚会](#聚会)
    - [Twitter](#twitter)
    - [网站](#网站)
        - [教程](#教程)

## 音频和音乐

*用于操作音频的库。*

* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) - **star:20** EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。![最近一年没有更新][Yellow]
* [flac](https://github.com/eaburns/flac) - **star:84** 原生 Go FLAC解码器，将FLAC文件解码为字节片。![最近一年没有更新][Yellow]
* [flac](https://github.com/mewkiz/flac) - **star:100** 原生 Go FLAC编码器/解码器，支持FLAC流。![star > 100][Bronze]   
* [gaad](https://github.com/Comcast/gaad) - **star:55** 原生 Go AAC位流解析器。![最近一年没有更新][Yellow]
* [go-sox](https://github.com/krig/go-sox) - **star:92** libsox 的 Go 语言实现接口。![最近一年没有更新][Yellow]
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) - **star:24** libmediainfo 的 Go 语言实现接口。![最近一年没有更新][Yellow]
* [gosamplerate](https://github.com/dh1tw/gosamplerate) - **star:8** libsamplerate 的 Go 语言实现接口。![最近一年没有更新][Yellow]
* [id3v2](https://github.com/bogem/id3v2) - **star:107** 快速稳定的 ID3 解析及写入Go库。![star > 100][Bronze]   
* [malgo](https://github.com/gen2brain/malgo) - **star:68** 迷你音频库。
* [minimp3](https://github.com/tosone/minimp3) - **star:25** 轻量级MP3解码器库。
* [mix](https://github.com/go-mix/mix) - **star:96** 基于序列的 Go 原生音乐混音器。![最近一年没有更新][Yellow]
* [mp3](https://github.com/tcolgate/mp3) - **star:89** 原生 Go MP3解码器。![最近一年没有更新][Yellow]
* [music-theory](https://github.com/go-music-theory/music-theory) - **star:251** 基于 Go 的音乐理论模型。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Oto](https://github.com/hajimehoshi/oto) - **star:386** 多平台的 low-level 声音播放库。![star > 100][Bronze]   
* [PortAudio](https://github.com/gordonklaus/portaudio) - **star:295** 基于 Go 的PortAudio audio I/O库。![star > 100][Bronze]   
* [portmidi](https://github.com/rakyll/portmidi) - **star:203** PortMidi的 Go 语言实现接口。。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [taglib](https://github.com/wtolson/go-taglib) - **star:66** taglib 的 Go 语言实现接口。。
* [vorbis](https://github.com/mccoyst/vorbis) - **star:22** “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。
* [waveform](https://github.com/mdlayher/waveform) - **star:245** 通过音频流生成波形图像的包。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 身份验证和OAuth

*用于实现验证方案的库。*

* [authboss](https://github.com/volatiletech/authboss) - **star:1894** web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [branca](https://github.com/hako/branca) - **star:67** 基于 Go 实现Branca令牌。
* [casbin](https://github.com/hsluoyz/casbin) - **star:4693** 支持ACL、RBAC、ABAC等访问控制模型的授权库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) - **star:2** 提供cookie .txt文件格式的解析器。![最近一年没有更新][Yellow]
* [go-jose](https://github.com/square/go-jose) - **star:1087** 相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。![star > 1000][Silver]   
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) - **star:1249** 用 Golang 编写的独立且符合规范的OAuth2服务器。![star > 1000][Silver]   
* [gologin](https://github.com/dghubble/gologin) - **star:1029** 用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。![star > 1000][Silver]   
* [gorbac](https://github.com/mikespook/gorbac) - **star:897** 轻量级的基于角色的访问控制(RBAC)实现。![star > 100][Bronze]   
* [goth](https://github.com/markbates/goth) - **star:2214** 提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。![star > 1000][Silver]   
* [httpauth](https://github.com/goji/httpauth) - **star:175** HTTP身份验证中间件。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [jwt](https://github.com/robbert229/jwt) - **star:68** 简单易用的JSON Web令牌实现(JWT)。
* [jwt](https://github.com/pascaldekloe/jwt) - **star:76** 轻量级JSON Web令牌库。![最近一个周有更新][Green]
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) - **star:151** JWT中间件，可用于Golang http服务器，提供了许多配置选项。![star > 100][Bronze]   
* [jwt-go](https://github.com/dgrijalva/jwt-go) - **star:5714** JSON Web令牌(JWT)。![star > 5000][Gold]   
* [loginsrv](https://github.com/tarent/loginsrv) - **star:793** JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。![star > 100][Bronze]   
* [oauth2](https://github.com/golang/oauth2) - **star:2329** goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。![star > 1000][Silver]   
* [osin](https://github.com/openshift/osin) - **star:1534** OAuth2服务器库。![star > 1000][Silver]   
* [paseto](https://github.com/o1egl/paseto) - **star:220** 平台无关的安全令牌(PASETO)。![star > 100][Bronze]   
* [permissions2](https://github.com/xyproto/permissions2) - **star:346** 用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。![star > 100][Bronze]   
* [rbac](https://github.com/zpatrick/rbac) - **star:25** 最小的RBAC包。
* [scs](https://github.com/alexedwards/scs) - **star:515** HTTP服务器的会话管理器。![star > 100][Bronze]   
* [securecookie](https://github.com/chmike/securecookie) - **star:31** 高效安全的cookie编码/解码。
* [session](https://github.com/icza/session) - **star:88** web服务器会话管理(包括支持谷歌应用程序引擎- GAE)。![最近一个周有更新][Green]
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) - **star:8** 使用SessionGate Redis模块进行会话管理。
* [sessions](https://github.com/adam-hanna/sessions) - **star:45** 非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。
* [signedvalue](https://github.com/sashka/signedvalue) - **star:7** 与[Tornado's](https://github.com/tornado oweb/tornado) 完全兼容的签名和时间戳字符串实现. create_signed_value '， ' decode_signed_value '，因此' set_secure_cookie '和' get_secure_cookie '。

## Bot建设

*用于构建和使用机器人的库。*

* [go-chat-bot](https://github.com/go-chat-bot/bot) - **star:454** 用 Go 编写的IRC, Slack和电报机器人。![star > 100][Bronze]   
* [go-sarah](https://github.com/oklahomer/go-sarah) - **star:129** 此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-tgbot](https://github.com/olebedev/go-tgbot) - **star:82** 由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。![最近一年没有更新][Yellow]
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - **star:207** 基于控制台的，用于加密货币交易所的的交易机器人。![star > 100][Bronze]   
* [govkbot](https://github.com/nikepan/govkbot) - **star:22** 简单的Go [VK](https://vk.com) bot库。
* [hanu](https://github.com/sbstjn/hanu) - **star:107** 用于编写Slack机器人的框架。![star > 100][Bronze]   
* [Kelp](https://github.com/stellar/kelp) - **star:146** 官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [margelet](https://github.com/zhulik/margelet) - **star:57** 构建电报机器人的框架。![最近一年没有更新][Yellow]
* [micha](https://github.com/onrik/micha) - **star:10** 基于 GO 实现的Telegram 机器人API库。![最近一年没有更新][Yellow]
* [slacker](https://github.com/shomali11/slacker) - **star:298** 可简单创建Slack机器人的框架。![star > 100][Bronze]   
* [slackscot](https://github.com/alexandre-normand/slackscot) - **star:10** 另一个构建Slack机器人的框架。![最近一个周有更新][Green]
* [tbot](https://github.com/yanzay/tbot) - **star:212** 带有类似于net/http API的Telegram bot服务器。![star > 100][Bronze]   
* [telebot](https://github.com/tucnak/telebot) - **star:925** 用Go编写的Telegram bot框架。![star > 100][Bronze]   
* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - **star:1567** 简单轻量级的Telegram bot客户端。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Tenyks](https://github.com/kyleterry/tenyks) - **star:167** 面向服务的IRC bot，使用Redis和JSON进行消息传递。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。*

* [argparse](https://github.com/akamensky/argparse) - **star:99** 命令行参数分析器，灵感来自Python的argparse模块。
* [argv](https://github.com/cosiner/argv) - **star:16** 基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库，
* [cli](https://github.com/mkideal/cli) - **star:470** 基于golang结构标签，功能丰富易于使用的命令行包。![star > 100][Bronze]   
* [cli](https://github.com/teris-io/cli) - **star:56** 为 Go 构建命令接口提供简单而完整的API。
* [cli-init](https://github.com/tcnksm/gcli) - **star:867** 一个简单就可开启构建Golang命令行的应用程序。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [climax](http://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
* [cmdr](https://github.com/hedzr/cmdr) - **star:7** 一个POSIX/GNU风格的、类似getopt的命令行UI Go库。
* [cobra](https://github.com/spf13/cobra) - **star:12580** 现代Go CLI命令行交互工具。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [commandeer](https://github.com/jaffee/commandeer) - **star:78** 开发友好的CLI应用程序。![最近一个周有更新][Green]
* [complete](https://github.com/posener/complete) - **star:607** 使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具.![star > 100][Bronze]   ![最近一个周有更新][Green]
* [docopt.go](https://github.com/docopt/docopt.go) - **star:1133** 会让你满意的命令行参数解析器。![star > 1000][Silver]   
* [env](https://github.com/codingconcepts/env) - **star:41** 基于标记的结构化的环境配置。
* [flag](https://github.com/cosiner/flag) - **star:100** 简单但功能强大的命令行选项解析库，用于支持Go子命令。![star > 100][Bronze]   
* [flaggy](https://github.com/integrii/flaggy) - **star:441** 一个健壮的、易用的标志包，具有出色的子命令支持。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [flagvar](https://github.com/sgreben/flagvar) - **star:31** 符合 Go 标准的“flag”标志参数类型包。
* [go-arg](https://github.com/alexflint/go-arg) - **star:642** 基于结构的参数解析。![star > 100][Bronze]   
* [go-commander](https://github.com/yitsushi/go-commander) - **star:14** 用于简化CLI工作流的 Go 库。
* [go-flags](https://github.com/jessevdk/go-flags) - **star:1491**  Go 命令行选项解析器。![star > 1000][Silver]   
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) - **star:5**  Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。![最近一个周有更新][Green]
* [gocmd](https://github.com/devfacet/gocmd) - **star:33** 用于构建命令行应用程序。
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - 具有自动配置和依赖注入的cli应用程序框架。
* [job](https://github.com/liujianping/job) - **star:43** 工作，把你的短期指令当作长期任务。
* [kingpin](https://github.com/alecthomas/kingpin) - **star:2493** 支持子命令的命令行和标志解析器。![star > 1000][Silver]   
* [liner](https://github.com/peterh/liner) - **star:569** 类似readline-like的命令行接口库。![star > 100][Bronze]   
* [mitchellh/cli](https://github.com/mitchellh/cli) - **star:984** 用于实现命令行接口的Go库。![star > 100][Bronze]   
* [mow.cli](https://github.com/jawher/mow.cli) - **star:619** 用于构建具有复杂标志和参数解析和验证的CLI应用程序。![star > 100][Bronze]   
* [ops](https://github.com/nanovms/ops) - **star:210** Unikernel Builder /协调器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [pflag](https://github.com/spf13/pflag) - **star:731** 基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [readline](https://github.com/chzyer/readline) - **star:1362** 纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。![star > 1000][Silver]   
* [sand](https://github.com/Zaba505/sand) - **star:5** 用于创建解释器等的简单API。
* [sflags](https://github.com/octago/sflags) - **star:84** 基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。
* [strumt](https://github.com/antham/strumt) - **star:27** 用于创建提示链。
* [ukautz/clif](https://github.com/ukautz/clif) - **star:98** 简小的命令行接口框架。
* [urfave/cli](https://github.com/urfave/cli) - **star:11072** 可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [wlog](https://github.com/dixonwille/wlog) - **star:34** 支持跨平台和并发的简单日志记录接口。![最近一年没有更新][Yellow]
* [wmenu](https://github.com/dixonwille/wmenu) - **star:80** 为cli程序提供了简单上手的菜单，可提示用户作出选择。

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。*

* [asciigraph](https://github.com/guptarohit/asciigraph) - **star:1111** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。![star > 1000][Silver]   
* [aurora](https://github.com/logrusorgru/aurora) - **star:599** 支持fmt.Printf/Sprintf的ANSI终端颜色。![star > 100][Bronze]   
* [cfmt](https://github.com/mingrammer/cfmt) - **star:67** 提供上下文的fmt，灵感来自于bootstrap color classes。
* [chalk](https://github.com/ttacon/chalk) - **star:302** 美化终端/控制台输出。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [color](https://github.com/fatih/color) - **star:2979** 多功能包装，彩色终端输出。![star > 1000][Silver]   
* [colourize](https://github.com/TreyBastian/colourize) - **star:16** 在终端提供ANSI彩色文本。![最近一年没有更新][Yellow]
* [ctc](https://github.com/wzshiming/ctc) - **star:9** 不需要Print方法的非侵入性跨平台终端颜色库。
* [go-ataman](https://github.com/workanator/go-ataman) - **star:8** 在终端提供ANSI彩色文本模板。![最近一年没有更新][Yellow]
* [go-colorable](https://github.com/mattn/go-colorable) - **star:370** 适用于windows的颜色编写器。![star > 100][Bronze]   
* [go-colortext](https://github.com/daviddengcn/go-colortext) - **star:198** 在终端中使用彩色文字。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-isatty](https://github.com/mattn/go-isatty) - **star:335** Go 实现的 isatty。![star > 100][Bronze]   
* [go-prompt](https://github.com/c-bata/go-prompt) - **star:2268** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gocui](https://github.com/jroimartin/gocui) - **star:4737** 旨在创建控制台用户界面的极简Go库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gommon/color](https://github.com/labstack/gommon/tree/master/color) - 更换终端文本样式。
* [gookit/color](https://github.com/gookit/color) - **star:182** 终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。![star > 100][Bronze]   
* [mpb](https://github.com/vbauerster/mpb) - **star:499** 可在终端显示多进度条。![star > 100][Bronze]   
* [progressbar](https://github.com/schollz/progressbar) - **star:550** 基本线程安全的进度条，在每个操作系统工作。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [simpletable](https://github.com/alexeyco/simpletable) - **star:154** 可在终端显示简易表格。![star > 100][Bronze]   
* [tabby](https://github.com/cheynewallace/tabby) - **star:244** 一个可在终端生成一个极简Golang表格轻量级库![star > 100][Bronze]   
* [tabular](https://github.com/InVisionApp/tabular) - **star:29** 不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。![最近一年没有更新][Yellow]
* [termbox-go](https://github.com/nsf/termbox-go) - **star:3435** 基于文本的跨平台接口库。![star > 1000][Silver]   
* [termdash](https://github.com/mum4k/termdash) - **star:781** 此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。![star > 100][Bronze]   
* [termtables](https://github.com/apcera/termtables) - **star:212** 使用Ruby库[terminal-tables](https://github.com/tj/terminal-table)的端口生成简单的ASCII表，并提供标记和HTML输出。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [termui](https://github.com/gizak/termui) - **star:8798** 此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [uilive](https://github.com/gosuri/uilive) - **star:816** 用于实时更新终端输出的库。![star > 100][Bronze]   
* [uiprogress](https://github.com/gosuri/uiprogress) - **star:1519** 在终端呈现进度条，可灵活配置的。![star > 1000][Silver]   
* [uitable](https://github.com/gosuri/uitable) - **star:494** 改善终端应用程序中表格数据的可读性。![star > 100][Bronze]   

## 配置

*配置解析的库。*

* [config](https://github.com/JeremyLoy/config) - **star:185** 云本地应用程序配置。将ENV绑定到结构体仅需两行代码。![star > 100][Bronze]   
* [config](https://github.com/olebedev/config) - **star:209** 带有环境变量和标记解析的JSON或YAML配置包装器。![star > 100][Bronze]   
* [configure](https://github.com/paked/configure) - **star:49** 通过多个源提供配置，包括JSON、flags和环境变量。
* [confita](https://github.com/heetch/confita) - **star:237** 从多个后端级联加载配置到struct中。![star > 100][Bronze]   
* [conflate](https://github.com/the4thamigo-uk/conflate) - **star:8** 合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。
* [env](https://github.com/caarlos0/env) - **star:833** 解析环境变量并赋值到struct中(默认值)。![star > 100][Bronze]   
* [envcfg](https://github.com/tomazk/envcfg) - **star:90** 对环境变量进行解析，并赋值到struct。![最近一年没有更新][Yellow]
* [envconf](https://github.com/ian-kent/envconf) - **star:7** 从环境配置中读取配置。![最近一年没有更新][Yellow]
* [envconfig](https://github.com/vrischmann/envconfig) - **star:146** 从环境变量中读取配置。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [envh](https://github.com/antham/envh) - **star:94** 协助管理环境变量的Helpers。
* [gcfg](https://github.com/go-gcfg/gcfg) - **star:115** 将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-up](https://github.com/ufoscout/go-up) - **star:24** 一个简单的配置库，具有递归占位符解析功能。
* [goConfig](https://github.com/crgimenes/goConfig) - **star:103** 将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。![star > 100][Bronze]   
* [godotenv](https://github.com/joho/godotenv) - **star:2051** Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。![star > 1000][Silver]   
* [gofigure](https://github.com/ian-kent/gofigure) - **star:57** 让程序配置变得简单。![最近一年没有更新][Yellow]
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - 模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。
* [gookit/config](https://github.com/gookit/config) - **star:73** 程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。![最近一个周有更新][Green]
* [harvester](https://github.com/beatlabs/harvester) - **star:22** 一个易于使用的静态和动态配置包
* [hjson](https://github.com/hjson/hjson-go) - **star:171** 更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。![star > 100][Bronze]   
* [ingo](https://github.com/schachmat/ingo) - **star:23** flag保存在类ini的配置文件中。![最近一年没有更新][Yellow]
* [ini](https://github.com/go-ini/ini) - **star:1520**  读和写INI文件。![star > 1000][Silver]   
* [joshbetz/config](https://github.com/joshbetz/config) - **star:195** 一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - **star:2350** 管理来自环境变量的配置数据。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [koanf](https://github.com/knadh/koanf) - **star:69** 轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。
* [konfig](https://github.com/lalamove/konfig) - **star:507** 可组合、可观察和高性能的分布式配置管理。![star > 100][Bronze]   
* [mini](https://github.com/sasbury/mini) - **star:19** 用于解析ini类型的配置文件。
* [sprbox](https://github.com/oblq/sprbox) - **star:3** 支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。
* [store](https://github.com/tucnak/store) - **star:243** 轻量级配置管理器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [viper](https://github.com/spf13/viper) - **star:8984** 配置管理。![star > 5000][Gold]   
* [xdg](https://github.com/OpenPeeDeeP/xdg) - **star:32** 遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。

## 持续集成

*用于帮助进行持续集成的工具。*

* [drone](https://github.com/drone/drone) - **star:18701** Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [duci](https://github.com/duck8823/duci) - **star:40** 一个简单的 ci 服务。![最近一个周有更新][Green]
* [gomason](https://github.com/nikogura/gomason) - **star:27** 在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。
* [goveralls](https://github.com/mattn/goveralls) - **star:570** Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。![star > 100][Bronze]   
* [overalls](https://github.com/go-playground/overalls) - **star:97** 针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。
* [roveralls](https://github.com/LawrenceWoodman/roveralls) - **star:12** 递归覆盖测试工具。![最近一年没有更新][Yellow]

## CSS预处理器

*用于预处理CSS文件的库。*

* [gcss](https://github.com/yosssi/gcss) - **star:421** 纯Go编写的 CSS 预处理器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-libsass](https://github.com/wellington/go-libsass) - **star:130**  采用 Go封装，100% 与 Sass 兼容的 libsass 项目。![star > 100][Bronze]   

## 数据结构

*用 Go 实现的通用的数据结构和算法。*

* [algorithms](https://github.com/shady831213/algorithms) - **star:229** 算法和数据结构。来源于CLRS。![star > 100][Bronze]   
* [binpacker](https://github.com/zhuangsirui/binpacker) - **star:121** 帮助用户构建自定义二进制流的二进制封装器和解包器![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [bit](https://github.com/yourbasic/bit) - **star:51** Go 语言集合数据结构。提供了额外的位操作功能。![最近一年没有更新][Yellow]
* [bitset](https://github.com/willf/bitset) - **star:476** 实现了 bitsets 的 Go 包。![star > 100][Bronze]   
* [bloom](https://github.com/zhenjl/bloom) - **star:128** 在Go中实现了Bloom过滤器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [bloom](https://github.com/yourbasic/bloom) - **star:38** Golang Bloom过滤器的实现。![最近一年没有更新][Yellow]
* [boomfilters](https://github.com/tylertreat/BoomFilters) - **star:1122** 用于处理连续的概率数据结构。![star > 1000][Silver]   
* [concurrent-writer](https://github.com/free/concurrent-writer) - **star:22** 具备高并发能力，可替换 bufio.Writer。![最近一年没有更新][Yellow]
* [conjungo](https://github.com/InVisionApp/conjungo) - **star:75** 一个小型、强大和灵活的合并库。
* [count-min-log](https://github.com/seiflotfy/count-min-log) - **star:43** Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。![最近一年没有更新][Yellow]
* [crunch](https://github.com/superwhiskers/crunch) - **star:19** 打包实现缓冲区，以便轻松处理各种数据类型。
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - **star:497** 布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。![star > 100][Bronze]   
* [deque](https://github.com/edwingeng/deque) - **star:4** 高度优化的双端队列。
* [deque](https://github.com/gammazero/deque) - **star:58** 快速环缓冲区deque(双端队列)。
* [dict](https://github.com/srfrog/dict) - **star:7** 实现类似 python dict的功能(dict)。
* [encoding](https://github.com/zhenjl/encoding) - **star:93** 整形压缩库。![最近一年没有更新][Yellow]
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - **star:84** 自适应基数树。
* [go-datastructures](https://github.com/Workiva/go-datastructures) - **star:5049** 可靠的、高性能的和线程安全的数据结构的集合。![star > 5000][Gold]   
* [go-ef](https://github.com/amallia/go-ef) - **star:10** 实现了 Elias-Fano 编码。![最近一年没有更新][Yellow]
* [go-geoindex](https://github.com/hailocab/go-geoindex) - **star:309** 基于内存的地理索引。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - **star:32** 基于内存的实现了高性能的key:value存储库。指针缓存。
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) - **star:98** 区域四叉树具有高效的点定位和邻域查找功能。![最近一年没有更新][Yellow]
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - **star:25** 并行FIFO队列。
* [gods](https://github.com/emirpasic/gods) - **star:6034** 数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。![star > 5000][Gold]   
* [golang-set](https://github.com/deckarep/golang-set) - **star:1119** 线程安全和非线程安全的高性能集。![star > 1000][Silver]   
* [goset](https://github.com/zoumo/goset) - **star:16** 一个有用的Go集合实现。![最近一年没有更新][Yellow]
* [goskiplist](https://github.com/ryszard/goskiplist) - **star:192** 基于 Go 的跳表实现。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gota](https://github.com/kniren/gota) - **star:850** 实现了数据帧，序列以及数据噪音。![star > 100][Bronze]   
* [hide](https://github.com/emvi/hide) - **star:7** ID type with marshalling to/from hash to prevent sending IDs to clients.
* [hilbert](https://github.com/google/hilbert) - **star:178** 用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。![star > 100][Bronze]   
* [hyperloglog](https://github.com/axiomhq/hyperloglog) - **star:657** HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.![star > 100][Bronze]   
* [levenshtein](https://github.com/agext/levenshtein) - **star:32** Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
* [levenshtein](https://github.com/agnivade/levenshtein) - **star:53** 实现在Go中计算levenshtein距离。
* [mafsa](https://github.com/smartystreets/mafsa) - **star:273** 实现了 MA-FSA ，包含最小完美哈希。![star > 100][Bronze]   
* [merkletree](https://github.com/cbergoon/merkletree) - **star:142** 实现了merkle树，提供了对数据结构内容的有效和安全的验证。![star > 100][Bronze]   
* [mspm](https://github.com/BlackRabbitt/mspm) - **star:7** 用于信息检索的多字符串模式匹配算法。![最近一年没有更新][Yellow]
* [null](https://github.com/emvi/null) - **star:5** 对空的 Go 数据类型也可以进行JSON进行解析/反解析。
* [parsefields](https://github.com/MonaxGT/parsefields) - **star:3** 用于解析类似json的日志的工具，用于收集惟一的字段和事件。
* [pipeline](https://github.com/hyfather/pipeline) - **star:15** 实现了 fan-in 和 fan-out 的管道功能。
* [ring](https://github.com/TheTannerRyan/ring) - **star:86** 高性能、线程安全的bloom过滤器。
* [roaring](https://github.com/RoaringBitmap/roaring) - **star:642** 实现了压缩 bitsets 的Go包。![star > 100][Bronze]   
* [set](https://github.com/StudioSol/set) - **star:6** 使用LinkedHashMap在Go中实现简单的set数据结构。
* [skiplist](https://github.com/MauriceGit/skiplist) - **star:96** 高性能的 Go 跳表实现。
* [skiplist](https://github.com/gansidui/skiplist) - **star:62** 在Go中实现了跳表。![最近一年没有更新][Yellow]
* [timedmap](https://github.com/zekroTJA/timedmap) - **star:1** 实现了有生命周期的键值对Map。
* [treap](https://github.com/perdata/treap) - **star:7** 使用树堆进行持久、快速有序的映射。
* [trie](https://github.com/derekparker/trie) - **star:408** 在Go中实现Trie。![star > 100][Bronze]   
* [ttlcache](https://github.com/diegobernardes/ttlcache) - **star:92** 基于内存的LRU算法实现。
* [typ](https://github.com/gurukami/typ) - **star:9** 从复杂结构中获取值，支持空类型、安全的类型转换。
* [willf/bloom](https://github.com/willf/bloom) - **star:647** 实现Bloom过滤器。![star > 100][Bronze]   

## 数据库

*数据库。*

* [badger](https://github.com/dgraph-io/badger) - **star:6105** 快速 K/V 存储。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [bcache](https://github.com/iwanbk/bcache) - **star:26** 基于内存的最终一致的分布式缓存。
* [BigCache](https://github.com/allegro/bigcache) - **star:2392** 高效的键/值缓存为千兆字节的数据。![star > 1000][Silver]   
* [bolt](https://github.com/boltdb/bolt) - **star:9869** K/V 数据库。![star > 5000][Gold]   ![最近一年没有更新][Yellow]
* [buntdb](https://github.com/tidwall/buntdb) - **star:2419** 基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。![star > 1000][Silver]   
* [cache](https://github.com/akyoto/cache) - **star:10** 基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。
* [cache2go](https://github.com/muesli/cache2go) - **star:929** 基于内存的 K/V 缓存，支持超时的自动失效。![star > 100][Bronze]   
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - **star:29** BigCache 支持集群和独立且生命周期存储项。![最近一年没有更新][Yellow]
* [cockroach](https://github.com/cockroachdb/cockroach) - **star:16566** 可伸缩、区域备份、事务性数据存储。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [couchcache](https://github.com/codingsince1985/couchcache) - **star:40** 由 Couchbase服务 支持的RESTful缓存微服务。
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - **star:1425** 区块链领域的一个SQL数据库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [dgraph](https://github.com/dgraph-io/dgraph) - **star:9918** 可伸缩、分布式、低延迟、高吞吐量的图形数据库。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [diskv](https://github.com/peterbourgon/diskv) - **star:736** 支持磁盘备份的可持久化 K/V 存储。![star > 100][Bronze]   
* [eliasdb](https://github.com/krotik/eliasdb) - **star:532** 无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。![star > 100][Bronze]   
* [fastcache](https://github.com/VictoriaMetrics/fastcache) - **star:467** 基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。![star > 100][Bronze]   
* [GCache](https://github.com/bluele/gcache) - **star:863** 支持过期缓存、LFU、LRU和ARC的缓存库。![star > 100][Bronze]   
* [go-cache](https://github.com/pmylund/go-cache) - **star:2792** 基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。![star > 1000][Silver]   
* [goleveldb](https://github.com/syndtr/goleveldb) - **star:3100** 在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) - **star:8** 用 Go 对[RocksDB](https://rocksdb.org)实现了封装。![最近一年没有更新][Yellow]
* [groupcache](https://github.com/golang/groupcache) - **star:7552** Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [influxdb](https://github.com/influxdb/influxdb) - **star:16709** 可伸缩的数据存储，用于指标衡量、事件和实时分析。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [ledisdb](https://github.com/siddontang/ledisdb) - **star:3040** Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。![star > 1000][Silver]   
* [levigo](https://github.com/jmhodges/levigo) - **star:363** 实现了对LevelDB封装。![star > 100][Bronze]   
* [moss](https://github.com/couchbase/moss) - **star:715** Moss是一个用100% Go编写的简单LSM键值存储引擎。![star > 100][Bronze]   
* [nutsdb](https://github.com/xujiajun/nutsdb) - **star:846** Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。![star > 100][Bronze]   
* [piladb](https://github.com/fern4lvarez/piladb) - **star:170** 基于堆栈数据结构的轻量级RESTful数据库引擎。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [prometheus](https://github.com/prometheus/prometheus) - **star:24922** 用于监控系统和时序的数据库。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [pudge](https://github.com/recoilme/pudge) - **star:215** 使用Go的标准库编写的快速和简单的键/值存储。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [rqlite](https://github.com/rqlite/rqlite) - **star:4637** 基于SQLite的轻量级分布式关系数据库。![star > 1000][Silver]   
* [Scribble](https://github.com/nanobox-io/golang-scribble) - **star:55** 小型平面文件JSON存储。
* [slowpoke](https://github.com/recoilme/slowpoke) - **star:85** 具有持久性的键值存储。
* [tempdb](https://github.com/rafaeljesus/tempdb) - **star:13** 用于临时数据存放的 K/V 存储。![最近一年没有更新][Yellow]
* [tidb](https://github.com/pingcap/tidb) - **star:19538** TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [tiedot](https://github.com/HouzuoGuo/tiedot) - **star:2352** 属于你的NoSQL数据库。![star > 1000][Silver]   
* [Vasto](https://github.com/chrislusf/vasto) - **star:142** 分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。![star > 100][Bronze]   
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - **star:880** 开源，快速，可伸缩的时间序列数据库。支持PromQL。![star > 100][Bronze]   ![最近一个周有更新][Green]

*数据库迁移。*

* [avro](https://github.com/khezen/avro) - **star:4** 发现SQL schemas并将其转换为AVRO schemas。![最近一个周有更新][Green]
* [darwin](https://github.com/GuiaBolso/darwin) - **star:84** 用于数据库 schema 升级的库。
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) - **star:19** 类似 Django fixture，用于 Go 建立内置数据库/sql库。
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - **star:23** 用Go -pg/pg编写的迁移包。
* [gondolier](https://github.com/emvi/gondolier) - **star:26** 使用结构修饰的数据库迁移库。
* [goose](https://github.com/steinbacher/goose) - **star:115** 数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gormigrate](https://github.com/go-gormigrate/gormigrate) - **star:317** 面向Gorm ORM的数据库 schema 迁移辅助程序。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [migrate](https://github.com/golang-migrate/migrate) - **star:2433** 基于CLI的数据库迁移库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [migrator](https://github.com/lopezator/migrator) - **star:26** 非常简单的 Go 数据库迁移库。
* [pravasan](https://github.com/pravasan/pravasan) - **star:24** 简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。
* [soda](https://github.com/gobuffalo/pop/tree/master/soda) - 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。
* [sql-migrate](https://github.com/rubenv/sql-migrate) - **star:1374** 数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。![star > 1000][Silver]   

*数据库工具。*

* [chproxy](https://github.com/Vertamedia/chproxy) - **star:293** ClickHouse数据库的HTTP代理。![star > 100][Bronze]   
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - **star:127** 收集小的 insterts 并向 ClickHouse 服务器发送大请求。![star > 100][Bronze]   
* [datagen](https://github.com/codingconcepts/datagen) - **star:5** 一个快速的数据生成器，支持多表感知和多行DML。
* [dbbench](https://github.com/sj14/dbbench) - **star:30** 数据库基准测试工具，支持多个数据库和脚本。
* [go-mysql](https://github.com/siddontang/go-mysql) - **star:1804**  Go 工具集，用于处理MySQL协议和复制。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - **star:2286** 自动将MySQL数据同步到Elasticsearch中。![star > 1000][Silver]   
* [kingshard](https://github.com/flike/kingshard) - **star:4530** kingshard 是基于 Golang 的MySQL高性能代理。![star > 1000][Silver]   
* [myreplication](https://github.com/2tvenom/myreplication) - **star:142** MySql二进制日志复制监听器。支持基于语句和行的复制。![star > 100][Bronze]   
* [octillery](https://github.com/knocknote/octillery) - **star:46** 用于数据库分表(支持每个ORM或原生SQL)。
* [orchestrator](https://github.com/github/orchestrator) - **star:2958** MySQL复制拓扑管理器和可视化工具。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [pgweb](https://github.com/sosedoff/pgweb) - **star:5940** 基于web的PostgreSQL数据库浏览器。![star > 5000][Gold]   
* [prep](https://github.com/hexdigest/prep) - **star:24** 在不更改代码的情况下使用准备好的SQL语句。![最近一年没有更新][Yellow]
* [pREST](https://github.com/nuveo/prest) - **star:2055** 基于PostgreSQL database的RESTful API服务。![star > 1000][Silver]   
* [rwdb](https://github.com/andizzle/rwdb) - **star:10** rwdb为多个数据库服务器的设置提供读取副本功能。![最近一年没有更新][Yellow]
* [vitess](https://github.com/youtube/vitess) - **star:8284** vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。![star > 5000][Gold]   ![最近一个周有更新][Green]

*SQL查询生成器，用于构建和使用SQL的库。*

* [Dotsql](https://github.com/gchaincl/dotsql) - **star:435** Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。![star > 100][Bronze]   
* [gendry](https://github.com/didi/gendry) - **star:695** 非入侵的SQL构建器和强大的数据绑定器。![star > 100][Bronze]   
* [godbal](https://github.com/xujiajun/godbal) - **star:50** 数据库抽象层(dbal)。支持SQL builder，轻松获取结果。
* [goqu](https://github.com/doug-martin/goqu) - **star:521** 常用的SQL生成器和查询库。![star > 100][Bronze]   
* [igor](https://github.com/galeone/igor) - **star:77** PostgreSQL的抽象层，支持高级功能和类似gorm的语法。![最近一年没有更新][Yellow]
* [ormlite](https://github.com/pupizoid/ormlite) - 包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - **star:434** Powerful data retrieval methods as well as DB-agnostic query building capabilities.![star > 100][Bronze]   
* [scaneo](https://github.com/variadico/scaneo) - **star:149** 生成用于将数据库行转换为任意结构体的 Go 代码。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [sqrl](https://github.com/elgris/sqrl) - **star:173** SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。![star > 100][Bronze]   
* [Squalus](https://gitlab.com/qosenergy/squalus) - Go SQL中间层，能使得执行查询更加容易。
* [Squirrel](https://github.com/Masterminds/squirrel) - **star:2194** 帮助您构建SQL查询的Go库。![star > 1000][Silver]   
* [xo](https://github.com/knq/xo) - **star:2118** 基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。![star > 1000][Silver]   ![最近一个周有更新][Green]

## 数据库驱动程序

*用于连接和操作数据库的库。*

* Relational Databases
    * [avatica](https://github.com/apache/calcite-avatica-go) - **star:31** Apache Avatica/Phoenix SQL驱动程序。
    * [bgc](https://github.com/viant/bgc) - **star:12** BigQuery 的数据存储连接。
    * [firebirdsql](https://github.com/nakagami/firebirdsql) - **star:102** Firebird RDBMS SQL驱动程序。![star > 100][Bronze]   
    * [go-adodb](https://github.com/mattn/go-adodb) - **star:90** Microsoft ActiveX对象数据库驱动程序。
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - **star:999** 微软MSSQL驱动程序。![star > 100][Bronze]   
    * [go-oci8](https://github.com/mattn/go-oci8) - **star:398** Oracle 驱动程序。![star > 100][Bronze]   
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - **star:7875** MySQL驱动程序。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - **star:3351** SQLite3驱动程序。![star > 1000][Silver]   
    * [gofreetds](https://github.com/minus5/gofreetds) - **star:90** 基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。
    * [goracle](https://github.com/go-goracle/goracle) - **star:228** 基于 ODPI-C 的 Oracle 驱动程序![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [pgx](https://github.com/jackc/pgx) - **star:1856** PostgreSQL驱动，支持比现有database/sql更多的特性。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [pq](https://github.com/lib/pq) - **star:5071** 纯 Go 的Postgres驱动。![star > 5000][Gold]   ![最近一个周有更新][Green]

* NoSQL Databases
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - **star:301** Aerospike 客户端。![star > 100][Bronze]   
    * [arangolite](https://github.com/solher/arangolite) - **star:65** 轻量级的 ArangoDB 驱动。
    * [asc](https://github.com/viant/asc) - **star:4** Aerospike 的数据存储连接器。
    * [dynago](https://github.com/underarmour/dynago) - **star:65** 满足 principle of least surprise 的 DynamoDB 客户端。![最近一年没有更新][Yellow]
    * [forestdb](https://github.com/couchbase/goforestdb) - **star:30** 基于 Go 的 ForestDB 接口实现。![最近一年没有更新][Yellow]
    * [go-couchbase](https://github.com/couchbase/go-couchbase) - **star:292** Couchbase客户端。![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [go-couchdb](https://github.com/fjl/go-couchdb) - **star:52** 基于 Go 的 Yet another CouchDB 的 Http 接口封装。
    * [go-pilosa](https://github.com/pilosa/go-pilosa) - **star:32**  Pilosa客户端。
    * [go-rejson](https://github.com/nitishm/go-rejson) - **star:85** 实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。
    * [gocb](https://github.com/couchbase/gocb) - **star:289** 官方Couchbase Go SDK。![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [gocql](http://gocql.github.io) - Apache Cassandra 的 Go 驱动。
    * [godscache](https://github.com/defcronyke/godscache) - **star:6** 谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache客户端库。
    * [gorethink](https://github.com/dancannon/gorethink) - **star:1456** RethinkDB 驱动。![star > 1000][Silver]   
    * [goriak](https://github.com/zegl/goriak) - **star:24**  Riak KV 驱动。
    * [mgo](https://github.com/globalsign/mgo) - **star:1605** (已停止维护) MongoDB驱动。![star > 1000][Silver]   
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - **star:2895** 官方的 MongoDB 驱动。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [neo4j](https://github.com/cihangir/neo4j) - **star:24** Neo4j Rest API实现。![最近一年没有更新][Yellow]
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) - **star:72** Neo4j REST 客户端。![最近一年没有更新][Yellow]
    * [neoism](https://github.com/jmcvetta/neoism) - **star:355** Golang 的 Neo4j 客户端。![star > 100][Bronze]   
    * [redeo](https://github.com/bsm/redeo) - **star:258** 与 redis 协议兼容的 TCP 服务器/服务。![star > 100][Bronze]   
    * [redigo](https://github.com/gomodule/redigo) - **star:6128** Redigo 是基于 Go 的Redis 客户端。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [redis](https://github.com/go-redis/redis) - **star:6189** 基于 Go 的 Redis 客户端。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [xredis](https://github.com/shomali11/xredis) - **star:9** 类型安全，可定制，清晰和易用的Redis客户端。

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - **star:5745** 基于 Go 的现代文本索引库。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [elastic](https://github.com/olivere/elastic) - **star:4001** Elasticsearch 客户端。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [elasticsql](https://github.com/cch123/elasticsql) - **star:370** 将 SQL 转换为 elasticsearch dsl。![star > 100][Bronze]   
    * [elastigo](https://github.com/mattbaird/elastigo) - **star:948** Elasticsearch 客户端。![star > 100][Bronze]   
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - **star:1468** 官方 Elasticsearch 客户端。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [goes](https://github.com/OwnLocal/goes) - **star:24** 实现了与 Elasticsearch 交互的库。![最近一年没有更新][Yellow]
    * [riot](https://github.com/go-ego/riot) - **star:4633** 基于 Go 的 开源、分布式、简单高效的搜索引擎。![star > 1000][Silver]   
    * [skizze](https://github.com/seiflotfy/skizze) - **star:68** 面向概率数据结构的服务和存储。![最近一年没有更新][Yellow]

* Multiple Backends.
    * [cachego](https://github.com/fabiorphp/cachego) - **star:110** 基于多个驱动程序的缓存组件。![star > 100][Bronze]   
    * [cayley](https://github.com/google/cayley) - **star:12601** 图形数据库，支持多个后端。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [dsc](https://github.com/viant/dsc) - **star:12** 面向 SQL、NoSQL、结构化文件的数据存储连接。
    * [gokv](https://github.com/philippgille/gokv) - **star:74** 可扩展的简单的 K/V 存储(Redis、、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。

## 日期和时间

*用于处理日期和时间的库。*

* [carbon](https://github.com/uniplaces/carbon) - **star:331** 简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。![star > 100][Bronze]   
* [date](https://github.com/rickb777/date) - **star:27** 增加处理日期、日期范围、时间跨度、时间段和time-of-day。
* [dateparse](https://github.com/araddon/dateparse) - **star:876** 可以解析很多格式不固定的日期字符串。![star > 100][Bronze]   
* [durafmt](https://github.com/hako/durafmt) - **star:235** 轻量级、可让time.Duration更加易读的库。![star > 100][Bronze]   
* [feiertage](https://github.com/wlbr/feiertage) - **star:21** 用于计算德国公共假期的函数，比如复活节、感恩节等
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - **star:59** 太阳历实现。
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) - **star:13** 计算指定位置的日出和日落时间。![最近一年没有更新][Yellow]
* [goweek](https://github.com/grsmv/goweek) - **star:18** 用于处理以星期实体单位的库。![最近一年没有更新][Yellow]
* [iso8601](https://github.com/relvacode/iso8601) - **star:67** 不用正则表达式有效解析 ISO8601 日期时间。
* [kair](https://github.com/GuilhermeCaruso/kair) - **star:9** 用于处理日期和时间的 golang 库。
* [now](https://github.com/jinzhu/now) - **star:2132** now 是时间有关的工具类。![star > 1000][Silver]   
* [NullTime](https://github.com/kirillDanshin/nulltime) - **star:9** 可以允许 time.Time 为null。![最近一年没有更新][Yellow]
* [strftime](https://github.com/awoodbeck/strftime) - **star:5** C99-compatible strftime formatter。![最近一年没有更新][Yellow]
* [timespan](https://github.com/SaidinWoT/timespan) - **star:60** 用于处理时间间隔相关的库，可定义开始时间和持续时间。
* [timeutil](https://github.com/leekchan/timeutil) - **star:168** 面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。![star > 100][Bronze]   
* [tuesday](https://github.com/osteele/tuesday) - **star:7** Ruby-compatible Strftime function。![最近一年没有更新][Yellow]

## 分布式系统

*协助构建分布式系统的包。*

* [celeriac](https://github.com/svcavallar/celeriac.v1) - **star:52** 用于对 Celery worker、任务、事件进行交互和监控的库。
* [consistent](https://github.com/buraksezer/consistent) - **star:181** Consistent hashing with bounded loads。![star > 100][Bronze]   
* [dht](https://github.com/anacrolix/dht) - **star:122** BitTorrent Kademlia DHT的实现。![star > 100][Bronze]   
* [digota](https://github.com/digota/digota) - **star:296** 基于 grpc 的电子商务微服务。![star > 100][Bronze]   
* [dot](https://github.com/dotchain/dot/) - 基于 transformation/OT 的分布式同步。
* [doublejump](https://github.com/edwingeng/doublejump) - **star:38** 实现了谷歌的jump consistent hash。
* [dragonboat](https://github.com/lni/dragonboat) - **star:2444** 一个功能齐全，高性能的库集。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [drmaa](https://github.com/dgruber/drmaa) - **star:24** 符合 DRMAA 标准的集群调度程序作业提交库。![最近一年没有更新][Yellow]
* [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed 分布式锁定实现。
* [dynatomic](https://github.com/tylfin/dynatomic) - **star:8** 基于 DynamoDB 的 原子计数器的库。
* [emitter-io](https://github.com/emitter-io/emitter) - **star:1872** 高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [flowgraph](https://github.com/vectaport/flowgraph) - **star:17** flow-based programming package。
* [gleam](https://github.com/chrislusf/gleam) - **star:2041** 使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [glow](https://github.com/chrislusf/glow) - **star:2495** 全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。![star > 1000][Silver]   
* [go-health](https://github.com/InVisionApp/go-health) - **star:473** 用于在服务中启用异步依赖项健康检查的库。![star > 100][Bronze]   
* [go-jump](https://github.com/dgryski/go-jump) - **star:251** 提供了谷歌的 “Jump” 一致哈希函数接口。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-kit](https://github.com/go-kit/kit) - **star:14106** 支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [gorpc](https://github.com/valyala/gorpc) - **star:546** 简单、快速和可伸缩的RPC库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [grpc-go](https://github.com/grpc/grpc-go) - **star:8744** gRPC的Go语言实现。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [hprose](https://github.com/hprose/hprose-golang) - **star:990** 支持25+种语言RPC库。![star > 100][Bronze]   
* [jaeger](https://github.com/jaegertracing/jaeger) - **star:8402** 分布式跟踪系统。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [jsonrpc](https://github.com/osamingo/jsonrpc) - **star:113** jsonrpc 包，实现了 JSON-RPC 2.0。![star > 100][Bronze]   
* [jsonrpc](https://github.com/ybbus/jsonrpc) - **star:97** JSON-RPC 2.0 HTTP客户端。
* [KrakenD](https://github.com/devopsfaith/krakend) - **star:1637** 具有中间件的高性能API网关框架。![star > 1000][Silver]   
* [micro](https://github.com/micro/micro) - **star:6425** 可插拔的微服务 toolkit 和分布式系统平台。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [NATS](https://github.com/nats-io/gnatsd) - **star:5924** 轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [outboxer](https://github.com/italolelis/outboxer) - **star:2** 实现了 outbox pattern Go 库。
* [pglock](https://cirello.io/pglock) - postgresql 的分布式锁定实现。
* [raft](https://github.com/hashicorp/raft) - **star:2774** Raft consensus协议的实现。 by HashiCorp。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Raft consensus协议的实现。 by CoreOS。
* [redis-lock](https://github.com/bsm/redis-lock) - **star:146** 基于redis的分布式锁简易实现。![star > 100][Bronze]   
* [resgate](https://resgate.io/) - 用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。
* [ringpop-go](https://github.com/uber/ringpop-go) - **star:564** 可伸缩的，容错、应用分层的的Go应用程序。![star > 100][Bronze]   
* [rpcx](https://github.com/smallnest/rpcx) - **star:3674** 分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [sleuth](https://github.com/ursiform/sleuth) - **star:298** 用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [tendermint](https://github.com/tendermint/tendermint) - **star:3064** 一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [torrent](https://github.com/anacrolix/torrent) - **star:2769** BitTorrent 客户端。![star > 1000][Silver]   

## 电子邮件

*实现了电子邮件创建和发送。*

* [chasquid](https://blitiri.com.ar/p/chasquid) - 用Go编写的SMTP服务器。
* [douceur](https://github.com/aymerick/douceur) - **star:157** 在HTML邮件中支持CSS内联。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [email](https://github.com/jordan-wright/email) - **star:1074** 一个强大和灵活的电子邮件库。![star > 1000][Silver]   
* [go-dkim](https://github.com/toorop/go-dkim) - **star:46** DKIM库，用于签署 & 验证电子邮件。
* [go-imap](https://github.com/emersion/go-imap) - **star:706** 用于客户端和服务器的IMAP库。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-message](https://github.com/emersion/go-message) - **star:102** 用于Internet消息格式化和邮件消息的流媒体库。![star > 100][Bronze]   
* [go-premailer](https://github.com/vanng822/go-premailer) - **star:34** 在HTML邮件中支持CSS内联。
* [Gomail](https://github.com/go-gomail/gomail/) - 一个非常简单和强大的邮件发送库。
* [Hectane](https://github.com/hectane/hectane) - **star:168** 轻量级的SMTP客户机，提供了HTTP API。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [hermes](https://github.com/matcornic/hermes) - **star:1592** 可生成干净的、响应式的HTML电子邮件。![star > 1000][Silver]   
* [MailHog](https://github.com/mailhog/MailHog) - **star:5030** 电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。![star > 5000][Gold]   
* [SendGrid](https://github.com/sendgrid/sendgrid-go) - **star:515** SendGrid 的 Go语言库，用于发送电子邮件。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [smtp](https://github.com/mailhog/smtp) - **star:49** SMTP服务器协议状态机。![最近一年没有更新][Yellow]

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。*

* [agora](https://github.com/PuerkitoBio/agora) - **star:321** 基于 Go 的动态类型，可嵌入的编程语言。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [anko](https://github.com/mattn/anko) - **star:902** 用Go编写的解释器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [binder](https://github.com/alexeyco/binder) - **star:29** Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。
* [expr](https://github.com/antonmedv/expr) - **star:594** 一个可以计算表达式的引擎。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [gentee](https://github.com/gentee/gentee) - **star:25** 嵌入式脚本编程语言。![最近一个周有更新][Green]
* [gisp](https://github.com/jcla1/gisp) - **star:428** LISP 的 Go 接口。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-duktape](https://github.com/olebedev/go-duktape) - **star:648** 支持 Duktape JavaScript 引擎。![star > 100][Bronze]   
* [go-lua](https://github.com/Shopify/go-lua) - **star:1639** 用 Go 实现的 Lua 5.2 VM接口。![star > 1000][Silver]   
* [go-php](https://github.com/deuill/go-php) - **star:669** PHP 的 Go 接口。![star > 100][Bronze]   
* [go-python](https://github.com/sbinet/go-python) - **star:890** CPython C-API 的 Go 接口。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [golua](https://github.com/aarzilli/golua) - **star:434** Lua C 的 Go 接口。![star > 100][Bronze]   
* [gopher-lua](https://github.com/yuin/gopher-lua) - **star:2906** 用 Go 实现的 Lua 5.1 虚拟机和编译器。![star > 1000][Silver]   
* [gval](https://github.com/PaesslerAG/gval) - **star:131** 一种用Go编写的高度可定制的表达式语言。![star > 100][Bronze]   
* [ngaro](https://github.com/db47h/ngaro) - **star:18** 嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。![最近一年没有更新][Yellow]
* [otto](https://github.com/robertkrimen/otto) - **star:4654** 用 Go 编写的 JavaScript 解释器。![star > 1000][Silver]   
* [purl](https://github.com/ian-kent/purl) - **star:27** 嵌入 Go 的 Perl 5.18.2。![最近一年没有更新][Yellow]
* [tengo](https://github.com/d5/tengo) - **star:1269** 字节码编译的脚本语言。![star > 1000][Silver]   ![最近一个周有更新][Green]

## 错误处理

*处理错误的库。*

* [errlog](https://github.com/snwfdhmp/errlog) - **star:142** 用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。![star > 100][Bronze]   
* [errors](https://github.com/pkg/errors) - **star:4701** 可让你很简单的进行错误处理。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [errorx](https://github.com/joomcode/errorx) - **star:546** 一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。![star > 100][Bronze]   
* [go-multierror](https://github.com/hashicorp/go-multierror) - **star:703** 可将一系列的错误作为一个整体来显示。![star > 100][Bronze]   
* [tracerr](https://github.com/ztrue/tracerr) - **star:485** 可展示错误的堆栈跟踪信息和源码片段。![star > 100][Bronze]   
* [werr](https://github.com/txgruppi/werr) - **star:10** 对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。![最近一年没有更新][Yellow]

## 文件

*处理文件和文件系统的库。*

* [afero](https://github.com/spf13/afero) - **star:2178** 文件系统的抽象系统。![star > 1000][Silver]   
* [checksum](https://github.com/codingsince1985/checksum) - **star:6** 生成大型文件的消息摘要(如 MD5 和 SHA256)。
* [flop](https://github.com/homedepot/flop) - **star:8** 文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp- invoc.html)的镜像。
* [go-csv-tag](https://github.com/artonge/go-csv-tag) - **star:44** 使用 tag 加载 csv 文件。
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - **star:11** 拷贝文件。
* [go-exiftool](https://github.com/barasher/go-exiftool) - **star:1** ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。
* [go-gtfs](https://github.com/artonge/go-gtfs) - **star:15** 加载gtfs文件。
* [notify](https://github.com/rjeczalik/notify) - **star:484** 文件系统事件通知库，具有类似于os/signal的简单API，。![star > 100][Bronze]   
* [opc](https://github.com/qmuntal/opc) - **star:57** 加载Open Packaging Conventions (OPC)文件。
* [pdfcpu](https://github.com/hhrutter/pdfcpu) - **star:923** PDF处理器。![star > 100][Bronze]   
* [skywalker](https://github.com/dixonwille/skywalker) - **star:47** 可以轻松地并发地遍历文件系统。![最近一年没有更新][Yellow]
* [stl](https://gitlab.com/russoj88/stl) - 采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。
* [tarfs](https://github.com/posener/tarfs) - **star:35** tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。![最近一年没有更新][Yellow]
* [vfs](https://github.com/C2FO/vfs) - **star:19** 一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。![最近一个周有更新][Green]

## 金融

*会计和财务软件包。*

* [accounting](https://github.com/leekchan/accounting) - **star:478** 货币和货币格式。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [currency](https://github.com/bnkamalesh/currency) - **star:8** 高性能、准确的货币计算软件包。
* [decimal](https://github.com/shopspring/decimal) - **star:1544** 任意精度定点的十进制数。![star > 1000][Silver]   
* [go-finance](https://github.com/FlashBoys/go-finance) - **star:538** 综合金融市场数据。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-finance](https://github.com/alpeb/go-finance) - **star:39** 用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。![最近一年没有更新][Yellow]
* [go-money](https://github.com/rhymond/go-money) - **star:606** Fowler 货币模式的实现。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [ofxgo](https://github.com/aclindsa/ofxgo) - **star:59** 查询 OFX 服务器和/或解析响应。![最近一个周有更新][Green]
* [orderbook](https://github.com/i25959341/orderbook) - **star:63** 限购单匹配引擎。
* [techan](https://github.com/sdcoffey/techan) - **star:143** 拥有先进的市场分析和交易策略的技术分析库。![star > 100][Bronze]   
* [transaction](https://github.com/claygod/transaction) - **star:52** 嵌入式事务数据库，可多线程模式运行。
* [vat](https://github.com/dannyvankooten/vat) - **star:60** 增值税编号验证 & 欧盟增值税税率。

## 表单

*用于处理表单的库。*

* [bind](https://github.com/robfig/bind) - **star:23** 将表单数据与任意 Go 变量进行绑定。![最近一年没有更新][Yellow]
* [binding](https://github.com/mholt/binding) - **star:753** 将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [conform](https://github.com/leebenson/conform) - **star:171** 控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [form](https://github.com/go-playground/form) - **star:347**  将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。![star > 100][Bronze]   
* [formam](https://github.com/monoculum/formam) - **star:123** 将表单的值解码为 struct。![star > 100][Bronze]   
* [forms](https://github.com/albrow/forms) - **star:103** 与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gorilla/csrf](https://github.com/gorilla/csrf) - **star:423** 用于Go web应用程序和服务的CSRF保护。![star > 100][Bronze]   
* [nosurf](https://github.com/justinas/nosurf) - **star:956** CSRF保护中间件。![star > 100][Bronze]   

## 方法

*在Go中支持函数式编程的包。*

* [fpGo](https://github.com/TeaEntityLab/fpGo) - **star:100** 提供函数式编程功能。![star > 100][Bronze]   
* [fuego](https://github.com/seborama/fuego) - **star:33** Functional Experiment in Go。
* [go-underscore](https://github.com/tobyhede/go-underscore) - **star:1060** 常用辅助方法集合。![star > 1000][Silver]   

## 游戏开发

*很棒的游戏开发库。*

* [Azul3D](https://github.com/azul3d/engine) - **star:422** 用Go编写的 3D 游戏引擎。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Ebiten](https://github.com/hajimehoshi/ebiten) - **star:1783** 很简单的 2D 游戏库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [engo](https://github.com/EngoEngine/engo) - **star:1072** 开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。![star > 1000][Silver]   
* [g3n](https://github.com/g3n/engine) - **star:722**  3D游戏引擎。![star > 100][Bronze]   
* [GarageEngine](https://github.com/vova616/GarageEngine) - **star:308** 用 OpenGL 编写的 2D 游戏引擎。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [glop](https://github.com/runningwild/glop) - **star:77** Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。![最近一年没有更新][Yellow]
* [go-astar](https://github.com/beefsack/go-astar) - **star:324** 实现了A\*路径查找算法。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-collada](https://github.com/GlenKelley/go-collada) - **star:12** 处理Collada文件。![最近一年没有更新][Yellow]
* [go-sdl2](https://github.com/veandco/go-sdl2) - **star:1133** 实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。![star > 1000][Silver]   
* [go3d](https://github.com/ungerik/go3d) - **star:162** 以性能为主的2D/3D数学相关包。![star > 100][Bronze]   
* [gonet](https://github.com/xtaci/gonet) - **star:1042** 实现了游戏服务器骨架。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [goworld](https://github.com/xiaonanln/goworld) - **star:1134** 可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。![star > 1000][Silver]   
* [Leaf](https://github.com/name5566/leaf) - **star:2994** 轻量级游戏服务器框架。![star > 1000][Silver]   
* [nano](https://github.com/lonng/nano) - **star:961** 轻量级、方便、高性能的基于golang的游戏服务器框架。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [Oak](https://github.com/oakmound/oak) - **star:622** 纯 Go 实现的游戏引擎。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [Pitaya](https://github.com/topfreegames/pitaya) - **star:287** 可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。![star > 100][Bronze]   
* [Pixel](https://github.com/faiface/pixel) - **star:2372** 手工制作的 2D 游戏库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [raylib-go](https://github.com/gen2brain/raylib-go) - **star:377** 实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。![star > 100][Bronze]   
* [termloop](https://github.com/JoelOtter/termloop) - **star:1018** 基于终端的 Go 游戏引擎，建立在 Termbox 之上。![star > 1000][Silver]   

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。*

* [efaceconv](https://github.com/t0pep0/efaceconv) - **star:42** 代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。![最近一年没有更新][Yellow]
* [gen](https://github.com/clipperhouse/gen) - **star:1018** 用于生成泛型等类似方法的功能代码生成工具。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [generis](https://github.com/senselogic/GENERIS) - **star:18** 提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。
* [go-enum](https://github.com/abice/go-enum) - **star:80** 从代码注释中生成枚举。
* [go-linq](https://github.com/ahmetalpbalkan/go-linq) - **star:1760** 提供类似 .NET LINQ 的查询方法。![star > 1000][Silver]   
* [goderive](https://github.com/awalterschulze/goderive) - **star:720** 从输入类型来派生函数。![star > 100][Bronze]   
* [gotype](https://github.com/wzshiming/gotype) - **star:19** Golang 源码解析，用法类似reflect(反射)。
* [GoWrap](https://github.com/hexdigest/gowrap) - **star:258** 使用简单模板为 Go 接口生成装饰器。![star > 100][Bronze]   
* [interfaces](https://github.com/rjeczalik/interfaces) - **star:185** 用于生成接口定义的命令行工具。![star > 100][Bronze]   
* [jennifer](https://github.com/dave/jennifer) - **star:1251** 不使用模板生成任意 Go 代码。![star > 1000][Silver]   
* [pkgreflect](https://github.com/ungerik/pkgreflect) - **star:84** 用于包作用域反射的 Go 预处理器。![最近一年没有更新][Yellow]

## 地理

*地理工具和服务器*

* [geocache](https://github.com/melihmucuk/geocache) - **star:107** 基于内存缓存的的地理位置的应用程序。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [geoserver](https://github.com/hishamkaram/geoserver) - **star:25** 基于geoserver REST API的 geoserver 实例。![最近一个周有更新][Green]
* [gismanager](https://github.com/hishamkaram/gismanager) - **star:18** 将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。
* [osm](https://github.com/paulmach/osm) - **star:59** 用于读取、写入和处理 OpenStreetMap 数据和 APIs。
* [pbf](https://github.com/maguro/pbf) - **star:15** 基于Golang 的 OpenStreetMap PBF 编码器/解码器。
* [S2 geometry](https://github.com/golang/geo) - **star:871** S2 geometry 库。![star > 100][Bronze]   
* [Tile38](https://github.com/tidwall/tile38) - **star:6267** 具有空间索引和实时地理定位功能的地理定位数据库。![star > 5000][Gold]   ![最近一个周有更新][Green]

## Go 编译器

*可将 Go 转换为其他语言的编译工具。*

* [c4go](https://github.com/Konstantin8105/c4go) - **star:142** 将 C 代码转换为 Go 代码。![star > 100][Bronze]   
* [f4go](https://github.com/Konstantin8105/f4go) - **star:11** 将 FORTRAN 77 转换为 Go代码。
* [gopherjs](https://github.com/gopherjs/gopherjs) - **star:8426** 将 Go 编译成 JavaScript。![star > 5000][Gold]   
* [llgo](https://github.com/go-llvm/llgo) - **star:985** 基于 llvm 的编译器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [tardisgo](https://github.com/tardisgo/tardisgo) - **star:392** Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器.![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## Goroutines

*管理和处理 Goroutines 的工具。*

* [ants](https://github.com/panjf2000/ants) - **star:1755** 一个高性能的协程池。![star > 1000][Silver]   
* [artifex](https://github.com/borderstech/artifex) - **star:12** 简单的内存作业队列。
* [async](https://github.com/studiosol/async) - **star:18** 一种异步执行函数的安全方法，在出现 panic 时恢复它们。
* [breaker](https://github.com/kamilsk/breaker) - **star:24** 灵活的机制，可以使执行流可中断。![最近一个周有更新][Green]
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - **star:27** 基于 Go 的 CyclicBarrier 实现。
* [go-floc](https://github.com/workanator/go-floc) - **star:168** 轻松编排 goroutines。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) - **star:103** 控制 goroutines 的执行顺序。![star > 100][Bronze]   
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - **star:5** 轻量级的协程池库，可以通过简单的API来管理。
* [go-trylock](https://github.com/subchen/go-trylock) - **star:4** 支持 read-write 锁。![最近一年没有更新][Yellow]
* [gollback](https://github.com/vardius/gollback) - **star:25** 异步简单的函数实用程序，用于管理闭包和回调的执行。
* [GoSlaves](https://github.com/themester/GoSlaves) - **star:74** 简单异步的协程池。
* [goworker](https://github.com/benmanns/goworker) - **star:2220** 基于 go 的后台 worker。![star > 1000][Silver]   
* [gpool](https://github.com/Sherifabdlnaby/gpool) - **star:58** manages a resizeable pool of context-aware goroutines to bound concurrency
* [grpool](https://github.com/ivpusic/grpool) - **star:491** 轻量级协程池。![star > 100][Bronze]   
* [Hunch](https://github.com/AaronJan/Hunch) - **star:8** Hunch 提供了诸如 All、First、Retry、Waterfall 等功能，这使得异步流控制更加直观。
* [oversight](https://cirello.io/oversight) - 完整的实现了Erlang supervision trees。
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - **star:24** 并行运行函数。![最近一年没有更新][Yellow]
* [pool](https://github.com/go-playground/pool) - **star:471** 有限消费者协程或无限协程池，可用于更加简单的处理和取消协程![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [queue](https://github.com/AnikHasibul/queue) - **star:1** 提供类似队列组可访问性 sync.WaitGroup 的功能。帮助你节流和限制协程、等待所有协程结束以及更多功能。
* [routine](https://github.com/x-mod/routine) - **star:1** go routine control with context, support: Main, Go, Pool and some useful Executors.
* [semaphore](https://github.com/kamilsk/semaphore) - **star:74** 信号量模式实现，可根据通道和上下文进行具备超时功能的锁定/解锁操作。
* [semaphore](https://github.com/marusama/semaphore) - **star:69** 基于 CAS 的可快速调整的信号量实现(比基于通道的信号量实现更快)。
* [stl](https://github.com/ssgreg/stl) - **star:7** 基于软件事务内存(STM)并发控制机制的软件事务锁。
* [threadpool](https://github.com/shettyh/threadpool) - **star:17** Golang 的 threadpool 实现。
* [tunny](https://github.com/Jeffail/tunny) - **star:1300** golang 的协程池。![star > 1000][Silver]   
* [worker-pool](https://github.com/vardius/worker-pool) - **star:43** 一个简单的 Go 异步工作池。
* [workerpool](https://github.com/gammazero/workerpool) - **star:120** 限制任务执行并发数，而不是队列中的任务数量的协程池，。![star > 100][Bronze]   

## GUI

*用于构建GUI应用程序的库。*

*工具包*

* [app](https://github.com/murlokswarm/app) - **star:2916** 用于创建包含了 GO, HTML 和 CSS 的应用程序。支持 MacOS, Windows 正在开发中。![star > 1000][Silver]   
* [fyne](https://github.com/fyne-io/fyne) - **star:6025** 为 Go 而设计的跨平台的本地GUIs，使用EFL呈现。支持 : Linux, macOS, Windows。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [go-astilectron](https://github.com/asticode/go-astilectron) - **star:2593** 使用 GO 和 HTML/JS/CSS (电子驱动)进行构建跨平台 GUI 应用程序。![star > 1000][Silver]   
* [go-gtk](http://mattn.github.io/go-gtk/) - 实现了 GTK 的 Go接口。
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - **star:1417** 实现了 Sciter 的 Go 接口 : 用于现代桌面 UI 开发的可嵌入HTML/CSS/脚本引擎。可跨平台。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gotk3](https://github.com/gotk3/gotk3) - **star:731** 实现了 GTK3 的 Go接口。![star > 100][Bronze]   
* [gowd](https://github.com/dtylman/gowd) - **star:203** 跨平台、快速、简单的桌面UI开发，采用了GO, HTML, CSS和NW.js实现。![star > 100][Bronze]   
* [qt](https://github.com/therecipe/qt) - **star:5812** 实现了 Qt 的 Go接口(支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [ui](https://github.com/andlabs/ui) - **star:6828** 跨平台的 Platform-native GUI 库。![star > 5000][Gold]   
* [Wails](https://wails.app) - Mac, Windows, Linux桌面应用程序，主要基于含有内置的OS HTML渲染器的HTML UI。
* [walk](https://github.com/lxn/walk) - **star:3631** Windows应用程序库。![star > 1000][Silver]   
* [webview](https://github.com/zserge/webview) - **star:4514** 跨平台webview窗口，具有简单的双向JavaScript绑定(Windows / macOS / Linux)。![star > 1000][Silver]   ![最近一个周有更新][Green]

*交互*

* [go-appindicator](https://github.com/dawidd6/go-appindicator) - **star:1** 实现了 libappindicator3 C库 的 Go接口。
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) - **star:493** OSX 桌面通知库。![star > 100][Bronze]   
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - **star:1** 用于通知计算机上的任何(可插入的)活动的 OSX 库。
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX 睡眠/唤醒通知。
* [robotgo](https://github.com/go-vgo/robotgo) - **star:4356** 实现跨平台的GUI系统自动化。包含了控制鼠标、键盘等功能。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [systray](https://github.com/getlantern/systray) - **star:758** 跨平台 Go 库，可在通知区放置图标和菜单。![star > 100][Bronze]   
* [trayhost](https://github.com/shurcooL/trayhost) - **star:158** 跨平台 Go 库，可用于在主机操作系统的任务栏中放置图标。![star > 100][Bronze]   


## 硬件

*硬件交互相关的库、工具和教程。*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## 图片

*图像处理相关的库。*

* [bild](https://github.com/anthonynsimon/bild) - **star:2019** 纯Go语言实现的图像处理算法合集。![star > 1000][Silver]   
* [bimg](https://github.com/h2non/bimg) - **star:772** 使用libvips实现的快速高效的图像处理包。![star > 100][Bronze]   
* [cameron](https://github.com/aofei/cameron) - **star:31** 一个Go语言的头像生成器。
* [geopattern](https://github.com/pravj/geopattern) - **star:1008** 由字符串创建漂亮图案的图片生成器。![star > 1000][Silver]   
* [gg](https://github.com/fogleman/gg) - **star:1873** 纯Go语言实现的2D渲染。![star > 1000][Silver]   
* [gift](https://github.com/disintegration/gift) - **star:1203** 图像处理包。![star > 1000][Silver]   
* [gltf](https://github.com/qmuntal/gltf) - **star:34** 一个高效、健壮的glTF 2.0文件读取、写入和验证器。
* [go-cairo](https://github.com/ungerik/go-cairo) - **star:85**  cairo图形库的Go binding。
* [go-gd](https://github.com/bolknote/go-gd) - **star:48**  GD库的Go binding。![最近一年没有更新][Yellow]
* [go-nude](https://github.com/koyachi/go-nude) - **star:284** Go语言实现的裸照检测工具。![star > 100][Bronze]   
* [go-opencv](https://github.com/lazywei/go-opencv) - **star:1081** OpenCV库的Go bindings。![star > 1000][Silver]   
* [go-webcolors](https://github.com/jyotiska/go-webcolors) - **star:24** Python下webcolors库的Go语言调用。![最近一年没有更新][Yellow]
* [gocv](https://github.com/hybridgroup/gocv) - **star:2364** 使用OpenCV 3.3+实现的计算机视觉(ComputerVision)的Go语言包。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [goimagehash](https://github.com/corona10/goimagehash) - **star:206**  图像哈希处理的Go语言包。![star > 100][Bronze]   
* [goimghdr](https://github.com/corona10/goimghdr) - **star:26** Go语言实现的imghdr模块用于确定文件的图像类型。
* [govatar](https://github.com/o1egl/govatar) - **star:308** 生成有趣头像的库和CMD工具。![star > 100][Bronze]   
* [image2ascii](https://github.com/qeesung/image2ascii) - **star:284** 将图像转换为ASCII码。![star > 100][Bronze]   
* [imagick](https://github.com/gographics/imagick) - **star:951**  ImageMagick下MagickWand的C API的Go binding。![star > 100][Bronze]   
* [imaginary](https://github.com/h2non/imaginary) - **star:2541** 用于图像大小调整的快速、简单的HTTP微服务。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [imaging](https://github.com/disintegration/imaging) - **star:2470** 简单的Go图像处理包。![star > 1000][Silver]   
* [img](https://github.com/hawx/img) - **star:128** 图像处理工具的集合。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [ln](https://github.com/fogleman/ln) - **star:2440** Go实现的3D线艺术（3D Line Art）渲染。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [mergi](https://github.com/noelyahan/mergi) - **star:68** 用于图像处理(合并、裁剪、调整大小、水印、动画)的工具和Go库。
* [mort](https://github.com/aldor007/mort) - **star:362** Go语言实现的图像存储和处理服务器。![star > 100][Bronze]   
* [mpo](https://github.com/donatj/mpo) - **star:6** MPO三维照片的解码和转换工具。
* [picfit](https://github.com/thoas/picfit) - **star:1049** Go实现的图像调整服务器。![star > 1000][Silver]   
* [pt](https://github.com/fogleman/pt) - **star:1756** Go实现的路径跟踪（path tracing）引擎。![star > 1000][Silver]   
* [resize](https://github.com/nfnt/resize) - **star:2107** Go实现的使用常用的插值法（interpolation methods）调整图像大小的库。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [rez](https://github.com/bamiaux/rez) - **star:186** 纯Go语言和SIMD实现的图像大小调整。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [smartcrop](https://github.com/muesli/smartcrop) - **star:1241** 为任意图片寻找合适的位置进行图片裁剪。![star > 1000][Silver]   
* [steganography](https://github.com/auyer/steganography) - **star:25** 纯Go实现的LSB隐写（LSB steganography）的库。
* [stegify](https://github.com/DimitarPetrov/stegify) - **star:482**  Go实现的LSB隐写（LSB steganography），能够隐藏任何文件到一个图像中。![star > 100][Bronze]   
* [svgo](https://github.com/ajstarks/svgo) - **star:1307**  Go实现的SVG生成库。![star > 1000][Silver]   
* [tga](https://github.com/ftrvxmtrx/tga) - **star:23** tga包是一个TARGA图像的解码、编码器。![最近一年没有更新][Yellow]

## 物联网

*物联网设备编程库。*

* [connectordb](https://github.com/connectordb/connectordb) - **star:166** 自我量化和物联网的开源平台。![star > 100][Bronze]   
* [devices](https://github.com/goiot/devices) - **star:224** 一套用于物联网设备的库，实验性地用于x/exp/io。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [eywa](https://github.com/xcodersun/eywa) - **star:35** Eywa是一个用于跟踪连接的设备连接管理器。![最近一年没有更新][Yellow]
* [flogo](https://github.com/tibcosoftware/flogo) - **star:1090** Flogo是一个面向物联网边缘应用和集成的开源框架。![star > 1000][Silver]   
* [gatt](https://github.com/paypal/gatt) - **star:807** Gatt是一个用于构建低能耗蓝牙外围设备的Go语言包。![star > 100][Bronze]   
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot是一个用于机器人、物理计算和物联网的框架。
* [huego](https://github.com/amimof/huego) - **star:108** 一个包含广泛的Philips Hue客户端的Go语言库。![star > 100][Bronze]   
* [iot](https://github.com/vaelen/iot/) - IoT是一个实现谷歌物联网核心设备的简单框架。
* [mainflux](https://github.com/Mainflux/mainflux) - **star:555** 工业物联网消息和设备管理服务器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [periph](https://periph.io/) - 外围设备I/O与低级板(low-level board)设备接口。
* [sensorbee](https://github.com/sensorbee/sensorbee) - **star:175** 轻量级物联网流处理引擎。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 作业调度器

*用于作业调度的库。*

* [clockwerk](http://github.com/onatm/clockwerk) - 使用简单、流畅的语法调度作业的Go语言库。
* [clockwork](https://github.com/whiteShtef/clockwork) - **star:74** Go实现的简单直观的作业调度库。
* [go-cron](https://github.com/rk/go-cron) - **star:177** 一个Go实现的简单的定时任务库。可以在不同的时间间隔（每秒一次到在每年在特定的日期执行）执行闭包或函数。主要用于web应用和长时间运行的守护进程。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gron](https://github.com/roylee0704/gron) - **star:622** 使用简单的Go API定义基于时间的任务。 之后Gron的调度程序将运行它们。![star > 100][Bronze]   
* [JobRunner](https://github.com/bamzi/jobrunner) - **star:560** 智能和功能丰富的cron作业调度程序（包含任务队列和实时监控）。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [jobs](https://github.com/albrow/jobs) - **star:449** 持久和灵活的后台作业库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [leprechaun](https://github.com/kilgaloon/leprechaun) - **star:36** 支持webhook、crons和经典调度的作业调度程序。
* [scheduler](https://github.com/carlescere/scheduler) - **star:290** Cronjobs让调度变得很简单。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## JSON

*用于JSON处理的库。*

* [ajson](https://github.com/spyzhov/ajson) - **star:10** 为Go语言开发的包含JSONPath支持的抽象JSON。
* [gjo](https://github.com/skanehira/gjo) - **star:57** 用于创建JSON对象的小工具。
* [GJSON](https://github.com/tidwall/gjson) - **star:4734** 使用一行代码获取JSON的值。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-respond](https://github.com/nicklaw5/go-respond) - **star:21** 用于处理常见的HTTP JSON响应的Go语言库。![最近一个周有更新][Green]
* [gojq](https://github.com/elgs/gojq) - **star:139** Go语言实现的JSON请求。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gojson](https://github.com/ChimeraCoder/gojson) - **star:2021** 从JSON自动生成Go的结构（struct）定义。![star > 1000][Silver]   
* [JayDiff](https://github.com/yazgazan/jaydiff) - **star:37** 用Go编写的JSON比对工具。
* [JSON-to-Go](https://mholt.github.io/json-to-go/) - 将JSON转换为Go的结构（struct）。
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - **star:5** 基于JSON API错误引用的Go bindings。![最近一年没有更新][Yellow]
* [jsonf](https://github.com/miolini/jsonf) - **star:55** 用于高亮展示和查询JSON的控制台工具。![最近一年没有更新][Yellow]
* [jsongo](https://github.com/ricardolonga/jsongo) - **star:93** 使用Fluent API来更容易地创建Json对象。![最近一年没有更新][Yellow]
* [jsonhal](https://github.com/RichardKnop/jsonhal) - **star:9** 让自定义结构（struct）转化为JSON兼容的HAL（Hypertext Application Language）返回数据的简单Go包。
* [kazaam](https://github.com/Qntfy/kazaam) - **star:123** 用于任意JSON文档转换的API。![star > 100][Bronze]   
* [mp](https://github.com/sanbornm/mp) - **star:33** 简单的cli电子邮件解析器。它目前接受stdin并输出JSON。![最近一年没有更新][Yellow]

## 日志记录

*用于生成和处理日志文件的库。*

* [distillog](https://github.com/amoghe/distillog) - **star:18** 经过蒸馏的水平日志记录(可以将其视为stdlib +日志级别)。
* [glg](https://github.com/kpango/glg) - **star:51** glg是一个简单而快速的Go日志库。
* [glo](https://github.com/lajosbencz/glo) - **star:7** PHP独白激发了具有相同严重性级别的日志记录功能。
* [glog](https://github.com/golang/glog) - **star:2268** 为Go提供了水平的执行日志。![star > 1000][Silver]   
* [go-cronowriter](https://github.com/utahta/go-cronowriter) - **star:19** 基于当前日期和时间自动旋转日志文件的简单编写器，如cronolog。
* [go-log](https://github.com/subchen/go-log) - **star:10** 简单且可配置的登录Go，带有level、格式化程序和编写器。![最近一年没有更新][Yellow]
* [go-log](https://github.com/siddontang/go-log) - **star:23** 日志库支持级别和多处理程序。
* [go-log](https://github.com/ian-kent/go-log) - **star:34** 在Go中实现Log4j。![最近一年没有更新][Yellow]
* [go-logger](https://github.com/apsdehal/go-logger) - **star:230** 简单的日志程序的 Go 程序，与级别处理程序。![star > 100][Bronze]   
* [gologger](https://github.com/sadlil/gologger) - **star:40** 简单易用的日志库，日志在彩色控制台，简单控制台，文件或弹性搜索。![最近一年没有更新][Yellow]
* [gomol](https://github.com/aphistic/gomol) - **star:16** 具有可扩展日志输出的多输出、结构化日志记录。
* [gone/log](https://github.com/One-com/gone/tree/master/log) - 快速、可扩展、功能齐全、std-lib源代码兼容的日志库。
* [journald](https://github.com/ssgreg/journald) - **star:18**  Go 实现systemd Journal的本地日志API。
* [log](https://github.com/aerogo/log) - **star:4** 一个O(1)日志系统，允许您将一个日志连接到多个写入器(例如stdout、文件和TCP连接)。
* [log](https://github.com/apex/log) - **star:723** Go的结构化日志包。![star > 100][Bronze]   
* [log](https://github.com/go-playground/log) - **star:266** 简单、可配置和可伸缩的Go结构化日志。![star > 100][Bronze]   
* [log](https://github.com/teris-io/log) - **star:22** Go的结构化日志接口清晰地将日志外观与其实现分离开来。![最近一年没有更新][Yellow]
* [log-voyage](https://github.com/firstrow/logvoyage) - **star:83** 用golang编写的功能齐全的日志saas。![最近一年没有更新][Yellow]
* [log15](https://github.com/inconshreveable/log15) - **star:878** 简单、强大的Go日志。![star > 100][Bronze]   
* [logdump](https://github.com/ewwwwwqm/logdump) - **star:8** 用于多级日志记录的包。![最近一年没有更新][Yellow]
* [logex](https://github.com/chzyer/logex) - **star:32** Golang日志库，支持跟踪和水平，包装由标准日志库。![最近一年没有更新][Yellow]
* [logger](https://github.com/azer/logger) - **star:135** Go的最小化日志库。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [logmatic](https://github.com/borderstech/logmatic) - **star:7** 带有动态日志级别配置的Golang彩色日志记录器。
* [logo](https://github.com/mbndr/logo) - **star:4** Golang日志程序到不同的可配置作家。![最近一年没有更新][Yellow]
* [logrus](https://github.com/Sirupsen/logrus) - **star:11458** 结构化的日志 Go 。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [logrusly](https://github.com/sebest/logrusly) - **star:26** [logrus](https://github.com/sirupsen/logrus)插件将错误发送到[Loggly](https://www.loggly.com/)。![最近一年没有更新][Yellow]
* [logutils](https://github.com/hashicorp/logutils) - **star:247** 用于稍微更好地登录的实用程序Go (Golang)扩展了标准日志记录器。![star > 100][Bronze]   
* [logxi](https://github.com/mgutz/logxi) - **star:333** 12因素的应用程序日志程序是快速的，让你快乐。![star > 100][Bronze]   
* [lumberjack](https://github.com/natefinch/lumberjack) - **star:1383** 简单的滚动日志程序，实现io.WriteCloser。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [mlog](https://github.com/jbrodriguez/mlog) - **star:17** 简单的go日志模块，有5个级别，可选的旋转日志文件功能和stdout/stderr输出。
* [onelog](https://github.com/francoispqt/onelog) - **star:325** Onelog是一个非常简单但非常高效的JSON日志程序。它是所有场景中速度最快的JSON日志程序。而且，它是配置最低的日志记录器之一。![star > 100][Bronze]   
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) - **star:108** 支持日志严重性、分类和过滤的高性能日志记录。可以发送过滤日志消息到各种目标(如控制台，网络，邮件)。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) - **star:94** RollingWriter是一个自动旋转的io。作者的实现与多个策略，以提供日志文件旋转。
* [seelog](https://github.com/cihub/seelog) - **star:1335** 具有灵活调度、过滤和格式化的日志功能。![star > 1000][Silver]   
* [spew](https://github.com/davecgh/go-spew) - **star:3237** 为Go数据结构实现一个漂亮的深层打印机，以帮助调试。![star > 1000][Silver]   
* [stdlog](https://github.com/alexcesaro/log) - **star:43** Stdlog是一个面向对象的库，提供水平日志记录。它对cron作业非常有用。![最近一年没有更新][Yellow]
* [tail](https://github.com/hpcloud/tail) - **star:1497** Go软件包努力模拟BSD tail程序的特性。![star > 1000][Silver]   
* [xlog](https://github.com/xfxdev/xlog) - **star:7** 插件架构和灵活的日志系统的Go，与级别ctrl，多日志目标和自定义日志格式。
* [xlog](https://github.com/rs/xlog) - **star:130** 结构化记录器'net/context`意识到HTTP处理程序的灵活调度。![star > 100][Bronze]   
* [zap](https://github.com/uber-go/zap) - **star:7195** 快速、结构化、水平登录Go。![star > 5000][Gold]   
* [zerolog](https://github.com/rs/zerolog) - **star:2096** 零JSON记录器。![star > 1000][Silver]   ![最近一个周有更新][Green]

## 机器学习

*机器学习库。*

* [bayesian](https://github.com/jbrukh/bayesian) - **star:625** Golang的朴素贝叶斯分类。![star > 100][Bronze]   
* [CloudForest](https://github.com/ryanbressler/CloudForest) - **star:642** 快速、灵活、多线程的决策树集成，用于纯Go中的机器学习。![star > 100][Bronze]   
* [eaopt](https://github.com/MaxHalford/eaopt) - **star:615** 一个进化优化库。![star > 100][Bronze]   
* [evoli](https://github.com/khezen/evoli) - **star:8** 遗传算法和粒子群优化库。
* [fonet](https://github.com/Fontinalis/fonet) - **star:31** 一个用Go编写的深度神经网络库。![最近一年没有更新][Yellow]
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - **star:21** Go实现了k模式和k原型聚类算法。
* [go-deep](https://github.com/patrikeh/go-deep) - **star:213** 一个功能丰富的神经网络库在 Go 。![star > 100][Bronze]   
* [go-fann](https://github.com/white-pony/go-fann) - **star:99** 快速人工神经网络(FANN)库的Go绑定。![最近一年没有更新][Yellow]
* [go-galib](https://github.com/thoj/go-galib) - **star:170** 用Go / golang编写的遗传算法库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-pr](https://github.com/daviddengcn/go-pr) - **star:57** 模式识别包在Go lang。![最近一年没有更新][Yellow]
* [gobrain](https://github.com/goml/gobrain) - **star:369** 用 Go 编写的神经网络。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [godist](https://github.com/e-dard/godist) - **star:24** 各种概率分布，以及相关的方法。![最近一年没有更新][Yellow]
* [goga](https://github.com/tomcraven/goga) - **star:79** Go的遗传算法库。![最近一年没有更新][Yellow]
* [GoLearn](https://github.com/sjwhitworth/golearn) - **star:6606** 通用机器学习库。![star > 5000][Gold]   
* [golinear](https://github.com/danieldk/golinear) - **star:39**  Go 的线性绑定。
* [GoMind](https://github.com/surenderthakran/gomind) - **star:6** 一个简单的神经网络库在 Go 。
* [goml](https://github.com/cdipaolo/goml) - **star:1005** 在线机器学习在 Go 。![star > 1000][Silver]   
* [goRecommend](https://github.com/timkaye11/goRecommend) - **star:141** 推荐算法库用Go编写。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gorgonia](https://github.com/chewxy/gorgonia) - **star:2645** 基于图形的计算库，如Theano for Go，它为构建各种机器学习和神经网络算法提供了基本框架。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gorse](https://github.com/zhenghaoz/gorse) - **star:508** 基于协同过滤的Go高性能推荐系统包。![star > 100][Bronze]   
* [goscore](https://github.com/asafschers/goscore) - **star:34**  Go 为PMML评分API。
* [gosseract](https://github.com/otiai10/gosseract) - **star:847** 使用Tesseract c++库为OCR(光学字符识别)打包。![star > 100][Bronze]   
* [libsvm](https://github.com/datastream/libsvm) - **star:63** 基于libsvm的golang版本派生工作。![最近一年没有更新][Yellow]
* [mlgo](https://github.com/NullHypothesis/mlgo) - **star:5** 这个项目的目的是在 Go 中提供最小化的机器学习算法。![最近一年没有更新][Yellow]
* [neat](https://github.com/jinyeom/neat) - **star:55** 即插即用的并行Go框架，用于增强拓扑的神经进化(整洁)。![最近一年没有更新][Yellow]
* [neural-go](https://github.com/schuyler/neural-go) - **star:61** 多层感知器网络在Go中实现，通过反向传播进行训练。![最近一年没有更新][Yellow]
* [ocrserver](https://github.com/otiai10/ocrserver) - **star:219** 一个简单的OCR API服务器，非常容易被Docker和Heroku部署。![star > 100][Bronze]   
* [onnx-go](https://github.com/owulveryck/onnx-go) - **star:141** Go接口打开神经网络交换(ONNX)。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [probab](https://github.com/ThePaw/probab) - **star:10** 概率分布函数。贝叶斯推理。用纯 Go 写的。![最近一年没有更新][Yellow]
* [regommend](https://github.com/muesli/regommend) - **star:243** 推荐&协同过滤引擎。![star > 100][Bronze]   
* [shield](https://github.com/eaigner/shield) - **star:124** 贝叶斯文本分类器，具有灵活的令牌器和存储后端。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [tfgo](https://github.com/galeone/tfgo) - **star:1160** 易于使用的Tensorflow绑定:简化了官方Tensorflow Go绑定的使用。在Go中定义计算图形，加载和执行Python中训练的模型。![star > 1000][Silver]   
* [Varis](https://github.com/Xamber/Varis) - **star:24** Golang神经网络。

## 消息

*实现消息传递系统的库。*

* [APNs2](https://github.com/sideshow/apns2) - **star:2024** HTTP / 2苹果推送通知供应商——发送推送通知到iOS, tvo, Safari和OSX的应用。![star > 1000][Silver]   
* [Beaver](https://github.com/Clivern/Beaver) - **star:714** 一个实时消息服务器，可构建一个可伸缩的应用程序内通知，多人游戏，聊天应用程序在web和移动应用程序。![star > 100][Bronze]   
* [Benthos](https://github.com/Jeffail/benthos) - **star:1909** 一系列协议之间的消息流桥。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Bus](https://github.com/mustafaturan/bus) - **star:110** 内部通信的最小消息总线实现。![star > 100][Bronze]   
* [Centrifugo](https://github.com/centrifugal/centrifugo) - **star:3615** 实时消息(Websockets或SockJS)服务器。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Commander](https://github.com/jeroenrinzema/commander) - **star:21** 高级事件驱动的消费者/生产者，支持各种“方言”，如Apache Kafka。![最近一个周有更新][Green]
* [dbus](https://github.com/godbus/dbus) - **star:350** D-Bus的本地Go绑定。![star > 100][Bronze]   
* [drone-line](https://github.com/appleboy/drone-line) - **star:59** 使用二进制、docker或从属CI发送[Line](https://at.line.me/en)通知。
* [emitter](https://github.com/olebedev/emitter) - **star:307** 使用通配符、谓词、取消可能性和许多其他优点，使用Go way发出事件。![star > 100][Bronze]   
* [event](https://github.com/agoalofalife/event) - **star:27** 模式观察者的实现。![最近一年没有更新][Yellow]
* [EventBus](https://github.com/asaskevich/EventBus) - **star:539** 具有异步兼容性的轻量级事件总线。![star > 100][Bronze]   
* [gaurun-client](https://github.com/osamingo/gaurun-client) - **star:8** 用Go编写的Gaurun客户端。
* [Glue](https://github.com/desertbit/glue) - **star:312** 健壮的Go和Javascript套接字库(替代Socket.io)。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-notify](https://github.com/TheCreeper/go-notify) - **star:47** 本地实现的freedesktop通知规范。
* [go-nsq](https://github.com/nsqio/go-nsq) - **star:1437** NSQ的官方Go包。![star > 1000][Silver]   
* [go-socket.io](https://github.com/googollee/go-socket.io) - **star:2830** 套接字。面向golang的io库，一个实时应用程序框架。![star > 1000][Silver]   
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) - **star:11** 客户端库到Viessmann Vitotrol web服务。
* [Gollum](https://github.com/trivago/gollum) - **star:761** n:m多路复用器，它收集来自不同来源的消息并将其广播到一组目的地。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [golongpoll](https://github.com/jcuga/golongpoll) - **star:419** HTTP longpoll服务器库，使web发布-订阅变得简单。![star > 100][Bronze]   
* [goose](https://github.com/ian-kent/goose) - **star:37** 服务器在Go中发送事件。![最近一年没有更新][Yellow]
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - **star:1821** gopush-cluster是一个gopush服务器集群。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [gorush](https://github.com/appleboy/gorush) - **star:3635** 使用[APNs2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm)推送通知服务器。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [guble](https://github.com/smancke/guble) - **star:138** 消息服务器使用推送通知(谷歌Firebase云消息、苹果推送通知服务、SMS)以及websockets，一个REST API，具有分布式操作和消息持久性。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [hub](https://github.com/leandro-lugaresi/hub) - **star:24** 用于Go应用程序的消息/事件中心，使用发布/订阅模式，并支持别名(如rabbitMQ交换)。![最近一年没有更新][Yellow]
* [jazz](https://github.com/socifi/jazz) - **star:6** 一个简单的RabbitMQ抽象层，用于队列管理和消息的发布和消费。
* [machinery](https://github.com/RichardKnop/machinery) - **star:3306** 基于分布式消息传递的异步任务队列/作业队列。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [mangos](https://github.com/go-mangos/mangos) - **star:1531** 具有传输互操作性的Nanomsg(“可伸缩协议”)的纯go实现。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [melody](https://github.com/olahol/melody) - **star:1514** 处理websocket会话的极简框架，包括广播和自动乒乓球处理。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Mercure](https://github.com/dunglas/mercure) - **star:1434** 使用Mercure协议(构建在服务器发送事件之上)分派服务器发送的更新的服务器和库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [messagebus](https://github.com/vardius/message-bus) - **star:62** messagebus是一种Go简单异步消息总线，非常适合在执行事件源、CQRS和DDD时用作事件总线。
* [NATS Go Client](https://github.com/nats-io/nats) - **star:2344** 轻量级和高性能的发布-订阅和分布式队列消息传递系统——这是Go库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - **star:49** 一个围绕NSQ主题和通道的小包装。![最近一年没有更新][Yellow]
* [oplog](https://github.com/dailymotion/oplog) - **star:94** 用于REST api的通用oplog/复制系统。![最近一年没有更新][Yellow]
* [pubsub](https://github.com/tuxychandru/pubsub) - **star:272** 简单的pubsubpackage for go。![star > 100][Bronze]   
* [rabbus](https://github.com/rafaeljesus/rabbus) - **star:61** amqp交换器和队列上的一个小包装。
* [rabtap](https://github.com/jandelgado/rabtap) - **star:67** RabbitMQ瑞士军刀cli应用。
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) - **star:55** RapidMQ是用于管理本地消息队列的轻量级可靠库。![最近一年没有更新][Yellow]
* [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ重新连接。amqp包装器。连接和amqp.Dial。在强制关闭对Close()方法的调用之前，允许在连接断开时重新连接。
* [sarama](https://github.com/Shopify/sarama) - **star:4468**  Go Apache Kafka的库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) - **star:1093** Redis支持面向移动设备的服务器端通知的统一推送服务。![star > 1000][Silver]   
* [zmq4](https://github.com/pebbe/zmq4) - **star:770** 转接口到ZeroMQ版本4。也可用于[版本3](https://github.com/pebbe/zmq3)和[版本2](https://github.com/pebbe/zmq2)。![star > 100][Bronze]   

## 微软办公软件

### Microsoft Excel

*用于使用Microsoft Excel的库。*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - **star:4289** Golang库读写Microsoft Excel™(XLSX)文件。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-excel](https://github.com/szyhf/go-excel) - **star:47** 一个简单而轻便的阅读器，可以将类似于关系数据库的excel作为表来读取。
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - **star:12** 用于编写XLSX (Microsoft Excel)文件的libxlsxwriter的Golang绑定。
* [xlsx](https://github.com/tealeg/xlsx) - **star:3275** 库，以简化在Go程序中读取Microsoft Excel最新版本使用的XML格式。![star > 1000][Silver]   
* [xlsx](https://github.com/plandem/xlsx) - **star:58** 快速和安全的方式读取/更新您现有的Microsoft Excel文件在 Go 程序。![最近一个周有更新][Green]

## 杂项

### 依赖注入

*用于处理依赖项注入的库。*

* [alice](https://github.com/magic003/alice) - **star:34** Golang的添加依赖注入容器。![最近一年没有更新][Yellow]
* [dig](https://github.com/uber-go/dig) - **star:863** 一个基于反射的Go依赖注入工具包。![star > 100][Bronze]   
* [fx](https://github.com/uber-go/fx) - **star:638** 基于依赖注入的Go应用程序框架(构建在dig之上)。![star > 100][Bronze]   
* [gocontainer](https://github.com/vardius/gocontainer) - **star:4** 简单的依赖注入容器。
* [inject](https://github.com/defval/inject) - **star:17** 一个基于反射的依赖注入容器，具有简单的接口。![最近一个周有更新][Green]
* [wire](https://github.com/Fs02/wire) - **star:20** Golang严格的运行时依赖注入。

### 项目布局

*用于组织项目的非正式模式集。*

* [go-sample](https://github.com/zitryss/go-sample) - **star:18** 使用实际代码的Go应用程序项目的示例布局。
* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - **star:8453** Go生态系统中常见的历史和新兴的项目布局模式。![star > 5000][Gold]   
* [scaffold](https://github.com/catchplay/scaffold) - **star:21** 脚手架生成starter Go项目布局。让您专注于已实现的业务逻辑。

### 字符串

*处理字符串的库。*

* [strutil](https://github.com/ozgio/strutil) - **star:61** 字符串工具。
* [xstrings](https://github.com/huandu/xstrings) - **star:605** 从其他语言移植的有用字符串函数的集合。![star > 100][Bronze]   

*这些库之所以放在这里，是因为其他类别似乎都不适合。*

* [anagent](https://github.com/mudler/anagent) - **star:11** 最小化，可插入的Golang evloop/计时器处理程序与依赖注入。
* [antch](https://github.com/antchfx/antch) - **star:137** 一个快速、强大和可扩展的web爬行和抓取框架。![star > 100][Bronze]   
* [archiver](https://github.com/mholt/archiver) - **star:2439** 用于生成和提取.zip和.tar.gz存档的库和命令。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [autoflags](https://github.com/artyom/autoflags) - **star:24** Go package从struct字段自动定义命令行标志。
* [avgRating](https://github.com/kirillDanshin/avgRating) - **star:9** 根据Wilson评分方程计算平均分和评分。![最近一年没有更新][Yellow]
* [banner](https://github.com/dimiro1/banner) - **star:229** 在Go应用程序中添加漂亮的横幅。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [base64Captcha](https://github.com/mojocn/base64Captcha) - **star:608** Base64captch支持数字，数字，字母，算术，音频和数字-字母验证码。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [battery](https://github.com/distatus/battery) - **star:134** 跨平台、标准化的电池信息库。![star > 100][Bronze]   
* [bitio](https://github.com/icza/bitio) - **star:91** 高度优化的位级读写器。![最近一年没有更新][Yellow]
* [browscap_go](https://github.com/digitalcrab/browscap_go) - **star:29** 用于[浏览器功能项目]的GoLang库(http://browscap.org/)。
* [captcha](https://github.com/steambap/captcha) - **star:41** 软件包captcha为captcha的生成提供了一个易于使用的、未绑定的API。
* [conv](https://github.com/cstockton/go-conv) - **star:341** 包conv提供了跨Go类型的快速和直观的转换。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [datacounter](https://github.com/miolini/datacounter) - **star:27** 读取器/写入器/http.ResponseWriter的计数器。![最近一年没有更新][Yellow]
* [ffmt](https://github.com/go-ffmt/ffmt) - **star:126** 美化数据显示为人类。![star > 100][Bronze]   
* [ghorg](https://github.com/gabrie30/ghorg) - **star:22** 将所有repos从GitHub org复制到一个目录中。
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) - **star:653** Golang的通用对象池。![star > 100][Bronze]   
* [go-openapi](https://github.com/go-openapi) - 用于解析和利用开放api模式的包的集合。
* [go-resiliency](https://github.com/eapache/go-resiliency) - **star:832**  Go 的弹性模式。![star > 100][Bronze]   
* [go-unarr](https://github.com/gen2brain/go-unarr) - **star:66** 用于RAR、TAR、ZIP和7z存档的解压缩库。
* [gofakeit](https://github.com/brianvoe/gofakeit) - **star:404** 用go编写的随机数据生成器。![star > 100][Bronze]   
* [gommit](https://github.com/antham/gommit) - **star:65** 分析git提交消息，确保它们遵循已定义的模式。
* [gopsutil](https://github.com/shirou/gopsutil) - **star:3811** 用于检索进程和系统利用率(CPU、内存、磁盘等)的跨平台库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gosh](https://github.com/osamingo/gosh) - **star:16** 提供Go统计处理程序，结构，测量方法。
* [gosms](https://github.com/haxpax/gosms) - **star:1220** 您自己的本地短信网关在Go，可以用来发送短信。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [gotoprom](https://github.com/cabify/gotoprom) - **star:15** 为Prometheus客户端提供类型安全的度量构建器包装库。
* [gountries](https://github.com/pariz/gountries) - **star:205** 公开国家和细分数据的包。![star > 100][Bronze]   
* [health](https://github.com/dimiro1/health) - **star:359** 易于使用，可扩展的健康检查库。![star > 100][Bronze]   
* [healthcheck](https://github.com/etherlabsio/healthcheck) - **star:78** 用于RESTful服务的自以为是的并发健康检查HTTP处理程序。
* [hostutils](https://github.com/Wing924/hostutils) - **star:7** 一个用于打包和解包FQDNs列表的golang库。
* [indigo](https://github.com/osamingo/indigo) - **star:51** 分布式唯一ID生成器使用Sonyflake，并由Base58编码。
* [lk](https://github.com/hyperboloide/lk) - **star:111** 一个简单的golang授权库。![star > 100][Bronze]   
* [llvm](https://github.com/llir/llvm) - **star:403** 用于在纯Go中与LLVM IR交互的库。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [metrics](https://github.com/pascaldekloe/metrics) - **star:4** 用于度量仪器和普罗米修斯博览会的库。
* [morse](https://github.com/alwindoss/morse) - **star:48** 转换成莫尔斯电码和从莫尔斯电码转换成莫尔斯电码的程序库。
* [numa](https://github.com/lrita/numa) - **star:2** NUMA是一个用go编写的实用程序库。它帮助我们编写一些NUMA-AWARED代码。
* [pdfgen](https://github.com/hyperboloide/pdfgen) - **star:32** HTTP服务从Json请求生成PDF。![最近一年没有更新][Yellow]
* [persian](https://github.com/mavihq/persian) - **star:33** 一些实用的波斯语在 Go 。
* [sandid](https://github.com/aofei/sandid) - **star:12** 地球上的每一粒沙子都有自己的身份。
* [shellwords](https://github.com/Wing924/shellwords) - **star:7** 一个Golang库，根据UNIX Bourne shell的单词解析规则操纵字符串。![最近一年没有更新][Yellow]
* [shortid](https://github.com/teris-io/shortid) - **star:443** 分布式生成超短、唯一、非顺序、URL友好的id。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [stats](https://github.com/go-playground/stats) - **star:120** 显示器 Go MemStats +系统统计，如内存，交换和CPU，并通过UDP发送到任何地方，你想记录等…![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [turtle](https://github.com/hackebrot/turtle) - **star:73** Emojis Go 。![最近一年没有更新][Yellow]
* [url-shortener](https://github.com/pantrif/url-shortener) - **star:17** 一个现代的、强大的、健壮的URL缩短器微服务，支持mysql。![最近一年没有更新][Yellow]
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - 生成样板http输入和输出处理。
* [xdg](https://github.com/rkoesters/xdg) - **star:20** FreeDesktop.org (xdg)规范在Go中实现。
* [xkg](https://github.com/go-xkg/xkg) - **star:39** X键盘打捞工具。![最近一年没有更新][Yellow]

## 自然语言处理

*用于处理人类语言的库。*

* [getlang](https://github.com/rylans/getlang) - **star:71** 快速自然语言检测包。
* [go-eco](https://github.com/ThePaw/go-eco) - **star:4** 相似、不相似和距离矩阵;多样性、公平性和不平等度量;物种丰富度估计;coenocline模型。![最近一年没有更新][Yellow]
* [go-i18n](https://github.com/nicksnyder/go-i18n/) - 软件包和用于处理本地化文本的附带工具。
* [go-mystem](https://github.com/dveselov/mystem) - **star:23** CGo绑定到Yandex。Mystem -俄罗斯形态学分析仪。![最近一年没有更新][Yellow]
* [go-nlp](https://github.com/nuance/go-nlp) - **star:79** 用于处理离散概率分布的实用程序和用于进行NLP工作的其他工具。![最近一年没有更新][Yellow]
* [go-pinyin](https://github.com/mozillazg/go-pinyin) - **star:513** 中文汉字到汉语拼音的转换。![star > 100][Bronze]   
* [go-stem](https://github.com/agonopol/go-stem) - **star:51** 波特词干算法的实现。![最近一年没有更新][Yellow]
* [go-unidecode](https://github.com/mozillazg/go-unidecode) - **star:54** Unicode文本的ASCII音译。
* [go2vec](https://github.com/danieldk/go2vec) - **star:30** 用于word2vec嵌入式的阅读器和实用程序函数。
* [gojieba](https://github.com/yanyiwu/gojieba) - **star:791** 这是一个Go实现的[jieba](https://github.com/fxsjy/jieba)，这是一个中文分词算法。![star > 100][Bronze]   
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - **star:15**  Go 绑定斯诺鲍libstemmer库，包括波特2。![最近一年没有更新][Yellow]
* [gotokenizer](https://github.com/xujiajun/gotokenizer) - **star:6** 一种基于字典和双字母格朗语言模型的记号赋予器。(现在只支持中文分割)
* [gounidecode](https://github.com/fiam/gounidecode) - **star:67** 用于Go的Unicode音译器(也称为unidecode)。![最近一年没有更新][Yellow]
* [gse](https://github.com/go-ego/gse) - **star:1039** 高效的文本分割;支持英语、汉语、日语等。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [icu](https://github.com/goodsign/icu) - **star:19** Cgo绑定用于icu4c C库的检测和转换功能。保证与版本50.1兼容。![最近一年没有更新][Yellow]
* [kagome](https://github.com/ikawaha/kagome) - **star:412** JP形态学分析仪编写的纯Go。![star > 100][Bronze]   
* [libtextcat](https://github.com/goodsign/libtextcat) - **star:10** 用于libtextcat C库的Cgo绑定。保证与版本2.2兼容。![最近一年没有更新][Yellow]
* [MMSEGO](https://github.com/awsong/MMSEGO) - **star:59** 这是一个 Go 实现的[MMSEG](http://technology.chtsai.org/mmseg/)，这是一个中文分词算法。![最近一年没有更新][Yellow]
* [nlp](https://github.com/Shixzie/nlp) - **star:354** 从字符串中提取值并用nlp填充结构。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [nlp](https://github.com/james-bowman/nlp) - **star:212** 支持LSA(潜在语义分析)的Go自然语言处理库。![star > 100][Bronze]   
* [paicehusk](https://github.com/rookii/paicehusk) - **star:25** Golang实现了Paice/外壳阻塞算法。![最近一年没有更新][Yellow]
* [petrovich](https://github.com/striker2000/petrovich) - **star:22** 彼得罗维奇是一个图书馆，它把俄语名字的词形变化成特定的语法格。
* [porter](https://github.com/a2800276/porter) - **star:8** 这是Martin Porter在C语言中实现的Porter词干分析算法的一个相当简单的移植。![最近一年没有更新][Yellow]
* [porter2](https://github.com/zhenjl/porter2) - **star:33** 非常快的波特2史坦默。![最近一年没有更新][Yellow]
* [prose](https://github.com/jdkato/prose) - **star:2019** 用于支持标记化、词性标记、名称实体提取等文本处理的库。![star > 1000][Silver]   
* [RAKE.go](https://github.com/Obaied/RAKE.go) - **star:42** 快速自动关键字提取算法(RAKE)的Go端口。
* [segment](https://github.com/blevesearch/segment) - **star:47** 如[Unicode标准附件#29]所述，执行Unicode文本分割的Go库(http://www.unicode.org/reports/tr29/)![最近一年没有更新][Yellow]
* [sentences](https://github.com/neurosnap/sentences) - **star:261** 句子标记器:将文本转换为句子列表。![star > 100][Bronze]   
* [shamoji](https://github.com/osamingo/shamoji) - **star:10** shamoji是用Go编写的word过滤包。
* [snowball](https://github.com/goodsign/snowball) - **star:24** 滚雪球柄端口(cgo包装)为 Go 。提供词干提取功能[Snowball native](http://snowball.tartarus.org/)。![最近一年没有更新][Yellow]
* [stemmer](https://github.com/dchest/stemmer) - **star:47** 用于Go编程语言的Stemmer包。包括英语和德语词根。![最近一年没有更新][Yellow]
* [textcat](https://github.com/pebbe/textcat) - **star:60** Go package支持基于n-gram的文本分类，支持utf-8和原始文本。
* [whatlanggo](https://github.com/abadojack/whatlanggo) - **star:342** Go的自然语言检测包。支持84种语言和24种脚本(书写系统，如拉丁语、西里尔语等)。![star > 100][Bronze]   
* [when](https://github.com/olebedev/when) - **star:923** 带有可插入规则的自然EN和RU语言日期/时间解析器。![star > 100][Bronze]   

## 网络

*用于处理网络各层的库。*

* [arp](https://github.com/mdlayher/arp) - **star:191** 包arp实现了arp协议，如RFC 826中所述。![star > 100][Bronze]   
* [buffstreams](https://github.com/stabbycutyou/buffstreams) - **star:229** 通过TCP传输协议缓冲区数据变得很容易。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [canopus](https://github.com/zubairhamed/canopus) - **star:134** CoAP客户机/服务器实现(RFC 7252)。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [cidranger](https://github.com/yl2chen/cidranger) - **star:379** 快速IP到CIDR查找 Go 。![star > 100][Bronze]   
* [dhcp6](https://github.com/mdlayher/dhcp6) - **star:61** 包dhcp6实现了一个DHCPv6服务器，如RFC 3315所述。
* [dns](https://github.com/miekg/dns) - **star:3719** 使用DNS的库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [ether](https://github.com/songgao/ether) - **star:62** 用于发送和接收以太网帧的跨平台Go包。![最近一年没有更新][Yellow]
* [ethernet](https://github.com/mdlayher/ethernet) - **star:182** 包以太网实现了对IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的编组和解组。![star > 100][Bronze]   
* [fasthttp](https://github.com/valyala/fasthttp) - **star:9031** 软件包fasthttp是Go的一个快速HTTP实现，比net/http快10倍。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [fortio](https://github.com/fortio/fortio) - **star:834** 负载测试库和命令行工具，先进的echo服务器和web UI。允许指定一组每秒查询的负载，并记录延迟直方图和其他有用的统计数据，并将它们作图。Tcp、Http、gRPC。![star > 100][Bronze]   
* [ftp](https://github.com/jlaffaye/ftp) - **star:503** 包ftp实现了[RFC 959](http://tools.ietf.org/html/rfc959)中描述的ftp客户机。![star > 100][Bronze]   
* [gmqtt](https://github.com/DrmagicE/gmqtt) - **star:65** Gmqtt是一个灵活、高性能的MQTT代理库，它完全实现了MQTT协议V3.1.1。
* [gNxI](https://github.com/google/gnxi) - **star:100** 一组使用gNMI和gNOI协议的网络管理工具。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-getter](https://github.com/hashicorp/go-getter) - **star:689**  Go 图书馆下载文件或目录从各种来源使用一个URL。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-stun](https://github.com/ccding/go-stun) - **star:328** Go实现了STUN客户机(RFC 3489和RFC 5389)。![star > 100][Bronze]   
* [gobgp](https://github.com/osrg/gobgp) - **star:1649** 用 Go 编程语言实现的BGP。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [golibwireshark](https://github.com/sunwxg/golibwireshark) - **star:14** golibwireshark包使用libwireshark库解码pcap文件并分析解剖数据。![最近一年没有更新][Yellow]
* [gopacket](https://github.com/google/gopacket) - **star:2784** 使用libpcap绑定访问包处理库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gopcap](https://github.com/akrennmair/gopcap) - **star:348**  Go 包装libpcap。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [goshark](https://github.com/sunwxg/goshark) - **star:9** goshark包使用tshark来解码IP包，并创建数据结构来分析包。![最近一年没有更新][Yellow]
* [gosnmp](https://github.com/soniah/gosnmp) - **star:426** 用于执行SNMP操作的本机Go库。![star > 100][Bronze]   
* [gotcp](https://github.com/gansidui/gotcp) - **star:406**  Go 包快速编写tcp应用程序。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [grab](https://github.com/cavaliercoder/grab) - **star:541**  Go 软件包管理文件下载。![star > 100][Bronze]   
* [graval](https://github.com/koofr/graval) - **star:25** 实验FTP服务器框架。![最近一年没有更新][Yellow]
* [HTTPLab](https://github.com/gchaincl/httplab) - **star:3380** HTTPLabs允许您检查HTTP请求并伪造响应。![star > 1000][Silver]   
* [iplib](https://github.com/c-robinson/iplib) - **star:24** 用于处理IP地址的库(net)。受python [ipaddress](https://docy-doc.org/3/library/ipaddress.html)和ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)的启发
* [jazigo](https://github.com/udhos/jazigo) - **star:122** Jazigo是一个用Go编写的工具，用于检索多个网络设备的配置。![star > 100][Bronze]   
* [kcp-go](https://github.com/xtaci/kcp-go) - **star:2202** 快速可靠的ARQ协议。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [kcptun](https://github.com/xtaci/kcptun) - **star:10525** 非常简单和快速udp隧道基于KCP协议。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [lhttp](https://github.com/fanux/lhttp) - **star:507** 强大的websocket框架，使您的IM服务器更容易构建。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [linkio](https://github.com/ian-kent/linkio) - **star:45** 用于读写器接口的网络链路速度模拟。![最近一年没有更新][Yellow]
* [llb](https://github.com/kirillDanshin/llb) - **star:8** 这是一个非常简单但快速的代理服务器后端。可用于快速重定向到预定义域，具有零内存分配和快速响应。![最近一年没有更新][Yellow]
* [mdns](https://github.com/hashicorp/mdns) - **star:542** Golang中的简单mDNS(多播DNS)客户机/服务器库。![star > 100][Bronze]   
* [mqttPaho](https://eclipse.org/paho/clients/golang/) - Paho Go客户机提供一个MQTT客户机库，用于通过TCP、TLS或WebSockets连接到MQTT代理。
* [NFF-Go](https://github.com/intel-go/nff-go) - **star:644** 快速开发云计算和裸机网络功能的框架(原YANFF)。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [packet](https://github.com/aerogo/packet) - **star:26** 通过TCP和UDP发送数据包。如果需要，它可以缓冲消息和热交换连接。
* [peerdiscovery](https://github.com/schollz/peerdiscovery) - **star:356** 使用UDP组播进行跨平台本地对等点发现的纯Go库。![star > 100][Bronze]   
* [portproxy](https://github.com/aybabtme/portproxy) - **star:42** 简单的TCP代理将CORS支持添加到不支持它的API中。![最近一年没有更新][Yellow]
* [publicip](https://github.com/polera/publicip) - **star:18** 包publicip返回面向公共的IPv4地址(internet出口)。![最近一年没有更新][Yellow]
* [quic-go](https://github.com/lucas-clemente/quic-go) - **star:2803** 在纯Go中实现了QUIC协议。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [raw](https://github.com/mdlayher/raw) - **star:300** Package raw支持在设备驱动程序级别读取和写入网络接口的数据。![star > 100][Bronze]   
* [sftp](https://github.com/pkg/sftp) - **star:713** 包sftp实现了SSH文件传输协议，如https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt所述。![star > 100][Bronze]   
* [ssh](https://github.com/gliderlabs/ssh) - **star:1087** 用于构建SSH服务器的高级API(封装密码/ SSH)。![star > 1000][Silver]   
* [sslb](https://github.com/eduardonunesp/sslb) - **star:114** 它是一个超级简单的负载平衡器，只是一个实现某种性能的小项目。![star > 100][Bronze]   
* [stun](https://github.com/go-rtc/stun) - **star:259** Go实现的RFC 5389 STUN协议。![star > 100][Bronze]   
* [tcp_server](https://github.com/firstrow/tcp_server) - **star:276**  Go 图书馆建设tcp服务器更快。![star > 100][Bronze]   
* [tspool](https://github.com/two/tspool) - **star:5** TCP库使用工作池来提高性能并保护服务器。
* [utp](https://github.com/anacrolix/utp) - **star:150** Go uTP微传输协议的实现。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [water](https://github.com/songgao/water) - **star:827** 简单TUN / TAP图书馆。![star > 100][Bronze]   
* [webrtc](https://github.com/pions/webrtc) - **star:2048** WebRTC API的纯Go实现。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [winrm](https://github.com/masterzen/winrm) - **star:208**  Go WinRM客户端远程执行Windows机器上的命令。![star > 100][Bronze]   
* [xtcp](https://github.com/xfxdev/xtcp) - **star:80** TCP服务器框架具有同时全双工通信，优雅关机，自定义协议。

### HTTP客户端

*用于发出HTTP请求的库。*

* [gentleman](https://github.com/h2non/gentleman) - **star:669** 功能齐全的插件驱动HTTP客户端库。![star > 100][Bronze]   
* [goreq](https://github.com/smallnest/goreq) - **star:98** 基于gorequest的增强简化HTTP客户机。
* [grequests](https://github.com/levigross/grequests) - **star:1392** 一个 Go “克隆”的伟大和著名的请求库。![star > 1000][Silver]   
* [heimdall](https://github.com/gojektech/heimdall) - **star:1050** 具有重试和hystrix功能的增强http客户机。![star > 1000][Silver]   
* [pester](https://github.com/sethgrid/pester) - **star:319** 使用重试、后退和并发执行HTTP客户机调用。![star > 100][Bronze]   
* [rq](https://github.com/ddo/rq) - **star:25** golang stdlib HTTP客户端更好的接口。
* [sling](https://github.com/dghubble/sling) - **star:845** Sling是一个用于创建和发送API请求的Go HTTP客户端库。![star > 100][Bronze]   

## OpenGL

*用于在Go中使用OpenGL的库。*

* [gl](https://github.com/go-gl/gl) - **star:628** OpenGL的Go绑定(通过glow生成)。![star > 100][Bronze]   
* [glfw](https://github.com/go-gl/glfw) - **star:711** Go绑定用于glfw3。![star > 100][Bronze]   
* [goxjs/gl](https://github.com/goxjs/gl) - **star:131** 跨平台的OpenGL绑定(OS X, Linux, Windows，浏览器，iOS, Android)。![star > 100][Bronze]   
* [goxjs/glfw](https://github.com/goxjs/glfw) - **star:58** 使用跨平台glfw库创建OpenGL上下文并接收事件。
* [mathgl](https://github.com/go-gl/mathgl) - **star:285** 纯Go数学软件包专门为三维数学，与灵感来自GLM。![star > 100][Bronze]   

## ORM

*实现对象关系映射或数据映射技术的库。*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - 强大的orm框架。支持:pq / mysql / sqlite3。
* [go-firestorm](https://github.com/jschoedt/go-firestorm) - 一个用于谷歌/Firebase云Firestore的简单ORM。
* [go-pg](https://github.com/go-pg/pg) - **star:2882** 关注PostgreSQL的特性和性能。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-queryset](https://github.com/jirfag/go-queryset) - **star:444** 100%类型安全ORM与代码生成和MySQL, PostgreSQL, Sqlite3, SQL Server支持基于GORM。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - **star:220** 一个灵活而强大的SQL字符串构建器库加上一个零配置ORM。![star > 100][Bronze]   
* [go-store](https://github.com/gosuri/go-store) - **star:92** 简单而快速的Redis支持的键值存储库。![最近一年没有更新][Yellow]
* [GORM](https://github.com/jinzhu/gorm) - **star:14172** Golang出色的ORM库的目标是对开发人员友好。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [gorp](https://github.com/go-gorp/gorp) - **star:3060** Go的关系持久性，ORM-ish库。![star > 1000][Silver]   
* [grimoire](https://github.com/Fs02/grimoire) - **star:111** Grimoire是golang的数据库访问层和验证。(支持:MySQL, PostgreSQL和SQLite3)。![star > 100][Bronze]   
* [lore](https://github.com/abrahambotros/lore) - **star:4** 用于Go的简单轻量级伪orm /伪结构映射环境。![最近一年没有更新][Yellow]
* [Marlow](https://github.com/dadleyy/marlow) - **star:60** 从项目结构生成ORM，用于编译时安全保证。
* [pop/soda](https://github.com/gobuffalo/pop) - **star:655** 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [QBS](https://github.com/coocood/qbs) - **star:537** 表示结构查询。一个ORM。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [reform](https://github.com/go-reform/reform) - **star:787** 更好的ORM for Go，基于非空接口和代码生成。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) - **star:2206** ORM生成器。根据您的数据库模式生成一个功能强大且运行速度快的ORM。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [upper.io/db](https://github.com/upper/db) - **star:1817** 通过使用封装成熟数据库驱动程序的适配器与不同数据源交互的单一接口。![star > 1000][Silver]   
* [Xorm](https://github.com/go-xorm/xorm) - **star:5021** 简单而强大的ORM for Go。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Zoom](https://github.com/albrow/zoom) - **star:237** 基于Redis的快速数据存储和查询引擎。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 包管理

*用于管理依赖和包的官方工具*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules 是源码的版本控制和交换的单位。go命令直接支持处理模块，包括记录和解决对其他模块的依赖关系。

*包管理的官方实验工具*

* [dep](https://github.com/golang/dep) - **star:12394**  Go 的依赖管理工具，需要 Go 1.9+![star > 5000][Gold]   
* [vgo](https://go.googlesource.com/vgo/) - Go 命令版本管理

*用于包和依赖项管理的非官方库。*

* [gigo](https://github.com/LyricalSecurity/gigo) - **star:196** 类似pip的golang依赖工具，支持私有存储库和散列。![star > 100][Bronze]   
* [glide](https://github.com/Masterminds/glide) - **star:7738** 轻松管理您的 golang 第三方包。受Maven、Bundler和Pip等工具的启发。![star > 5000][Gold]   
* [godep](https://github.com/tools/godep) - **star:5651** godep是go的依赖工具，它通过修复包的依赖关系来帮助构建可重复的包。![star > 5000][Gold]   ![最近一年没有更新][Yellow]
* [gom](https://github.com/mattn/gom) - **star:1352** Go Manager - bundle for Go。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [goop](https://github.com/nitrous-io/goop) - **star:778** Go 的简单依赖管理器，灵感来自Bundler。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gop](https://github.com/lunny/gop) - **star:50** 在GOPATH之外构建和管理Go应用程序。
* [gopm](https://github.com/gpmgo/gopm) - **star:2332** 包管理器。![star > 1000][Silver]   
* [govendor](https://github.com/kardianos/govendor) - **star:4664** 包管理器。使用 vendor 文件的 Go vendor 工具。![star > 1000][Silver]   
* [gpm](https://github.com/pote/gpm) - **star:1204** 基本的 Go 依赖管理器。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [johnny-deps](https://github.com/VividCortex/johnny-deps) - **star:213** 使用Git的最小依赖版本。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [mvn-golang](https://github.com/raydac/mvn-golang) - **star:87** 插件，为自动加载Golang SDK，依赖关系管理和启动Maven项目基础设施中的构建环境提供了方法。![最近一个周有更新][Green]
* [nut](https://github.com/jingweno/nut) - **star:246** vendor 依赖。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [VenGO](https://github.com/DamnWidget/VenGO) - **star:116** 创建和管理可导出的隔离go虚拟环境。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 查询语言

* [gojsonq](https://github.com/thedevsaddam/gojsonq) - **star:835** 一个用来查询JSON数据的Go包。![star > 100][Bronze]   
* [graphql](https://github.com/tmc/graphql) - **star:51** graphql解析器+工具集![最近一年没有更新][Yellow]
* [graphql](https://github.com/neelance/graphql-go) - **star:2702** 关注易用性的GraphQL服务器。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [graphql-go](https://github.com/graphql-go/graphql) - **star:5061** 为Go实现GraphQL。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [jsonql](https://github.com/elgs/jsonql) - **star:201** Golang中的JSON查询表达式库。![star > 100][Bronze]   
* [jsonslice](https://github.com/bhmj/jsonslice) - **star:22** 使用高级过滤器查询Jsonpath。
* [rql](https://github.com/a8m/rql) - **star:110** 用于REST API的资源查询语言。![star > 100][Bronze]   

## 嵌入的资源

* [esc](https://github.com/mjibson/esc) - **star:458** 将文件嵌入到Go程序中并提供http文件系统接口。![star > 100][Bronze]   
* [fileb0x](https://github.com/UnnoTed/fileb0x) - **star:416** 一个可定制的工具用来在Go中嵌入文件![star > 100][Bronze]   
* [go-embed](https://github.com/pyros2097/go-embed) - **star:14** 生成go代码，将资源文件嵌入到库或可执行文件中。![最近一年没有更新][Yellow]
* [go-resources](https://github.com/omeid/go-resources) - **star:155** 嵌入到Go中的普通资源。![star > 100][Bronze]   
* [go.rice](https://github.com/GeertJohan/go.rice) - **star:1618** go.rice 是一个Go包，它使处理html、js、css、图像和模板等资源变得非常容易。![star > 1000][Silver]   
* [packr](https://github.com/gobuffalo/packr) - **star:2021** 将静态文件嵌入到Go二进制文件中的简单方法。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [statics](https://github.com/go-playground/statics) - **star:53** 将静态资源嵌入到go文件中，用于单个二进制编译+使用http。文件系统+符号链接。![最近一年没有更新][Yellow]
* [statik](https://github.com/rakyll/statik) - **star:2026** 将静态文件嵌入到Go可执行文件中。![star > 1000][Silver]   
* [templify](https://github.com/wlbr/templify) - **star:19** 将外部模板文件嵌入到Go代码中，以创建单个文件二进制文件。
* [vfsgen](https://github.com/shurcooL/vfsgen) - **star:635** 生成一个vfsdata。静态实现给定虚拟文件系统的go文件。![star > 100][Bronze]   

## 科学与数据分析

*用于科学计算和数据分析的库。*

* [assocentity](https://github.com/ndabAP/assocentity) - **star:3** assocentity 返回单词到给定实体的平均距离。
* [bradleyterry](https://github.com/seanhagen/bradleyterry) - 为成对比较提供了一个 Bradley-Terry 模型。
* [chart](https://github.com/vdobler/chart) - **star:573** 简单的图表绘制库。支持多种图形类型。![star > 100][Bronze]   
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - **star:63** 用于机器学习和统计的数据模型(类似于 pandas)。![最近一个周有更新][Green]
* [evaler](https://github.com/soniah/evaler) - **star:40** 简单的浮点算术表达式求值器。
* [ewma](https://github.com/VividCortex/ewma) - **star:264** 提供指数加权移动平均算法。![star > 100][Bronze]   
* [geom](https://github.com/skelterjohn/geom) - **star:40**  Go 的二维几何。![最近一年没有更新][Yellow]
* [go-dsp](https://github.com/mjibson/go-dsp) - **star:622** Go数字信号处理。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-fn](https://github.com/ematvey/go-fn) - **star:11** 用Go语言编写的数学函数，不包括在math pkg中。![最近一年没有更新][Yellow]
* [go-gt](https://github.com/ThePaw/go-gt) - **star:5** 用“Go”语言编写的图论算法。![最近一年没有更新][Yellow]
* [gocomplex](https://github.com/varver/gocomplex) - **star:5** 用于 Go 编程语言的复数库。![最近一年没有更新][Yellow]
* [goent](https://github.com/kzahedi/goent) - **star:13**  Go 实现熵度量。
* [gohistogram](https://github.com/VividCortex/gohistogram) - **star:126** 数据流的近似直方图。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gonum](https://github.com/gonum/gonum) - **star:2857** Gonum是一组用于Go编程语言的数字库。它包含用于矩阵、统计、优化等的库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gonum/plot](https://github.com/gonum/plot) - **star:1184** gonum/plot提供了一个API，用于在Go中构建和绘制绘图。![star > 1000][Silver]   
* [goraph](https://github.com/gyuho/goraph) - **star:597** 纯Go图论库(数据结构，算法可视化)。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gosl](https://github.com/cpmech/gosl) - **star:1291** 提供线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程，等等。![star > 1000][Silver]   
* [GoStats](https://github.com/OGFris/GoStats) - **star:9** GoStats是一个开放源码的GoLang库，主要用于机器学习领域的数学统计，它涵盖了大多数统计度量函数。
* [graph](https://github.com/yourbasic/graph) - **star:226** 基本图形算法库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [ode](https://github.com/ChristopherRabotin/ode) - **star:10** 常微分方程(ODE)求解器，支持扩展状态和基于信道的迭代停止条件。![最近一年没有更新][Yellow]
* [orb](https://github.com/paulmach/orb) - **star:186** 2D几何类型，支持剪切、GeoJSON和Mapbox矢量平铺。![star > 100][Bronze]   
* [pagerank](https://github.com/alixaxel/pagerank) - **star:48** 加权 PageRank 算法在Go中的实现。
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) - **star:5** 微型线性插值库。
* [PiHex](https://github.com/claygod/PiHex) - **star:9** 实现了针对16进制数 Pi 的“bailee - borwein - plouffe”算法。
* [rootfinding](https://github.com/khezen/rootfinding) - **star:3** 二次函数求根算法库。
* [sparse](https://github.com/james-bowman/sparse) - **star:66**  Go 稀疏矩阵格式的线性代数支持科学和机器学习应用程序，兼容gonum矩阵库。
* [stats](https://github.com/montanaflynn/stats) - **star:1331** 包含Golang标准库中缺少的公共函数的统计软件包。![star > 1000][Silver]   
* [streamtools](https://github.com/nytlabs/streamtools) - **star:1315** 通用图形工具，用于处理数据流。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [TextRank](https://github.com/DavidBelicza/TextRank) - **star:65** TextRank在Golang中的实现，支持扩展特性(摘要、加权、短语提取)和多线程(goroutine)。
* [triangolatte](https://github.com/tchayen/triangolatte) - **star:11** 二维三角库。允许将线和多边形(都基于点)转换为gpu语言。

## 安全

*用于帮助您的应用程序更安全的库。*

* [acmetool](https://github.com/hlandau/acme) - **star:1691** ACME(让我们用自动更新加密)客户端工具。![star > 1000][Silver]   
* [acra](https://github.com/cossacklabs/acra) - **star:441** 网络加密代理保护基于数据库的应用程序免受数据泄漏:强选择性加密，SQL注入预防，入侵检测系统。![star > 100][Bronze]   
* [argon2pw](https://github.com/raja/argon2pw) - **star:72** 使用常量时间密码比较生成Argon2密码散列。
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - 让我们加密证书并启动TLS服务器。
* [BadActor](https://github.com/jaredfolkins/badactor) - **star:241** 一个驻留在内存中的，应用驱动的监控程序，受 fail2ban 的启发![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Cameradar](https://github.com/Ullaakut/cameradar) - **star:1783** 工具和库，以远程入侵RTSP流从监控摄像头。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [certificates](https://github.com/mvmaasakkers/certificates) - **star:6** 用于生成tls证书的自定义工具。
* [go-yara](https://github.com/hillu/go-yara) - **star:132** YARA的 Go 语言接口，号称是 “对于恶意软件研究者（以及其他人）来说是模式匹配的瑞士军刀”![star > 100][Bronze]   
* [goArgonPass](https://github.com/dwin/goArgonPass) - **star:10** Argon2密码散列和验证设计为与现有Python和PHP实现兼容。
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - **star:28** 一个安全哈希和加密密码的偏执包。
* [Interpol](https://bitbucket.org/vahidi/interpol) - 基于规则的数据生成器，用于模糊和渗透测试。
* [jwc](https://github.com/khezen/jwc) - **star:5** JSON Web加密库。
* [lego](https://github.com/xenolf/lego) - **star:3423** 纯 Go ACME 客户端库及命令行工具![star > 1000][Silver]   ![最近一个周有更新][Green]
* [memguard](https://github.com/awnumar/memguard) - **star:995** 一个用于处理内存中敏感值的纯Go库。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [nacl](https://github.com/kevinburke/nacl) - **star:450**  Go 实现NaCL API的集合。![star > 100][Bronze]   
* [passlib](https://github.com/hlandau/passlib) - **star:224** 不过时的密码哈希库。![star > 100][Bronze]   
* [secure](https://github.com/unrolled/secure) - **star:1186** Go 语言 HTTP 中间件，为 Go 提供了一些安全功能![star > 1000][Silver]   
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) - **star:155** Scrypt 库，具有简单、易懂的 API，同时具有内置的自动校准功能![star > 100][Bronze]   ![最近一个周有更新][Green]
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - **star:194** 使用ssh密钥加密/解密。![star > 100][Bronze]   
* [sslmgr](https://github.com/adrianosela/sslmgr) - **star:7** 使用围绕acme/autocert的高级包装器，SSL证书变得很容易。

## 序列化

*用于二进制序列化的库和工具。*

* [asn1](https://github.com/PromonLogicalis/asn1) - **star:40** 面向golang的BER和DER编码库。
* [bambam](https://github.com/glycerine/bambam) - **star:61** 用于 Go 语言生成 Cap'n Proto schemas 的生成器![最近一年没有更新][Yellow]
* [bel](https://github.com/32leaves/bel) - **star:5** 从Go structs/interface生成TypeScript接口。对JSON RPC很有用。
* [binstruct](https://github.com/ghostiam/binstruct) - **star:7** 用于将数据映射到结构中的Golang二进制解码器。![最近一个周有更新][Green]
* [colfer](https://github.com/pascaldekloe/colfer) - **star:470** 为Colfer二进制格式生成代码。![star > 100][Bronze]   
* [csvutil](https://github.com/jszwec/csvutil) - **star:300** 高性能、惯用的CSV记录编码和解码到本机Go结构。![star > 100][Bronze]   
* [fwencoder](https://github.com/o1egl/fwencoder) - **star:6** 用于Go的固定宽度文件解析器(编码和解码库)。![最近一年没有更新][Yellow]
* [go-capnproto](https://github.com/glycerine/go-capnproto) - **star:273** Go 语言用的 Cap'n Proto 库及解析器![star > 100][Bronze]   
* [go-codec](https://github.com/ugorji/go) - **star:1206** 高性能、多功能、规范化编码解码以及 rpc 库， 用于 msgpack, cbor 和 json，支持基于运行时的 OR 码生成![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gogoprotobuf](https://github.com/gogo/protobuf) - **star:2836** Go 语言的 Protocol Buffer 库。![star > 1000][Silver]   
* [goprotobuf](https://github.com/golang/protobuf) - **star:4869** 通过库和协议编译器插件使 Go 语言支持 Google的 protocol buffers.![star > 1000][Silver]   ![最近一个周有更新][Green]
* [jsoniter](https://github.com/json-iterator/go) - **star:5275** 高性能，100% 兼容的“encoding/json” 替代品![star > 5000][Gold]   
* [mapstructure](https://github.com/mitchellh/mapstructure) - **star:2327** 用于对原生键值对进行解码生成 Go 语言结构体![star > 1000][Silver]   ![最近一个周有更新][Green]
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - **star:118** 用于协同 PHP session 格式数据和 PHP 序列化／反序列化函数工作的go语言库![star > 100][Bronze]   
* [structomap](https://github.com/tuvistavie/structomap) - **star:92** 用于从静态结构体简单、动态的生成键值对的库

## 服务器应用程序

* [algernon](https://github.com/xyproto/algernon) - **star:1574** 内置支持Lua、Markdown、GCSS和Amber的HTTP/2 web服务器。![star > 1000][Silver]   
* [Caddy](https://github.com/mholt/caddy) - **star:22544** Caddy是另一种HTTP/2 web服务器，易于配置和使用。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [consul](https://www.consul.io/) - Consul 是一个用于服务发现、监控和配置的工具
* [devd](https://github.com/cortesi/devd) - **star:2780** 为开发人员提供本地web服务器。![star > 1000][Silver]   
* [discovery](https://github.com/Bilibili/discovery) - **star:628** 用于弹性中间层负载平衡和故障转移的注册表。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [etcd](https://github.com/coreos/etcd) - **star:25796** 为共享配置和服务发现提供高可用的键值存储。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Fider](https://github.com/getfider/fider) - **star:773** Fider是一个收集和组织客户反馈的开放平台。![star > 100][Bronze]   
* [Flagr](https://github.com/checkr/flagr) - **star:781** Flagr是一个开源特性标记和A/B测试服务。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [flipt](https://github.com/markphelps/flipt) - **star:975** 一个用Go和Vue.js编写的自包含特性标志解决方案![star > 100][Bronze]   ![最近一个周有更新][Green]
* [jackal](https://github.com/ortuman/jackal) - **star:707** 用Go编写的XMPP服务器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [minio](https://github.com/minio/minio) - **star:16858** Minio是一个分布式对象存储服务器。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - **star:5** Nginx日志解析器和Prometheus 导出。
* [nsq](http://nsq.io/) - 一个实时分布式消息平台。
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) - **star:5** 从PostgreSQL到Kafka的流数据库事件。
* [riemann-relay](https://github.com/blind-oracle/riemann-relay) - 传递到负载平衡Riemann事件并/或将其转换为 Carbon。
* [RoadRunner](https://github.com/spiral/roadrunner) - **star:3140** 高性能PHP应用服务器，负载平衡器和进程管理器。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [yakvs](https://git.sci4me.com/sci4me/yakvs) - 小型化、网络化、基于内存的键值存储

## 模板引擎

*用于模板和词法分析的库和工具。*

* [ace](https://github.com/yosssi/ace) - **star:761** Ace 是一个 Go 语言的 HTML 模板引擎，受到了 Slim 和 Jade 的启发。 Ace 是对Gold的一种改进。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [amber](https://github.com/eknkc/amber) - **star:820** Amber是一个优雅的Go编程语言模板引擎，它的灵感来自HAML和Jade。![star > 100][Bronze]   
* [damsel](https://github.com/dskinner/damsel) - **star:20** 标记语言，通过css选择器实现了 html 框架 ，并可以通过 pkg html/template 等进行扩展![最近一年没有更新][Yellow]
* [ego](https://github.com/benbjohnson/ego) - **star:409** 轻量级模板语言，允许您在Go中编写模板。模板被翻译成Go并编译。![star > 100][Bronze]   
* [extemplate](https://github.com/dannyvankooten/extemplate) - **star:13**  对 html/template 进行了简单的封装，支持基于文件的模板可以利用其他模板文件进行扩展
* [fasttemplate](https://github.com/valyala/fasttemplate) - **star:288** 简单快速的模板引擎。进行模板元素替换时，速度是比[text/template](http://golang.org/pkg/text/template/)快10倍。![star > 100][Bronze]   
* [gofpdf](https://github.com/jung-kurt/gofpdf) - **star:3007** PDF 文档生成器，支持文本，绘图和图片![star > 1000][Silver]   ![最近一个周有更新][Green]
* [goview](https://github.com/foolin/goview) - **star:39** Goview是一个轻量级、极简的模板库，基于golang html/template构建Go web应用程序。
* [hero](https://github.com/shiyanhui/hero) - **star:1192** Hero是一个方便、快速和强大的go模板引擎。![star > 1000][Silver]   
* [jet](https://github.com/CloudyKit/jet) - **star:578** Jet模板引擎。![star > 100][Bronze]   
* [kasia.go](https://github.com/ziutek/kasia.go) - **star:70** 一个用于HTML 和其他文本文件的模板系统，使用go语言实现![最近一年没有更新][Yellow]
* [liquid](https://github.com/osteele/liquid) - **star:80** Go 语言实现的 Shopify Liquid 模板.
* [mustache](https://github.com/hoisie/mustache) - **star:964** Go 语言实现的 Mustache 模板语言![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [pongo2](https://github.com/flosch/pongo2) - **star:1479** 类似 DjanGo 的模板引擎![star > 1000][Silver]   
* [quicktemplate](https://github.com/valyala/quicktemplate) - **star:1359** 快速、强大且易用的模板引擎。将模板转化为 Go 语言并进行编译![star > 1000][Silver]   
* [raymond](https://github.com/aymerick/raymond) - **star:336** 使用 Go 语言实现的完整的 handlebars![star > 100][Bronze]   
* [Razor](https://github.com/sipin/gorazor) - **star:670** Go 语言的 Razor 视图引擎![star > 100][Bronze]   
* [Soy](https://github.com/robfig/soy) - **star:143** Go 语言实现的谷歌闭包模板(也就是 Soy templates) ,遵循[官方规范](https://developer.google.com/closure/templates/)。![star > 100][Bronze]   
* [velvet](https://github.com/gobuffalo/velvet) - **star:65** 使用 Go 语言实现的完整的 handlebars![最近一年没有更新][Yellow]

## 测试

*用于测试代码库和生成测试数据的库。*

* Testing Frameworks
    * [assert](https://github.com/go-playground/assert) - **star:13** 基础断言库，用于对 Go 语言程序进行测试，提供了一些用于自定义断言的代码块![最近一年没有更新][Yellow]
    * [badio](https://github.com/cavaliercoder/badio) - **star:8** Go 语言 testing/iotest 包的扩展。![最近一年没有更新][Yellow]
    * [baloo](https://github.com/h2non/baloo) - **star:635** 表达性强、多功能的、端到端的HTTP API 测试工具![star > 100][Bronze]   
    * [biff](https://github.com/fulldump/biff) - **star:6** 分支测试框架，BDD兼容。![最近一年没有更新][Yellow]
    * [bro](https://github.com/marioidival/bro) - **star:26** 监控目录中的文件并对其进行测试![最近一年没有更新][Yellow]
    * [charlatan](https://github.com/percolate/charlatan) - **star:188** 为测试生成假接口实现的工具。![star > 100][Bronze]   
    * [commander](https://github.com/SimonBaeumer/commander) - **star:31** 用于在windows、linux和osx上测试cli应用程序的工具。
    * [cupaloy](https://github.com/bradleyjkemp/cupaloy) - **star:78** 测试框架的简单快照测试插件。
    * [dbcleaner](https://github.com/khaiql/dbcleaner) - **star:81** 清空数据库用于测试，受到database_cleaner 的启发
    * [dsunit](https://github.com/viant/dsunit) - **star:24** 用于SQL、NoSQL、结构化文件的数据存储测试。![最近一个周有更新][Green]
    * [endly](https://github.com/viant/endly) - **star:84** 声明性端到端功能测试。
    * [frisby](https://github.com/verdverm/frisby) - **star:245** REST API测试框架。![star > 100][Bronze]   
    * [ginkgo](http://onsi.github.io/ginkgo/) - Go的BDD测试框架。
    * [go-carpet](https://github.com/msoap/go-carpet) - **star:195** 在终端中查看测试覆盖率的工具。![star > 100][Bronze]   
    * [go-cmp](https://github.com/google/go-cmp) - **star:1091** 用于比较测试中的Go值的包。![star > 1000][Silver]   
    * [go-mutesting](https://github.com/zimmski/go-mutesting) - **star:245** 变异测试的Go源代码。![star > 100][Bronze]   
    * [go-testdeep](https://github.com/maxatome/go-testdeep) - **star:49** 极具灵活性的golang深度比较，扩展了go测试包。
    * [go-vcr](https://github.com/dnaeon/go-vcr) - **star:325** 记录并回放HTTP交互，以便进行快速、确定和准确的测试。![star > 100][Bronze]   
    * [goblin](https://github.com/franela/goblin) - **star:613** 类似Mocha的测试框架。![star > 100][Bronze]   
    * [gocheck](http://labix.org/gocheck) - 更加高级的测试框架，用于替换 Gotest
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD 风格的测试框架，具有 web 界面和计时刷新功能
    * [gocrest](https://github.com/corbym/gocrest) - **star:8** 用于 Go 断言的可组合的类似 hamcrest 的 matchers。![最近一年没有更新][Yellow]
    * [godog](https://github.com/DATA-DOG/godog) - **star:724** 类似 Cucumber 或 Behat 的 BDD 框架![star > 100][Bronze]   
    * [gofight](https://github.com/appleboy/gofight) - **star:252** 对 Go 语言的路由框架进行 API 测试![star > 100][Bronze]   
    * [gogiven](https://github.com/corbym/gogiven) - **star:7** 类似于 YATSPEC 的Go BDD测试框架。![最近一年没有更新][Yellow]
    * [gomatch](https://github.com/jfilipczyk/gomatch) - **star:29** 为针对模式测试JSON而创建的库。
    * [gomega](http://onsi.github.io/gomega/) - 类似 Rspec 的 matcher/assertion 库
    * [GoSpec](https://github.com/orfjackal/gospec) - **star:111** 用于 Go 编程语言的bdd风格的测试框架。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
    * [gospecify](https://github.com/stesla/gospecify) - **star:51** 支持 BDD 语法 。对于任何使用过 rspec 等库的人来说应该非常熟悉。![最近一年没有更新][Yellow]
    * [gosuite](https://github.com/pavlo/gosuite) - **star:9** 轻量级测试套，为 Go1.7's Subtests 带来了setup/teardown 功能![最近一年没有更新][Yellow]
    * [gotest.tools](https://github.com/gotestyourself/gotest.tools) - **star:112** 一组包，用于增强go测试包并支持公共模式。![star > 100][Bronze]   
    * [Hamcrest](https://github.com/rdrdr/hamcrest) - **star:26** 用于声明性 Matcher 对象的连贯框架，当将其应用于输入值时，将产生自描述结果。![最近一年没有更新][Yellow]
    * [httpexpect](https://github.com/gavv/httpexpect) - **star:1104** 简洁的、声明式的、易用的端到端HTTP 及 REST API 测试![star > 1000][Silver]   
    * [jsonassert](https://github.com/kinbiko/jsonassert) - **star:20** 用于验证JSON有效负载已正确序列化的包。![最近一个周有更新][Green]
    * [restit](https://github.com/yookoala/restit) - **star:48** 帮助编写 RESTful API 集成测试的 Go 语言微型框架.。![最近一年没有更新][Yellow]
    * [testcase](https://github.com/adamluzsi/testcase) - **star:9** 行为驱动开发的惯用测试框架。
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - **star:314** 类似 Rails 的测试工具，用于测试数据库应用![star > 100][Bronze]   
    * [Testify](https://github.com/stretchr/testify) - **star:7806** 对标准测试包的扩展。![star > 5000][Gold]   
    * [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - 将markdown代码段转换为可测试的go代码。
    * [testsql](https://github.com/zhulongcheng/testsql) - **star:7** 在测试前从SQL文件生成测试数据，并在测试完成后清除数据。
    * [Tt](https://github.com/vcaesar/tt) - **star:5** 简单而丰富多彩的测试工具。
    * [wstest](https://github.com/posener/wstest) - **star:61** 用于单元测试Websocket http.Handler的Websocket客户机。![最近一年没有更新][Yellow]

* Mock
    * [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - **star:354** 用于生成自包含 mock 对象的工具![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - **star:1632** Mock SQL ，用于测试数据库交互![star > 1000][Silver]   
    * [go-txdb](https://github.com/DATA-DOG/go-txdb) - **star:154** 基于单事务的数据库驱动，主要用于测试目的![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [gock](https://github.com/h2non/gock) - **star:786** 多功能、易用 HTTP mock![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [gomock](https://github.com/golang/mock) - **star:2677** 用于Go编程语言的mock框架。![star > 1000][Silver]   
    * [govcr](https://github.com/seborama/govcr) - **star:78** HTTP mock : 离线测试时记录和重放浏览器的动作
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - **star:1411** 使用可扩展中间件和易于使用的CLI记录和模拟REST/SOAP api的HTTP(S)代理。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [httpmock](https://github.com/jarcoal/httpmock) - **star:557** 轻松模拟来自外部资源的HTTP响应。![star > 100][Bronze]   
    * [minimock](https://github.com/gojuno/minimock) - **star:193** Go接口的模拟生成器。![star > 100][Bronze]   
    * [mockhttp](https://github.com/tv42/mockhttp) - **star:22** Go http.ResponseWriter的模拟对象。![最近一年没有更新][Yellow]

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - **star:2838** 随机测试系统。![star > 1000][Silver]   
    * [gofuzz](https://github.com/google/gofuzz) - **star:518** 用于生成随机值来初始化 Go 语言对象的库![star > 100][Bronze]   
    * [Tavor](https://github.com/zimmski/tavor) - **star:208** 通用模糊测试框架![star > 100][Bronze]   

* Selenium and browser control tools.
    * [cdp](https://github.com/mafredri/cdp) - **star:343** 用于Chrome调试协议的类型安全绑定，可与实现该协议的浏览器或其他调试目标一起使用。![star > 100][Bronze]   
    * [chromedp](https://github.com/knq/chromedp) - **star:3397** 用于驱动和测试 Chrome, Safari, Edge, Android Webviews, 以及其他支持 Chrome 调试协议的产品![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [ggr](https://github.com/aerokube/ggr) - **star:208** 一个轻量级服务器，可以将 Selenium Wedriver 的请求路由或代理到多个 Selenium hubs![star > 100][Bronze]   
    * [selenoid](https://github.com/aerokube/selenoid) - **star:1177** Selenium hub 服务器的替代品，在容器中启动浏览器![star > 1000][Silver]   ![最近一个周有更新][Green]

* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - **star:366** 为Golang实现[failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail)。![star > 100][Bronze]   ![最近一个周有更新][Green]

## 文本处理

*用于解析和操作文本的库。*

* Specific Formats
    * [align](https://github.com/Guitarbum722/align) - **star:57** 对文本进行对齐的通用应用程序。![最近一年没有更新][Yellow]
    * [allot](https://github.com/sbstjn/allot) - **star:33** 用于CLI工具和机器人的占位符和通配符文本解析。
    * [bbConvert](https://github.com/CalebQ42/bbConvert) - **star:5** 将bbCode转换为HTML，使您可以添加对自定义bbCode标记的支持。![最近一年没有更新][Yellow]
    * [blackfriday](https://github.com/russross/blackfriday) - **star:3805** Markdown 解析器![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - **star:1213** HTML 清理工具![star > 1000][Silver]   
    * [codetree](https://github.com/aerogo/codetree) - **star:6** 解析缩进代码(python、pixy、scarlet等)并返回树结构。
    * [colly](https://github.com/asciimoo/colly) - **star:8079** 快速和优雅的 Scraping 框架。![star > 5000][Gold]   ![最近一个周有更新][Green]
    * [commonregex](https://github.com/mingrammer/commonregex) - **star:547** 一组用于Go的公共正则表达式。![star > 100][Bronze]   
    * [dataflowkit](https://github.com/slotix/dataflowkit) - **star:280** Web抓取框架将网站转换为结构化数据。![star > 100][Bronze]   
    * [did](https://github.com/ockam-network/did) - **star:21** DID(分散标识符)解析器和Stringer。
    * [doi](https://github.com/hscells/doi) - **star:4** 文档对象标识符(doi)解析器。![最近一年没有更新][Yellow]
    * [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - **star:37** Editorconfig文件解析器和Go操作器。
    * [enca](https://github.com/endeveit/enca) - **star:7** [libenca](http://cihar.com/software/enca/)的最小cgo绑定。![最近一年没有更新][Yellow]
    * [encdec](https://github.com/mickep76/encdec) - **star:3** 软件包为编码器和解码器提供了通用接口。
    * [genex](https://github.com/alixaxel/genex) - **star:50** 将正则表达式计数并展开为所有匹配的字符串。
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub 风格的 Markdown 渲染器 (使用 blackfriday) ，支持代码块高亮以及可点击的锚点
    * [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - **star:21** 固定宽度的文本格式(带反射的编码器/解码器)。![最近一个周有更新][Green]
    * [go-humanize](https://github.com/dustin/go-humanize) - **star:1847** 格式化程序，用于将时间、数字和内存大小转换为可读格式。![star > 1000][Silver]   
    * [go-nmea](https://github.com/adrianmo/go-nmea) - **star:91** 用于Go语言的NMEA解析器库。
    * [go-runewidth](https://github.com/mattn/go-runewidth) - **star:207** 函数获取字符或字符串的固定宽度。![star > 100][Bronze]   
    * [go-slugify](https://github.com/mozillazg/go-slugify) - **star:27** 生成漂亮的固定链接地址（slug），支持多种语言![最近一年没有更新][Yellow]
    * [go-toml](https://github.com/pelletier/go-toml) - **star:593** 使用带有查询支持和方便的cli工具的TOML格式库。![star > 100][Bronze]   
    * [go-vcard](https://github.com/emersion/go-vcard) - **star:24** 解析和格式化vCard。
    * [go-zero-width](https://github.com/trubitsyn/go-zero-width) - **star:41** 用于Go的零宽度字符检测和删除。
    * [gofeed](https://github.com/mmcdole/gofeed) - **star:1077** 在Go中解析RSS和Atom feeds。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [gographviz](https://github.com/awalterschulze/gographviz) - **star:286** 解析Graphviz DOT语言。![star > 100][Bronze]   
    * [gommon/bytes](https://github.com/labstack/gommon/tree/master/bytes) - 格式化二进制为字符串。
    * [gonameparts](https://github.com/polera/gonameparts) - **star:30** 将人名解析为单独的名称部分。![最近一年没有更新][Yellow]
    * [goq](https://github.com/andrewstuart/goq) - **star:141**  声明式 HTML 编组，使用结构标签和 jQuery 语法 (使用 GoQuery).![star > 100][Bronze]   
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - **star:7429** GoQuery 为 Go 语言带来了一组类似 jQuery 的语法和功能![star > 5000][Gold]   
    * [goregen](https://github.com/zach-klippenstein/goregen) - **star:35** 根据正则表达式生成随机字符串![最近一年没有更新][Yellow]
    * [gotext](https://github.com/leonelquinteros/gotext) - **star:228** GNU gettext 工具![star > 100][Bronze]   
    * [guesslanguage](https://github.com/endeveit/guesslanguage) - **star:44** 通过一个 unicode 文本来猜测该文本使用的语言![最近一年没有更新][Yellow]
    * [htmlquery](https://github.com/antchfx/htmlquery) - **star:116** 用于HTML的XPath查询包，允许您通过XPath表达式从HTML文档中提取数据或求值。![star > 100][Bronze]   
    * [inject](https://github.com/facebookgo/inject) - **star:1129** 包注入提供了一个基于反射的注入器。![star > 1000][Silver]   
    * [ltsv](https://github.com/Wing924/ltsv) - **star:2** 用于Go的高性能[LTSV(标签为Tab Separeted Value)](http://ltsv.org/)阅读器。
    * [mxj](https://github.com/clbanning/mxj) - **star:324** 将XML编码/解码为JSON或map[string]接口{};使用点符号路径和通配符提取值。替换x2j和j2x包。![star > 100][Bronze]   ![最近一个周有更新][Green]
    * [sdp](https://github.com/gortc/sdp) - **star:66** SDP:会话描述协议[[RFC 4566](https://tools.ietf.org/html/rfc4566)]。![最近一个周有更新][Green]
    * [sh](https://github.com/mvdan/sh) - **star:1918** Shell解析器和格式化工具。![star > 1000][Silver]   ![最近一个周有更新][Green]
    * [slug](https://github.com/gosimple/slug) - **star:365** URL 友好的 slug 化工具，支持多种语言![star > 100][Bronze]   
    * [Slugify](https://github.com/avelino/slugify) - **star:26** 字符串 slug 化的工具。![最近一年没有更新][Yellow]
    * [syndfeed](https://github.com/zhengchun/syndfeed) - **star:4** Atom 1.0和RSS 2.0的联合提要。![最近一年没有更新][Yellow]
    * [toml](https://github.com/BurntSushi/toml) - **star:2712** TOML配置格式(带反射的编码器/解码器)。![star > 1000][Silver]   
* Utility
    * [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - **star:15** 一个基于 sanitization 的 Go 敏感词过滤器。
    * [gotabulate](https://github.com/bndr/gotabulate) - **star:198** 使用 Go 语言简单、美观的打印表格数据![star > 100][Bronze]   ![最近一年没有更新][Yellow]
    * [kace](https://github.com/codemodus/kace) - **star:12** 通用大小写转换工具
    * [parseargs-go](https://github.com/nproc/parseargs-go) - **star:5** 字符串参数解析器，能够理解引用及反斜杠。![最近一年没有更新][Yellow]
    * [parth](https://github.com/codemodus/parth) - **star:31** URL路径分割解析。
    * [radix](https://github.com/yourbasic/radix) - **star:141** 快速字符串排序算法。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
    * [Tagify](https://github.com/zoomio/tagify) - 从给定源生成一组标记。
    * [TySug](https://github.com/Dynom/TySug) - **star:3** 关于键盘布局的其他建议。
    * [xj2go](https://github.com/stackerzzq/xj2go) - **star:17** 将xml或json转换为struct。
    * [xurls](https://github.com/mvdan/xurls) - **star:454** 从文本中提取url。![star > 100][Bronze]   

## 第三方api

*用于访问第三方api的库。*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - **star:39** 使用[Amazon Product Advertising API]的客户端库(https://program.amazon.com/gp/advertising /api/detail/main.html)。![最近一年没有更新][Yellow]
* [anaconda](https://github.com/ChimeraCoder/anaconda) - **star:984**  Twitter 1.1 API 的 go 语言客户端![star > 100][Bronze]   
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - **star:4922** AWS 提供的官方go语言 SDK![star > 1000][Silver]   ![最近一个周有更新][Green]
* [brewerydb](https://github.com/naegelejd/brewerydb) - **star:16** 用于访问 BreweryDB API的 Go 语言库![最近一年没有更新][Yellow]
* [cachet](https://github.com/andygrunwald/cachet) - **star:65** 使用客户端库[Cachet(开源状态页系统)](https://cachethq.io/)。![最近一年没有更新][Yellow]
* [circleci](https://github.com/jszwedko/go-circleci) - **star:41** CircleCI的API的客户端![最近一个周有更新][Green]
* [clarifai](https://github.com/samuelcouch/clarifai) - **star:57** Clarifai API的客户端。![最近一年没有更新][Yellow]
* [codeship-go](https://github.com/codeship/codeship-go) - **star:14**  Codeship API v2的客户端。
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - **star:11** Coinpaprika API的客户端。
* [discordgo](https://github.com/bwmarrin/discordgo) - **star:932**  Discord Chat API的客户端。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [ethrpc](https://github.com/onrik/ethrpc) - **star:165**  Ethereum JSON RPC API的客户端。![star > 100][Bronze]   
* [facebook](https://github.com/huandu/facebook) - **star:765** 支持 Facebook Graph API 的库![star > 100][Bronze]   
* [fcm](https://github.com/maddevsio/fcm) - **star:33**  Firebase Cloud Messaging 的 Go 语言库
* [gads](https://github.com/emiddleton/gads) - **star:44**  Google Adwords 非官方 API
* [gami](https://github.com/bit4bit/gami) - **star:26**  Asterisk Manager Interface 的 Go 语言库![最近一年没有更新][Yellow]
* [gcm](https://github.com/Aorioli/gcm) - **star:30**  Google Cloud Messaging 库![最近一年没有更新][Yellow]
* [geo-golang](https://github.com/codingsince1985/geo-golang) - **star:301** 访问谷歌地图(https://developers.google.com/maps/documentation/geocoding/intro), (MapQuest) (http://open.mapquestapi.com/geocoding/), (Nominatim) (https://developer.mapquest.com/documentation/open/nominatim-search), (OpenCage) (http://geocoder.opencagedata.com/api.html), (Bing) (https://msdn.microsoft.com/en-us/library/ff701715.aspx), (Mapbox) (https://www.mapbox.com/developers/api/geocoding/),以及[OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding api 的库![star > 100][Bronze]   
* [github](https://github.com/google/go-github) - **star:4681** 访问GitHub REST API v3的库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [githubql](https://github.com/shurcooL/githubql) - **star:484** 访问GitHub GraphQL API v4的库。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-chronos](https://github.com/axelspringer/go-chronos) - **star:3** 用于与[Chronos](https://mesos.github.io/chronos/)作业调度程序进行交互的Go库![最近一年没有更新][Yellow]
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - **star:9** HackerNews API的小型Go客户端。![最近一年没有更新][Yellow]
* [go-imgur](https://github.com/koffeinsource/go-imgur) - **star:12**  Go [imgur]的客户端库(https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - **star:551**  Go [Atlassian JIRA]的客户端库(https://www.atlassian.com/software/jira)![star > 100][Bronze]   
* [go-marathon](https://github.com/gambol99/go-marathon) - **star:188**  用于和 Mesosphere's Marathon PAAS 交互的 Go 语言库![star > 100][Bronze]   
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - **star:16** 访问[MyAnimeList API]的客户端库(http://myanimelist.net/modules.php?go=api)。![最近一年没有更新][Yellow]
* [go-sophos](https://github.com/esurdam/go-sophos) - **star:5** 为[Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/pdfs/documentation/utmonaws/sophos-ut-restful-api.pdf?
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - **star:8**  SPTrans Olho Vivo API 的客户端。![最近一年没有更新][Yellow]
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph 发布平台 API 客户端。
* [go-trending](https://github.com/andygrunwald/go-trending) - **star:99** 在Github上访问[trends repository](https://github.com/trends)和[developers](https://github.com/trending/developers)的库。
* [go-twitch](https://github.com/knspriggs/go-twitch) - **star:16**  Twitch v3 API 的客户端。![最近一年没有更新][Yellow]
* [go-twitter](https://github.com/dghubble/go-twitter) - **star:693**  Twitter v1.1 api 的客户端。。![star > 100][Bronze]   
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - **star:20** 使用[Unsplash.com](https://unsplash.com) API的客户端库。
* [go-xkcd](https://github.com/nishanths/go-xkcd) - **star:37**  xkcd API 的客户端。![最近一年没有更新][Yellow]
* [golyrics](https://github.com/mamal72/golyrics) - **star:29** Golyrics是一个从Wikia网站获取音乐歌词数据的Go库。![最近一年没有更新][Yellow]
* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - **star:36**  Go MusicBrainz WS2客户端库。
* [google](https://github.com/google/google-api-go-client) - **star:1892** 为Go自动生成谷歌api。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [google-analytics](https://github.com/chonthu/go-google-analytics) - **star:12** 简单的包装，方便的谷歌分析报告。![最近一年没有更新][Yellow]
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - **star:1730** 谷歌云api Go 客户端库。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - **star:6** [谷歌G Suite Email Audit API](https://developer.google.com/admin-sdk/email-audit/) 的客户端。![最近一年没有更新][Yellow]
* [gostorm](https://github.com/jsgilmore/gostorm) - **star:119** GoStorm是一个Go库，它实现了编写Storm spout和bolt所需的通信协议，这些协议用于与Storm shell通信。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [hipchat](https://github.com/andybons/hipchat) - **star:109** 这个项目为Hipchat API实现了一个golang客户端库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - **star:114** 一个用于通过XMPP与HipChat通信的golang包。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [igdb](https://github.com/Henry-Sarabia/igdb) - **star:52** [Internet Game Database API](https://api.igdb.com/) 客户端。
* [Medium](https://github.com/Medium/medium-sdk-go) - **star:116** Medium的OAuth2 API 客户端。![star > 100][Bronze]   
* [megos](https://github.com/andygrunwald/megos) - **star:57** 用于访问[Apache Mesos](http://mesos.apache.org/)集群的客户端库。![最近一年没有更新][Yellow]
* [minio-go](https://github.com/minio/minio-go) - **star:704** 用于Amazon S3兼容云存储的Minio Go库。![star > 100][Bronze]   
* [mixpanel](https://github.com/dukex/mixpanel) - **star:28** Mixpanel是一个库，用于跟踪事件并将Mixpanel概要文件更新从go应用程序发送到Mixpanel。
* [patreon-go](https://github.com/mxpv/patreon-go) - **star:17**  Go Patreon API库。
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - **star:297** PayPal支付API的包装器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - **star:1** Playlyfe Rest API Go SDK。![最近一年没有更新][Yellow]
* [pushover](https://github.com/gregdel/pushover) - **star:57**  Go 包装的 Pushover API。
* [rrdaclient](https://github.com/Omie/rrdaclient) - **star:8** 用于接入 statdns.com API 的库——RRDA API。通过HTTP协议进行 DNS查询。![最近一年没有更新][Yellow]
* [shopify](https://github.com/rapito/go-shopify) - **star:20** 一个用于通过 Shopify API 进行增删改查的 Go 语言库。![最近一年没有更新][Yellow]
* [simples3](https://github.com/rhnvrm/simples3) - **star:9** 使用REST和用Go编写的V4签名的AWS S3库非常简单。
* [slack](https://github.com/nlopes/slack) - **star:2345** Slack API。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [smite](https://github.com/sergiotapia/smitego) - **star:10** 对 Smite game API 的封装。![最近一年没有更新][Yellow]
* [spotify](https://github.com/rapito/go-spotify) - **star:16**  用于接入 Spotify WEB API 的 Go 语言库![最近一年没有更新][Yellow]
* [steam](https://github.com/sostronk/go-steam) - **star:14**  用于与Steam服务器进行交互的库。![最近一年没有更新][Yellow]
* [stripe](https://github.com/stripe/stripe-go) - **star:912**  Stripe API 的 Go 语言客户端![star > 100][Bronze]   ![最近一个周有更新][Green]
* [textbelt](https://github.com/dietsche/textbelt) - **star:14** textbelt.com txt messaging API 的go语言客户端。![最近一年没有更新][Yellow]
* [TheMovieDb](https://github.com/jbrodriguez/go-tmdb) - **star:13** 简单的golang包与[themoviedb.org]通信(https://themoviedb.org)。![最近一年没有更新][Yellow]
* [translate](https://github.com/poorny/translate) - **star:27**  Go 在线翻译包。![最近一年没有更新][Yellow]
* [Trello](https://github.com/adlio/trello) - **star:98**  Trello API的 Go 语言封装。
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) -  TripAdvisor API 的 Go 语言封装。
* [tumblr](https://github.com/mattcunningham/gumblr) - **star:6**  Tumblr v2 API 的 Go 语言封装。![最近一年没有更新][Yellow]
* [uptimerobot](https://github.com/bitfield/uptimerobot) - **star:34** 运行时Robot v2 API 的 Go 语言封装和命令行客户端。
* [webhooks](https://github.com/go-playground/webhooks) - **star:337** GitHub 和 Bitbucket 的Webhook接收器。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [wit-go](https://github.com/wit-ai/wit-go) - **star:45** wit.ai HTTP API 客户端。
* [ynab](https://github.com/brunomvsouza/ynab.go) - **star:10**  YNAB API 的 Go 语言封装。
* [zooz](https://github.com/gojuno/go-zooz) - **star:5**  Zooz API 的 Go 语言客户端。

## 公用事业公司

*可以让你的生活变得更简单的实用工具.。*

* [abutil](https://github.com/bahlo/abutil) - **star:52** 常用 Go 语言工具的集合。![最近一年没有更新][Yellow]
* [apm](https://github.com/topfreegames/apm) - **star:127** Go 语言进程管理工具具有HTTP API.。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [backscanner](https://github.com/icza/backscanner) - **star:8** 类似 bufio 的扫描器，但它以相反的顺序读取和返回行，从给定的位置开始，然后返回。
* [blank](https://github.com/Henry-Sarabia/blank) - **star:1** 验证或删除字符串中的空白。
* [boilr](https://github.com/tmrts/boilr) - **star:921** 非常快的CLI工具，用于从样板模板创建项目。![star > 100][Bronze]   
* [chyle](https://github.com/antham/chyle) - **star:107** 使用具有多种配置可能性的git存储库生成变更日志。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [circuit](https://github.com/cep21/circuit) - **star:316** 一个高效和功能齐全的 类似 Hystrix Go 实现断路器模式。![star > 100][Bronze]   
* [circuitbreaker](https://github.com/rubyist/circuitbreaker) - **star:776** 接通断路器。![star > 100][Bronze]   
* [clockwork](https://github.com/jonboulle/clockwork) - **star:217** 一个简单的假 clock 。![star > 100][Bronze]   
* [command](https://github.com/txgruppi/command) - **star:9** 命令模式，支持线程安全的串行、并行调度。![最近一年没有更新][Yellow]
* [copy-pasta](https://github.com/jutkko/copy-pasta) - **star:37** 通用多工作站剪切板，使用类似 S3 的后端作为存储。
* [ctop](https://github.com/bcicen/ctop) - **star:8641** [Top-like](http://ctop.sh)接口(例如htop)， 用于容器数据收集。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [ctxutil](https://github.com/posener/ctxutil) - **star:6** 上下文工具。
* [dbt](https://github.com/nikogura/dbt) - **star:10** 用于从中心可信存储库运行自更新签名二进制文件的框架。
* [Death](https://github.com/vrecan/death) - **star:132** 利用信号管理应用程序的关闭。![star > 100][Bronze]   
* [Deepcopier](https://github.com/ulule/deepcopier) - **star:201** 结构体拷贝![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [delve](https://github.com/derekparker/delve) - **star:11721** Go 语言调试器![star > 5000][Gold]   ![最近一个周有更新][Green]
* [dlog](https://github.com/kirillDanshin/dlog) - **star:15** 编译时控制的日志，让你的 release 包变得更小而不需移除 debug 调用。![最近一年没有更新][Yellow]
* [ergo](https://github.com/cristianoliveira/ergo) - **star:308** 管理运行在不同端口上的多个本地服务变得很容易。![star > 100][Bronze]   
* [evaluator](https://github.com/nullne/evaluator) - **star:14** 基于 s-expression。它很简单，很容易扩展。![最近一年没有更新][Yellow]
* [fastlz](https://github.com/digitalcrab/fastlz) - **star:11** [FastLz](http://fastlz.org/)(免费，开源，可移植实时压缩库) 的一个封装![最近一年没有更新][Yellow]
* [filetype](https://github.com/h2non/filetype) - **star:925** 通过数字签名来推测文件类型。![star > 100][Bronze]   
* [filler](https://github.com/yaronsumel/filler) - **star:14** 使用“fill”标签填充结构的小工具。![最近一年没有更新][Yellow]
* [filter](https://github.com/gookit/filter) - **star:11** 提供Go数据的过滤、清理和转换。
* [fzf](https://github.com/junegunn/fzf) - **star:22407** 用Go编写的命令行模糊查找器。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [gaper](https://github.com/maxcnunes/gaper) - **star:37** 当Go项目崩溃或一些人看到文件更改时，构建并重新启动该项目。
* [generate](https://github.com/go-playground/generate) - **star:19** 针对一个路径或环境变量，递归的执行 Go generate，可以通过正则表达式来进行过滤。![最近一年没有更新][Yellow]
* [ghokin](https://github.com/antham/ghokin) - **star:12** 没有外部依赖的gherkin (cucumber, behat…)并行格式化程序。
* [git-time-metric](https://github.com/git-time-metric/gtm) - **star:710** git-time-metric - 。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [go-astitodo](https://github.com/asticode/go-astitodo) - **star:46** 解析你 Go 语言代码中的 TODOs（待办事项）。
* [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - **star:159** Go:generate 工具，用于构建 Go 语言插件(1.8 only)，并对导出的符号进行包装。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-bsdiff](https://github.com/gabstv/go-bsdiff) - **star:79** 纯Go bsdiff和bspatch库和CLI工具。
* [go-dry](https://github.com/ungerik/go-dry) - **star:432** DRY(don't repeat yourself)库。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-funk](https://github.com/thoas/go-funk) - **star:1051** 现代 Go 语言工具库，提供了很多有用的工具 (map, find, contains, filter, chunk, reverse, ...)![star > 1000][Silver]   
* [go-health](https://github.com/Talento90/go-health) - **star:63** 健康包简化了向服务中添加健康检查的方式。![最近一年没有更新][Yellow]
* [go-httpheader](https://github.com/mozillazg/go-httpheader) - **star:14**  用于将结构体编码进 http 头的 Go 语言库
* [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - **star:2** 打包处理问题细节。
* [go-rate](https://github.com/beefsack/go-rate) - **star:292**  Go 限速器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - **star:103** 用Go编写的XML站点地图生成器。![star > 100][Bronze]   
* [go-torch](https://github.com/uber/go-torch) - **star:3622** 为 Go 语言程序生成火焰图。![star > 1000][Silver]   
* [go-trigger](https://github.com/sadlil/go-trigger) - **star:181** Go 语言全局事件触发器，通过 id 和触发器，在程序的任何地方注册事件。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [goback](https://github.com/carlescere/goback) - **star:39**  一个 Go 语言的简单的指数补偿包。![最近一年没有更新][Yellow]
* [godaemon](https://github.com/VividCortex/godaemon) - **star:401** 用于编写守护进程的工具![star > 100][Bronze]   
* [godropbox](https://github.com/dropbox/godropbox) - **star:3730** 用于编写 Go 语言服务／应用的库，来自 Dropbox.。![star > 1000][Silver]   
* [gohper](https://github.com/cosiner/gohper) - **star:248** 多种能够帮助你进行软件开发的工具和模块。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [golarm](https://github.com/msempere/golarm) - **star:34** 告警（支持系统事件）。![最近一年没有更新][Yellow]
* [golog](https://github.com/mlimaloureiro/golog) - **star:43** 简单、轻量级的命令后工具，用于对你的计划任务进行跟踪。
* [gopencils](https://github.com/bndr/gopencils) - **star:423** 小而简单的包，可以轻松地使用REST api。![star > 100][Bronze]   
* [goplaceholder](https://github.com/michiwend/goplaceholder) - **star:22** 一个小巧的 Go 语言库用于生成占位图片。![最近一年没有更新][Yellow]
* [goreadability](https://github.com/philipjkim/goreadability) - **star:28** 网页摘要提取器使用Facebook开放图形和arc90的可读性。
* [goreleaser](https://github.com/goreleaser/goreleaser) - **star:4345** 尽可能快速的发布 Go 语言二进制文件。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [goreporter](https://github.com/wgliang/goreporter) - **star:2458** 进行代码静态分析，单元测试，代码检视并生成代码质量报告的工具![star > 1000][Silver]   
* [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - **star:25** conseilSeaweedFS 客户端，几乎具有全部的特性。
* [gostrutils](https://github.com/ik5/gostrutils) - **star:14** 字符串操作和转换函数的集合。
* [gotenv](https://github.com/subosito/gotenv) - **star:136** 从 `.env` 或者任何 `io.Reader`。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gpath](https://github.com/tenntenn/gpath) - **star:25**  用于简化结构体域访问的库。![最近一年没有更新][Yellow]
* [gubrak](https://github.com/novalagung/gubrak) - **star:127** 带有语法糖的Golang实用工具，就像lodash。![star > 100][Bronze]   
* [handy](https://github.com/miguelpragier/handy) - **star:43** 许多实用程序和帮助程序，如字符串处理程序/格式化程序和验证器。
* [htcat](https://github.com/htcat/htcat) - **star:480** 并行及流水线的 HTTP GET 工具。![star > 100][Bronze]   
* [hub](https://github.com/github/hub) - **star:16579** 封装了 git 命令，提供了额外的功能用于在终端中和 Github 进行交互。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [hystrix-go](https://github.com/afex/hystrix-go) - **star:1946** 实现 Hystrix 风格的、程序员预定义的 fallback 机制（熔断。![star > 1000][Silver]   
* [immortal](https://github.com/immortal/immortal) - **star:599** \*nix 跨平台 (与操作系统无关的)监控程序。![star > 100][Bronze]   
* [intrinsic](https://github.com/mengzhuo/intrinsic) - **star:39** 不需要编写任何汇编代码就能使用 x86 SIMD。![最近一年没有更新][Yellow]
* [jump](https://github.com/gsamokovarov/jump) - **star:641** 通过学习你的习惯，可以帮助你更快地导航。![star > 100][Bronze]   
* [koazee](https://github.com/wesovilabs/koazee) - **star:276** 库的灵感来自于延迟计算和函数式编程，从而减少了使用数组的麻烦。![star > 100][Bronze]   
* [lrserver](https://github.com/jaschaephraim/lrserver) - **star:99** LiveReload 服务器。![最近一年没有更新][Yellow]
* [mc](https://github.com/minio/mc) - **star:1070** Minio Client 提供了一组工具，用于操作 Amazon S3 兼容云存储和文件系统。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [mergo](https://github.com/imdario/mergo) - **star:824** 用于将结构体和map合并进 Go 语言的工具。对于配置默认值，避免杂乱的if语句很有帮助。![star > 100][Bronze]   
* [mimemagic](https://github.com/zRedShift/mimemagic) - **star:43** 纯粹 Go 超性能MIME嗅探库/实用程序。
* [mimesniffer](https://github.com/aofei/mimesniffer) - **star:6** 一个用于Go的MIME类型嗅探器。
* [mimetype](https://github.com/gabriel-vasile/mimetype) - **star:99** 用于基于神奇数字的MIME类型检测的包。
* [minify](https://github.com/tdewolff/minify) - **star:1836** 用于HTML、CSS、JS、XML、JSON和SVG文件格式的快速缩小器。![star > 1000][Silver]   
* [minquery](https://github.com/icza/minquery) - **star:50** MongoDB / mgo.v2, 支持高效分页查询(用于继续列出我们停止的文档的游标)。
* [mmake](https://github.com/tj/mmake) - **star:1450** 现代 Make 工具![star > 1000][Silver]   
* [moldova](https://github.com/StabbyCutyou/moldova) - **star:148** 基于输入目标生成随机数据的工具![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [mole](https://github.com/davrodpin/mole) - **star:1290** cli应用程序可以轻松创建ssh隧道。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [mssqlx](https://github.com/linxGnu/mssqlx) - **star:57** 数据库客户端，用于主-从 (或主-主) 数据库，集成了简单的、轻量级的轮询调度负载均衡。
* [multitick](https://github.com/VividCortex/multitick) - **star:58** 用于 aligned tickers 的多路复用![最近一年没有更新][Yellow]
* [myhttp](https://github.com/inancgumus/myhttp) - **star:34** 简单的API，使HTTP GET请求与超时支持。![最近一年没有更新][Yellow]
* [netbug](https://github.com/e-dard/netbug) - **star:65** 远程对你的服务进行性能分析![最近一年没有更新][Yellow]
* [okrun](https://github.com/xta/okrun) - **star:14**  Go 运行错误 steamroller。![最近一年没有更新][Yellow]
* [olaf](https://github.com/btnguyen2k/olaf) - **star:1** Twitter Snowflake 在Go中实现。
* [onecache](https://github.com/adelowo/onecache) - **star:98** 支持多个后端存储(Redis、Memcached、文件系统等)的缓存库。
* [panicparse](https://github.com/maruel/panicparse) - **star:2077** 将类似的协程分组并对调用栈进行着色![star > 1000][Silver]   ![最近一个周有更新][Green]
* [peco](https://github.com/peco/peco) - **star:5404** 简单的交互过滤工具。![star > 5000][Gold]   
* [pgo](https://github.com/arthurkushman/pgo) - **star:23** 用于PHP社区的 Convenient 函数。
* [pm](https://github.com/VividCortex/pm) - **star:72** 进程(即goroutine)管理器与HTTP API。
* [profile](https://github.com/pkg/profile) - **star:984** Go的简单分析支持包。![star > 100][Bronze]   
* [rclient](https://github.com/zpatrick/rclient) - **star:26** 可读、灵活、易于使用的REST api客户端。
* [realize](https://github.com/tockins/realize) - **star:3089** Go 语言构建系统，可以监控文件变化并重新加载。运行，构建，监控文件并支持自定义路径。![star > 1000][Silver]   
* [repeat](https://github.com/ssgreg/repeat) - **star:56** 执行不同的后 backoff 策略，这对重新尝试操作和心跳非常有用。
* [request](https://github.com/mozillazg/request) - **star:355** Go 语言版的 HTTP Requests for Humans™.。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [rerate](https://github.com/abo/rerate) - **star:12** 基于 Redis 的速率计数器和限速器![最近一年没有更新][Yellow]
* [rerun](https://github.com/ivpusic/rerun) - **star:153** 当源代码发生更改时，重新编译和重新运行go应用程序。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [resty](https://github.com/go-resty/resty) - **star:1816** 简单的 HTTP 和 REST 客户端，受到 Ruby rest-client 的启发。![star > 1000][Silver]   
* [retry](https://github.com/kamilsk/retry) - **star:139** 基于上下文的功能机制，反复执行命令直到成功。![star > 100][Bronze]   
* [retry](https://github.com/percolate/retry) - **star:2** 一个简单但高度可配置的Go重试包。
* [retry](https://github.com/thedevsaddam/retry) - **star:34** 简单易用的重试机制包，为 Go 。![最近一年没有更新][Yellow]
* [retry](https://github.com/shafreeck/retry) - **star:9** 一个相当简单的库，以确保您的工作可以完成。
* [retry-go](https://github.com/rafaeljesus/retry-go) - **star:26** 对 Go 来说，重试变得简单而容易。
* [robustly](https://github.com/VividCortex/robustly) - **star:133** 有弹性的执行函数，遇到错误时捕获并重新运行。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [scan](https://github.com/blockloop/scan) - **star:11** 扫描golang的sql。行直接指向结构、片或基本类型。
* [serve](https://github.com/syntaqx/serve) - **star:190** 任何您需要的静态http服务器。![star > 100][Bronze]   
* [silk](https://github.com/chrispassas/silk) - **star:4** 阅读silk netflow文件。
* [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - **star:2** 基本类型之间的片转换。
* [slicer](https://github.com/leaanthony/slicer) - **star:3** 使处理切片更容易。![最近一个周有更新][Green]
* [spinner](https://github.com/briandowns/spinner) - **star:764**  一个 Go 语言软件包，提供多种选项，方便在终端中创建加载动画。![star > 100][Bronze]   
* [sqlx](https://github.com/jmoiron/sqlx) - **star:6579** 为内建的数据库/sql 软件包提供一组扩展。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [sslice](https://github.com/yaa110/sslice) - **star:2** 创建一个总是排序的切片。
* [Storm](https://github.com/asdine/storm) - **star:1332** 一个简单又强大的用于 BoltDB 的工具![star > 1000][Silver]   
* [structs](https://github.com/PumpkinSeed/structs) - **star:12** 简单来讲就是 "Make" 的替代品。![最近一年没有更新][Yellow]
* [Task](https://github.com/go-task/task) - **star:1860** 简单的“Go”的选择。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [toolbox](https://github.com/viant/toolbox) - **star:86** 切片, map, multimap, 结构体, 函数,数据转换工具。服务路由，宏求值和标记器。![最近一个周有更新][Green]
* [tracer](https://github.com/kamilsk/tracer) - **star:2** 简单、轻量级的跟踪。![最近一个周有更新][Green]
* [ugo](https://github.com/alxrm/ugo) - **star:20** uGo 是一个切片工具箱，有着和 Go 语言一致的语法法。![最近一年没有更新][Yellow]
* [UNIS](https://github.com/esemplastic/unis) - **star:70** Go 语言字符串处理函数的通用架构 。![最近一年没有更新][Yellow]
* [usql](https://github.com/knq/usql) - **star:4651** usql 是一个通用的命令行接口，用于操作 sql 数据库。![star > 1000][Silver]   
* [util](https://github.com/shomali11/util) - **star:131** 有用实用函数的集合。(字符串，并发，操作，…)![star > 100][Bronze]   
* [wuzz](https://github.com/asciimoo/wuzz) - **star:8203** 用于HTTP检查的交互式cli工具。![star > 5000][Gold]   
* [xferspdy](https://github.com/monmohan/xferspdy) - **star:68** Xferspdy在golang中提供二进制diff和补丁库。![最近一年没有更新][Yellow]

## UUID

*用于处理uuid的库。*

* [goid](https://github.com/jakehl/goid) - **star:20** 生成和解析RFC4122兼容的V4 uuid。
* [sno](https://github.com/muyo/sno) - **star:12** 使用嵌入元数据的紧凑、可排序和快速的惟一id。
* [ulid](https://github.com/oklog/ulid) - **star:1652** 实现了ULID(普遍唯一的词典分类标识符)。![star > 1000][Silver]   
* [uuid](https://github.com/agext/uuid) - **star:10** 使用快速或加密质量的随机节点标识符生成、编码和解码UUIDs v1。
* [uuid](https://github.com/gofrs/uuid) - **star:550** 通用唯一标识符(UUID)的实现。支持uuid的创建和解析。积极维护satori uuid的fork。![star > 100][Bronze]   
* [wuid](https://github.com/edwingeng/wuid) - **star:277** 一个非常快的唯一数字生成器，比UUID快10-135倍。![star > 100][Bronze]   

## 验证

*库进行验证。*

* [checkdigit](https://github.com/osamingo/checkdigit) - **star:43** 提供校验数字算法(Luhn, Verhoeff, Damm)和计算器(ISBN, EAN, JAN, UPC等)。
* [govalidator](https://github.com/asaskevich/govalidator) - **star:3484** 用于字符串，数字，切片和结构的验证器和sanitizers。![star > 1000][Silver]   
* [govalidator](https://github.com/thedevsaddam/govalidator) - **star:695** 用简单的规则验证Golang请求数据。深受Laravel请求验证的启发。![star > 100][Bronze]   
* [jio](https://github.com/faceair/jio) - **star:21** jio是一个json模式验证器，类似于[joi](https://github.com/hapijs/joi)。
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - **star:1010** 支持各种数据类型(结构、字符串、映射、片等)的验证，使用可配置和可扩展的验证规则，这些规则在通常的代码构造中指定，而不是在结构标签中指定。![star > 1000][Silver]   
* [validate](https://github.com/gookit/validate) - **star:84**  Go 封装数据验证和过滤。支持验证映射、结构、请求(表单、JSON、url)。值，上载文件)数据和更多特性。
* [validate](https://github.com/gobuffalo/validate) - **star:19** 这个包提供了一个框架，用于为Go应用程序编写验证。
* [validator](https://github.com/go-playground/validator) - **star:3305**  Go 结构体及域验证，包括：跨域、跨结构体, Map, 切片和数组。![star > 1000][Silver]   ![最近一个周有更新][Green]

## 版本控制

*用于版本控制的库。*

* [gh](https://github.com/rjeczalik/gh) - **star:68** 用于GitHub webhook的可编写脚本的服务器和net/http中间件。
* [git2go](https://github.com/libgit2/git2go) - **star:1339**  libgit2 的 Go 语言接口。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-git](https://github.com/src-d/go-git) - **star:4108** 纯Go中高度可扩展的Git实现。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [go-vcs](https://github.com/sourcegraph/go-vcs) - **star:69** 在Go中操作和检查VCS存储库。
* [hercules](https://github.com/src-d/hercules) - **star:504** 从Git存储库历史中获得高级见解。![star > 100][Bronze]   
* [hgo](https://github.com/beyang/hgo) - **star:12** Hgo是一组Go包的集合，提供对本地Mercurial存储库的读取访问。![最近一年没有更新][Yellow]

## 视频

*用于操作视频的库。*

* [gmf](https://github.com/3d0c/gmf) - **star:508**  FFmpeg av\* 库的 Go 语言接口。![star > 100][Bronze]   
* [go-astisub](https://github.com/asticode/go-astisub) - **star:162** 使用 Go 语言操作字幕(.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.)。![star > 100][Bronze]   
* [go-astits](https://github.com/asticode/go-astits) - **star:256** 在GO中解析和演示MPEG传输流(.ts)。![star > 100][Bronze]   
* [go-m3u8](https://github.com/quangngotan95/go-m3u8) - **star:36** 苹果m3u8播放列表的解析器和生成器库。
* [goav](https://github.com/giorgisio/goav) - **star:749** FFmpeg的Comphrensive。![star > 100][Bronze]   
* [gst](https://github.com/ziutek/gst) - **star:153**  GStreamer的Go工具。![star > 100][Bronze]   
* [libgosubs](https://github.com/wargarblgarbl/libgosubs) - **star:11** 字幕格式支持 .srt、.ttml和.ass。
* [libvlc-go](https://github.com/adrg/libvlc-go) - **star:60** Go绑定libvlc 2.X/3.X/4。X(由VLC媒体播放器使用)。
* [v4l](https://github.com/korandiz/v4l) - **star:26** 用于Linux的视频捕捉库，用Go编写。![最近一年没有更新][Yellow]

## Web框架

*全栈 web 框架。*

* [aah](https://aahframework.org) - 可伸缩、高性能、快速开发的Go Web框架。
* [Aero](https://github.com/aerogo/aero) - **star:152** 高性能的Go web框架，在Lighthouse中达到最高分。![star > 100][Bronze]   
* [Air](https://github.com/aofei/air) - **star:512** 一个理想的精细化的Go web框架。![star > 100][Bronze]   
* [Banjo](https://github.com/nsheremet/banjo) - **star:7** 非常简单和快速的网络框架 Go 。![最近一年没有更新][Yellow]
* [Beego](https://github.com/astaxie/beego) - **star:21045** beego是一种用于 Go 编程语言的开源高性能web框架。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Buffalo](http://gobuffalo.io) - 为 Go 语言带来堪比 Rails 的高生产效率!
* [Echo](https://github.com/labstack/echo) - **star:14365** 高性能、极简的Go web框架。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Fireball](https://github.com/zpatrick/fireball) - **star:48** 感觉更加自然的 web 框架。
* [Gem](https://github.com/go-gem/gem) - **star:153** 简单快速的web框架，对REST API友好。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Gin](https://github.com/gin-gonic/gin) - **star:28757** Gin是一个用Go编写的web框架!它具有一个类似于martini的API，性能更好，速度快40倍。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Gizmo](https://github.com/NYTimes/gizmo) - **star:2811** 《纽约时报》使用的微服务工具包。![star > 1000][Silver]   
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - **star:3317** 设置RESTful JSON API的快速简便方法。![star > 1000][Silver]   
* [go-rest](https://github.com/ungerik/go-rest) - **star:115** 小型的 REST 框架。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Goa](https://github.com/goadesign/goa) - **star:3460** Goa为在Go中开发远程api和微服务提供了一种全面的方法。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Golax](https://github.com/fulldump/golax) - **star:71** 一个非Sinatra快速HTTP框架，支持谷歌自定义方法、深度拦截器、递归等。![最近一年没有更新][Yellow]
* [Golf](https://github.com/dinever/golf) - **star:235** Golf 是一个快速、简单、轻量级的 Go 语言微型 web 框架。具有强大的功能且没有标准库以外的依赖。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Gondola](https://github.com/rainycape/gondola) - **star:315** web框架写的网站越快越好。![star > 100][Bronze]   
* [gongular](https://github.com/mustafaakin/gongular) - **star:415**  快速 Go web 框架，支持输入映射／验证以及依赖注入。![star > 100][Bronze]   
* [hiboot](https://github.com/hidevopsio/hiboot) - **star:80** hiboot是一个高性能的web应用程序框架，支持自动配置和依赖注入。
* [Macaron](https://github.com/go-macaron/macaron) - **star:2783** Macaron 是一个高效的模块化设计的web框架![star > 1000][Silver]   
* [mango](https://github.com/paulbellamy/mango) - **star:339** ManGo 是一个模块化 web 应用框架，受到 Rack 和 PEP333 的启发。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Microservice](https://github.com/claygod/microservice) - **star:56** 创建微服务的框架，用Golang编写。
* [neo](https://github.com/ivpusic/neo) - **star:392** Neo是一个非常简单且快速的Web框架API。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [nio](https://github.com/go-nio/nio) - **star:21** 现代的、最小的和高效的Go HTTP框架。
* [patron](https://github.com/beatlabs/patron) - **star:21** Patron是一个遵循最佳云实践的微服务框架，专注于提升开发效率。![最近一个周有更新][Green]
* [Resoursea](https://github.com/resoursea/api) - **star:29** 用于快速编写基于资源的服务的REST框架。![最近一年没有更新][Yellow]
* [REST Layer](http://rest-layer.io) - 框架，用于在数据库之上构建REST/GraphQL API，主要是通过代码进行配置。
* [Revel](https://github.com/revel/revel) - **star:11171** 用于Go语言的高效web框架。![star > 5000][Gold]   
* [rex](https://github.com/goanywhere/rex) - **star:25**  Rex 是一个用于进行模块化开发的库，基于Gorilla/mux 完全兼容大多数的 net/HTTP.![最近一年没有更新][Yellow]
* [sawsij](https://github.com/jaybill/sawsij) - **star:2** 轻量级、开源的web框架，用于构建高性能、数据驱动的web应用程序。![最近一年没有更新][Yellow]
* [tango](https://github.com/lunny/tango) - **star:814** 微型的、支持插件的 web 框架。![star > 100][Bronze]   
* [tigertonic](https://github.com/rcrowley/go-tigertonic) - **star:997** 用于构建 JSON web 服务的 Go 语言框架，受到 Dropwizard 的启发。![star > 100][Bronze]   
* [traffic](https://github.com/pilu/traffic) - **star:518** Sinatra启发了regexp/pattern mux和用于Go的web框架。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [uAdmin](https://github.com/uadmin/uadmin) - **star:47** 受到 Sinatra 启发的 Go 语言 web 框架。![最近一个周有更新][Green]
* [utron](https://github.com/gernest/utron) - **star:2138** Go(Golang)的轻量级MVC框架。![star > 1000][Silver]   
* [vox](https://github.com/aisk/vox) - **star:27** 一个面向人类的golang web框架，深受Koa的启发。![最近一个周有更新][Green]
* [WebGo](https://github.com/bnkamalesh/webgo) - **star:70** 构建web应用程序的微框架;处理程序链接、中间件和上下文注入。与标准库兼容的HTTP处理程序(即http.HandlerFunc)。![最近一个周有更新][Green]
* [YARF](https://github.com/yarf-framework/yarf) - **star:49** 快速微框架，旨在以快速和简单的方式构建REST api和web服务。
* [Zerver](https://github.com/cosiner/zerver) - Zerver是一个表现力强、模块化、功能完备的RESTful框架。

### 中间件

#### 仿真中间件

* [client-timing](https://github.com/posener/client-timing) - **star:11** 用于服务器定时报头的HTTP客户机。
* [CORS](https://github.com/rs/cors) - **star:1176** 轻松地向API添加CORS功能。![star > 1000][Silver]   
* [formjson](https://github.com/rs/formjson) - **star:33** 透明地将JSON输入作为标准表单POST处理。![最近一年没有更新][Yellow]
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - **star:744** 添加/解析Server-Timing头。![star > 100][Bronze]   
* [Limiter](https://github.com/ulule/limiter) - **star:764** 简单的速度限制中间件。![star > 100][Bronze]   
* [ln-paywall](https://github.com/philippgille/ln-paywall) - **star:86** 使用Lightning Network(比特币)实现基于每个请求的api货币化中间件。
* [Tollbooth](https://github.com/didip/tollbooth) - **star:1212** 限制速率的 HTTP 请求处理程序。![star > 1000][Silver]   
* [XFF](https://github.com/sebest/xff) - **star:71** 处理 X-Forwarded-For 头的中间件。

#### 用于创建HTTP中间件的库

* [alice](https://github.com/justinas/alice) - **star:1805** 用于连接中间件的库，简单无痛苦。![star > 1000][Silver]   
* [catena](https://github.com/codemodus/catena) - **star:7** HTTP.Handler wrapper catenation (和chain具有相同的 API ).。
* [chain](https://github.com/codemodus/chain) - **star:63** 带有范围数据的处理程序包装器链接(基于网络/上下文的“中间件”)。
* [go-wrap](https://github.com/go-on/wrap) - **star:56** net/http的小型中间件包。
* [gores](https://github.com/alioygur/gores) - **star:82** 处理HTML、JSON、XML等响应的Go包。对于RESTful api非常有用。
* [interpose](https://github.com/carbocation/interpose) - **star:290** golang的极简网络/http中间件。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [muxchain](https://github.com/stephens2424/muxchain) - **star:208** 用于net/http的轻量级中间件。![star > 100][Bronze]   
* [negroni](https://github.com/urfave/negroni) - **star:6283** 符合语言习惯的 HTTP 中间件库。![star > 5000][Gold]   
* [render](https://github.com/unrolled/render) - **star:1261** Go package用于方便地呈现JSON、XML和HTML模板响应。![star > 1000][Silver]   
* [renderer](https://github.com/thedevsaddam/renderer) - **star:166** 简单、轻量级和更快的响应(JSON、JSONP、XML、YAML、HTML、文件)。![star > 100][Bronze]   
* [rye](https://github.com/InVisionApp/rye) - **star:92** 支持JWT、CORS、Statsd和Go 1.7上下文的小型Go中间件库(带有罐装中间件)。
* [stats](https://github.com/thoas/stats) - **star:536** 使用中间件来存储关于web应用程序的各种信息。![star > 100][Bronze]   

### 路由器

* [alien](https://github.com/gernest/alien) - **star:105** 轻量级和快速http路由器从外层空间。![star > 100][Bronze]   
* [bellt](https://github.com/GuilhermeCaruso/bellt) - **star:37** 一个简单的Go HTTP路由器。
* [Bone](https://github.com/go-zoo/bone) - **star:1220** 闪电快速HTTP多路复用器。![star > 1000][Silver]   
* [Bxog](https://github.com/claygod/Bxog) - **star:93** 简单和快速的HTTP路由器 Go 。它可以处理不同难度、长度和嵌套的路径。他还知道如何根据接收到的参数创建URL。
* [chi](https://github.com/go-chi/chi) - **star:5866** 小巧、快速、具有丰富表达力的 HTTP 路由，基于net/context.。![star > 5000][Gold]   
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - **star:735** 高性能路由器分叉从`httprouter`。第一个路由器适合`fasthttp`。![star > 100][Bronze]   
* [FastRouter](https://github.com/razonyang/fastrouter) - **star:18** 一个快速，灵活的HTTP路由器写在Go。![最近一年没有更新][Yellow]
* [gocraft/web](https://github.com/gocraft/web) - **star:1390** Mux和中间件包在Go中。![star > 1000][Silver]   
* [Goji](https://github.com/goji/goji) - **star:761** 枸杞是一种简约的和灵活的与支持'net/context` HTTP请求多路复用器。![star > 100][Bronze]   
* [GoRouter](https://github.com/vardius/gorouter) - **star:47** GoRouter 是一个服务器/API 微型框架、HTTP 请求路由 router, 数据分选器，提供了支持net/context的中间件。
* [gowww/router](https://github.com/gowww/router) - **star:158** 超快的HTTP 路由，完全兼容 net/HTTP.Handler 接口.。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [httprouter](https://github.com/julienschmidt/httprouter) - **star:9494** 高性能路由。使用这个库和标准http处理工具可以构建一个非常高性能大web框架。![star > 5000][Gold]   
* [httptreemux](https://github.com/dimfeld/httptreemux) - **star:386** 高速，灵活，基于树的 HTTP 路由。受到了 httprouter 的启发。![star > 100][Bronze]   
* [lars](https://github.com/go-playground/lars) - **star:375** 是一个轻量级、快速、可扩展、零分配的HTTP路由，用于创建定制化的框架。![star > 100][Bronze]   
* [mux](https://github.com/gorilla/mux) - **star:9399** 强大的URL路由器和调度器为golang。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - **star:358** 一个非常快的Go (golang) HTTP路由器，支持正则表达式路由匹配。完全支持构建RESTful api。![star > 100][Bronze]   
* [pure](https://github.com/go-playground/pure) - **star:83** 是一个轻量级HTTP路由器，它坚持net/ HTTP“实现”的std。
* [Siesta](https://github.com/VividCortex/siesta) - **star:349** 编写中间件和处理程序的可组合框架。![star > 100][Bronze]   
* [vestigo](https://github.com/husobee/vestigo) - **star:250** 高性能，独立，HTTP兼容的URL路由器的go web应用程序。![star > 100][Bronze]   
* [violetear](https://github.com/nbari/violetear) - **star:95** HTTP路由器。
* [xmux](https://github.com/rs/xmux) - **star:87** 高性能mux基于httprouter 'net/context`支持。![最近一年没有更新][Yellow]
* [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - **star:445** 一个简单和快速的HTTP路由器 Go 。![star > 100][Bronze]   ![最近一个周有更新][Green]

## Windows

* [d3d9](https://github.com/gonutz/d3d9) - **star:86**  Direct3D9 的 Go 语言接口。
* [go-ole](https://github.com/go-ole/go-ole) - **star:541** 为 Go 语言实现的 Win32 OLE。![star > 100][Bronze]   
* [gosddl](https://github.com/MonaxGT/gosddl) - **star:1** 从SDDL-string到用户友好的JSON的转换器。SDDL由四个部分组成:所有者、主群、DACL、SACL。

## XML

*用于操作XML的库和工具。*

* [XML-Comp](https://github.com/xml-comp/xml-comp) - **star:15** 简单的命令行XML比较器，生成文件夹、文件和标记的差异。
* [xml2map](https://github.com/sbabiv/xml2map) - **star:15** XML来映射转换器编写的Golang。
* [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - **star:6** 基于libxml2的xmlwriter模块的过程性XML生成API。
* [xpath](https://github.com/antchfx/xpath) - **star:152** Go的XPath包。![star > 100][Bronze]   
* [xquery](https://github.com/antchfx/xquery) - **star:145** XQuery允许您使用XPath表达式从HTML/XML文档中提取数据。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [zek](https://github.com/miku/zek) - **star:243** 从XML生成Go结构。![star > 100][Bronze]   

# 工具

* Go 软件和插件。*

## 代码分析

* [apicompat](https://github.com/bradleyfalzon/apicompat) - **star:165** 检查 Go 项目最近的向下不兼容修改。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [dupl](https://github.com/mibk/dupl) - **star:167** 用于代码克隆检测的工具。![star > 100][Bronze]   
* [errcheck](https://github.com/kisielk/errcheck) - **star:1310** Errcheck是一个用于检查Go程序中未检查错误的程序。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gcvis](https://github.com/davecheney/gcvis) - **star:912** 实时可视化跟踪 GC 数据。![star > 100][Bronze]   
* [go-checkstyle](https://github.com/qiniu/checkstyle) - **star:95** checkstyle是一个类似于java checkstyle的样式检查工具
* [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - **star:277** go-cleanarch 的创建是为了验证 Clean 体系结构规则，比如 Go 项目中的依赖关系。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-critic](https://github.com/go-critic/go-critic) - **star:552** 源代码检查工具。![star > 100][Bronze]   
* [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - **star:177** 找出项目中过期的依赖项。![star > 100][Bronze]   
* [go-outdated](https://github.com/firstrow/go-outdated) - **star:45** 显示过期包的终端应用。
* [goast-viewer](https://github.com/yuroyoro/goast-viewer) - **star:368** 基于 Web 的 Golang AST 可视化工具。![star > 100][Bronze]   
* [GoCover.io](http://gocover.io/) - GoCover.io 提供了任意 golang 包的代码覆盖率服务。
* [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - 来修复(添加，删除) Go 中自动导入的工具。
* [GolangCI](https://golangci.com/) - GolangCI 是一个针对 GitHub pull 请求的自动代码审查服务。服务是开源的，对开源项目是免费的。
* [GoLint](https://github.com/golang/lint) - **star:3101** Go 源码的 linter。![star > 1000][Silver]   
* [Golint online](http://go-lint.appspot.com/) - Lints online Go source files on GitHub, Bitbucket and Google Project Hosting using the golint package.
* [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - 添加 zero 返回声明，以匹配 func 返回类型。
* [gosimple](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple 是 Go 源代码的linter，专门用于简化代码。
* [gostatus](https://github.com/shurcooL/gostatus) - **star:241** 用于显示包含 Go 包的存储库的状态的命令行工具，。![star > 100][Bronze]   
* [lint](https://github.com/surullabs/lint) - **star:63** 将 linters 作为测试的一部分。
* [php-parser](https://github.com/z7zmey/php-parser) - **star:616** 用 Go 编写的 PHP 解析器。![star > 100][Bronze]   
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - 用于大量静态分析检查，您可能已经从 c# 的 ReSharper 等工具中习惯了这些检查。
* [tarp](https://github.com/verygoodsoftwarenotvirus/tarp) - **star:14** 在源码中寻找没有直接单元测试的函数和方法。
* [unconvert](https://github.com/mdempsky/unconvert) - **star:257** 在源码中删除不必要的类型转换。![star > 100][Bronze]   
* [unused](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - 对未使用的常量、变量、函数和类型的代码进行检查。
* [validate](https://github.com/mccoyst/validate) - **star:62** 使用 tags 自动验证结构体字段。![最近一年没有更新][Yellow]

## 编辑器插件

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - JetBrains IDEs 的 Go 插件。
* [go-language-server](https://github.com/theia-ide/go-language-server) - **star:28** A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode](https://github.com/dominikh/go-mode.el) - **star:940** 在 GNU/Emacs 支持 GO。![star > 100][Bronze]   
* [go-plus](https://github.com/joefitzgerald/go-plus) - **star:1479** 在 Atom 中添加自动完成，格式化，语法检查，高亮和审查。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gocode](https://github.com/nsf/gocode) - **star:4713** Autocompletion daemon for the Go programming language.![star > 1000][Silver]   
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - 在 VS Code 中支持 Go 的基准分析。
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - **star:3220** 包含了可为文本编辑器 SublimeText 3 提供代码自动填充和其他类似IDE的功能的 Golang IDE 插件集合。![star > 1000][Silver]   
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - **star:17** 基于函数或方法的签名生成Go测试的Vim插件。
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - **star:12** 在 Theia IDE中支持 Go。
* [velour](https://github.com/velour/velour) - **star:16** acme编辑器的IRC客户端。
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - **star:80** 在保存时突出显示语法错误的 Vim 插件。![最近一年没有更新][Yellow]
* [vim-go](https://github.com/fatih/vim-go) - **star:10675** Go 开发会用到的 Vim 插件。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [vscode-go](https://github.com/Microsoft/vscode-go) - **star:5021** Visual Studio代码的扩展(VS代码)，它提供了对Go语言的支持。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Watch](https://github.com/eaburns/Watch) - **star:166** Runs a command in an acme win on file changes.![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## Go 生成工具

* [generic](https://github.com/usk81/generic) - **star:28** 灵活的 Go 数据类型。
* [genny](https://github.com/cheekybits/genny) - **star:922** 优雅的 Go 泛型。![star > 100][Bronze]   
* [gocontracts](https://github.com/Parquery/gocontracts) - **star:52** 通过同步代码和文档来实现 design-by-contract 设计。
* [gonerics](http://github.com/bouk/gonerics) - Go中的易用的泛型。
* [gotests](https://github.com/cweill/gotests) - **star:2124** 从源代码生成测试用例。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gounit](https://github.com/hexdigest/gounit) - **star:28** 使用您自己的模板生成Go测试用例。
* [hasgo](https://github.com/DylanMeeus/hasgo) - **star:11** 可生成用于切片的 Haskell。
* [re2dfa](https://github.com/opennota/re2dfa) - **star:169** 将正则表达式转换为有限状态机，并输出 Go 源代码。![star > 100][Bronze]   
* [TOML-to-Go](https://xuri.me/toml-to-go) - 在浏览器中将 TOML 转换为 Go 类型。

## Go 工具

* [colorgo](https://github.com/songgao/colorgo) - **star:95** 将 go 命令包装成彩色的 go build 输出。![最近一年没有更新][Yellow]
* [depth](https://github.com/KyleBanks/depth) - **star:370** 通过分析导入，将包依赖关系树可视化输出。![star > 100][Bronze]   
* [gb](https://getgb.io/) - 一个基于项目的易用的构建工具。
* [generator-go-lang](https://github.com/axelspringer/generator-go-lang) - **star:13** 一个[Yeoman](http://yeoman.io)生成器，用于启动新的 Go 项目。
* [gilbert](https://go-gilbert.github.io) - 一个为 Go 项目而生的构建系统和任务运行器。
* [go-callvis](https://github.com/TrueFurby/go-callvis) - **star:1923** 使用 dot format 可视化 Go 程序的调用图。![star > 1000][Silver]   
* [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) - **star:37** Bash completion for go and wgo。![最近一年没有更新][Yellow]
* [go-swagger](https://github.com/go-swagger/go-swagger) - **star:3825** 基于 Go 的Swagger 2.0实现。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [godbg](https://github.com/tylerwince/godbg) - **star:157** 实现了 Rusts 的 dbg! 宏，可以方便的在开发过程中快速、容易地调试。![star > 100][Bronze]   
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - **star:3688** 借助的 OctoLinker 浏览器扩展，可以高效的地浏览  GitHub go文件。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [richgo](https://github.com/kyoh86/richgo) - **star:379** 用文本装饰丰富 go test 的输出。![star > 100][Bronze]   
* [rts](https://github.com/galeone/rts) - **star:184** 从服务器响应生成Go结构。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 软件包

*用Go编写的软件。*

### DevOps 工具

* [aptly](https://github.com/smira/aptly) - **star:1724** Debian存储库管理工具。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [aurora](https://github.com/xuri/aurora) - **star:390** 基于web的跨平台 Beanstalkd 队列服务器控制台。![star > 100][Bronze]   
* [awsenv](https://github.com/soniah/awsenv) - **star:20** 可以为 profile 加载Amazon (AWS)环境变量的轻量二进制文件。
* [Blast](https://github.com/dave/blast) - **star:168** 一个用于API负载测试和批处理作业的简单工具。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [bombardier](https://github.com/codesenberg/bombardier) - **star:1678** 快速跨平台 HTTP 基准测试工具。![star > 1000][Silver]   
* [bosun](https://github.com/bosun-monitor/bosun) - **star:2840** 按照时间轴发出告警的框架。![star > 1000][Silver]   
* [DepCharge](https://github.com/centerorbit/depcharge) - **star:9** Helps orchestrating the execution of commands across the many dependencies in larger projects.
* [dogo](https://github.com/liudng/dogo) - **star:216** 监视源文件中的更改并自动编译和运行(restart)。![star > 100][Bronze]   
* [drone-jenkins](https://github.com/appleboy/drone-jenkins) - **star:22** 使用二进制文件、docker或 Drone CI 来触发下游Jenkins作业。
* [drone-scp](https://github.com/appleboy/drone-scp) - **star:54** 通过 SSH 进行文件拷贝。其中 SSH 通过二进制文件、docker 或 Drone CI触发。
* [Dropship](https://github.com/chrismckenzie/dropship) - **star:46** 通过 cdn 部署代码的工具。
* [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - **star:96** Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.![最近一个周有更新][Green]
* [fac](https://github.com/mkchoi212/fac) - **star:1593** 修复 git 合并冲突。![star > 1000][Silver]   
* [gaia](https://github.com/gaia-pipeline/gaia) - **star:3694** 可用于任何编程语言来构建强大的管道。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Gitea](https://github.com/go-gitea/gitea) - **star:14635** 从 Gogs fork，完全由社区驱动。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - 将所有GitHub repositories、issues、milestones 和 labels 都迁移到 Gitea。
* [go-furnace](https://github.com/go-furnace/go-furnace) - **star:63** 用Go编写的托管解决方案，可轻松地在AWS、GCP或DigitalOcean上部署应用程序。![最近一个周有更新][Green]
* [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - **star:659** 允许你的 Go应用程序 进行自我更新。![star > 100][Bronze]   
* [gobrew](https://github.com/cryptojuice/gobrew) - **star:175** gobrew 允许您轻松地在 go 的多个版本之间切换。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [godbg](https://github.com/sirnewton01/godbg) - **star:219** 基于 web 的 gdb 前端应用程序。![star > 100][Bronze]   
* [Gogs](https://gogs.io/) - 自托管的Git服务。
* [gonative](https://github.com/inconshreveable/gonative) - **star:312** 用原生 Go 创建一个跨平台的 Go 工具链。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [govvv](https://github.com/ahmetalpbalkan/govvv) - **star:372** 可轻松地添加版本信息到 Go 二进制文件。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [gox](https://github.com/mitchellh/gox) - **star:3323** 非常简单，没有多余的跨平台编译工具。![star > 1000][Silver]   
* [goxc](https://github.com/laher/goxc) - **star:1627** 专注于跨平台编译和打包的 Go 构建工具。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [grapes](https://github.com/yaronsumel/grapes) - **star:133** 旨在轻松地通过ssh分发命令的轻量级工具。![star > 100][Bronze]   
* [GVM](https://github.com/moovweb/gvm) - **star:4415** GVM 提供了一个接口来管理 Go 版本。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Hey](https://github.com/rakyll/hey) - **star:6064** 压力测试工具，可用来代替 ApacheBench (ab)。![star > 5000][Gold]   
* [kala](https://github.com/ajvb/kala) - **star:1346** 简单、现代和高性能的作业调度程序。![star > 1000][Silver]   
* [kcli](https://github.com/cswank/kcli) - **star:68** 用于检查kafka主题/分区/消息的命令行工具。
* [kubernetes](https://github.com/kubernetes/kubernetes) - **star:54822** 来自谷歌的容器集群管理器。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [lstags](https://github.com/ivanilves/lstags) - **star:220** 提供了工具和API，可用来同步不同注册中心的Docker图像。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [lwc](https://github.com/timdp/lwc) - **star:8** UNIX wc命令的实时更新版本。![最近一年没有更新][Yellow]
* [manssh](https://github.com/xwjdsh/manssh) - **star:202** manssh是一个命令行工具，可以方便地管理ssh别名配置。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Moby](https://github.com/moby/moby) - **star:53985** Collaborative project for the container ecosystem to assemble container-based systems.![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Mora](https://github.com/emicklei/mora) - **star:263** 用于访问 MongoDB 文档和元数据的 REST 服务器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [ostent](https://github.com/ostrost/ostent) - **star:165** 收集和显示系统指标，并可选 Graphite and/or fluxdb作为依赖。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Packer](https://github.com/mitchellh/packer) - **star:9072** 用于从一个源配置为多个平台创建相同的机器图像。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Pewpew](https://github.com/bengadbois/pewpew) - **star:198** 灵活的 HTTP 命令行压测工具。![star > 100][Bronze]   
* [Pomerium](https://github.com/pomerium/pomerium) - **star:464** Pomerium是一个可识别身份的访问代理。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [Rodent](https://github.com/alouche/rodent) - **star:30** 管理Go版本、项目和跟踪依赖项。![最近一年没有更新][Yellow]
* [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - **star:987** 小型实用程序/库，针对大型对象在Amazon S3中的高速传输进行了优化。![star > 100][Bronze]   
* [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - **star:533** 从命令行管理 BareMetal 服务器(与使用Docker一样容易)。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [script](https://github.com/bitfield/script) - **star:658** 让DevOps编写类shell和系统管理任务变得更加容易。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [sg](https://github.com/ChristopherRabotin/sg) - **star:5** 可测试一组HTTP极限(如ab)，可以在每个调用之间使用响应代码和数据，根据之前的响应来确定特定的服务器压力。![最近一年没有更新][Yellow]
* [skm](https://github.com/TimothyYe/skm) - **star:544** SKM是一个简单而强大的SSH密钥管理器，它可以帮助您轻松地管理多个SSH密钥!![star > 100][Bronze]   
* [StatusOK](https://github.com/sanathp/statusok) - **star:1143** 监视您的网站和REST api。当服务器宕机或响应时间超过预期时，通过Slack、电子邮件获得通知。![star > 1000][Silver]   
* [traefik](https://github.com/containous/traefik) - **star:23178** 反向代理和负载均衡器，支持多个后端。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [Vegeta](https://github.com/tsenart/vegeta) - **star:11887** HTTP负载测试工具和库。超过9000 !![star > 5000][Gold]   ![最近一个周有更新][Green]
* [webhook](https://github.com/adnanh/webhook) - **star:3987** 允许用户创建在服务器上执行命令的 HTTP hooks。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [Wide](https://wide.b3log.org/login) - 为使用 Golang 的团队提供基于 web 的 IDE。
* [winrm-cli](https://github.com/masterzen/winrm-cli) - **star:64** 在Windows机器上远程执行命令的Cli工具。

### 其他软件

* [borg](https://github.com/crufter/borg) - **star:1416** 基于终端的bash代码段搜索引擎。![star > 1000][Silver]   ![最近一年没有更新][Yellow]
* [boxed](https://github.com/tejo/boxed) - **star:72** 基于Dropbox的博客引擎。
* [Cherry](https://github.com/rafael-santiago/cherry) - **star:192** 微型网络聊天服务器。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [Circuit](https://github.com/gocircuit/circuit) - **star:1777** Circuit 是一个可编程平台即服务(PaaS)和/或基础设施即服务(IaaS)，用于管理、发现、同步和编排包含云应用程序的服务和主机。![star > 1000][Silver]   
* [Comcast](https://github.com/tylertreat/Comcast) - **star:6128** 模拟坏的网络连接。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [confd](https://github.com/kelseyhightower/confd) - **star:6318** 使用 etcd 或 consul 的模板和数据管理本地应用程序配置文件。![star > 5000][Gold]   
* [DDNS](https://github.com/skibish/ddns) - **star:97** 个人 DDNS 客户端。
* [Docker](http://www.docker.com/) - 面向开发人员和系统管理员的分布式应用程序的开放平台。
* [Documize](https://github.com/documize/community) - **star:794** 集成了SaaS工具数据的现代wiki软件。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [drive](https://github.com/odeke-em/drive) - **star:4919** 基于命令行的谷歌驱动器客户端。![star > 1000][Silver]   
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - **star:2660** 跨平台网络和云备份工具。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [gfile](https://github.com/Antonito/gfile) - **star:486** 通过WebRTC在两台计算机之间安全地传输文件，不需要任何第三方依赖。![star > 100][Bronze]   
* [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - **star:878** App that displays updates for the Go packages in your GOPATH.![star > 100][Bronze]   
* [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - **star:372** 视频流 torrent 客户端。![star > 100][Bronze]   
* [GoBoy](https://github.com/Humpheh/goboy) - **star:2096** 用 Go 编写的任天堂Game Boy彩色模拟器。![star > 1000][Silver]   
* [gocc](https://github.com/goccmack/gocc) - **star:338** Gocc是一个用Go编写的编译器工具包。![star > 100][Bronze]   
* [GoDNS](https://github.com/timothyye/godns) - **star:417** 一个动态DNS客户端工具，支持DNSPod & HE.net。![star > 100][Bronze]   
* [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - **star:12** 包含了 Go 使用手册文档的 Chrome 扩展。![最近一年没有更新][Yellow]
* [GoLand](https://jetbrains.com/go) - 功能齐全的跨平台 Go IDE。
* [Gor](https://github.com/buger/gor) - **star:11202** Http 流量复制工具，用于实时回放从生产环境到阶段/开发环境的流量。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [hugo](http://gohugo.io/) - 快速、现代的静态网站引擎。
* [ide](https://github.com/thestrukture/ide) - **star:250** 基于浏览器的IDE![star > 100][Bronze]   
* [ipe](https://github.com/dimiro1/ipe) - **star:274** Open source Pusher server implementation compatible with Pusher client libraries written in GO.![star > 100][Bronze]   
* [joincap](https://github.com/assafmo/joincap) - **star:121** 用于合并多个pcap文件的命令行实用程序。![star > 100][Bronze]   
* [Juju](https://jujucharms.com/) - Cloud-agnostic的服务部署和编制 —— 支持EC2、Azure、Openstack、MAAS等。
* [Leaps](https://github.com/jeffail/leaps) - **star:641** 使用操作转换的成对编程服务。![star > 100][Bronze]   
* [lgo](https://github.com/yunabe/lgo) - **star:1765** 与 Jupyter 可进行交互 Go 程序。它支持代码完成、代码检查以及与Go 100% 兼容性。![star > 1000][Silver]   
* [limetext](http://limetext.org/) - 一个强大而优雅的文本编辑器。
* [LiteIDE](https://github.com/visualfc/liteide) - **star:5419** 简单的、开源的、跨平台的Go IDE。![star > 5000][Gold]   
* [mockingjay](https://github.com/quii/mockingjay-server) - **star:410** 一份配置文件中便可伪造HTTP服务器与用户之间的行为。您还可以使服务器随机宕机，以帮助进行更实际的性能测试。![star > 100][Bronze]   
* [myLG](https://github.com/mehrdadrad/mylg) - **star:2184** 命令行网络诊断工具。![star > 1000][Silver]   
* [naclpipe](https://github.com/unix4fun/naclpipe) - **star:20** 基于加密管的简单的NaCL EC25519工具。
* [nes](https://github.com/fogleman/nes) - **star:4104** 任天堂娱乐系统(NES)模拟器。![star > 1000][Silver]   
* [orange-cat](https://github.com/noraesae/orange-cat) - **star:178** 用Go编写的Markdown预览器。![star > 100][Bronze]   
* [Orbit](https://github.com/gulien/orbit) - **star:128** 一个根据模板来运行命令和生成文件的简单小工具。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [peg](https://github.com/pointlander/peg) - **star:587** 解析表达式语法，是Packrat解析器生成器的实现。![star > 100][Bronze]   
* [Pipe](https://github.com/b3log/pipe) - **star:2602** 一个小巧漂亮的博客平台。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [restic](https://github.com/restic/restic) - **star:7219** 消除重复项备份程序。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [rkt](https://github.com/coreos/rkt) - **star:8701** 一个应用容器，与其他容器格式(如Docker)兼容，并支持其他执行引擎(如KVM)。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [scc](https://github.com/boyter/scc) - **star:761** 一个非常快速准确的代码计数器，采用了复杂的计算和 COCOMO 预估。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - **star:8039** 快速、简单、可伸缩的分布式文件系统，采用了O(1)磁盘查找。![star > 5000][Gold]   ![最近一个周有更新][Green]
* [shell2http](https://github.com/msoap/shell2http) - **star:396** 通过http服务器执行shell命令(用于原型或远程控制)。![star > 100][Bronze]   
* [snap](https://github.com/intelsdi-x/snap) - **star:1802** 强大的遥测框架。![star > 1000][Silver]   
* [Snitch](https://github.com/lucasgomide/snitch) - **star:15** 当有人通过 Tsuru 部署任何应用程序时，会通知您的团队以及其他工具。
* [Stack Up](https://github.com/pressly/sup) - **star:1979** Stack Up 是一个超级简单的部署工具 — 只面向Unix。![star > 1000][Silver]   
* [syncthing](https://syncthing.net/) - 开放，分散的文件同步工具和协议。
* [term-quiz](https://github.com/crazcalm/term-quiz) - **star:17** 测试你的终端。
* [toxiproxy](https://github.com/shopify/toxiproxy) - **star:3776** 为自动化测试模拟网络和系统条件的代理。![star > 1000][Silver]   
* [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
* [vFlow](https://github.com/VerizonDigital/vflow) - **star:587** 高性能、可伸缩和可靠的 IPFIX、sFlow和 Netflow 收集器。![star > 100][Bronze]   
* [wellington](https://github.com/wellington/wellington) - **star:288** Sass 项目管理工具，使用sprite函数(如Compass)扩展语言。![star > 100][Bronze]   

# 资源

*在哪里可以找到新的Go库。*

## 基准

* [autobench](https://github.com/davecheney/autobench) - **star:89** 用来来比较不同Go版本之间的性能的框架。![最近一年没有更新][Yellow]
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - **star:19** 强大的HTTP基准测试工具，包含了Аb，Wrk，Siege工具。收集统计和各种参数指标，并比较相关结果。![最近一年没有更新][Yellow]
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - **star:119** Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - **star:1253** HTTP请求路由器基准测试和比较。![star > 1000][Silver]   
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - **star:975** web框架基准测试。![star > 100][Bronze]   
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - **star:841** Go序列化方法的基准测试。![star > 100][Bronze]   
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - **star:52** Go语言常用基本操作的基准测试。![最近一年没有更新][Yellow]
* [golang-micro-benchmarks](https://github.com/amscanne/golang-micro-benchmarks) - **star:17** Go 基础操作的基准测试集合。其目的是将一些语言特性与其他特性进行比较。
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - **star:48** 为流行的 Go 数据库/SQL实用程序收集基准测试。![最近一年没有更新][Yellow]
* [gospeed](https://github.com/feyeleanor/GoSpeed) - **star:93** 计算语言结构的速度的微观基准测试。
* [kvbench](https://github.com/jimrobinson/kvbench) - **star:14** K / V 类型数据库基准测试。![最近一年没有更新][Yellow]
* [skynet](https://github.com/atemerev/skynet) - **star:909** 天网 1M 线程微基准测试。![star > 100][Bronze]   
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - **star:172** 对比各种图像大小调整算法性能。![star > 100][Bronze]   ![最近一年没有更新][Yellow]

## 会议

* [Capital Go](http://www.capitalgolang.com) - 华盛顿特区。,美国。
* [dotGo](http://www.dotgo.eu) - 巴黎,法国。
* [GoCon](http://gocon.connpass.com/) - 东京,日本。
* [GoDays](https://www.godays.io/) - 德国柏林。
* [GoLab](http://golab.io/) - 佛罗伦萨,意大利。
* [GolangUK](http://golanguk.com/) - 伦敦,英国。
* [GopherChina](http://gopherchina.org) - 上海,中国。
* [GopherCon](http://www.gophercon.com/) - 美国丹佛。
* [GopherCon Australia](https://gophercon.com.au/) - 澳大利亚悉尼。
* [GopherCon Brazil](https://gopherconbr.org) - 弗洛,BR。
* [GopherCon Europe](https://gophercon.is/) - 雷克雅未克,冰岛。
* [GopherCon India](https://www.gophercon.in/) - 印度浦那。
* [GopherCon Israel](https://www.gophercon.org.il/) - 特拉维夫,以色列。
* [GopherCon Russia](https://www.gophercon-russia.ru) - 莫斯科,俄罗斯。
* [GopherCon Singapore](https://gophercon.sg) - 新加坡枫树商贸城。
* [GopherCon Vietnam](https://gophercon.vn/) - 越南胡志明市。
* [GothamGo](http://gothamgo.com/) - 美国纽约市。
* [GoWayFest](https://goway.io/) - 白俄罗斯明斯克。

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - 一本关注 Go 语法/语义和各种细节的书。
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - **star:10** in Persian.
* [GoBooks](https://github.com/dariubs/GoBooks) - **star:6681** 一份精选的 Go 书籍清单。![star > 5000][Gold]   
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

## Gophers

* [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - **star:1462** 由 Maria Letta 提供的与 Gopher 有关的图片包，其中包含了插图,表情文字。![star > 1000][Silver]   
* [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - **star:32** 与 Go gopher 相关的媒介数据[。ai . svg)。![最近一年没有更新][Yellow]
* [gopher-logos](https://github.com/GolangUA/gopher-logos) - **star:62** 可爱的 gopher 标识。![最近一年没有更新][Yellow]
* [gopher-stickers](https://github.com/tenntenn/gopher-stickers)
* [gopher-vector](https://github.com/golang-samples/gopher-vector)
* [gophericons](https://github.com/shalakhin/gophericons)
* [gopherize.me](https://github.com/matryer/gopherize.me) - **star:313** Gopherize自己。![star > 100][Bronze]   
* [gophers](https://github.com/ashleymcnamara/gophers) - **star:1812** 阿什莉·麦克纳马拉的歌斐艺术品。![star > 1000][Silver]   
* [gophers](https://github.com/egonelbre/gophers) - **star:1548** Free gophers.![star > 1000][Silver]   
* [gophers](https://github.com/rogeralsing/gophers) - **star:49** 随机gopher图形。![最近一年没有更新][Yellow]
* [gophers](https://github.com/sillecelik/go-gopher) - **star:41** Gopher amigurumi玩具图案。

## 聚会

* [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
* [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
* [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
* [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
* [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
* [Go Toronto](https://www.meetup.com/go-toronto/)
* [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
* [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
* [GoJakarta](https://www.meetup.com/GoJakarta/)
* [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
* [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
* [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
* [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
* [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
* [Golang Boston](https://www.meetup.com/bostongo/)
* [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
* [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
* [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
* [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
* [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
* [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
* [Golang Israel](https://www.meetup.com/Go-Israel/)
* [Golang Joinville - Brazil](https://www.meetup.com/Joinville-Go-Meetup/)
* [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
* [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
* [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
* [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
* [Golang Melbourne](https://www.meetup.com/golang-mel/)
* [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
* [Golang New York](https://www.meetup.com/nycgolang/)
* [Golang Paris](https://www.meetup.com/Golang-Paris/)
* [Golang Pune](https://www.meetup.com/Golang-Pune/)
* [Golang Singapore](https://www.meetup.com/golangsg/)
* [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
* [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
* [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
* [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
* [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
* [Golang Казань](https://www.meetup.com/GolangKazan/)
* [Golang Москва](https://www.meetup.com/Golang-Moscow/)
* [Golang Питер](https://www.meetup.com/Golang-Peter/)
* [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
* [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
* [Seattle Go Programmers](https://www.meetup.com/golang/)
* [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
* [Utah Go User Group](https://www.meetup.com/utahgophers/)
* [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*在这里添加您所在城市/国家的群组(发送**PR**)*

## Twitter

* [@golang](https://twitter.com/golang)
* [@golang_news](https://twitter.com/golang_news)
* [@golangch](https://twitter.com/golangch)
* [@golangflow](https://twitter.com/golangflow)
* [@golangweekly](https://twitter.com/golangweekly)

## 网站

* [Awesome Go @LibHunt](https://go.libhunt.com) - 属于你的 Go 工具箱。
* [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - **star:14379** Curated list of awesome remote jobs. A lot of them are looking for Go hackers.![star > 5000][Gold]   ![最近一个周有更新][Green]
* [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - **star:24483** 其他 awesome 系列的列表。![star > 5000][Gold]   
* [CodinGame](https://www.codingame.com/) - 以小游戏互动完成任务的形式来学习 Go。
* [Go Blog](http://blog.golang.org) - 官方 Go 博客。
* [Go Challenge](http://golang-challenge.org/) - 通过解决问题并从 Go 专家那里得到反馈来学习 Go。
* [Go Community on Hashnode](https://hashnode.com/n/go) - Hashnode上的Go社区。
* [Go Forum](https://forum.golangbridge.org) - 讨论 Go 的论坛。
* [Go In 5 Minutes](https://www.goin5minutes.com/) - 5 minute screencasts focused on getting one thing done.
* [Go Projects](https://github.com/golang/go/wiki/Projects) - wiki上的 Go 社区项目列表。
* [Go Report Card](https://goreportcard.com) - 为你的 Go 包生成一份报告单。
* [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - **star:35** 专门收集需要帮助的Go项目，这是你开启开源之路的好去处。![最近一年没有更新][Yellow]
* [godoc.org](https://godoc.org/) - 开源 Go 包的文档。
* [Golang Flow](https://golangflow.io) - 发布更新、新闻、包等等。
* [Golang News](https://golangnews.com) - 关于 Go 编程的链接和新闻。
* [golang-graphics](https://github.com/mholt/golang-graphics) - **star:141** 收藏的 Go 图像，图形和艺术作品。![star > 100][Bronze]   ![最近一年没有更新][Yellow]
* [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go 邮件列表。
* [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - Google+社区 golang爱好者聚集地。
* [Gopher Community Chat](https://invite.slack.golangbridge.org) - 加入我们为Gophers设立的全新Slack社区([了解它是如何产生的](https://blog.gopheracademy.com/gophers-slack-community/))。
* [Gophercises](https://gophercises.com/) - 为 Go 初学者提供免费的代码训练。
* [gowalker.org](https://gowalker.org) -  Go API 文档。
* [justforfunc](https://www.youtube.com/c/justforfunc) - 致力于传授 Go 编程语言技巧和技巧的Youtube 频道，由Francesc Campoy [@francesc](https://twitter.com/francesc)主办。
* [r/Golang](https://www.reddit.com/r/golang) - 与 Go 有关的新闻。
* [studygolang](https://studygolang.com) - Go语言中文网
* [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - 寻找最新的 Go库 的好地方。
* [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

### 教程

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Go 初学者经常遇到的陷阱、误区、错误
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - 教你如何用 Go 搭建一个电商平台 (包括demo)。
* [A Tour of Go](http://tour.golang.org/) - 互动的 Go 之旅。
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - **star:30961** Golang电子书，主要讲述如何用 Golang 建立一个web应用程序。![star > 5000][Gold]   
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - 如何缓存数据库的慢查询。
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - 如何取消MySQL查询。
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - **star:436** 一本讲述如何用 Go 进行以太开发的小册。![star > 100][Bronze]   ![最近一个周有更新][Green]
* [Games With Go](http://gameswithgo.org/) - 关于编程和游戏开发系列教学视频。
* [Go By Example](https://gobyexample.com/) - 手把手教你 如何在 Go 应用程序中使用注释。
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - **star:3973**  Go's reference card。![star > 1000][Silver]   
* [Go database/sql tutorial](http://go-database-sql.org/) - 数据库概论/ sql。
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - 在你的移动设备上编辑你编辑和运行你的 Go 代码。
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - **star:666** 引入示例讲述 Golang 与Node.js在学习上的差异。![star > 100][Bronze]   
* [Golangbot](https://golangbot.com/learn-golang-series/) - Go 编程教程。
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Go社区投票选举出来的最好的在线 Go 教程。
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - 快速使用Godog —— 一个行为驱动开发的构建和测试应用程序框架。
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - **star:3891** 学习使用测试驱动开发。![star > 1000][Silver]   ![最近一个周有更新][Green]
* [package main](https://www.youtube.com/packagemain) - 关于 Go 编程的YouTube频道。
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - **star:1127** 由一个经验丰富的Go程序员群体编写的一系列Go学习范例。![star > 1000][Silver]   
* [Your basic Go](http://yourbasic.org/golang) - 如何收集大量的教程。

