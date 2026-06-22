# Hello World! <img src="https://github.com/sciencepal/sciencepal/blob/master/assets/Hi.gif" width="29px">

![](https://komarev.com/ghpvc/?username=pierocarrion&label=Profile%20Visits&color=blue&style=for-the-badge)

<img src="https://github.com/sciencepal/sciencepal/blob/master/assets/life_balance.gif" alt="side Image" align="right" width="200" height="auto" />
<a href="https://ko-fi.com/sold1erstark">
<img src="https://media3.giphy.com/media/ZEB6yFbLnhyQf7g3hn/giphy.gif" alt="side Gif" align="right" width="150" height="auto"/>
</a>

## 👋 About Me

- 🔭 Senior Software Engineer & Open Source Creator
- 📦 Creator of **SurrealDb.Net.Linq** and **build_slim**
- 🌱 Currently learning AI Agents, AI Nodes and LLM Architectures
- ☁️ Building scalable systems with .NET, Flutter, Go and Cloud technologies
- 💬 Ask me about .NET, Flutter, System Design, Databases and FPS Games
- 😄 Pronouns: He / Him
- ⚡ Fun fact: My Steam nickname is **Sold1erStark**

---

## 📫 How to reach me

[<img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Steam_icon_logo.svg" width="3.5%"/>](https://steamcommunity.com/id/soldierstark/)
&nbsp;
[<img src="https://img.icons8.com/color/48/000000/linkedin.png" width="3.5%"/>](https://www.linkedin.com/in/carrionpintopiero/)
&nbsp;
[<img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" width="3.5%"/>](https://www.instagram.com/pcar.15/)
&nbsp;
<a href="mailto:piero.january15@gmail.com">
<img src="https://img.icons8.com/fluent/48/000000/gmail.png" width="3.5%"/>
</a>
&nbsp;
<a href="https://www.nuget.org/profiles/pierocarrion">
<img src="https://www.nuget.org/Content/gallery/img/logo-og-600x600.png" width="3.5%"/>
</a>
&nbsp;
<a href="https://pub.dev/packages/build_slim">
<img src="https://cdn.worldvectorlogo.com/logos/flutter.svg" width="3.5%"/>
</a>

---

## 👨🏻‍💻 Languages and Tools

<p>
  <img src="https://skillicons.dev/icons?i=dotnet,cs,go,flutter,ts,js,nodejs,react,angular,firebase,mongodb,postgres,mysql,redis,surrealdb,docker,kubernetes,aws,azure,git,github,vscode,linux" />
</p>

---

# 🚀 Featured Projects

## 🌊 SurrealDb.Net.Linq

A fluent, parameter-safe query builder for SurrealDB that plugs directly into the official `SurrealDb.Net` SDK.

### Highlights

- EF Core inspired API
- CBOR-bound parameters
- Parameter-safe query generation
- No SQL injection risks
- SELECT / LIVE SELECT / CREATE / UPDATE / UPSERT / DELETE / KILL
- Supports .NET 8, 9 and 10

[![NuGet Version](https://img.shields.io/nuget/v/SurrealDb.Net.Linq?style=for-the-badge&logo=nuget&color=004880)](https://www.nuget.org/packages/SurrealDb.Net.Linq)
[![NuGet Downloads](https://img.shields.io/nuget/dt/SurrealDb.Net.Linq?style=for-the-badge&logo=nuget&color=blue)](https://www.nuget.org/packages/SurrealDb.Net.Linq)
[![License](https://img.shields.io/github/license/pierocarrion/SurrealDb.Net.Linq?style=for-the-badge&color=A31F34)](https://github.com/pierocarrion/SurrealDb.Net.Linq/blob/main/LICENSE)
[![.NET](https://img.shields.io/badge/.NET-8.0%20%7C%209.0%20%7C%2010.0-512BD4?style=for-the-badge&logo=dotnet)](https://www.nuget.org/packages/SurrealDb.Net.Linq)

```csharp
using SurrealDb.Net.Linq;

var cmd = SurrealQuery.From("user")
    .Where("email", SurrealOperator.Equals, "alice@example.com")
    .And("active", SurrealOperator.Equals, true)
    .OrderBy("created_at", SortDirection.Desc)
    .Limit(10)
    .Build();

var users = await client.ExecuteListAsync<UserRow>(cmd);
```

```bash
dotnet add package SurrealDb.Net.Linq
```

🔗 Repository: https://github.com/pierocarrion/SurrealDb.Net.Linq

---

## 🚀 build_slim

A lightweight Flutter build automation toolkit designed to simplify release pipelines and repetitive build tasks.

### Highlights

- Flutter build automation
- Faster release workflows
- Lightweight integration
- CI/CD friendly
- Developer productivity focused

[![Pub Version](https://img.shields.io/pub/v/build_slim?style=for-the-badge&logo=dart)](https://pub.dev/packages/build_slim)
[![Pub Likes](https://img.shields.io/pub/likes/build_slim?style=for-the-badge&logo=flutter)](https://pub.dev/packages/build_slim)
[![Pub Points](https://img.shields.io/pub/points/build_slim?style=for-the-badge)](https://pub.dev/packages/build_slim)

```bash
dart pub global activate build_slim
```

🔗 Package: https://pub.dev/packages/build_slim

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats-fork-orpin.vercel.app/api?username=pierocarrion&show_icons=true&theme=radical" />
</p>

<p align="center">
  <img src="https://github.com/sciencepal/sciencepal/blob/master/assets/saved.gif" width="195">
</p>

---

<p align="center">
  <img src="https://github-profile-trophy-fork-two.vercel.app/?username=pierocarrion&theme=juicyfresh&no-frame=true&row=1&margin-w=20&no-bg=true" />
</p>

---

# 🎮 Gaming

### Counter-Strike 2

- 🔫 FPS Enthusiast
- 🎯 Competitive Player
- 🚀 Steam: Sold1erStark
- 💥 Favorite Game: Counter-Strike 2

[![Steam](https://img.shields.io/badge/Steam-Sold1erStark-171A21?style=for-the-badge&logo=steam)](https://steamcommunity.com/id/soldierstark)

<!-- Reemplaza STEAM_ID por tu SteamID64 -->

![Steam Stats](https://github-profile-steam.vercel.app/api?steamid=STEAM_ID)

---

### 💡 Fun Fact

I enjoy building open-source software, experimenting with databases, scaling distributed systems, and spending far too many hours trying to improve my CS2 aim.
