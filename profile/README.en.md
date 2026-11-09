<div align="center">

# n8n Community Nodes Workspace

Connect your business apps and take automation further.

[简体中文](https://github.com/luka-n8n-nodes/.github/blob/main/profile/README.md) | **English**

</div>

---

## 📦 About This Repository

This repository is used for developing and maintaining N8N community node plugins. Plugins are primarily developed using TypeScript and follow N8N community node development standards and best practices.

## 🎯 Repository Directory

All 18 public repositories are grouped by purpose below: 17 n8n plugins and one organization profile repository. Select a repository for documentation and usage instructions.

Verified on 2026-11-09 · [Browse all repositories](https://github.com/orgs/luka-n8n-nodes/repositories)

### Collaboration & Workflow Automation

| Repository | Description |
| --- | --- |
| [n8n-nodes-feishu](https://github.com/luka-n8n-nodes/n8n-nodes-feishu) | **Dual event modes and enhanced Bitable operations**: WebSocket/Webhook listeners with synchronous responses, field mapping, conditional branches, and upserts. Covers documents, wikis, messages, and calendars, with automatic pagination, batching, and multipart uploads. |
| [n8n-nodes-feishu-project](https://github.com/luka-n8n-nodes/n8n-nodes-feishu-project) | **Visually configured project automation**: Manage work items, workflow nodes, views, comments, and attachments. Dynamically loaded spaces and work item types reduce manual entry; pagination, batching, and timeouts support cross-system synchronization. |
| [n8n-nodes-qingflow-oa](https://github.com/luka-n8n-nodes/n8n-nodes-qingflow-oa) | **Directory synchronization and approval workflows**: Manage members, departments, roles, apps, and form data; process, remind, reassign, roll back, and delegate tasks. Includes automatic pagination and token refresh with request retry on expiry. |
| [n8n-nodes-yingdao-rpa](https://github.com/luka-n8n-nodes/n8n-nodes-yingdao-rpa) | **Start robots and wait for results**: Pause an n8n workflow after launching a Job and resume on its callback, without a separate Wait node. Robot groups, retries, logs, and work queues connect API workflows with desktop RPA. |
| [n8n-nodes-browserless](https://github.com/luka-n8n-nodes/n8n-nodes-browserless) | **Web data and file processing**: Browserless API V2 provides rendered HTML, structured scraping, screenshots, PDFs, custom scripts, and downloads. Usable as an AI Agent tool, with configurable filenames and MIME types for PDF and download outputs. |

### HR & Enterprise Management

| Repository | Description |
| --- | --- |
| [n8n-nodes-moka-people](https://github.com/luka-n8n-nodes/n8n-nodes-moka-people) | **HR synchronization and BI report transformation**: Create and update employees, handle bulk attachments, write back basic information, and maintain departments. Transform BI rows into individual n8n items keyed by column titles, including nested headers. |
| [n8n-nodes-mokahr](https://github.com/luka-n8n-nodes/n8n-nodes-mokahr) | **Recruitment data across candidate stages**: Access candidates, parsed resumes, attachments, tags, evaluations, and talent pools in Chinese and international editions. Cursor pagination, resumable queries for selected operations, and batching controls support larger imports. |
| [n8n-nodes-italent](https://github.com/luka-n8n-nodes/n8n-nodes-italent) | **Beisen AI interview automation**: Arrange or cancel interviews and retrieve invitation links, answers, applicant details, and activity data. Per-operation invite-ID limits, expression arrays, pagination, and batching help connect interview notifications with result collection. |
| [n8n-nodes-kingdee](https://github.com/luka-n8n-nodes/n8n-nodes-kingdee) | **ERP integration across 47 resource types**: Connect master data, finance, purchasing, sales, inventory, production, quality, and tax. Resource-specific operations include saving, submitting, auditing, and batch processing, with application authorization, cookie sessions, and date/multilingual-field handling. |
| [n8n-nodes-didi-enterprise-admin](https://github.com/luka-n8n-nodes/n8n-nodes-didi-enterprise-admin) | **Organization and employee synchronization for corporate travel**: Manage departments, projects, employees, and project membership. Handles authorization, request signing, and AES encryption, with automatic query pagination and a default 150 ms interval between writes. |

### Identity, Security & Cloud Services

| Repository | Description |
| --- | --- |
| [n8n-nodes-authing-admin](https://github.com/luka-n8n-nodes/n8n-nodes-authing-admin) | **Identity and account lifecycle automation**: Manage users, groups, departments, public accounts, and custom domains, including offboarding and domain ownership verification. Dynamic group selectors reduce manual code entry; custom requests extend access to other Admin APIs. |
| [n8n-nodes-feilian](https://github.com/luka-n8n-nodes/n8n-nodes-feilian) | **Event-driven IT and endpoint management**: Webhooks handle URL verification, token checks, encrypted payloads, and event filtering. Manage people, roles, Wi-Fi logs, devices, software usage, and license assignments, with recursive department queries and pagination. |
| [n8n-nodes-volcengine](https://github.com/luka-n8n-nodes/n8n-nodes-volcengine) | **Knowledge-base AI and cloud identity management**: Combine VikingDB semantic search and multi-turn conversations using Doubao models with IAM user and login settings. Custom GET/POST requests with query and body parameters extend access to Volcengine OpenAPI. |
| [n8n-nodes-pgp](https://github.com/luka-n8n-nodes/n8n-nodes-pgp) | **OpenPGP encryption and signing for text and files**: Six operations cover encryption, decryption, signing, verification, and combined actions, with binary files, embedded signatures, and compression. Encrypt-and-sign or decrypt-and-verify in a single step for file exchange workflows. |
| [n8n-nodes-bcryptjs](https://github.com/luka-n8n-nodes/n8n-nodes-bcryptjs) | **Password hashing with inspection utilities**: Asynchronous hashing, password comparison, and salt generation, plus salt/round extraction and checks for truncation beyond 72 bytes. Configurable cost and output fields support account creation, verification, and inspection workflows. |

### Development & File Utilities

| Repository | Description |
| --- | --- |
| [n8n-nodes-semver](https://github.com/luka-n8n-nodes/n8n-nodes-semver) | **From version validation to release decisions**: Parse, compare, match ranges, increment, clean, coerce, and sort versions. Find the highest or lowest compatible version and handle prereleases for dependency checks and automated release versioning. |
| [n8n-nodes-heic-convert](https://github.com/luka-n8n-nodes/n8n-nodes-heic-convert) | **Batch image conversion for workflows**: Convert HEIC/HEIF to PNG or JPEG with adjustable JPEG quality and configurable binary input/output fields. Preserves original filenames with updated extensions and supports continuing after individual conversion failures. |

### Organization Profile

| Repository | Description |
| --- | --- |
| [.github](https://github.com/luka-n8n-nodes/.github) | **Bilingual navigation for the organization**: Chinese by default with switching in both directions. Groups all public repositories by purpose, bringing together plugin highlights, project links, and development conventions to help readers choose an integration. |

## 🛠️ Tech Stack

- **TypeScript** - Type-safe development experience
- **N8N** - Workflow automation platform
- **Node.js** - Runtime environment

## 📝 Development Standards

All plugins follow these development standards:

- Developed using TypeScript
- Follow N8N community node code structure
- Provide complete type definitions
- Comprehensive error handling and user prompts
- Unified parameter design

## 🔗 Related Links

- [N8N Official Documentation](https://docs.n8n.io/)
- [N8N Community Node Development Guide](https://docs.n8n.io/integrations/community-nodes/)


---

[切换至中文 / Switch to Chinese](https://github.com/luka-n8n-nodes/.github/blob/main/profile/README.md)
