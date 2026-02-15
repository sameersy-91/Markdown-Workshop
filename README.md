# Markdown-Workshop
## Chapter 2 

# Dataflix (Oracle)
_Last updated: 26 Sep, 2025 by Syed Sameer_

```
The Dataflix application is a specialized data management app that allows you to browse
available database services and create clones from your point-in-time recovery (PITR) regions,
snapshots, or sanitized snapshots. It also lets you download your database backups.
```
---
![Image](/img/Screenshot.png)

<table class="table table-striped">
<caption>Caption for this Table</caption>
<thead class="thead-dark">
<tr>
    <th width="30%">Property</th>
    <th width="70%">Description</th>
    </tr>
</thead>
<tbody>
<tr>
    <td>Topic1 </td>
    <td>Topic2
        <ul>
        <li>Bullet item</li>
        <li>Bullet item</li>
        </ul>
        </td>
    </tr>
<tr>
    <td>TopicA</td>
    <td>TopicB</td>
    </tr>
</tbody>
</table>


## Prerequisites
- Ensure that you have created your database service in the Provisioning application
under the DB Services app family.
For more information on provisioning, see [Provisioning an Oracle DB Service](https://docs.tessell.com/tessell/tessell-for-oracle/db-services/provisioning-an-oracle-db-service).

1. From the Tessell home page, select the **Provisioning** application under the DB Services application family in the left-hand menu.
<br>Available database engines are displayed and categorized into relational databases, vector databases, and NoSQL databases.</br>

2. From the available options in the relational databases, select Oracle database engine.

Granted Role: `DBA`, `RESOURCE`, `CONNECT`, `SELECT_CATALOG_ROLE`, `EXECUTE_CATALOG_ROLE`

> **Note**: Tessell supports Shell scripts for pre-scripts that are executed after VM creation and database software installation, but prior to the Oracle instance creation.

<details>
  <summary>Click to expand</summary>

  This content is hidden by default.
  You can include text, lists, code, or even images here.

</details>
<details>
  <summary><strong>Project Architecture</strong></summary>

  ### Components
  - Frontend
  - Backend
  - Database

  ```bash
  npm install
  ```

<ul>
  <li>
    <details>
      <summary>Frontend</summary>
      <ul>
        <li>React</li>
        <li>CSS</li>
        <li>HTML</li>
      </ul>
    </details>
  </li>

  <li>
    <details>
      <summary>Backend</summary>
      <ul>
        <li>Node.js</li>
        <li>Express</li>
      </ul>
    </details>
  </li>

  <li>
    <details>
      <summary>Database</summary>
      <ul>
        <li>PostgreSQL</li>
        <li>MongoDB</li>
      </ul>
    </details>
  </li>
</ul>


