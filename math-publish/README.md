# 初中数学线上练习 · GitHub Pages 发布入口

此目录用于逐步恢复 GitHub Pages 试卷发布，不替换现有学生网站或数据库。

## 安全发布约定

1. AI 生成完整试卷并独立检查题目、答案、解析、题型及章节。
2. 教师审核并明确批准与完整试卷内容绑定的版本。
3. 仅将批准后的静态学生页面写入 `p/`，不得把正确答案、教师凭据或 Google Sheets 写入凭据公开给学生；如果页面需要客户端评分，需明确其答案可被查看的限制。
4. 学生作答的上传端点须单独验收，确认服务端回执和 Google Sheets `Submissions` / `Answers` 读回，禁止仅凭 `fetch(..., {mode:'no-cors'})` 的 Promise 成功就声称数据库已保存。
5. 新卷必须使用新文件名，旧链接和历史数据不得覆盖；只有完整端到端验收通过才宣布发布成功。

当前状态：已建立 GitHub 端的独立发布工作目录；**尚未接通或验证学生提交接口，尚未发布新卷**。

现有初中独立数据库仍为 `1DzXN7Aqlu-GHcejhxI6tOi8-B9yNoclgyTeMi7AIdl0`。学生网站仍为 `https://junior-high-math-practice.phdblue.chatgpt.site/`。本目录不代表已完成这两个系统的整合。
