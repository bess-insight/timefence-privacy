TimeFence Privacy Policy
Effective date: 2026-10-10

TimeFence is a local-first browser extension for user-configured website access limits and time budgets.

Data processed
To determine whether the current website matches a user-created rule, TimeFence reads the URL of the active browser tab and extracts its hostname. To calculate daily limits, TimeFence stores locally aggregated usage information by rule, configured domain, date, and elapsed seconds.

TimeFence also processes a user-created 10-character protection password. Plaintext is not stored. Only a PBKDF2-SHA256 hash with a random salt is kept in local extension storage.

TimeFence does not store webpage contents, form contents, page titles, a full URL history, or credentials for other websites.

Purpose
Data is used only to match websites against user-created groups, enforce always-block rules, shared daily quotas and weekly schedules, display local aggregate usage, and protect rule changes.

Transmission and third parties
TimeFence 1.3 has no account system, analytics SDK, advertising SDK, or remote service. Rules, password hashes, and usage data remain in local browser extension storage. TimeFence does not sell, share, license, or transmit this data to third parties.

Private / incognito browsing
TimeFence can run in private/incognito windows only after the user explicitly enables that permission in browser extension settings. Aggregate usage can be combined with regular-window usage; TimeFence does not retain a full private-browsing URL history.

Export and deletion
Users can export rules and aggregate usage to a local JSON backup. The backup does not contain the protection password or password hash. Removing the extension or clearing extension storage deletes locally stored TimeFence data.

Permissions
storage: local rules, password hash, privacy consent, aggregate usage.
tabs: active-tab URL and redirecting blocked tabs to a local page.
webNavigation: prompt enforcement on navigation and SPA URL changes.
alarms: background timing and quota/schedule boundary checks.
Contact
For privacy questions, contact the developer through the support contact shown on the extension store listing.

TimeFence 隐私政策
生效日期：2026-10-10

TimeFence 是一款本地优先的网站访问限制与时间预算浏览器扩展。

处理的数据
为了判断当前网站是否命中用户创建的规则，TimeFence 会读取当前活动标签页的 URL 并提取域名。为了计算每日额度，TimeFence 会在浏览器本地按“规则、配置域名、日期、累计秒数”保存聚合使用数据。

保护密码明文不会被保存；本地仅保存带随机盐的 PBKDF2-SHA256 哈希。TimeFence 不保存网页正文、表单内容、页面标题、完整 URL 浏览历史，也不读取或保存其他网站的账号密码。

数据用途
数据仅用于网站组匹配、始终禁止、共享每日额度、每周允许时段、本地聚合用时展示以及规则修改保护。

传输与第三方
TimeFence 1.3 不包含账号系统、分析 SDK、广告 SDK 或远程服务。规则、密码哈希和累计用时都保存在浏览器本地扩展存储中，不出售、不共享、也不向第三方传输。

隐私 / 无痕浏览
只有用户在浏览器扩展设置中明确允许后，TimeFence 才能在隐私 / 无痕窗口中运行。其聚合用时可以与普通窗口合并计算，但不会保存完整隐私浏览 URL 历史。

导出与删除
用户可将规则和聚合用时导出为本地 JSON 备份；备份不包含保护密码或密码哈希。删除扩展或清除扩展存储即可删除本地数据。

联系方式
如有隐私问题，请通过扩展商店页面中显示的开发者支持联系方式联系开发者。
