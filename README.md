```jsonc
{
    "university": {
        "department": "Computer Science"
    },
    "using": {
        "framework": [
            "Flutter",
            "discordgo",
            "Echo",
            "GORM",
            "Unity"
        ],
        "specification": [
            "OpenID Connect",
            "FIDO2",
            "OpenAPI",
            "FeliCa Lite-S"
        ],
        "language": [
            "Go",
            "Dart",
            "Java",
            "TypeScript",
            "JavaScript",
            "C++",
            "Lua",
            "Python",
            "SQL",
            "HTML",
            "bash",
            "ja_JP",
            "en_US"
        ],
        "environment": [
            "Arch Linux",
            "GNOME",
            "linux-zen"
        ],
        "application": [
            "Visual Studio Code",
            "Git",
            "Docker",
            "GitHub Desktop",
            "OpenSSH",
            "GnuPG",
            "virt-manager",
            "nautilus"
        ]
    },
    "hobby": [
        "AtCoder",
        "Minecraft",
        "[censored]"
    ],
    "contacts": [
        {
            "protocol": "ActivityPub",
            "implementation": "Misskey",
            "id": "@ozraru@key.tpc3.org"
        },
        {
            "protocol": "SMTP",
            "implementation": "Cloudflare Email Routing",
            "address": "<redacted to avoid spam>"
        }
    ]
}
```

![GitHub Readme Stats Wakapi](https://github-readme-stats.vercel.app/api/wakatime?username=ozraru&bg_color=1A202C&title_color=2F855A&icon_color=2F855A&text_color=ffffff&layout=compact)

<details>
<summary>available only in ja_JP</summary>
<details>
<summary>経歴(?)</summary>

※一部Privateリポジトリへのリンクを含みます

2005年7月 出生

2014年3月 Excelで表を作ったり  
2014年? プログラミンでブロックプログラミングを行う  

2017年2月 Scratchを始める  
2017年6月 Raspberry Piで電子工作を行う(プログラムはほぼ書籍の丸写しだったためプログラミングと言えるかは微妙)  
2017年8月 ComputerCraftでテキストプログラミングに入門  
2017年8月 VPSを借りてWordPressを公開,運用  
2017年12月 Unityでゲームを作ろうとする  

2018年3月? Raspberry Piをファイルサーバー運用  
2018年4月 AWSを使用開始  
2018年6月 Raspberry PiとFeliCaリーダーを用いた自宅用スマートロックの開発に着手  
2018年7月 GitHubを使ったUnityの共同開発に挑戦  

2020年1月 Minecraft Spigotプラグイン開発を開始  
2020年8月 自宅用スマートロックシステムが2年越しに完成し実運用開始  

- Python Flask  
- HTTPS API  
    - JWT使用  
- NFC認証(nfcpy)  
- 専用Androidアプリ(Java)あり  
- Googleカレンダー連携あり  

2020年8月 Flutter,Java Tomcatでチャットアプリの開発を試行(未完成のまま放棄)  
2020年11月 スマートプラグと連携して充電制御するAndroidアプリ([ChargeManager](https://github.com/ozraru/ChargeManager))を開発(Java)し使用  

2021年5月 Arch Linuxデビュー  
2021年8月 Pepperを遠隔操作するPepperアプリ([PepperServer](https://github.com/ozraru/PepperServer))を開発(Java)  
2021年11月 MinecraftとDiscord間の連携システム([DiscordChat](https://github.com/ozraru/DiscordChat-old))を開発(Java)  
2022年4月 高校パソコン部サーバー管理者就任、Proxmox,Ceph,Dockerで基盤を構成し、以下を導入し運用  
- [Keycloak](https://github.com/PCCSuite/PCCKeycloak): OSS認証基盤(既存)  
- [PCCSamba](https://github.com/PCCSuite/PCCSamba): SMBファイルサーバー+Keycloak連携用API(Go,自作)  
- [PCCISO](https://github.com/PCCSuite/PCCISO): 最新OSインストーラーの定期自動ダウンロード/内部配布サーバー(Go,自作)  
- [ProxyPassport](https://github.com/PCCSuite/ProxyPassport): 中間HTTPプロキシサーバー(Go,自作)  
- [PCCProxy-tiny](https://github.com/PCCSuite/PCCProxy-tiny): tinyproxyによるプロキシサーバー(既存)  
- [PCCCache](https://github.com/PCCSuite/PCCCache): nginx+自作アプリケーション(Go)によるパッケージキャッシュサーバー  
- [PCCTips](https://github.com/PCCSuite/PCCTips): RFC865準拠の内製Tips配信サーバー  
- [PCCWeb](https://github.com/PCCSuite/PCCWeb): WordPress, Mediawikiなどの既存Webアプリケーション  
- [PCCPluginSys](https://github.com/PCCSuite/PCCPluginSys): 学校環境特化型パッケージマネージャバックエンド(Go,自作)  
- [PCCClient](https://github.com/PCCSuite/PCCClient-v3): Keycloak認証,sambaマウント,PCCPluginフロントエンドなどの機能を備えたクライアントアプリケーション(Flutter,自作)  

2022年5月 Discord絵文字管理Bot([Vanilla](https://github.com/tpc3/Vanilla))制作  
2022年8月 DiscordのVCに接続し音声をsnapcastに流すBot([Konfes-Bot](https://github.com/tpc3/Konfes-bot))を開発  
2022年9月 [DiscordChat](https://github.com/ozraru/DiscordChat)をSpigot,Forge両対応に大幅書き直し(Java)  
2022年10月 身内以外に対しては初のプルリクを[discordgo](https://github.com/bwmarrin/discordgo)に送りマージされる  
2022年12月 イベント進行補助Bot([Konfes-assistant](https://github.com/tpc3/Konfes-assistant))を開発(Go)  
2022年12月 Discord Slash commandでDocker containerを起動できるBot([ContainerStarterBot](https://github.com/ozraru/ContainerStarterBot))を開発(Go)  

2023年2月 MisskeyにDiscord Slash Commandで広告を投稿できるサーバーレスアプリケーション([MisskeyIntegrate](https://github.com/tpc3/MisskeyIntegrate))を開発(TypeScript,Cloudflare Workers)  
2023年5月 イベントスケジューリングWebアプリの[バックエンド](https://github.com/tpc3/Konfes-sys-api)(Go,Echo)全体と[フロントエンド](https://github.com/tpc3/KonFes-Sys)(TypeScript,Next.js)の一部を担当  
2024年2月 FIDO2 NFC Security KeyとFeliCa Lite-Sで認証できるスマートロックのソフトウェア([smartlock](https://github.com/tpc3/smartlock))をライブラリ([go-fido](https://github.com/tpc3/go-fido),[go-ctap](https://github.com/tpc3/go-ctap),[go-felica](https://github.com/tpc3/go-felica))から開発(Go)  
2024年4月 [AtCoder](https://atcoder.jp/users/ozraru)2級(青)達成  
</details>

</details>

