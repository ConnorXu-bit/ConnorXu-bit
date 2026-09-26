## 你好，我是许伟志 👋

数学老师转行做后端开发，目前在北京找 **Python 后端 / AI Agent 开发** 的岗位。

两年多的教学经历留给我两样东西：把复杂问题拆成可执行步骤的习惯，和把一件事讲到别人能听懂的能力。现在我把它们用在写代码上。

### 技能

`Python` · `FastAPI` · `MySQL` · `Redis` · `SQLAlchemy 2.0` · `Alembic` · `Docker` · `pytest` · `GitHub Actions` · `RAG（向量检索 / BM25 / RRF 融合）`

### 项目

**[fastapi-user-system](https://github.com/ConnorXu-bit/fastapi-user-system)**
基于 FastAPI 的异步用户认证与授权系统。双 JWT Token 刷新轮换 + Redis 黑名单实现登出即时失效，五表 RBAC 权限模型按请求实时校验权限，Docker Compose 一键启动，37 个 pytest 用例。

**[shortlink-agent](https://github.com/ConnorXu-bit/shortlink-agent)**
基于 DeepSeek Function Calling 的对话式短链 Agent。模型只负责决策、程序负责执行；支持多轮工具调用循环、Redis 短码原子写入与 SCAN 模糊查询，22 个 pytest 用例。

**[rag-kb-qa](https://github.com/ConnorXu-bit/rag-kb-qa)**
RAG 知识库问答服务。文档按标题路径切分并保留重叠，向量化后入库；提问走向量 + BM25 混合检索、用 RRF 按名次融合，命中低于阈值时不调用模型、直接返回「未找到相关内容」以抑制幻觉。50 个 pytest 通过构造器注入假 Embedder 与假 LLM，不联网即可跑通全链路。

### 联系

- 邮箱：weizhix@hotmail.com
- GitHub：[@ConnorXu-bit](https://github.com/ConnorXu-bit)
