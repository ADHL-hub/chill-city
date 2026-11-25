# Chill City 🌃

马来西亚夜生活虚拟社交小游戏（18+）。3D 低多边形画面，直接在手机或电脑浏览器打开就能玩。

- 地点：广场（Lok Lok 车）、PULSE 夜店、Starlight KTV、The Barrel 酒吧、Bali Breeze Spa、Lotus 泰式按摩、Lucky 4D（免费玩、不用真钱）、Chill Mart 24/7
- 登入 / 注册（邮箱 + 密码，要确认 18 岁以上）
- 同一个地方的真人玩家互相看得到，每条线最多 30 人，满了自动开新线
- 附近聊天、头上状态、资料卡、头像、最多 5 张只有好友看得到的生活照
- 加好友（一小时最多 30 个邀请）、私聊、封锁、举报
- 🤖 NPC 都有标明不是真人
- 中文 / English / Bahasa Melayu

技术：一个 `index.html`，Three.js 画 3D，Supabase 管登入、资料库、照片和即时同步。

调整路人多少：在 `index.html` 里找 `const CROWD`（1 = 很多，0 = 没有路人）。
