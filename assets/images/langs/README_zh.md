## 选择语言

| Русский | English | Español | 中文 | Français | Deutsch |
|---|---|---|---|---|---|
| [Русский](../README.md) | [English](README_en.md) | [Español](README_es.md) | **已选择** | [Français](README_fr.md) | [Deutsch](README_de.md) |

---

我主要处理后端逻辑、API 集成、遗留项目和企业内部系统。仓库中包含项目、PHP 包以及用于实验、练习和日常任务的小工具。

---

## 技术栈

<table>
  <thead>
    <tr>
      <th align="left">类别</th>
      <th align="left">技术</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="middle"><img src="../assets/icons/languages.svg" width="28" height="34" alt="" align="middle"> <strong>编程语言</strong></td>
      <td valign="middle">PHP · SQL · JavaScript</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/php.svg" width="28" height="34" alt="" align="middle"> <strong>PHP</strong></td>
      <td valign="middle">Native PHP · Symfony · Laravel · Yii</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/databases.svg" width="28" height="34" alt="" align="middle"> <strong>数据库</strong></td>
      <td valign="middle">PostgreSQL · MySQL · MariaDB</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/search.svg" width="28" height="34" alt="" align="middle"> <strong>缓存与搜索</strong></td>
      <td valign="middle">Redis · Elasticsearch · Sphinx</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/devops.svg" width="28" height="34" alt="" align="middle"> <strong>平台 / DevOps</strong></td>
      <td valign="middle">Linux · Docker · Kubernetes</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/git.svg" width="28" height="34" alt="" align="middle"> <strong>Git / Forge / CI</strong></td>
      <td valign="middle">Git · GitHub · GitLab · Gitea · GitHub Actions</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/development.svg" width="28" height="34" alt="" align="middle"> <strong>开发</strong></td>
      <td valign="middle">PhpStorm</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/ai.svg" width="28" height="34" alt="" align="middle"> <strong>AI</strong></td>
      <td valign="middle">ChatGPT Projects · Codex · OpenCode · LM Studio</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/local-llm.svg" width="28" height="34" alt="" align="middle"> <strong>本地 LLM</strong></td>
      <td valign="middle">Qwen3.8 27B · Qwen2.5-Coder 14B · Qwen3.5 9B</td>
    </tr>
  </tbody>
</table>

---

## PHP

<p align="center">
  <img src="../assets/images/php-mascot.png" alt="PHP 吉祥物 — 蓝色小象在笔记本电脑前">
</p>

### 项目

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/mvc-v1">
        <img src="../assets/images/projects/mvc-v1.png" width="100%" alt="mvc-v1 — 使用自定义 MVC 核心的 PHP 教学博客">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/mvc-v1"><strong>mvc-v1</strong></a><br>
      <sub>Native PHP</sub><br><br>
      使用原生 PHP 实现 MVC 架构模式的示例，包含 CRUD、通过 PDO 使用 PostgreSQL，以及 Docker 环境。
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/symfony-shop">
        <img src="../assets/images/projects/symfony-shop.png" width="100%" alt="symfony-shop — 基于 Symfony 的教学电商项目">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/symfony-shop"><strong>symfony-shop</strong></a><br>
      <sub>Symfony</sub><br><br>
      基于 Symfony 的在线商店，使用 PostgreSQL、Doctrine ORM、API Platform、OAuth，并配有独立的 Vue 前端。
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/yii2-book-catalog">
        <img src="../assets/images/projects/yii2-book-catalog.png" width="100%" alt="yii2-book-catalog — 基于 Yii2 的图书 Web 目录">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/yii2-book-catalog"><strong>yii2-book-catalog</strong></a><br>
      <sub>Yii2</sub><br><br>
      基于 Yii2 和 MySQL 的图书与作者目录，包含 Docker、测试以及外部短信集成。
    </td>
    <!--
    <td align="center" valign="top" width="50%">
      <img src="../assets/images/projects/laravel-temporal.png" width="100%" alt="Laravel、RoadRunner 和 Temporal 配送聚合器 — 开发中"><br><br>
      <strong>开发中...</strong><br>
      <sub>Laravel</sub><br><br>
      使用 Laravel、RoadRunner 和 Temporal 实现的项目，以配送聚合器作为示例。
    </td>
    -->
    <td valign="top" width="50%"></td>
  </tr>
