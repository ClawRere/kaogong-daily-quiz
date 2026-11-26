# kaogong-daily-quiz

2027 湖北省考每日练习（时政新闻 + 行测申论 5 题），GitHub Pages 站点，域名 https://kaogong.ldddd.eu.org/

## 每日发布流程

1. 当天练习做成 web artifact（goal_id=goal_39255ef37338），导出静态 HTML（artifact.export）。
2. 把导出的 HTML 存为 `<YYYYMMDD>.html`（如 20261126.html），提交到本仓库根目录。
3. 更新 `index.html`，指向最新一天的页面。
4. push 后用 curl 核实 `https://kaogong.ldddd.eu.org/<YYYYMMDD>.html` 能打开（HTTP 200 且含当天题目）再向主代理报告。
5. 仓库不要放任何凭证、token。

## 文件

- `<YYYYMMDD>.html`：当日练习页
- `index.html`：首页，指向最新一天
- `CNAME`：自定义域名 kaogong.ldddd.eu.org
