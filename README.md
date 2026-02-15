- [1. Markdown-Workshop](#1-markdown-workshop)
  - [1.1. Chapter 2](#11-chapter-2)
    - [1.1.1. Dataflix (Oracle)](#111-dataflix-oracle)
  - [1.2. Prerequisites](#12-prerequisites)
    - [1.2.1. Components](#121-components)

# 1. Markdown-Workshop
## 1.1. Chapter 2 

### 1.1.1. Dataflix (Oracle)
_Last updated: 26 Sep, 2025 by Syed Sameer_


The Dataflix application is a specialized data management app that allows you to browse
available database services and create clones from your point-in-time recovery (PITR) regions,
snapshots, or sanitized snapshots. It also lets you download your database backups.

---
Table
Name | City | Profession
---: | :--- | :---:
Sameer | Bangalore | STW
Sameer | Bangalore | STW
Sameer | Bangalore | STW
Sameer | Bangalore | STW

```
{
    "status":"OK",
    "data":
        {
            "message": "Welcome, world!"
        }
}
```
[Stripe content](/Mardownfile.md)

![Image](/img/Screenshot.png)

<table class="table table-striped">
<caption>HTML Table</caption>
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


## 1.2. Prerequisites
- Ensure that you have created your database service in the Provisioning application
under the DB Services app family.
For more information on provisioning, see [Provisioning an Oracle DB Service](https://docs.tessell.com/tessell/tessell-for-oracle/db-services/provisioning-an-oracle-db-service).
- Ensure that you have scheduled snapshots in the Availability Machines application under
the DB Service app family.   
For more information on Availability Machines, see Availability Machines app.

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

  ### 1.2.1. Components
  - Frontend
  - Backend
  - Database

  ```bash
  npm install
  ```
</details>
<br>
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
</br>

Task lists
GitHub Flavored Markdown (GFM) supports it.
Useful for Project list, roadmap, or task reviews.
- [x] Setup repository
- [x] Write README
- [ ] Add documentation
- [ ] Review pull requests

