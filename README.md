# 👋 你好，我是陈伟俊 (Hi, I'm Weijun Chen)

<p align="left">
  一名对将前沿AI技术（特别是AIGC和RAG）与工程实践相结合充满热情的软件开发者。
  <br>
  我擅长<b>运用AI辅助开发工具</b>，将复杂的想法从0到1高效构建为稳定、可靠的应用程序。
  <br>
  目前正在积极寻求在<b>软件开发 / AI应用工程师</b>相关实习或工作机会。
</p>

---

### 🛠️ 我的技术栈 | My Tech Stack

<table>
  <tr>
    <td align="center"><strong>后端 (Backend)</strong></td>
    <td>
      <img src="https://img-shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
      <img src="https://img-shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
      <img src="https://img-shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img-shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" alt="Spring Security"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>前端 (Frontend)</strong></td>
    <td>
      <img src="https://img-shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue.js"/>
      <img src="https://img-shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
      <img src="https://img-shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img-shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
      <img src="https://img-shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
      <img src="https://img-shields.io/badge/微信小程序-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat Mini Program"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>AI / 数据 (AI / Data)</strong></td>
    <td>
      <img src="https://img-shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
      <img src="https://img-shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API"/>
      <img src="https://img-shields.io/badge/Stable_Diffusion-000000?style=for-the-badge&logo=stabilityai&logoColor=white" alt="Stable Diffusion"/>
      <img src="https://img-shields.io/badge/RAG-blueviolet?style=for-the-badge" alt="RAG"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>数据库 (Database)</strong></td>
    <td>
      <img src="https://img-shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
      <img src="https://img-shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
      <img src="https://img-shields.io/badge/ChromaDB-6A0DAD?style=for-the-badge" alt="ChromaDB"/>
    </td>
  </tr>
  <tr>
    <td align="center"><strong>工具 / 其他 (Tools / Others)</strong></td>
    <td>
      <img src="https://img-shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img-shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
      <img src="https://img-shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
      <img src="https://img-shields.io/badge/HarmonyOS-000000?style=for-the-badge&logo=harmonyos&logoColor=white" alt="HarmonyOS"/>
    </td>
  </tr>
</table>

---

### 🚀 我的精选项目 | Featured Projects

<table>
  <thead>
    <tr>
      <th width="50%">项目</th>
      <th>简介 & 核心贡献</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="[你的WikiUp项目仓库链接]"><strong>WikiUp: 基于RAG的企业级智能知识库平台</strong></a>
        <br><br>
        <!-- 在这里添加项目截图 <img src="URL"> -->
        <br><br>
        <strong>技术栈:</strong> <code>Java</code> <code>Spring Boot</code> <code>Spring Security</code> <code>Vue.js</code> <code>WebSocket</code> <code>Docker</code> <code>Redis</code> <code>DJL/PyTorch</code>
      </td>
      <td>
        一个面向企业的、基于RAG架构的智能问答平台，实现Markdown文档的自动化处理、向量化及动态更新。
        <ul>
          <li><strong>主导架构与AI协同开发:</strong> 负责项目的整体架构设计，确定RAG核心链路。借助AI工具高效生成了模块基础代码，并由我进行<b>代码审查、重构与性能调优</b>，利用<code>CompletableFuture</code>将知识库加载效率提升了约<b>300%</b>。</li>
          <li><strong>关键模块攻坚:</strong> 主导了WebSocket技术选型以解决实时通信需求。通过<b>精准的提示词工程引导AI生成流式响应的核心逻辑</b>，并独立完成后续的<b>调试与集成</b>，将首次响应时间从~8秒缩短至<b>1秒内</b>。</li>
          <li><strong>系统集成与部署:</strong> 主导了基于<code>Spring Security</code>与<code>JWT</code>的安全体系集成，并独立编写优化的多阶段<code>Dockerfile</code>，通过<code>Docker Compose</code>实现应用栈的<b>一键部署</b>。</li>
        </ul>
        <a href="[你的WikiUp项目仓库链接]"><strong>➡️ 查看代码</strong></a> | <a href="[你的WikiUp项目在线演示链接]"><strong>🚀 在线演示</strong></a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="[你的个人知识管理项目仓库链接]"><strong>基于AI的个人知识管理桌面应用</strong></a>
        <br><br>
        <!-- 在这里添加项目截图 <img src="URL"> -->
        <br><br>
        <strong>技术栈:</strong> <code>Python</code> <code>PySide6 (Qt)</code> <code>LLM API</code> <code>BeautifulSoup</code> <code>Jinja2</code>
      </td>
      <td>
        一款桌面端知识管理工具，旨在将分散的在线学习内容自动化整合为可离线检索的本地知识库。
        <ul>
          <li><strong>E2E自动化流程设计:</strong> 独立设计了“数据提取 → AI处理 → 静态网站生成”的全自动化流水线，并<b>负责定义各阶段接口与数据流</b>。</li>
          <li><strong>AI工程化实践:</strong> 深入实践提示词工程，并<b>通过编码实现了对AI输出结果的校验与归一化逻辑</b>，解决了AI输出不稳定的问题，确保了知识分类的准确性。</li>
          <li><strong>桌面端并发编程:</strong> 运用<code>Qt</code>多线程机制 (<code>QThread</code>) 对所有耗时操作进行<b>异步处理</b>，独立解决了UI假死问题，保证了流畅的用户体验。</li>
        </ul>
        <a href="[你的个人知识管理项目仓库链接]"><strong>➡️ 查看代码</strong></a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="[你的NatureE项目仓库链接]"><strong>NatureE: 云南民族服装数字化平台</strong></a>
        <br><br>
        <!-- 在这里添加项目截图 <img src="URL"> -->
        <br><br>
        <strong>技术栈:</strong> <code>微信小程序原生</code> <code>JavaScript (ES6+)</code> <code>Stable Diffusion API</code> <code>TDesign</code>
      </td>
      <td>
        一个集成了<b>在线商城</b>与<b>AI服装设计</b>功能的微信小程序，旨在通过数字化手段推广民族服饰文化。
        <ul>
          <li><strong>独立项目主导:</strong> 作为唯一开发者，独立负责该小程序从0到1的全过程，包括<b>技术选型、功能开发与发布</b>，锻炼了全面的项目掌控能力。</li>
          <li><strong>AI功能落地:</strong> 主导了<code>Stable Diffusion API</code>的集成工作，通过对API的封装与异步任务处理，将前沿AIGC技术成功落地为项目的核心亮点。</li>
          <li><strong>复杂业务逻辑实现:</strong> 深入学习并完整实现了电商项目的核心业务流程（购物车、订单状态机等）。AI主要用于辅助生成逻辑明确的UI和CRUD代码，让我能更<b>专注于核心业务逻辑的梳理与实现</b>。</li>
        </ul>
        <a href="[你的NatureE项目仓库链接]"><strong>➡️ 查看代码</strong></a>
      </td>
    </tr>
  </tbody>
</table>

---

### 📊 GitHub 统计 | My GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=unendev&show_icons=true&theme=vue&rank_icon=github" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=unendev&layout=compact&theme=vue" alt="Top Languages" />
p>

---

### 📫 如何联系我 | How to Connect

<p align="left">
  <a href="mailto:2931493353@qq.com"><img src="https://img-shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="[你的LinkedIn个人主页链接]"><img src="https://img-shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="[你的个人技术博客链接]"><img src="https://img-shields.io/badge/Blog-232323?style=for-the-badge&logo=blogger&logoColor=white" alt="Blog"></a>
</p>