</table>

### PHP 包

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/oauth2-yandex">
        <img src="../assets/images/packages/oauth2-yandex.png" width="100%" alt="oauth2-yandex — 用于 PHP 的 Yandex ID OAuth 2.0 Provider">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/oauth2-yandex">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/oauth2-yandex">Packagist</a></sub><br><br>
      通过 <code>league/oauth2-client</code> 集成 Yandex ID 的 OAuth 2.0 Provider。
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/weather">
        <img src="../assets/images/packages/weather.png" width="100%" alt="weather — PHP 统一当前天气客户端">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/weather">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/weather">Packagist</a></sub><br><br>
      通过 Open-Meteo 和 WeatherAPI 按坐标获取当前天气的 PHP 客户端。
    </td>
  </tr>
  <!--
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/archive-guard">
        <img src="../assets/images/packages/archive-guard.png" width="100%" alt="archive-guard — 用于 PHP 的安全 ZIP 归档检查">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/archive-guard">GitHub</a> · 开发中</sub><br><br>
      在 PHP 中安全检查并受控解压不受信任的 ZIP 归档。
    </td>
    <td valign="top" width="50%"></td>
  </tr>
  -->
</table>

### 工具

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-sql-lab">
        <img src="../assets/images/tools/docker-sql-lab.png" width="100%" alt="docker-sql-lab — 本地 SQL 学习环境">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-sql-lab"><strong>docker-sql-lab</strong></a><br>
      <sub>Docker · SQL</sub><br><br>
      用于学习 SQL 的本地环境，包含 PostgreSQL、MySQL、ClickHouse 以及开箱即用的演示表。
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-elasticsearch">
        <img src="../assets/images/tools/docker-elasticsearch.png" width="100%" alt="docker-elasticsearch — 本地 Elasticsearch 学习环境">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-elasticsearch"><strong>docker-elasticsearch</strong></a><br>
      <sub>Docker · Elasticsearch</sub><br><br>
      用于学习 Elasticsearch 的本地环境，包含 Kibana 和 Nginx，以及用于搜索实验的 ICU 和 phonetic 分析。
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/remove-prefix">
        <img src="../assets/images/tools/remove-prefix.png" width="100%" alt="remove-prefix — 批量删除文件和目录名称前缀">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/remove-prefix"><strong>remove-prefix</strong></a><br>
      <sub>Bash · PowerShell</sub><br><br>
      跨平台脚本，用于递归批量删除文件和目录名称中的前缀。
    </td>
    <td valign="top" width="50%"></td>
  </tr>
</table>

---

## 联系方式

<table>
  <tr>
    <td><strong>邮箱</strong></td>
    <td>
      <a href="mailto:y.aleksandr89@yandex.ru">y.aleksandr89@yandex.ru</a> ·
      <a href="mailto:y.aleksandr89@gmail.com">y.aleksandr89@gmail.com</a>
    </td>
  </tr>
  <tr>
    <td><strong>LinkedIn</strong></td>
    <td><a href="https://www.linkedin.com/in/yaleksandr89">in/yaleksandr89</a></td>
  </tr>
  <tr>
    <td><strong>VK</strong></td>
    <td><a href="https://vk.me/y.aleksandr89">vk.me/y.aleksandr89</a></td>
  </tr>
  <tr>
    <td><strong>Telegram</strong></td>
    <td><a href="https://t.me/yaleksandr89">@yaleksandr89</a></td>
  </tr>
</table>
