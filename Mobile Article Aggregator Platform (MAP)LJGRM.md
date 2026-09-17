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

gitlab.com/EHWGW/fxleljy/-/blob/main/2026%20%E7%A7%91%E6%99%AE%E6%9A%97%E8%83%BD%E9%87%8F%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E7%99%BB3-%E9%92%9B%E5%AA%92%E4%BD%93%E7%A4%BE%E5%8C%BA.md?/844=549
<br>
gitlab.com/EHWGW/fxleljy/-/commit/141a727bb595a9d9abdd7979cb7b89442458a5d0?/xX=iZm
<br>
gitlab.com/EHWGW/fxleljy/-/blob/main/2026%20%E7%A7%91%E6%99%AE%E6%9A%97%E8%83%BD%E9%87%8F%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB2%E7%99%BB3-%E9%92%9B%E5%AA%92%E4%BD%93%E7%A4%BE%E5%8C%BA.md?/jA1
<br>
gitlab.com/EHWGW/fxleljy/-/commit/141a727bb595a9d9abdd7979cb7b89442458a5d0?/lFj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dd251fef5882d2d77c8ea4dc637327e35d2da6c9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dd251fef5882d2d77c8ea4dc637327e35d2da6c9?/Zz=M77
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dd251fef5882d2d77c8ea4dc637327e35d2da6c9?/0Uy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/499e0665359f0ce0cffdf90f4cb17dc461fa5695
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/499e0665359f0ce0cffdf90f4cb17dc461fa5695?/WW=3do
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/499e0665359f0ce0cffdf90f4cb17dc461fa5695?/NrL
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c54162f5511fe0824af4c390dccdce6afff3c0b3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c54162f5511fe0824af4c390dccdce6afff3c0b3?/XK=vcV
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c54162f5511fe0824af4c390dccdce6afff3c0b3?/e8c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ad1b6975855608240fab6cb835eb6661c92995ac
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ad1b6975855608240fab6cb835eb6661c92995ac?/I5=gNH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ad1b6975855608240fab6cb835eb6661c92995ac?/NrL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e7ef7356df194ddbe570230fb2185820ed3e01f4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e7ef7356df194ddbe570230fb2185820ed3e01f4?/GG=HoO
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e7ef7356df194ddbe570230fb2185820ed3e01f4?/e8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a1a7db473649f702c5433665007b6cea45b83424
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a1a7db473649f702c5433665007b6cea45b83424?/Oe=BmT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/a1a7db473649f702c5433665007b6cea45b83424?/1Vz
<br>
gitlab.com/EHWGW/fxleljy/-/commit/433bf8b560ce5f0d4c8ff84ef73998b36e9c3ad7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/433bf8b560ce5f0d4c8ff84ef73998b36e9c3ad7?/4i=W9u
<br>
gitlab.com/EHWGW/fxleljy/-/commit/433bf8b560ce5f0d4c8ff84ef73998b36e9c3ad7?/GkE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b156c1f5760cf51226a8f634545c67eea94a358c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b156c1f5760cf51226a8f634545c67eea94a358c?/sZ=Tny
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b156c1f5760cf51226a8f634545c67eea94a358c?/X1V
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a14f5531eeaf7791a4828c48b464f436f9503f26
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a14f5531eeaf7791a4828c48b464f436f9503f26?/sm=6Ga
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a14f5531eeaf7791a4828c48b464f436f9503f26?/KoI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d761b5a734ee82653f6787ea456e9812ba6bb188
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d761b5a734ee82653f6787ea456e9812ba6bb188?/II=pPa
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d761b5a734ee82653f6787ea456e9812ba6bb188?/9d7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed4de12340aadfce592246d836379a16da7b19a3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed4de12340aadfce592246d836379a16da7b19a3?/L9=jQK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ed4de12340aadfce592246d836379a16da7b19a3?/Qus
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e1cf15e015904c64a60a64fe9394c8e1cc783304
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e1cf15e015904c64a60a64fe9394c8e1cc783304?/Ow=WDe
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e1cf15e015904c64a60a64fe9394c8e1cc783304?/DhB
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3094373ba2d2fe5f86cddc05c08defce57d04d1c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3094373ba2d2fe5f86cddc05c08defce57d04d1c?/DK=Y1y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3094373ba2d2fe5f86cddc05c08defce57d04d1c?/UyS
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de56df185267be183c79e9e4679de344dfb0c602
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de56df185267be183c79e9e4679de344dfb0c602?/7K=HC2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de56df185267be183c79e9e4679de344dfb0c602?/lFj
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0eff09a09fd50ef900ff2043508888f9c0042735
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0eff09a09fd50ef900ff2043508888f9c0042735?/ls=52T
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0eff09a09fd50ef900ff2043508888f9c0042735?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ec6b72be5f7e1dc72f37427c2018c56c1dbdaaff
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ec6b72be5f7e1dc72f37427c2018c56c1dbdaaff?/KB=OLm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/ec6b72be5f7e1dc72f37427c2018c56c1dbdaaff?/LpJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/758ecfe2cd6db936c6e9ee21a4634ccc0666c416
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/758ecfe2cd6db936c6e9ee21a4634ccc0666c416?/x7=UFF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/758ecfe2cd6db936c6e9ee21a4634ccc0666c416?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/432e26b842b6509a7f30920e00b1c5023c4006a3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/432e26b842b6509a7f30920e00b1c5023c4006a3?/nX=YY5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/432e26b842b6509a7f30920e00b1c5023c4006a3?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f0092557f518b13e89d86ade5c888f0aebfc9182
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f0092557f518b13e89d86ade5c888f0aebfc9182?/qn=E8S
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f0092557f518b13e89d86ade5c888f0aebfc9182?/kEi
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fccaa5874ab295f679756cd268c855c57ac603bb
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fccaa5874ab295f679756cd268c855c57ac603bb?/aX=SmT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fccaa5874ab295f679756cd268c855c57ac603bb?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6ff6bd6c942a8698a0ef866b10274531f782baa9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6ff6bd6c942a8698a0ef866b10274531f782baa9?/bI=CW9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6ff6bd6c942a8698a0ef866b10274531f782baa9?/ImG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/308bfc5154b3d4f5f46fbb497d5aebd6cc1ee209
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/308bfc5154b3d4f5f46fbb497d5aebd6cc1ee209?/El=M3w
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/308bfc5154b3d4f5f46fbb497d5aebd6cc1ee209?/Z3X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b9a777a3bfd191c5e9e7f7978934dc9b828e49c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b9a777a3bfd191c5e9e7f7978934dc9b828e49c?/FV=3Au
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1b9a777a3bfd191c5e9e7f7978934dc9b828e49c?/qKo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e94bcd9321412d4aa0a91e44e0e67327bb86f49
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e94bcd9321412d4aa0a91e44e0e67327bb86f49?/wd=XrU
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7e94bcd9321412d4aa0a91e44e0e67327bb86f49?/7b5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/19c103258c45f4a4e3449bf9d498f373e91deea1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/19c103258c45f4a4e3449bf9d498f373e91deea1?/Ux=vLj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/19c103258c45f4a4e3449bf9d498f373e91deea1?/OsM
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4477f7690ad7618f3de7a46c5a882017b048fbc0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4477f7690ad7618f3de7a46c5a882017b048fbc0?/6N=x8z
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/4477f7690ad7618f3de7a46c5a882017b048fbc0?/Bfd
<br>
gitlab.com/EHWGW/fxleljy/-/commit/86d13b506042bf1b17e27b7880267d3795d4ce08
<br>
gitlab.com/EHWGW/fxleljy/-/commit/86d13b506042bf1b17e27b7880267d3795d4ce08?/Hy=sCM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/86d13b506042bf1b17e27b7880267d3795d4ce08?/SwQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/80a803947623112b9b2fe230dd7965bbec66fa29
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/80a803947623112b9b2fe230dd7965bbec66fa29?/G7=KHi
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/80a803947623112b9b2fe230dd7965bbec66fa29?/HlF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc62c52f5016e02cf9532830252536bf1cd8ec61
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc62c52f5016e02cf9532830252536bf1cd8ec61?/nN=4yI
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc62c52f5016e02cf9532830252536bf1cd8ec61?/Y2W
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc84c7dbfc6bf2427cc8dc64496e650f935c5132
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc84c7dbfc6bf2427cc8dc64496e650f935c5132?/Gk=EiC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc84c7dbfc6bf2427cc8dc64496e650f935c5132?/c6a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ec31c30a697fd6930998f4c0c39d0341ade145af
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ec31c30a697fd6930998f4c0c39d0341ade145af?/Bb=yij
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ec31c30a697fd6930998f4c0c39d0341ade145af?/8c6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e2f69e6be714b473f1ec490e41f729511ec4e74d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e2f69e6be714b473f1ec490e41f729511ec4e74d?/dh=K8i
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e2f69e6be714b473f1ec490e41f729511ec4e74d?/RvP
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b8ddd54d109e5c95d96166910f552864af923256
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b8ddd54d109e5c95d96166910f552864af923256?/Ls=TA3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b8ddd54d109e5c95d96166910f552864af923256?/CgA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1587c70f7de4dacc5d49d962f4e51798b8035c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1587c70f7de4dacc5d49d962f4e51798b8035c?/YW=xrB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1587c70f7de4dacc5d49d962f4e51798b8035c?/TxR
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e3ab1f56b7d966e1385ba1101d99f8bf73b05234
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e3ab1f56b7d966e1385ba1101d99f8bf73b05234?/R1=idT
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e3ab1f56b7d966e1385ba1101d99f8bf73b05234?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/129bae16fde61930533fd706c1aa4b480bb5f29e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/129bae16fde61930533fd706c1aa4b480bb5f29e?/5z=JxH
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/129bae16fde61930533fd706c1aa4b480bb5f29e?/Z3X
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6cb8f2dbea425d7028dad92ddcda011f2fff762
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6cb8f2dbea425d7028dad92ddcda011f2fff762?/wt=KEY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6cb8f2dbea425d7028dad92ddcda011f2fff762?/KoI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2df1557d47b4af17083d484415fa6175a71a5860
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2df1557d47b4af17083d484415fa6175a71a5860?/HK=SiG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2df1557d47b4af17083d484415fa6175a71a5860?/5Z3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a1477ffd1723cb40ec25181f8d1cf17f6b1d918
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a1477ffd1723cb40ec25181f8d1cf17f6b1d918?/UV=V3d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a1477ffd1723cb40ec25181f8d1cf17f6b1d918?/qKo
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ac92452eb5b6b6be4691f2b84ee19d44f70583d7
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ac92452eb5b6b6be4691f2b84ee19d44f70583d7?/kb=pIG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ac92452eb5b6b6be4691f2b84ee19d44f70583d7?/lFj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/69bf082877d0cdbc7b693d66d89cd9c03787b13d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/69bf082877d0cdbc7b693d66d89cd9c03787b13d?/cZ=0uE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/69bf082877d0cdbc7b693d66d89cd9c03787b13d?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/64308c232b6f819c7e14fba24e9a50255fb9a52e
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/64308c232b6f819c7e14fba24e9a50255fb9a52e?/7s=PT6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/64308c232b6f819c7e14fba24e9a50255fb9a52e?/FjD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a886b45e78997299120e22d501fac48c0603f75
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a886b45e78997299120e22d501fac48c0603f75?/fD=KY1
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9a886b45e78997299120e22d501fac48c0603f75?/0Uy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37c7a308a0d0877e1db328c395abac301d1e61e6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37c7a308a0d0877e1db328c395abac301d1e61e6?/No=esJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37c7a308a0d0877e1db328c395abac301d1e61e6?/rLp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e27e42938518b9e5c0deddfa1b338875a2f9f20d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e27e42938518b9e5c0deddfa1b338875a2f9f20d?/LS=Dko
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e27e42938518b9e5c0deddfa1b338875a2f9f20d?/6a4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5dca1c5107f6f233cae547a6fc8b42351e81b333
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5dca1c5107f6f233cae547a6fc8b42351e81b333?/W4=eLm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5dca1c5107f6f233cae547a6fc8b42351e81b333?/LpJ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a5b3f030d627025a21f1c29e1db5cd0e2af75183
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a5b3f030d627025a21f1c29e1db5cd0e2af75183?/qu=4OZ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/a5b3f030d627025a21f1c29e1db5cd0e2af75183?/8c6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9869b18693d36de36fd0b4eac26e6a50d60ba262
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9869b18693d36de36fd0b4eac26e6a50d60ba262?/kL=Yzt
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9869b18693d36de36fd0b4eac26e6a50d60ba262?/zTx
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c2a75b7b638e1cd4517514e580599ce4393d2407
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c2a75b7b638e1cd4517514e580599ce4393d2407?/8s=MqJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c2a75b7b638e1cd4517514e580599ce4393d2407?/ImG
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5ccf41d68c6f3ef261e868419c167683bd787466
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5ccf41d68c6f3ef261e868419c167683bd787466?/AB=mSq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/5ccf41d68c6f3ef261e868419c167683bd787466?/VzT
<br>
gitlab.com/EHWGW/fxleljy/-/commit/247e86ac2e31abea43b5b81007ced9acbf7ec75d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/247e86ac2e31abea43b5b81007ced9acbf7ec75d?/pm=D4o
<br>
gitlab.com/EHWGW/fxleljy/-/commit/247e86ac2e31abea43b5b81007ced9acbf7ec75d?/kEi
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c4b2c2fca3fa4984c172011983af88a6731d16fe
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c4b2c2fca3fa4984c172011983af88a6731d16fe?/lF=GHo
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c4b2c2fca3fa4984c172011983af88a6731d16fe?/7b5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5a9959dd7ae9bd7292bb7290d8e7283b8dedc5ac
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5a9959dd7ae9bd7292bb7290d8e7283b8dedc5ac?/zQ=KeI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5a9959dd7ae9bd7292bb7290d8e7283b8dedc5ac?/QuO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/116fc6c9cc3b6387d19138720060d785f4c83764
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/116fc6c9cc3b6387d19138720060d785f4c83764?/AY=ps0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/116fc6c9cc3b6387d19138720060d785f4c83764?/fd7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/206023c9457f32ab22d39b2dcea227ea0f25e16d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/206023c9457f32ab22d39b2dcea227ea0f25e16d?/QK=eH5
<br>
gitlab.com/EHWGW/fxleljy/-/commit/206023c9457f32ab22d39b2dcea227ea0f25e16d?/uOs
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e466ef8d035b0635113aa3cb8ba2878014a7b658
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e466ef8d035b0635113aa3cb8ba2878014a7b658?/eu=S2k
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/e466ef8d035b0635113aa3cb8ba2878014a7b658?/FjD
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ce4dac20f4a30ef7ad83d8ed7c5f46df9194a910
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ce4dac20f4a30ef7ad83d8ed7c5f46df9194a910?/1s=53T
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ce4dac20f4a30ef7ad83d8ed7c5f46df9194a910?/2W0
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c042907153389ed6ae2917fc5ba776d97a2cb026
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c042907153389ed6ae2917fc5ba776d97a2cb026?/4C=wTX
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c042907153389ed6ae2917fc5ba776d97a2cb026?/pJn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0be2a7544b9368666971b649ef21c18821c1895a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0be2a7544b9368666971b649ef21c18821c1895a?/nN=4zp
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0be2a7544b9368666971b649ef21c18821c1895a?/Y2W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/15a105c38c9e8f5aae21d69d120b8f1aa542b15a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/15a105c38c9e8f5aae21d69d120b8f1aa542b15a?/go=5cj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/15a105c38c9e8f5aae21d69d120b8f1aa542b15a?/vPt
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/74277e3c538f128b0f09578ad3661a2b057dbdd0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/74277e3c538f128b0f09578ad3661a2b057dbdd0?/lC=6t1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/74277e3c538f128b0f09578ad3661a2b057dbdd0?/gAe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/54333ed38f8b09411b973cbf3a64cd4ec68e9c89
<br>
gitlab.com/EHWGW/fxleljy/-/commit/54333ed38f8b09411b973cbf3a64cd4ec68e9c89?/pZ=3X0
<br>
gitlab.com/EHWGW/fxleljy/-/commit/54333ed38f8b09411b973cbf3a64cd4ec68e9c89?/zTx
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/694c01fde177ea1fc648008b41a95ffe6848bb9d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/694c01fde177ea1fc648008b41a95ffe6848bb9d?/bP=zDe
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/694c01fde177ea1fc648008b41a95ffe6848bb9d?/CgA
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3bdca600a999701a8e9b6b2864cf55614de110dc
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3bdca600a999701a8e9b6b2864cf55614de110dc?/a1=vip
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3bdca600a999701a8e9b6b2864cf55614de110dc?/1Vz
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc65f5a387c47992a7a18f64a3df5fb66670d96e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc65f5a387c47992a7a18f64a3df5fb66670d96e?/lb=Jke
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/bc65f5a387c47992a7a18f64a3df5fb66670d96e?/mGk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/515bbd6dc355a60a9aa6b5a36eb5d2b1f60183af
<br>
gitlab.com/EHWGW/fxleljy/-/commit/515bbd6dc355a60a9aa6b5a36eb5d2b1f60183af?/IP=ca1
<br>
gitlab.com/EHWGW/fxleljy/-/commit/515bbd6dc355a60a9aa6b5a36eb5d2b1f60183af?/Z3X
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be062b7e3324f8d6006334755dca3e85866eeb85
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be062b7e3324f8d6006334755dca3e85866eeb85?/2d=KBS
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be062b7e3324f8d6006334755dca3e85866eeb85?/oIm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e99135c049965dbff7c07f8f770ede6e7efbf257
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e99135c049965dbff7c07f8f770ede6e7efbf257?/Fj=klI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e99135c049965dbff7c07f8f770ede6e7efbf257?/7b5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0df8d355a35d5c8dcb752f44b43f90aa3adc1d70
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0df8d355a35d5c8dcb752f44b43f90aa3adc1d70?/dk=xvM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0df8d355a35d5c8dcb752f44b43f90aa3adc1d70?/OsM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/93ee2516e48060b3b82ab9332bfe1636b2d2fe75
<br>
gitlab.com/EHWGW/fxleljy/-/commit/93ee2516e48060b3b82ab9332bfe1636b2d2fe75?/rS=9Wn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/93ee2516e48060b3b82ab9332bfe1636b2d2fe75?/9d7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82c582e7f3acbe23d08d3f784296d415938b2b71
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82c582e7f3acbe23d08d3f784296d415938b2b71?/8B=p6A
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/82c582e7f3acbe23d08d3f784296d415938b2b71?/SQu
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/21cb9bac003a9c01afe86224ad078d18d16781eb
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/21cb9bac003a9c01afe86224ad078d18d16781eb?/YF=cQ0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/21cb9bac003a9c01afe86224ad078d18d16781eb?/jDh
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c1a0c65da99f86012d439af401578ef6fb87e662
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c1a0c65da99f86012d439af401578ef6fb87e662?/c5=3Tr
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/c1a0c65da99f86012d439af401578ef6fb87e662?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4a53ee47bfabf53b0fe83ee2ffcea56f4b147660
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4a53ee47bfabf53b0fe83ee2ffcea56f4b147660?/St=n7l
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4a53ee47bfabf53b0fe83ee2ffcea56f4b147660?/tNr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc9faed5214942b49a602b0a2eafa7ac2a734a4a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc9faed5214942b49a602b0a2eafa7ac2a734a4a?/kE=FFm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/dc9faed5214942b49a602b0a2eafa7ac2a734a4a?/8c6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e0489e75fb923d5babe1d4c4bccf5f29b52478f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e0489e75fb923d5babe1d4c4bccf5f29b52478f?/oI=mGk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e0489e75fb923d5babe1d4c4bccf5f29b52478f?/gAe
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fd9a09b7fe66644757baaf9a3ed3903b95f23c27
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fd9a09b7fe66644757baaf9a3ed3903b95f23c27?/R8=1pw
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/fd9a09b7fe66644757baaf9a3ed3903b95f23c27?/8c6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b23ffb40c1b2e1d1fdb8ace2120814f01feaf11
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b23ffb40c1b2e1d1fdb8ace2120814f01feaf11?/1z=TxR
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b23ffb40c1b2e1d1fdb8ace2120814f01feaf11?/NrL
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cec1e7b2bb63cf529d452ba6143ae9becb482c4d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cec1e7b2bb63cf529d452ba6143ae9becb482c4d?/Cg=e8c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/cec1e7b2bb63cf529d452ba6143ae9becb482c4d?/Y2W
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f4dc0432f8a40d30791db5a41b9f6b0c1fd296b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f4dc0432f8a40d30791db5a41b9f6b0c1fd296b?/Vp=UK2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f4dc0432f8a40d30791db5a41b9f6b0c1fd296b?/X1V
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/06e0e7379b68f925cde77048487f696393d3af6f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/06e0e7379b68f925cde77048487f696393d3af6f?/AO=rpG
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/06e0e7379b68f925cde77048487f696393d3af6f?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/945f4258ff55b8cfb3bf448b18451eb90ebac2cf
<br>
gitlab.com/EHWGW/fxleljy/-/commit/945f4258ff55b8cfb3bf448b18451eb90ebac2cf?/gX=ki8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/945f4258ff55b8cfb3bf448b18451eb90ebac2cf?/hBf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f3cd263309d9db5dcb7c4df78111ab0deea91ad
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f3cd263309d9db5dcb7c4df78111ab0deea91ad?/77=fFx
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f3cd263309d9db5dcb7c4df78111ab0deea91ad?/SwQ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5d8146eb9b6fcb7a0d6cdd18b17821d743e018b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5d8146eb9b6fcb7a0d6cdd18b17821d743e018b?/sP=0g4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5d8146eb9b6fcb7a0d6cdd18b17821d743e018b?/jDh
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a80bbca523d9b5907745465eaf4849b1711ecbdd
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a80bbca523d9b5907745465eaf4849b1711ecbdd?/RH=ysD
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a80bbca523d9b5907745465eaf4849b1711ecbdd?/SwQ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e4ca22d3bf68150f1afd7545967752be7d357b37
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e4ca22d3bf68150f1afd7545967752be7d357b37?/sI=9Nq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e4ca22d3bf68150f1afd7545967752be7d357b37?/pJn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/676cf5d5d2100816fe5bc4850d386524c7ad2dea
<br>
gitlab.com/EHWGW/fxleljy/-/commit/676cf5d5d2100816fe5bc4850d386524c7ad2dea?/qU=IvC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/676cf5d5d2100816fe5bc4850d386524c7ad2dea?/Y2W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f2c2cc1dec4905aa29f36271341755d152342a2b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f2c2cc1dec4905aa29f36271341755d152342a2b?/zT=xQO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f2c2cc1dec4905aa29f36271341755d152342a2b?/tNr
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6693a14fc77e748a66664b5d0679cf31b52cc2f4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6693a14fc77e748a66664b5d0679cf31b52cc2f4?/Bb=yij
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6693a14fc77e748a66664b5d0679cf31b52cc2f4?/8c6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/40eceb2ef76afb0d4ba1da52c7689e7aae906507
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/40eceb2ef76afb0d4ba1da52c7689e7aae906507?/dh=L8F
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/40eceb2ef76afb0d4ba1da52c7689e7aae906507?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c90fa96f968daea496b7b4377a54000f62262cb2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c90fa96f968daea496b7b4377a54000f62262cb2?/V7=Ov2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c90fa96f968daea496b7b4377a54000f62262cb2?/EiC
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c8d31cd1baa409ece5f1329c79359cb4a75e51a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c8d31cd1baa409ece5f1329c79359cb4a75e51a?/EL=Z20
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9c8d31cd1baa409ece5f1329c79359cb4a75e51a?/VzT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b09e850428308698a7e7da6566d8e3c1bcd978c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b09e850428308698a7e7da6566d8e3c1bcd978c?/Zh=yV6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b09e850428308698a7e7da6566d8e3c1bcd978c?/ImG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/46aa8fcf6e3d69d26e1c1ff0e0620decc655a2f3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/46aa8fcf6e3d69d26e1c1ff0e0620decc655a2f3?/yF=mt6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/46aa8fcf6e3d69d26e1c1ff0e0620decc655a2f3?/5Z3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/08961d89cb656b4d4045db9a8962c52d3facac26
<br>
gitlab.com/EHWGW/fxleljy/-/commit/08961d89cb656b4d4045db9a8962c52d3facac26?/I2=XXY
<br>
gitlab.com/EHWGW/fxleljy/-/commit/08961d89cb656b4d4045db9a8962c52d3facac26?/Qus
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1407ec2cdc06cb9b72023e29145d8e6a5a3722a3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1407ec2cdc06cb9b72023e29145d8e6a5a3722a3?/w4=KsS
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1407ec2cdc06cb9b72023e29145d8e6a5a3722a3?/Bf9
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad09c149b897dec4ae932fe744d589449f899a9
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad09c149b897dec4ae932fe744d589449f899a9?/Iw=jrb
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad09c149b897dec4ae932fe744d589449f899a9?/0Uy
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a9584c897a709a45868779e59c5af5de5687f6e6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a9584c897a709a45868779e59c5af5de5687f6e6?/Zj=4E5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a9584c897a709a45868779e59c5af5de5687f6e6?/HlF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/29a254fa3fe59534feb0168539e9f5d41a6093ef
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

> 外链数量: 350 | 生成时间:2026年09月18日03时50分43秒
