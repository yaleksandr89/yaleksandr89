## Choisir la langue

| Русский | English | Español | 中文 | Français | Deutsch |
|---|---|---|---|---|---|
| [Русский](../README.md) | [English](README_en.md) | [Español](README_es.md) | [中文](README_zh.md) | **Sélectionné** | [Deutsch](README_de.md) |

---

Je travaille sur la logique backend, les intégrations d’API, les projets legacy et les systèmes internes d’entreprise. Les dépôts regroupent des projets, des packages PHP et de petits outils pour l’expérimentation, la pratique et les tâches quotidiennes.

---

## Stack

<table>
  <thead>
    <tr>
      <th align="left">Domaine</th>
      <th align="left">Technologies</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="middle"><img src="../assets/icons/languages.svg" width="28" height="34" alt="" align="middle"> <strong>Langages</strong></td>
      <td valign="middle">PHP · SQL · JavaScript</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/php.svg" width="28" height="34" alt="" align="middle"> <strong>PHP</strong></td>
      <td valign="middle">Native PHP · Symfony · Laravel · Yii</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/databases.svg" width="28" height="34" alt="" align="middle"> <strong>Bases de données</strong></td>
      <td valign="middle">PostgreSQL · MySQL · MariaDB</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/search.svg" width="28" height="34" alt="" align="middle"> <strong>Cache et recherche</strong></td>
      <td valign="middle">Redis · Elasticsearch · Sphinx</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/devops.svg" width="28" height="34" alt="" align="middle"> <strong>Plateforme / DevOps</strong></td>
      <td valign="middle">Linux · Docker · Kubernetes</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/git.svg" width="28" height="34" alt="" align="middle"> <strong>Git / Forge / CI</strong></td>
      <td valign="middle">Git · GitHub · GitLab · Gitea · GitHub Actions</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/development.svg" width="28" height="34" alt="" align="middle"> <strong>Développement</strong></td>
      <td valign="middle">PhpStorm</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/ai.svg" width="28" height="34" alt="" align="middle"> <strong>IA</strong></td>
      <td valign="middle">ChatGPT Projects · Codex · OpenCode · LM Studio</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/local-llm.svg" width="28" height="34" alt="" align="middle"> <strong>LLM local</strong></td>
      <td valign="middle">Qwen3.8 27B · Qwen2.5-Coder 14B · Qwen3.5 9B</td>
    </tr>
  </tbody>
</table>

---

## PHP

<p align="center">
  <img src="../assets/images/php-mascot.png" alt="Mascotte PHP — éléphant bleu devant un ordinateur portable">
</p>

### Projets

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/mvc-v1">
        <img src="../assets/images/projects/mvc-v1.png" width="100%" alt="mvc-v1 — blog PHP éducatif avec noyau MVC personnalisé">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/mvc-v1"><strong>mvc-v1</strong></a><br>
      <sub>Native PHP</sub><br><br>
      Exemple d’implémentation du modèle architectural MVC en PHP natif avec CRUD, PostgreSQL via PDO et un environnement Docker.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/symfony-shop">
        <img src="../assets/images/projects/symfony-shop.png" width="100%" alt="symfony-shop — projet e-commerce éducatif sur Symfony">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/symfony-shop"><strong>symfony-shop</strong></a><br>
      <sub>Symfony</sub><br><br>
      Boutique en ligne sur Symfony avec PostgreSQL, Doctrine ORM, API Platform, OAuth et un frontend Vue séparé.
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/yii2-book-catalog">
        <img src="../assets/images/projects/yii2-book-catalog.png" width="100%" alt="yii2-book-catalog — catalogue web de livres sur Yii2">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/yii2-book-catalog"><strong>yii2-book-catalog</strong></a><br>
      <sub>Yii2</sub><br><br>
      Catalogue de livres et d’auteurs sur Yii2 et MySQL avec Docker, tests et intégration SMS externe.
    </td>
    <!--
    <td align="center" valign="top" width="50%">
      <img src="../assets/images/projects/laravel-temporal.png" width="100%" alt="Agrégateur de livraison Laravel, RoadRunner et Temporal — en cours"><br><br>
      <strong>En cours...</strong><br>
      <sub>Laravel</sub><br><br>
      Projet Laravel avec RoadRunner et Temporal basé sur l’exemple d’un agrégateur de livraison.
    </td>
    -->
    <td valign="top" width="50%"></td>
  </tr>
</table>

### Packages PHP

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/oauth2-yandex">
        <img src="../assets/images/packages/oauth2-yandex.png" width="100%" alt="oauth2-yandex — provider OAuth 2.0 Yandex ID pour PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/oauth2-yandex">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/oauth2-yandex">Packagist</a></sub><br><br>
      Provider OAuth 2.0 pour intégrer Yandex ID via <code>league/oauth2-client</code>.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/weather">
        <img src="../assets/images/packages/weather.png" width="100%" alt="weather — client unifié de météo actuelle pour PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/weather">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/weather">Packagist</a></sub><br><br>
      Client PHP permettant d’obtenir la météo actuelle à partir de coordonnées via Open-Meteo et WeatherAPI.
    </td>
  </tr>
  <!--
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/archive-guard">
        <img src="../assets/images/packages/archive-guard.png" width="100%" alt="archive-guard — inspection sécurisée d’archives ZIP pour PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/archive-guard">GitHub</a> · En développement</sub><br><br>
      Inspection sécurisée et extraction contrôlée d’archives ZIP non fiables en PHP.
    </td>
    <td valign="top" width="50%"></td>
  </tr>
  -->
</table>

### Outils

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-sql-lab">
        <img src="../assets/images/tools/docker-sql-lab.png" width="100%" alt="docker-sql-lab — environnement local d’apprentissage SQL">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-sql-lab"><strong>docker-sql-lab</strong></a><br>
      <sub>Docker · SQL</sub><br><br>
      Environnement local pour apprendre SQL avec PostgreSQL, MySQL et ClickHouse, ainsi que des tables de démonstration prêtes à l’emploi.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-elasticsearch">
        <img src="../assets/images/tools/docker-elasticsearch.png" width="100%" alt="docker-elasticsearch — environnement local d’apprentissage Elasticsearch">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-elasticsearch"><strong>docker-elasticsearch</strong></a><br>
      <sub>Docker · Elasticsearch</sub><br><br>
      Environnement local pour apprendre Elasticsearch avec Kibana et Nginx, incluant les analyses ICU et phonetic pour expérimenter avec la recherche.
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/remove-prefix">
        <img src="../assets/images/tools/remove-prefix.png" width="100%" alt="remove-prefix — suppression en masse de préfixes de fichiers et dossiers">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/remove-prefix"><strong>remove-prefix</strong></a><br>
      <sub>Bash · PowerShell</sub><br><br>
      Scripts multiplateformes pour supprimer récursivement et en masse les préfixes des noms de fichiers et de répertoires.
    </td>
    <td valign="top" width="50%"></td>
  </tr>
</table>

---

## Contacts

<table>
  <tr>
    <td><strong>Email</strong></td>
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
