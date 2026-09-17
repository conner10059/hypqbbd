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

gitlab.com/JDJTY/txiqmhb/-/blob/main/2026%E5%AE%98%E6%96%B9%E7%BA%A2%E7%9B%9B%E5%AE%B4:%E7%9A%87%E5%86%A0%E7%99%BB2%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F-%E4%BF%A1%E6%81%92%E8%B4%A2%E7%BB%8F.md?/td7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E9%87%8F%E5%AD%90%E8%AE%A1%E7%AE%97:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F-%E5%B8%A6%E5%AE%BD%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E9%87%8F%E5%AD%90%E8%AE%A1%E7%AE%97:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F-%E5%B8%A6%E5%AE%BD%E8%AE%BA%E5%9D%9B.md?/396=103
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2026%E5%AE%98%E6%96%B9%E6%96%B0%E9%87%8F%E5%AD%90%E8%AE%A1%E7%AE%97:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F-%E5%B8%A6%E5%AE%BD%E8%AE%BA%E5%9D%9B.md?/Llc
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E6%B0%A2%E8%83%BD%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E5%87%BA%E7%A7%9F-%E6%90%9C%E6%88%BF%E7%BD%91%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E6%B0%A2%E8%83%BD%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E5%87%BA%E7%A7%9F-%E6%90%9C%E6%88%BF%E7%BD%91%E8%AE%BA%E5%9D%9B.md?/362=285
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/2026%E6%B0%A2%E8%83%BD%E7%83%AD%E6%90%9C%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E5%87%BA%E7%A7%9F-%E6%90%9C%E6%88%BF%E7%BD%91%E8%AE%BA%E5%9D%9B.md?/Bf9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%94%9F%E6%88%90AI%E7%88%86%E6%96%99%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E5%87%BA%E7%A7%9F-%E5%A4%A7%E8%BF%9E%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%94%9F%E6%88%90AI%E7%88%86%E6%96%99%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E5%87%BA%E7%A7%9F-%E5%A4%A7%E8%BF%9E%E8%AE%BA%E5%9D%9B.md?/864=204
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E7%94%9F%E6%88%90AI%E7%88%86%E6%96%99%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E5%87%BA%E7%A7%9F-%E5%A4%A7%E8%BF%9E%E8%AE%BA%E5%9D%9B.md?/mW0
<br>
gitlab.com/JDJTY/txiqmhb/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%9B%9B%E5%AE%B4%E5%BC%80:%E7%9A%87%E5%86%A0%E7%99%BB1%E5%87%BA%E7%A7%9F-%E8%B9%A6%E6%9E%81%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/JDJTY/txiqmhb/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%9B%9B%E5%AE%B4%E5%BC%80:%E7%9A%87%E5%86%A0%E7%99%BB1%E5%87%BA%E7%A7%9F-%E8%B9%A6%E6%9E%81%E8%AE%BA%E5%9D%9B.md?/147=624
<br>
gitlab.com/JDJTY/txiqmhb/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%9B%9B%E5%AE%B4%E5%BC%80:%E7%9A%87%E5%86%A0%E7%99%BB1%E5%87%BA%E7%A7%9F-%E8%B9%A6%E6%9E%81%E8%AE%BA%E5%9D%9B.md?/7u1
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/%E7%8E%A9%E5%AE%B6%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C:%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E7%BD%91-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/%E7%8E%A9%E5%AE%B6%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C:%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E7%BD%91-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md?/518=391
<br>
gitlab.com/JHEJHR/auhkgvk/-/blob/main/%E7%8E%A9%E5%AE%B6%E7%AC%AC%E4%B8%80%E7%BB%8F%E9%AA%8C:%E6%96%B02%E5%B9%B3%E5%8F%B0%E5%87%BA%E7%A7%9F%E7%BD%91-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E7%BE%8E%E5%A6%86%E6%9D%BF%E5%9D%97.md?/BI2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%A1%AC%E5%AD%A6%E5%A0%82:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%87%BA%E7%A7%9F-%E6%B0%B4%E5%BD%A9%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%A1%AC%E5%AD%A6%E5%A0%82:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%87%BA%E7%A7%9F-%E6%B0%B4%E5%BD%A9%E8%AE%BA%E5%9D%9B.md?/877=043
<br>
gitlab.com/qwAREGTH/lesqxqz/-/blob/main/2027%E5%AE%98%E6%96%B9%E7%A1%AC%E5%AD%A6%E5%A0%82:%E7%9A%87%E5%86%A0%E7%99%BB0%E5%87%BA%E7%A7%9F-%E6%B0%B4%E5%BD%A9%E8%AE%BA%E5%9D%9B.md?/QXH
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/blob/main/2026%E4%B8%93%E6%A0%8F%E7%A7%92%E6%87%82%E5%88%86%E6%9E%90%EF%BC%9A%E6%96%B02%E5%87%BA%E7%A7%9F-ZBrush%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fdfe2509c443f4756761297a648f1eb787595328?/PW=mJu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fdfe2509c443f4756761297a648f1eb787595328?/9d7
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dc528a42cab77af914b13400b47971b9c436e3c2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dc528a42cab77af914b13400b47971b9c436e3c2?/mW=0Ux
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dc528a42cab77af914b13400b47971b9c436e3c2?/wQu
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a21b0741e66dbbb94416b69ecc21196043df12a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a21b0741e66dbbb94416b69ecc21196043df12a?/PZ=QAe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1a21b0741e66dbbb94416b69ecc21196043df12a?/a4Y
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/294f7c9bac3e7cdbbf052f93e942aa716d836a08
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/294f7c9bac3e7cdbbf052f93e942aa716d836a08?/RO=JDX
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/294f7c9bac3e7cdbbf052f93e942aa716d836a08?/pJn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/626a71c67e2de200c99f9605d65dff675a6560ca
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/626a71c67e2de200c99f9605d65dff675a6560ca?/6T=DEl
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/626a71c67e2de200c99f9605d65dff675a6560ca?/a4Y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b45cf7402f063a6c9e5d4f5c86cf95caac6bd522
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b45cf7402f063a6c9e5d4f5c86cf95caac6bd522?/VP=jNA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b45cf7402f063a6c9e5d4f5c86cf95caac6bd522?/zTx
<br>
gitlab.com/EHWGW/fxleljy/-/commit/45de1801e4e3b35bc04ff980259b7284258cfafb
<br>
gitlab.com/EHWGW/fxleljy/-/commit/45de1801e4e3b35bc04ff980259b7284258cfafb?/0b=oF9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/45de1801e4e3b35bc04ff980259b7284258cfafb?/HlF
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c057566651966e55829d1d2b16ccc972d24afb9e
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c057566651966e55829d1d2b16ccc972d24afb9e?/jq=a7B
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c057566651966e55829d1d2b16ccc972d24afb9e?/TRv
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cc7cb6efe6da4a5a86ed95676ba91eaf6525d83f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cc7cb6efe6da4a5a86ed95676ba91eaf6525d83f?/ol=C6Q
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cc7cb6efe6da4a5a86ed95676ba91eaf6525d83f?/iCg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f1a415b86149fe33fd7a41ef0d5225a703416af2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f1a415b86149fe33fd7a41ef0d5225a703416af2?/wm=UOE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f1a415b86149fe33fd7a41ef0d5225a703416af2?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7c4145d9cf4175a5ca3faae80870476efa9ed97
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7c4145d9cf4175a5ca3faae80870476efa9ed97?/SP=qk4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a7c4145d9cf4175a5ca3faae80870476efa9ed97?/MqK
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a9f94a05850d5d8dbb70801bd4d30e494626782
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a9f94a05850d5d8dbb70801bd4d30e494626782?/Qa=RBf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a9f94a05850d5d8dbb70801bd4d30e494626782?/b5Z
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b0ab174c99adfeb92085cc410e97f13f5ca3d0e0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b0ab174c99adfeb92085cc410e97f13f5ca3d0e0?/6D=xUY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b0ab174c99adfeb92085cc410e97f13f5ca3d0e0?/qKo
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c4b114e91746217658a085483c9530464bfdcb1a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c4b114e91746217658a085483c9530464bfdcb1a?/nO=YPd
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c4b114e91746217658a085483c9530464bfdcb1a?/b5Z
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5d697433935596c18b618ed8edadad79dffb1636
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5d697433935596c18b618ed8edadad79dffb1636?/pD=xyV
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5d697433935596c18b618ed8edadad79dffb1636?/KoI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e6e6f3fd66fbfe6c112415714772304838635a40
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e6e6f3fd66fbfe6c112415714772304838635a40?/2C=3nH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e6e6f3fd66fbfe6c112415714772304838635a40?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a04b8ee8b3dafbf3bf2b75ce91cbdfd34449ab2a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a04b8ee8b3dafbf3bf2b75ce91cbdfd34449ab2a?/ip=Z6A
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a04b8ee8b3dafbf3bf2b75ce91cbdfd34449ab2a?/SwQ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1bd7033910dc861027ef9478c71e4fd98ec87642
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1bd7033910dc861027ef9478c71e4fd98ec87642?/JG=hbv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1bd7033910dc861027ef9478c71e4fd98ec87642?/DhB
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ebad6257d15dea5416db64999140ab347a08a1f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ebad6257d15dea5416db64999140ab347a08a1f?/uO=sMq
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0ebad6257d15dea5416db64999140ab347a08a1f?/GkE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9d1897cbf9867ee5a3e12c78a6b9605fc68cbed8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9d1897cbf9867ee5a3e12c78a6b9605fc68cbed8?/wW=EeV
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/9d1897cbf9867ee5a3e12c78a6b9605fc68cbed8?/hBf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e9d245348946171c05e926e31673d9c39d08372c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e9d245348946171c05e926e31673d9c39d08372c?/Cd=4yI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e9d245348946171c05e926e31673d9c39d08372c?/a4Y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1852c1ae2ccee59226a7ca3f03eabdeaa15b1b77
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1852c1ae2ccee59226a7ca3f03eabdeaa15b1b77?/rF=29M
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1852c1ae2ccee59226a7ca3f03eabdeaa15b1b77?/LpJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e83551633a5ea0a70924de3aa8547d9b23e4bf41
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e83551633a5ea0a70924de3aa8547d9b23e4bf41?/3u=7Yv
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e83551633a5ea0a70924de3aa8547d9b23e4bf41?/a4Y
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/65a1d032a2257c2a296313cdc13e45c32cb22a78
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/65a1d032a2257c2a296313cdc13e45c32cb22a78?/4f=sJD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/65a1d032a2257c2a296313cdc13e45c32cb22a78?/LpJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/28442aa66df9333b36b2da9508d19b2390ecd2fa
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/28442aa66df9333b36b2da9508d19b2390ecd2fa?/SD=Dko
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/28442aa66df9333b36b2da9508d19b2390ecd2fa?/6a4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/edd145c90d142369d64f78a9f5def76a4f4ea330
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/edd145c90d142369d64f78a9f5def76a4f4ea330?/lP=Dq7
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/edd145c90d142369d64f78a9f5def76a4f4ea330?/TxR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2d9480d4a17bdc2b36389477881a0db018405105
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2d9480d4a17bdc2b36389477881a0db018405105?/Zj=aKo
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2d9480d4a17bdc2b36389477881a0db018405105?/EiC
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/532341cc3ed6b4f0abc4a0da675429fd4bb208b0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/532341cc3ed6b4f0abc4a0da675429fd4bb208b0?/pZ=3X0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/532341cc3ed6b4f0abc4a0da675429fd4bb208b0?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d67fe24e46f14995673d5c17b10c9baf6204acf8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d67fe24e46f14995673d5c17b10c9baf6204acf8?/nk=eSc
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d67fe24e46f14995673d5c17b10c9baf6204acf8?/iCg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f497c3408800e607b3f0140712c2b627af301b16
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f497c3408800e607b3f0140712c2b627af301b16?/lO=fjt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f497c3408800e607b3f0140712c2b627af301b16?/zTx
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/92fff455100a5ac08e01b1724d2a6f6e76133ded
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/92fff455100a5ac08e01b1724d2a6f6e76133ded?/G4=BRy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/92fff455100a5ac08e01b1724d2a6f6e76133ded?/oIm
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c65c42d4531a520408e33d9a67554061a2367d94
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c65c42d4531a520408e33d9a67554061a2367d94?/u4=vf9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c65c42d4531a520408e33d9a67554061a2367d94?/5Z3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a3ae3788bc112b9970d1de3042aa79ecbd335084
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a3ae3788bc112b9970d1de3042aa79ecbd335084?/ma=DUY
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a3ae3788bc112b9970d1de3042aa79ecbd335084?/KoI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/97e88e41036cae25ded877e1ce30f65541fcd716
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/97e88e41036cae25ded877e1ce30f65541fcd716?/OY=wgh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/97e88e41036cae25ded877e1ce30f65541fcd716?/Z3X
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/840ba26a5f7b02b6b67cc82d2c0ed2c83049a4b4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/840ba26a5f7b02b6b67cc82d2c0ed2c83049a4b4?/qd=DvL
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/840ba26a5f7b02b6b67cc82d2c0ed2c83049a4b4?/uOM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22946c76b17e30183f10c6e41eb2f306c4892d23
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22946c76b17e30183f10c6e41eb2f306c4892d23?/sQ=0h4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/22946c76b17e30183f10c6e41eb2f306c4892d23?/jDh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/84bcc13fc2404d113143c821e830557e0e6500bb
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/84bcc13fc2404d113143c821e830557e0e6500bb?/Al=vmz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/84bcc13fc2404d113143c821e830557e0e6500bb?/ySw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ba7afe7dda5afa815bd7e6bd0e19c7d3a1960c8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ba7afe7dda5afa815bd7e6bd0e19c7d3a1960c8?/nk=B5P
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ba7afe7dda5afa815bd7e6bd0e19c7d3a1960c8?/hBf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2960e0f902181e20b2dcb246c7ee73cd4dc59186
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2960e0f902181e20b2dcb246c7ee73cd4dc59186?/uF=PmX
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2960e0f902181e20b2dcb246c7ee73cd4dc59186?/wuO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4252fddd524ac69b69fc4c41ede8735b396959d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4252fddd524ac69b69fc4c41ede8735b396959d?/fT=6NR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4252fddd524ac69b69fc4c41ede8735b396959d?/jDh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/dbec3fe9e545430664a8f36e97780e004aa319cc
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/dbec3fe9e545430664a8f36e97780e004aa319cc?/t3=ue8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/dbec3fe9e545430664a8f36e97780e004aa319cc?/4Y2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/593245124563662ff37643c998b7f653b5da21ef
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/593245124563662ff37643c998b7f653b5da21ef?/k1=5Fa
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/593245124563662ff37643c998b7f653b5da21ef?/pJn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e5ee209b46e5abb9934e1c96503aa26f3796e6c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e5ee209b46e5abb9934e1c96503aa26f3796e6c?/bS=f60
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e5ee209b46e5abb9934e1c96503aa26f3796e6c?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a5ef45f5c1554066fd012c3a79ebb30d35c6e405
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a5ef45f5c1554066fd012c3a79ebb30d35c6e405?/I2=ZdH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a5ef45f5c1554066fd012c3a79ebb30d35c6e405?/PtN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18b7365bafb13057b7021dd3b08682091bdf2907
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18b7365bafb13057b7021dd3b08682091bdf2907?/t0=Ehf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18b7365bafb13057b7021dd3b08682091bdf2907?/Ae8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d292c58b02564968792a260f7df9e8105e25fc8d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d292c58b02564968792a260f7df9e8105e25fc8d?/q7=Bp9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d292c58b02564968792a260f7df9e8105e25fc8d?/RvP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/aa86c15787c4b9328f91ed2c8986b2193a804fb0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/aa86c15787c4b9328f91ed2c8986b2193a804fb0?/Ko=IJK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/aa86c15787c4b9328f91ed2c8986b2193a804fb0?/CgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b5e047379d090c85d386aed1c83b0a931a19c3a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b5e047379d090c85d386aed1c83b0a931a19c3a?/Na=VPC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7b5e047379d090c85d386aed1c83b0a931a19c3a?/1Vz
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18bd6136f06ee36af67fddd6c8f3f9bd1a340658
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18bd6136f06ee36af67fddd6c8f3f9bd1a340658?/mg=0eR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/18bd6136f06ee36af67fddd6c8f3f9bd1a340658?/GkE
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c18d8c8195e11b91693c85d5aead3b481135249d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c18d8c8195e11b91693c85d5aead3b481135249d?/BF=tgn
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c18d8c8195e11b91693c85d5aead3b481135249d?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b7f4d05076bf4353b5ab2259582b783ac8801a1e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b7f4d05076bf4353b5ab2259582b783ac8801a1e?/Gb=l8t
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b7f4d05076bf4353b5ab2259582b783ac8801a1e?/ImG
<br>
gitlab.com/EHWGW/fxleljy/-/commit/913f3a2dc3c78811a1bb5240ffde8aea29cb03ee
<br>
gitlab.com/EHWGW/fxleljy/-/commit/913f3a2dc3c78811a1bb5240ffde8aea29cb03ee?/RB=fd6
<br>
gitlab.com/EHWGW/fxleljy/-/commit/913f3a2dc3c78811a1bb5240ffde8aea29cb03ee?/5Z3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/50c7501e2df44f628c4f479c6127916ffde62d2d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/50c7501e2df44f628c4f479c6127916ffde62d2d?/JA=NLl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/50c7501e2df44f628c4f479c6127916ffde62d2d?/KoI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/73d3e8122caf80ce0bcf2be43787164a2dec231c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/73d3e8122caf80ce0bcf2be43787164a2dec231c?/XK=wCj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/73d3e8122caf80ce0bcf2be43787164a2dec231c?/5Z3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/890feee63a624ad980ca310de350a0d354a3f43d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/890feee63a624ad980ca310de350a0d354a3f43d?/OI=cm7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/890feee63a624ad980ca310de350a0d354a3f43d?/MqK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/72de776fd52c06faff4503eae9c3d024f63c14b8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/72de776fd52c06faff4503eae9c3d024f63c14b8?/nk=B5P
<br>
gitlab.com/EHWGW/fxleljy/-/commit/72de776fd52c06faff4503eae9c3d024f63c14b8?/Bf9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/139bf1052ab340912927a9ac805f9c23e19f50e8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/139bf1052ab340912927a9ac805f9c23e19f50e8?/5c=DtH
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/139bf1052ab340912927a9ac805f9c23e19f50e8?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9d53280642104ceb99c19c5f621d4706fda8f98f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9d53280642104ceb99c19c5f621d4706fda8f98f?/UB=5PW
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9d53280642104ceb99c19c5f621d4706fda8f98f?/f9d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c333e43eef6b6809f7d05c211ccad2b14ed5632f
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c333e43eef6b6809f7d05c211ccad2b14ed5632f?/HV=vJZ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c333e43eef6b6809f7d05c211ccad2b14ed5632f?/SwQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d90f5746c18f07b42a5176cb562ee0428b9757e8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d90f5746c18f07b42a5176cb562ee0428b9757e8?/R2=j6N
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d90f5746c18f07b42a5176cb562ee0428b9757e8?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0efe25dcca315b51f54e85c156bb2de580f1b381
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0efe25dcca315b51f54e85c156bb2de580f1b381?/oS=GtA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0efe25dcca315b51f54e85c156bb2de580f1b381?/W0U
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b760649dc8003eaae22288f6ed7aaffc460af6b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b760649dc8003eaae22288f6ed7aaffc460af6b?/MJ=DYF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b760649dc8003eaae22288f6ed7aaffc460af6b?/nlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fde98d0f3a029633e446b5b3adbf812a43b8d789
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fde98d0f3a029633e446b5b3adbf812a43b8d789?/kL=VM6
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fde98d0f3a029633e446b5b3adbf812a43b8d789?/2W0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/165dead90a0228f0e3253ce5b4b4be430a98de49
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/165dead90a0228f0e3253ce5b4b4be430a98de49?/do=eLm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/165dead90a0228f0e3253ce5b4b4be430a98de49?/Lpn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c583d2c6f0227c9c37301f721486a7cb1c959812
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c583d2c6f0227c9c37301f721486a7cb1c959812?/5v=9Zx
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c583d2c6f0227c9c37301f721486a7cb1c959812?/c6a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/720c8fdfe1cd66da1d5f7371130115ceaad8b917
<br>
gitlab.com/EHWGW/fxleljy/-/commit/720c8fdfe1cd66da1d5f7371130115ceaad8b917?/pc=k0Y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/720c8fdfe1cd66da1d5f7371130115ceaad8b917?/NrL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/12f735b6c1d46f65496457b23721749e8537ee2f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/12f735b6c1d46f65496457b23721749e8537ee2f?/8S=dTA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/12f735b6c1d46f65496457b23721749e8537ee2f?/gAe
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/082a008c42655a849e9a38509acd7a518041f8ca
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/082a008c42655a849e9a38509acd7a518041f8ca?/mT=NiP
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/082a008c42655a849e9a38509acd7a518041f8ca?/xRv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f622a6d6a3f5f739ca3d49130eafce3b614825f8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f622a6d6a3f5f739ca3d49130eafce3b614825f8?/z6=rOS
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f622a6d6a3f5f739ca3d49130eafce3b614825f8?/kEi
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c17d3bb05659672ea88feab62af15515fb5f3bab
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c17d3bb05659672ea88feab62af15515fb5f3bab?/kr=c9D
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c17d3bb05659672ea88feab62af15515fb5f3bab?/VzT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8167b06d016e8692d0eedb8fd44a404526c5eea3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8167b06d016e8692d0eedb8fd44a404526c5eea3?/C0=duU
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8167b06d016e8692d0eedb8fd44a404526c5eea3?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/281e40dbf771b8653fd0d76246ee18cdc915f866
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/281e40dbf771b8653fd0d76246ee18cdc915f866?/JT=nyo
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/281e40dbf771b8653fd0d76246ee18cdc915f866?/X1V
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/80dd02419545173be4d6b883e8d4c82dcf83f78f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/80dd02419545173be4d6b883e8d4c82dcf83f78f?/V3=dKl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/80dd02419545173be4d6b883e8d4c82dcf83f78f?/KoI
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cd80dbaad2dba69b8ff12600119aa6ca8448c0d8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cd80dbaad2dba69b8ff12600119aa6ca8448c0d8?/CA=bVp
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cd80dbaad2dba69b8ff12600119aa6ca8448c0d8?/7b5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1e60b6d2cf52f6ecd4ac800bb5c7c3d94b758b68
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1e60b6d2cf52f6ecd4ac800bb5c7c3d94b758b68?/Ic=Gak
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1e60b6d2cf52f6ecd4ac800bb5c7c3d94b758b68?/qKo
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6837a2d3a8df46d375c913689f37181afa1f870f
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6837a2d3a8df46d375c913689f37181afa1f870f?/P3=N0o
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6837a2d3a8df46d375c913689f37181afa1f870f?/d7b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/75e1b957c99495d875429337a4e4a6b97f915a61
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/75e1b957c99495d875429337a4e4a6b97f915a61?/KZ=6AK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/75e1b957c99495d875429337a4e4a6b97f915a61?/QuO
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48035bcd68402cf8eb00f0b2b59873d1d412b40b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48035bcd68402cf8eb00f0b2b59873d1d412b40b?/2j=dxa
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/48035bcd68402cf8eb00f0b2b59873d1d412b40b?/jDh
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ff439679e47888b0bbb96e28cefac379e6c1cb10
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ff439679e47888b0bbb96e28cefac379e6c1cb10?/b2=wGt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ff439679e47888b0bbb96e28cefac379e6c1cb10?/W0U
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed9c4949aa7a938daa543eb71aceb1034cf1854d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed9c4949aa7a938daa543eb71aceb1034cf1854d?/AQ=y5p
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed9c4949aa7a938daa543eb71aceb1034cf1854d?/lFj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f914d8a5fa85813fc22575e38184d242c2629032
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f914d8a5fa85813fc22575e38184d242c2629032?/gA=BBj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/f914d8a5fa85813fc22575e38184d242c2629032?/2W0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/24cceabd7d43f0f869ac0e5c95d6c660c9dfeb65
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/24cceabd7d43f0f869ac0e5c95d6c660c9dfeb65?/UU=1bm
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/24cceabd7d43f0f869ac0e5c95d6c660c9dfeb65?/LpJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/07baf5d21ede42bda7260c304e7d23b93f10591d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/07baf5d21ede42bda7260c304e7d23b93f10591d?/0k=EFF
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/07baf5d21ede42bda7260c304e7d23b93f10591d?/86a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e2281148f1b653f0bf8f5f9ecfd7c6e2ccc72520
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e2281148f1b653f0bf8f5f9ecfd7c6e2ccc72520?/FT=wtK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e2281148f1b653f0bf8f5f9ecfd7c6e2ccc72520?/tNr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/adc741df5f3da653bd42dbd248e085c8d78b48b2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/adc741df5f3da653bd42dbd248e085c8d78b48b2?/FC=7xe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/adc741df5f3da653bd42dbd248e085c8d78b48b2?/A8c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0f5537563dc09cfa4849c4c8cffa20a2f3286334
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0f5537563dc09cfa4849c4c8cffa20a2f3286334?/Bl=wnX
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0f5537563dc09cfa4849c4c8cffa20a2f3286334?/TxR
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/778e9112a8e80b1c2a86c044be8a8dd3c17882d2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/778e9112a8e80b1c2a86c044be8a8dd3c17882d2?/Ij=aoH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/778e9112a8e80b1c2a86c044be8a8dd3c17882d2?/GkE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91020c36686d4f86751623377b45f09193f76018
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91020c36686d4f86751623377b45f09193f76018?/N7=88g
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91020c36686d4f86751623377b45f09193f76018?/VzT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8fe899c77e42b6b1c021a06dcb69ab8c79f897cb
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8fe899c77e42b6b1c021a06dcb69ab8c79f897cb?/mf=TaK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8fe899c77e42b6b1c021a06dcb69ab8c79f897cb?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5509a5df1cf9312d9bc9a33816399fea2fd9e050
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5509a5df1cf9312d9bc9a33816399fea2fd9e050?/RB=fgg
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/5509a5df1cf9312d9bc9a33816399fea2fd9e050?/Z3X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3b97d58767192854fcb2c7d7156c8763ecf04a23
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3b97d58767192854fcb2c7d7156c8763ecf04a23?/rF=V3d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3b97d58767192854fcb2c7d7156c8763ecf04a23?/MqK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/96447f3ae707148db6bf0d5f2ae812ebcc9e9b73
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/96447f3ae707148db6bf0d5f2ae812ebcc9e9b73?/wA=bUI
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/96447f3ae707148db6bf0d5f2ae812ebcc9e9b73?/7b5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/aeaa8533d65c09e1912c4bcaf7cade1ace2835d8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/aeaa8533d65c09e1912c4bcaf7cade1ace2835d8?/qA=LiT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/aeaa8533d65c09e1912c4bcaf7cade1ace2835d8?/sMq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0b9d6cd8075a96fe3936fbf096d4d3ffc5db1176
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

> 外链数量: 350 | 生成时间:2026年09月18日03时51分55秒
