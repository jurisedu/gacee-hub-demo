# gacee-hub-demo

GACEE 协会平台 **高保真演示（Mock）** — 部署到 hub.gacee.org 供内部/合作方浏览。
纯静态（单页 index.html + seal.png），无后端。真实平台见 jurisedu/gacee-platform。

## 部署（Vercel）
```bash
npm i -g vercel        # 若未安装
cd ~/git/gacee-hub-demo
vercel --prod --scope db-agi
```
然后在 Vercel 该项目 → Settings → Domains 绑定 **hub.gacee.org**（DNS 走 Vercel）。
