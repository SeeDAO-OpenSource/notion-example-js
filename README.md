# ✅ Notion Example (nodejs)

> 🔰 本程序偏向新手友善，欢迎 Nodejs 初学者学习理解，并在开发者公会中分享研究心得

本 Repository 是为了验证 Notion Integration 的 API Key 与 Notion Database 页面有正确加入 Integration 的 Nodejs 范例程序。如果无法正常取得数据, 可能需要到 Discord 联系运营公会与开发者公会成员 `@Ricky Wang`。

## 快速开始

1. 取得 Notion API Key, 详细请见文件
2. 取得 Notion Database ID
    - 打开 Notion Database, 例如 [SeeDAO-Wiki / ... / SeeDAO 官网v2 / 资讯链结](https://www.notion.so/acdb747d7f0a4d56bc06f1878f3454fb)
    - 发现网址上的 notion.so 后面的就是 Database ID
        - Database 网址: `https://www.notion.so/acdb747d7f0a4d56bc06f1878f3454fb`
        - Database ID: `acdb747d7f0a4d56bc06f1878f3454fb`
3. 复制 `.env.example` 的内容, 建立一个新档案 `.env`
```sh
cp .env.example .env
```

打开并填入:
```
// .env
NOTION_API_KEY=secret_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
NOTION_DATABASE_ID=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx                   
```

4. 执行
```
npm install
npm run start
```

如果没有任何错误, 那就代表 integration 顺利成功取得 database 资料