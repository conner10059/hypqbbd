<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/JHEJHR/auhkgvk/-/commit/03b106802a3c9ece43bcb2f2e0c6e802c95a1e7f?/b5Z
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2ea7194059172a647703be616a39de277f82e025
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2ea7194059172a647703be616a39de277f82e025?/K7=l25
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2ea7194059172a647703be616a39de277f82e025?/OsM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c50bea500bacdad403c13dbe1cfeb926d13bbc98
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c50bea500bacdad403c13dbe1cfeb926d13bbc98?/IM=0HK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c50bea500bacdad403c13dbe1cfeb926d13bbc98?/d7b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fcbb7dabf12bcb510d030ad9ad7259c4620a2b8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fcbb7dabf12bcb510d030ad9ad7259c4620a2b8?/vJ=7DR
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fcbb7dabf12bcb510d030ad9ad7259c4620a2b8?/QuO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d8d01819997fc3c8c694bc197050b7347d1816c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d8d01819997fc3c8c694bc197050b7347d1816c?/no=MSg
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0d8d01819997fc3c8c694bc197050b7347d1816c?/f9d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7dfa857ba74e7485615df53fb928508d541ededd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7dfa857ba74e7485615df53fb928508d541ededd?/Wx=oY2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7dfa857ba74e7485615df53fb928508d541ededd?/ySw
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3c9615e0b259db15060ba4f9547028ad2dd95b02
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3c9615e0b259db15060ba4f9547028ad2dd95b02?/gR=1i5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3c9615e0b259db15060ba4f9547028ad2dd95b02?/lFj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aa6d8adac3050d400b9d76e105c0dffbf8109747
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aa6d8adac3050d400b9d76e105c0dffbf8109747?/6X=Ob5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aa6d8adac3050d400b9d76e105c0dffbf8109747?/4Y2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b43f9d31fd6ced0580a8913e863666060fe7871
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b43f9d31fd6ced0580a8913e863666060fe7871?/15=F4k
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3b43f9d31fd6ced0580a8913e863666060fe7871?/JnH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/12da8231d63062c47d647503abe5679acd50af73
<br>
gitlab.com/EHWGW/fxleljy/-/commit/12da8231d63062c47d647503abe5679acd50af73?/M0=KyH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/12da8231d63062c47d647503abe5679acd50af73?/a4Y
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9241369f12f2e61f2222c0f26d81bc68ac3aae91
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9241369f12f2e61f2222c0f26d81bc68ac3aae91?/gu=rId
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9241369f12f2e61f2222c0f26d81bc68ac3aae91?/pJn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/94ae1f0168e5e1a3fed1fca5bae0f1bcdd57e9a9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/94ae1f0168e5e1a3fed1fca5bae0f1bcdd57e9a9?/g7=xB8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/94ae1f0168e5e1a3fed1fca5bae0f1bcdd57e9a9?/e8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6973d00c45a563e532ba7611459b90f7baa73739
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6973d00c45a563e532ba7611459b90f7baa73739?/TN=gK8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6973d00c45a563e532ba7611459b90f7baa73739?/xvP
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f3b714c80fd25568c03419bf4090c81e8c0ece5f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f3b714c80fd25568c03419bf4090c81e8c0ece5f?/oI=IJq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f3b714c80fd25568c03419bf4090c81e8c0ece5f?/CgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/184b10a4ff7c4f5b86c8b0713cb02831d34cbb5a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/184b10a4ff7c4f5b86c8b0713cb02831d34cbb5a?/yM=dgK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/184b10a4ff7c4f5b86c8b0713cb02831d34cbb5a?/TRv
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ce7d8b3c1ffb3a1b545f1a420c66a8d6fb0106b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ce7d8b3c1ffb3a1b545f1a420c66a8d6fb0106b?/Fd=tx4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ce7d8b3c1ffb3a1b545f1a420c66a8d6fb0106b?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5a4b41aeec5faac306c945ca33f09a78c0cf3c68
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5a4b41aeec5faac306c945ca33f09a78c0cf3c68?/2Q=hlv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5a4b41aeec5faac306c945ca33f09a78c0cf3c68?/1VT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cf231dd8d1312179ae2372eb1669b34e83d3dc31
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cf231dd8d1312179ae2372eb1669b34e83d3dc31?/bi=T03
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cf231dd8d1312179ae2372eb1669b34e83d3dc31?/MqK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3f0dbd29377f1aa4b9e008ff74675553763e65c6
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3f0dbd29377f1aa4b9e008ff74675553763e65c6?/Gn=N4R
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3f0dbd29377f1aa4b9e008ff74675553763e65c6?/7b5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c27b881c685dc48e9fcb48687adaa260d6522ee1
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c27b881c685dc48e9fcb48687adaa260d6522ee1?/hO=Icn
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c27b881c685dc48e9fcb48687adaa260d6522ee1?/MqK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1eef14a1d2d1dc2177c8ce91137c398b3887e3a2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1eef14a1d2d1dc2177c8ce91137c398b3887e3a2?/Nx=8VF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1eef14a1d2d1dc2177c8ce91137c398b3887e3a2?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/503083edf63a4a2ec1c272f10e33e8554c160c6f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/503083edf63a4a2ec1c272f10e33e8554c160c6f?/DJ=XVv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/503083edf63a4a2ec1c272f10e33e8554c160c6f?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2a250a8a21a42f8865adebbf92d49dd8d19b9d2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2a250a8a21a42f8865adebbf92d49dd8d19b9d2?/gx=XiZ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c2a250a8a21a42f8865adebbf92d49dd8d19b9d2?/lFj
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eddd5994f19e0677f901c942e0ea2f8fc02a1057
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eddd5994f19e0677f901c942e0ea2f8fc02a1057?/qT=lsc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eddd5994f19e0677f901c942e0ea2f8fc02a1057?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d69a83751c6cc8043f264f50681eb1a17452775
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d69a83751c6cc8043f264f50681eb1a17452775?/JA=NoB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1d69a83751c6cc8043f264f50681eb1a17452775?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ade65fc4f088089581e0359a58b11f3eb5601403
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ade65fc4f088089581e0359a58b11f3eb5601403?/e5=SCC
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ade65fc4f088089581e0359a58b11f3eb5601403?/6a4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9d27532da317560c09fd7b53d85526b6e3847307
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9d27532da317560c09fd7b53d85526b6e3847307?/NA=o5f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9d27532da317560c09fd7b53d85526b6e3847307?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/080bd76c97de2b06a3d1e201434d848c4bda3524
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/080bd76c97de2b06a3d1e201434d848c4bda3524?/wX=lB5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/080bd76c97de2b06a3d1e201434d848c4bda3524?/Eig
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a2a43d602d0f6618a53cc7e935c2130c0505767
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a2a43d602d0f6618a53cc7e935c2130c0505767?/eB=mTu
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a2a43d602d0f6618a53cc7e935c2130c0505767?/TxR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5e3d0f97d8344dd6e9c6d61c34cffb8e7a3bde8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5e3d0f97d8344dd6e9c6d61c34cffb8e7a3bde8?/Vb=pmD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5e3d0f97d8344dd6e9c6d61c34cffb8e7a3bde8?/mGk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b498fea714ddbb386b329c3268d7793e8652ebb3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b498fea714ddbb386b329c3268d7793e8652ebb3?/d4=u85
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b498fea714ddbb386b329c3268d7793e8652ebb3?/b5Z
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e067665433a81017be61ebe8def00069cdc38827
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e067665433a81017be61ebe8def00069cdc38827?/dD=Rsl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e067665433a81017be61ebe8def00069cdc38827?/uOs
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4af5d36832e52b10cb074c305c961cbfd9e775f4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4af5d36832e52b10cb074c305c961cbfd9e775f4?/Bc=TgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4af5d36832e52b10cb074c305c961cbfd9e775f4?/9d7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9994ab452b10267f92c49647e5174dc83fcce1a2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9994ab452b10267f92c49647e5174dc83fcce1a2?/cD=Rrl
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9994ab452b10267f92c49647e5174dc83fcce1a2?/uOs
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c6389fc445a685b972bb0f335081085448b7b13
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c6389fc445a685b972bb0f335081085448b7b13?/R8=VmK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c6389fc445a685b972bb0f335081085448b7b13?/9d7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/399bbf2109976d4a4cdd36e194b777723f5ad46c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/399bbf2109976d4a4cdd36e194b777723f5ad46c?/p3=UOh
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/399bbf2109976d4a4cdd36e194b777723f5ad46c?/0Uy
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ffc9c08fc391150bf6117bf4d71096d6508ab2f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ffc9c08fc391150bf6117bf4d71096d6508ab2f?/cJ=gUb
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9ffc9c08fc391150bf6117bf4d71096d6508ab2f?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01ca5fe51bd968715a2335fcdd82317dca658793
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01ca5fe51bd968715a2335fcdd82317dca658793?/kK=VLZ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01ca5fe51bd968715a2335fcdd82317dca658793?/Y2W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a175543fa93acf60483c206f7b42575a18fdab8e
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a175543fa93acf60483c206f7b42575a18fdab8e?/8J=C07
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a175543fa93acf60483c206f7b42575a18fdab8e?/nHl
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ecb97a98207c15d7500b7b09882ea3e06cd8e762
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ecb97a98207c15d7500b7b09882ea3e06cd8e762?/VJ=xEH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ecb97a98207c15d7500b7b09882ea3e06cd8e762?/a4Y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/300fca4005893b9174a7b77d389e16200f7f5fbd
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/300fca4005893b9174a7b77d389e16200f7f5fbd?/Tu=kyv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/300fca4005893b9174a7b77d389e16200f7f5fbd?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a19c1a8599b2832b3e956f2102cf1a1e25d4aee2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a19c1a8599b2832b3e956f2102cf1a1e25d4aee2?/3k=dRZ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a19c1a8599b2832b3e956f2102cf1a1e25d4aee2?/EiC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b48d74281db30b48506191f04abd3e714eb741b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b48d74281db30b48506191f04abd3e714eb741b?/64=1vF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b48d74281db30b48506191f04abd3e714eb741b?/VzT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/955bb2014d696628ee0bed231ca9444e3e72867d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/955bb2014d696628ee0bed231ca9444e3e72867d?/Xe=Pw0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/955bb2014d696628ee0bed231ca9444e3e72867d?/ImG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3c891ebc82aae06a9a45b2748ce7892955da4429
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3c891ebc82aae06a9a45b2748ce7892955da4429?/lM=3wk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3c891ebc82aae06a9a45b2748ce7892955da4429?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/68f608a142d58b66142c25800a0ff839013f8ddb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/68f608a142d58b66142c25800a0ff839013f8ddb?/Ao=bFW
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/68f608a142d58b66142c25800a0ff839013f8ddb?/sMq
<br>
gitlab.com/EHWGW/fxleljy/-/commit/491700df5db5cce02400e325f093850090a5b937
<br>
gitlab.com/EHWGW/fxleljy/-/commit/491700df5db5cce02400e325f093850090a5b937?/JK=KOW
<br>
gitlab.com/EHWGW/fxleljy/-/commit/491700df5db5cce02400e325f093850090a5b937?/Bf9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/77bd63abf320bf56832548fcde19fd4f58bf136b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/77bd63abf320bf56832548fcde19fd4f58bf136b?/dA=lSM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/77bd63abf320bf56832548fcde19fd4f58bf136b?/SwQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ef64a7342f84fbb6f8f660e918c03741876e51e0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ef64a7342f84fbb6f8f660e918c03741876e51e0?/l6=mAQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ef64a7342f84fbb6f8f660e918c03741876e51e0?/JnH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d470a75cdfd4de1619b645341ad8e8c59539960
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d470a75cdfd4de1619b645341ad8e8c59539960?/4r=yFm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5d470a75cdfd4de1619b645341ad8e8c59539960?/86a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/32a9d172d377f331ed821ab27c658135f181296d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/32a9d172d377f331ed821ab27c658135f181296d?/BM=CQN
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/32a9d172d377f331ed821ab27c658135f181296d?/tNr
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/383bca062f25ac35bab93d14626925e4b6f77ea1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/383bca062f25ac35bab93d14626925e4b6f77ea1?/tT=h81
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/383bca062f25ac35bab93d14626925e4b6f77ea1?/A8c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8cb78fc35a0d3626a38a61fa8e2fc04748f05abb
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8cb78fc35a0d3626a38a61fa8e2fc04748f05abb?/xO=lVW
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8cb78fc35a0d3626a38a61fa8e2fc04748f05abb?/vPt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d212f1da6fb1081cbf8bccf3e7243d6dce027fd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d212f1da6fb1081cbf8bccf3e7243d6dce027fd?/Ta=nHE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d212f1da6fb1081cbf8bccf3e7243d6dce027fd?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/082fdbfd7e576b4ec97bd411570e23c775a54342
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/082fdbfd7e576b4ec97bd411570e23c775a54342?/Ma=1ui
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/082fdbfd7e576b4ec97bd411570e23c775a54342?/X1V
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7f358093cbf6bc448dee538dc2a35798dacf9bad
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7f358093cbf6bc448dee538dc2a35798dacf9bad?/ev=S3k
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7f358093cbf6bc448dee538dc2a35798dacf9bad?/ImG
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d0030f1139aaca54b904a2c86a046d22bf226d24
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d0030f1139aaca54b904a2c86a046d22bf226d24?/iF=qXy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d0030f1139aaca54b904a2c86a046d22bf226d24?/X1V
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6e6dcb9ccc21e03a14d0ae78f8a1683af855f226
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6e6dcb9ccc21e03a14d0ae78f8a1683af855f226?/8I=9qH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6e6dcb9ccc21e03a14d0ae78f8a1683af855f226?/qKo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f9a34ddd5b3e37094ad8ef70c8db4c5c0ff88aaf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f9a34ddd5b3e37094ad8ef70c8db4c5c0ff88aaf?/mm=KRB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f9a34ddd5b3e37094ad8ef70c8db4c5c0ff88aaf?/7b5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/af1fe57de942a41413da7c7b64be8c8e709f4c49
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/af1fe57de942a41413da7c7b64be8c8e709f4c49?/jq=b8C
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/af1fe57de942a41413da7c7b64be8c8e709f4c49?/UyS
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cb1d84603208699106b7ead39cfa378489b2af79
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cb1d84603208699106b7ead39cfa378489b2af79?/Km=D7R
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cb1d84603208699106b7ead39cfa378489b2af79?/jDh
<br>
gitlab.com/EHWGW/fxleljy/-/commit/43972f62fee05e074083b10fc8e2db7779ae17f0
<br>
gitlab.com/EHWGW/fxleljy/-/commit/43972f62fee05e074083b10fc8e2db7779ae17f0?/Wx=oY2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/43972f62fee05e074083b10fc8e2db7779ae17f0?/ySw
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/239b3697fb89f2e4de02dec62ab61163bf6c6b5f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/239b3697fb89f2e4de02dec62ab61163bf6c6b5f?/Pt=NLM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/239b3697fb89f2e4de02dec62ab61163bf6c6b5f?/lFj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5566a89e65770d4bd8ddb1f6d2d8447a9dc85349
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5566a89e65770d4bd8ddb1f6d2d8447a9dc85349?/DD=lr5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5566a89e65770d4bd8ddb1f6d2d8447a9dc85349?/4Y2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6abc748a59af374e543d6fce1f1d0cdf29edbfba
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6abc748a59af374e543d6fce1f1d0cdf29edbfba?/JA=rl5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6abc748a59af374e543d6fce1f1d0cdf29edbfba?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1eba9443113386db54e81de651e7118f49059c8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1eba9443113386db54e81de651e7118f49059c8c?/BV=gXH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1eba9443113386db54e81de651e7118f49059c8c?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f7ebf082578381c2e4d298ef70b3282fd4ffbbf4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f7ebf082578381c2e4d298ef70b3282fd4ffbbf4?/hs=jwQ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f7ebf082578381c2e4d298ef70b3282fd4ffbbf4?/tNr
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7c828038ff51d7a5e19eb389b5e6d12f3622755a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7c828038ff51d7a5e19eb389b5e6d12f3622755a?/4o=IJJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7c828038ff51d7a5e19eb389b5e6d12f3622755a?/CgA
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ec6fbc4292df68e36b7137167717d511536d368
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ec6fbc4292df68e36b7137167717d511536d368?/Rm=Sq6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0ec6fbc4292df68e36b7137167717d511536d368?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f0bba5011337a185046c27bb4e32c552ec28aba
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f0bba5011337a185046c27bb4e32c552ec28aba?/BR=yZG
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7f0bba5011337a185046c27bb4e32c552ec28aba?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ddd480c542bc30bc3b20627099cdcf73635fca05
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ddd480c542bc30bc3b20627099cdcf73635fca05?/FI=wDH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ddd480c542bc30bc3b20627099cdcf73635fca05?/Z3X
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b37ff975ea8bdc33616bbc0d5f3201d1d8b8fdbd
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b37ff975ea8bdc33616bbc0d5f3201d1d8b8fdbd?/8J=ANK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b37ff975ea8bdc33616bbc0d5f3201d1d8b8fdbd?/qKo
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/15ce17f1707856043b80793d2bff0cf21529854d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/15ce17f1707856043b80793d2bff0cf21529854d?/6x=A7Y
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/15ce17f1707856043b80793d2bff0cf21529854d?/7b5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/54994c4225094d9c1fbf597627323a2c3c3b5e35
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/54994c4225094d9c1fbf597627323a2c3c3b5e35?/Ao=8lZ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/54994c4225094d9c1fbf597627323a2c3c3b5e35?/OsM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a284731d0e0d8fb782f25778b31aecd1636bc85
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a284731d0e0d8fb782f25778b31aecd1636bc85?/2G=D7y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a284731d0e0d8fb782f25778b31aecd1636bc85?/hBf
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e91c4282cbc251da624786c595e6e925e381ad4c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e91c4282cbc251da624786c595e6e925e381ad4c?/xo=1yP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e91c4282cbc251da624786c595e6e925e381ad4c?/ySw
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6a432cd7f88ca405b0b6330a1ac5031e12e9639f
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6a432cd7f88ca405b0b6330a1ac5031e12e9639f?/xX=iYm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6a432cd7f88ca405b0b6330a1ac5031e12e9639f?/lFj
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07723732b32a6b758c78f175decb71533a64faaf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07723732b32a6b758c78f175decb71533a64faaf?/ZW=Qku
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/07723732b32a6b758c78f175decb71533a64faaf?/0Uy
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5a7e5e06d934dd32c7e585e9a7612dd0367a115f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5a7e5e06d934dd32c7e585e9a7612dd0367a115f?/F2=gxX
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5a7e5e06d934dd32c7e585e9a7612dd0367a115f?/nHl
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8437b3f8a177377a0018c7a45a30ab3eafad7c75
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8437b3f8a177377a0018c7a45a30ab3eafad7c75?/OZ=Pda
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8437b3f8a177377a0018c7a45a30ab3eafad7c75?/a4Y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac47f2733c1485fe5a758d8a1288a04c999f8cd0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac47f2733c1485fe5a758d8a1288a04c999f8cd0?/gN=HcJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ac47f2733c1485fe5a758d8a1288a04c999f8cd0?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ea7871d35f6fcafaa3a26466a75d0750a11063fc
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ea7871d35f6fcafaa3a26466a75d0750a11063fc?/Fg=ZNU
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ea7871d35f6fcafaa3a26466a75d0750a11063fc?/ge8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6eb13989054c9ed66b9a7dbbdce54cf50a456312
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6eb13989054c9ed66b9a7dbbdce54cf50a456312?/20=xrB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6eb13989054c9ed66b9a7dbbdce54cf50a456312?/RvP
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f39a41527ec3f55773a00174f362822f7118a9c5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f39a41527ec3f55773a00174f362822f7118a9c5?/wW=hXl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f39a41527ec3f55773a00174f362822f7118a9c5?/kEi
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c0d0a7c4b5f03f0f94a10d1a8da5f76a37318052
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c0d0a7c4b5f03f0f94a10d1a8da5f76a37318052?/uh=Izt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c0d0a7c4b5f03f0f94a10d1a8da5f76a37318052?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/79bc641f074091dda838ac723117244c4d4bd9ad
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/79bc641f074091dda838ac723117244c4d4bd9ad?/nB=Rz6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/79bc641f074091dda838ac723117244c4d4bd9ad?/ImG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ecf3695d44984c1753c4ac7449e84fe377b810f
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ecf3695d44984c1753c4ac7449e84fe377b810f?/Mw=A71
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ecf3695d44984c1753c4ac7449e84fe377b810f?/7b5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c767c3576181a1e1dfc0c6191ee9d4bb3aceeef6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c767c3576181a1e1dfc0c6191ee9d4bb3aceeef6?/Fw=qdl
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c767c3576181a1e1dfc0c6191ee9d4bb3aceeef6?/QuO
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a49dd5a7d7207c7b1a767a7383c42873cd2fb4e3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a49dd5a7d7207c7b1a767a7383c42873cd2fb4e3?/tw=4Ks
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a49dd5a7d7207c7b1a767a7383c42873cd2fb4e3?/hBf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6bdb35f3a73254eaf9efde8ea1039a1c5a5a3529
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6bdb35f3a73254eaf9efde8ea1039a1c5a5a3529?/uh=o5c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6bdb35f3a73254eaf9efde8ea1039a1c5a5a3529?/ySw
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9397aab88a28884d4504d2c05c83aa609a2686db
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9397aab88a28884d4504d2c05c83aa609a2686db?/Ow=3GD
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9397aab88a28884d4504d2c05c83aa609a2686db?/jDh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c869386abf66c2d76c2d36e0d3d3ae75be583912
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c869386abf66c2d76c2d36e0d3d3ae75be583912?/3t=7Xv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c869386abf66c2d76c2d36e0d3d3ae75be583912?/a4Y
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83584dbb53b5ea481ce6466f33465d0618ddd1f6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83584dbb53b5ea481ce6466f33465d0618ddd1f6?/Xb=E2c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83584dbb53b5ea481ce6466f33465d0618ddd1f6?/pJn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84f564161a1decae86d128b0fb4286ae9559f74e
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84f564161a1decae86d128b0fb4286ae9559f74e?/ry=FmM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84f564161a1decae86d128b0fb4286ae9559f74e?/c6a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/486f4d60ffe481c46c92fff1f1ffede7aa0e76a1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/486f4d60ffe481c46c92fff1f1ffede7aa0e76a1?/a8=iPq
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/486f4d60ffe481c46c92fff1f1ffede7aa0e76a1?/tNr
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/762b3e06906be0fe6e554b3aa3f22b19ff8a54d0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/762b3e06906be0fe6e554b3aa3f22b19ff8a54d0?/Oz=f3K
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/762b3e06906be0fe6e554b3aa3f22b19ff8a54d0?/gAe
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e56ca1434bd51aa96178d36d9d0620473a2807dd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e56ca1434bd51aa96178d36d9d0620473a2807dd?/N7=88g
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e56ca1434bd51aa96178d36d9d0620473a2807dd?/VzT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2855e46d6fc3b14b07f652176aece5a46a558984
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2855e46d6fc3b14b07f652176aece5a46a558984?/Yj=ank
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2855e46d6fc3b14b07f652176aece5a46a558984?/GkE
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8820adb947be1606981a69e9828390cfc10e3835
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8820adb947be1606981a69e9828390cfc10e3835?/P9=AhH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8820adb947be1606981a69e9828390cfc10e3835?/X1V
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e61dafbb4117854d6c791370a1944f4086225f0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e61dafbb4117854d6c791370a1944f4086225f0?/BP=qjX
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e61dafbb4117854d6c791370a1944f4086225f0?/MqK
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cff39728eff96373a19d9d825ff635e9d59d82f5
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时54分34秒
