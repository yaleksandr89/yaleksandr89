## Elegir idioma

| Русский | English | Español | 中文 | Français | Deutsch |
|---|---|---|---|---|---|
| [Русский](../README.md) | [English](README_en.md) | **Seleccionado** | [中文](README_zh.md) | [Français](README_fr.md) | [Deutsch](README_de.md) |

---

Trabajo con lógica backend, integraciones de API, proyectos legacy y sistemas corporativos internos. Los repositorios reúnen proyectos, paquetes PHP y pequeñas herramientas para experimentos, práctica y tareas cotidianas.

---

## Stack

<table>
  <thead>
    <tr>
      <th align="left">Área</th>
      <th align="left">Tecnologías</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td valign="middle"><img src="../assets/icons/languages.svg" width="28" height="34" alt="" align="middle"> <strong>Lenguajes</strong></td>
      <td valign="middle">PHP · SQL · JavaScript</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/php.svg" width="28" height="34" alt="" align="middle"> <strong>PHP</strong></td>
      <td valign="middle">Native PHP · Symfony · Laravel · Yii</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/databases.svg" width="28" height="34" alt="" align="middle"> <strong>Bases de datos</strong></td>
      <td valign="middle">PostgreSQL · MySQL · MariaDB</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/search.svg" width="28" height="34" alt="" align="middle"> <strong>Caché y búsqueda</strong></td>
      <td valign="middle">Redis · Elasticsearch · Sphinx</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/devops.svg" width="28" height="34" alt="" align="middle"> <strong>Plataforma / DevOps</strong></td>
      <td valign="middle">Linux · Docker · Kubernetes</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/git.svg" width="28" height="34" alt="" align="middle"> <strong>Git / Forge / CI</strong></td>
      <td valign="middle">Git · GitHub · GitLab · Gitea · GitHub Actions</td>
    </tr>
    <tr>
      <td valign="middle"><img src="../assets/icons/development.svg" width="28" height="34" alt="" align="middle"> <strong>Desarrollo</strong></td>
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
  <img src="../assets/images/php-mascot.png" alt="Mascota PHP — elefante azul frente a un portátil">
</p>

### Proyectos

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/mvc-v1">
        <img src="../assets/images/projects/mvc-v1.png" width="100%" alt="mvc-v1 — blog educativo en PHP con núcleo MVC propio">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/mvc-v1"><strong>mvc-v1</strong></a><br>
      <sub>Native PHP</sub><br><br>
      Ejemplo de implementación del patrón arquitectónico MVC en PHP nativo con CRUD, PostgreSQL mediante PDO y un entorno Docker.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/symfony-shop">
        <img src="../assets/images/projects/symfony-shop.png" width="100%" alt="symfony-shop — proyecto educativo de comercio electrónico en Symfony">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/symfony-shop"><strong>symfony-shop</strong></a><br>
      <sub>Symfony</sub><br><br>
      Tienda online en Symfony con PostgreSQL, Doctrine ORM, API Platform, OAuth y un frontend independiente en Vue.
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/yii2-book-catalog">
        <img src="../assets/images/projects/yii2-book-catalog.png" width="100%" alt="yii2-book-catalog — catálogo web de libros en Yii2">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/yii2-book-catalog"><strong>yii2-book-catalog</strong></a><br>
      <sub>Yii2</sub><br><br>
      Catálogo de libros y autores en Yii2 y MySQL con Docker, pruebas e integración externa de SMS.
    </td>
    <!--
    <td align="center" valign="top" width="50%">
      <img src="../assets/images/projects/laravel-temporal.png" width="100%" alt="Agregador de entregas con Laravel, RoadRunner y Temporal — en desarrollo"><br><br>
      <strong>En desarrollo...</strong><br>
      <sub>Laravel</sub><br><br>
      Proyecto en Laravel con RoadRunner y Temporal basado en el ejemplo de un agregador de entregas.
    </td>
    -->
    <td valign="top" width="50%"></td>
  </tr>
</table>

### Paquetes PHP

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/oauth2-yandex">
        <img src="../assets/images/packages/oauth2-yandex.png" width="100%" alt="oauth2-yandex — proveedor OAuth 2.0 de Yandex ID para PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/oauth2-yandex">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/oauth2-yandex">Packagist</a></sub><br><br>
      Proveedor OAuth 2.0 para integrar Yandex ID mediante <code>league/oauth2-client</code>.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/weather">
        <img src="../assets/images/packages/weather.png" width="100%" alt="weather — cliente unificado de clima actual para PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/weather">GitHub</a> · <a href="https://packagist.org/packages/yaleksandr89/weather">Packagist</a></sub><br><br>
      Cliente PHP para obtener el clima actual por coordenadas mediante Open-Meteo y WeatherAPI.
    </td>
  </tr>
  <!--
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/archive-guard">
        <img src="../assets/images/packages/archive-guard.png" width="100%" alt="archive-guard — inspección segura de archivos ZIP para PHP">
      </a><br><br>
      <sub><a href="https://github.com/yaleksandr89/archive-guard">GitHub</a> · En desarrollo</sub><br><br>
      Inspección segura y extracción controlada de archivos ZIP no confiables en PHP.
    </td>
    <td valign="top" width="50%"></td>
  </tr>
  -->
</table>

### Herramientas

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-sql-lab">
        <img src="../assets/images/tools/docker-sql-lab.png" width="100%" alt="docker-sql-lab — entorno local para aprender SQL">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-sql-lab"><strong>docker-sql-lab</strong></a><br>
      <sub>Docker · SQL</sub><br><br>
      Entorno local para aprender SQL con PostgreSQL, MySQL y ClickHouse, además de tablas demo listas para usar.
    </td>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/docker-elasticsearch">
        <img src="../assets/images/tools/docker-elasticsearch.png" width="100%" alt="docker-elasticsearch — entorno local para aprender Elasticsearch">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/docker-elasticsearch"><strong>docker-elasticsearch</strong></a><br>
      <sub>Docker · Elasticsearch</sub><br><br>
      Entorno local para aprender Elasticsearch con Kibana y Nginx, incluido el análisis ICU y fonético para experimentar con búsquedas.
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <a href="https://github.com/yaleksandr89/remove-prefix">
        <img src="../assets/images/tools/remove-prefix.png" width="100%" alt="remove-prefix — eliminación masiva de prefijos en archivos y carpetas">
      </a><br><br>
      <a href="https://github.com/yaleksandr89/remove-prefix"><strong>remove-prefix</strong></a><br>
      <sub>Bash · PowerShell</sub><br><br>
      Scripts multiplataforma para eliminar de forma recursiva y masiva prefijos de nombres de archivos y directorios.
    </td>
    <td valign="top" width="50%"></td>
  </tr>
</table>

---

## Contactos

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
