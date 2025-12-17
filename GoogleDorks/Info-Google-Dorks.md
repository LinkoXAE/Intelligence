# **Что такое Google Dorks? / What are Google Dorks? / 什么是 Google Dorks？**

# **Русский**

Google Dorks (гугл-дорки) — это продвинутые поисковые запросы Google, которые используют специальные операторы, чтобы находить информацию, скрытую от обычного поиска, но доступную публично.

Их часто называют:  
- Google Hacking  
- Advanced Google Search  
- OSINT-поиск  

Важно: сами по себе Google Dorks не взламывают сайты. Они лишь находят то, что уже открыто в интернете.

**1. Зачем вообще нужны Google Dorks**  

Google индексирует:  
- файлы (.pdf, .docx, .sql)  
- админ-панели  
- тестовые страницы  
- логи  
- резервные копии  
- ошибки серверов  
- камеры, принтеры, панели управления  

Обычный пользователь этого не видит. Google Dorks позволяют точечно искать такие вещи.

**2. Основные операторы Google Dorks**  

**site:**  
Ограничивает поиск одним сайтом или доменом  


**filetype:**  
Ищет файлы определённого типа 

filetype:pdf
filetype:xls
filetype:sql


**intitle:**  
Ищет текст в заголовке страницы  

intitle:"index of"

**inurl:**  
Ищет слова в URL  

inurl:admin

**intext:**  
Ищет текст внутри страницы  

intext:"password"

Логические операторы: AND, OR, -  

**Пример:**  

inurl:admin OR inurl:login

**3. Что обычно ищут с помощью Google Dorks**  

**Открытые директории**  

intitle:"index of /"

Позволяет увидеть содержимое папки на сервере.

**Админ-панели**  

inurl:admin login

**Конфиденциальные файлы**  

filetype:env
filetype:sql
filetype:bak

**Ошибки и логи**  

filetype:log
"Fatal error"


**Устройства и IoT**  

intitle:"Live View / - AXIS"


**4. Google Dorks и OSINT**  

Google Dorks — ключевой инструмент OSINT (Open Source Intelligence). Используется для:  
- анализа сайтов  
- поиска утечек  
- аудита безопасности  
- журналистских расследований  
- кибербезопасности  
- проверки собственного сайта  

---

# **English**

Google Dorks are advanced Google search queries that use special operators to find information hidden from regular searches but publicly accessible.

They are often called:  
- Google Hacking  
- Advanced Google Search  
- OSINT search  

Important: Google Dorks by themselves do not hack websites. They only find what is already open on the internet.

**1. Why Google Dorks are useful**  

Google indexes:  
- files (.pdf, .docx, .sql)  
- admin panels  
- test pages  
- logs  
- backups  
- server errors  
- cameras, printers, control panels  

Regular users do not see this. Google Dorks allow targeted searching for such things.

**2. Main Google Dorks operators**  

**site:**  
Limits search to a single website or domain  

site:example.com


**filetype:**  
Searches for files of a specific type  

filetype:pdf
filetype:xls
filetype:sql


**intitle:**  
Searches text in the page title  

intitle:"index of"


**inurl:**  
Searches words in the URL  

inurl:admin


**intext:**  
Searches text inside the page  

intext:"password"

Logical operators: AND, OR, -  

**Example:**  

inurl:admin OR inurl:login


**3. What is usually searched with Google Dorks**  

**Open directories**  

intitle:"index of /"

Allows seeing folder contents on the server.

**Admin panels**  

inurl:admin login


**Confidential files**  

filetype:env
filetype:sql
filetype:bak


**Errors and logs**  

filetype:log
"Fatal error"


**Devices and IoT**  

intitle:"Live View / - AXIS"


**4. Google Dorks and OSINT**  

Google Dorks are a key OSINT (Open Source Intelligence) tool. Used for:  
- website analysis  
- finding leaks  
- security auditing  
- journalistic investigations  
- cybersecurity  
- checking your own site  

---

# **中文**

Google Dorks（谷歌 Dorks）是高级 Google 搜索查询，它使用特殊的操作符来查找普通搜索无法发现但公开可访问的信息。

它们常被称为：  
- Google 黑客技术  
- 高级 Google 搜索  
- OSINT 搜索  

重要提示：Google Dorks 本身不会入侵网站。它们只查找互联网上已经公开的信息。

**1. Google Dorks 的用途**  

Google 索引：  
- 文件 (.pdf, .docx, .sql)  
- 管理面板  
- 测试页面  
- 日志  
- 备份  
- 服务器错误  
- 摄像头、打印机、控制面板  

普通用户无法看到。Google Dorks 可以精准搜索这些内容。

**2. 主要的 Google Dorks 操作符**  

**site:**  
限制搜索到单一网站或域名  

site:example.com


**filetype:**  
搜索特定类型的文件  

filetype:pdf
filetype:xls
filetype:sql


**intitle:**  
搜索页面标题中的文本  

intitle:"index of"


**inurl:**  
搜索 URL 中的单词  

inurl:admin


**intext:**  
搜索页面内部文本  

intext:"password"


逻辑操作符: AND, OR, -  

**示例：**  

inurl:admin OR inurl:login


**3. 通常用 Google Dorks 搜索的内容**  

**开放目录**  

intitle:"index of /"

可查看服务器上的文件夹内容。

**管理面板**  

inurl:admin login


**机密文件**  

filetype:env
filetype:sql
filetype:bak


**错误和日志**  

filetype:log
"Fatal error"


**设备和物联网 (IoT)**  

intitle:"Live View / - AXIS"


**4. Google Dorks 与 OSINT**  

Google Dorks 是 OSINT（开源情报）的关键工具。用于：  
- 网站分析  
- 查找泄露信息  
- 安全审计  
- 新闻调查  
- 网络安全  
- 检查自己的网站
