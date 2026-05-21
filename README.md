# 🎯 Google Coding 面经汇总

22 道独立 coding 题，整理自一亩三分地 2026.4–5 共 16 份 Google 面经 PDF。
每题包含：题目（中英）、澄清问题（中英）、Python 实现、Strong-Hire 讲解策略、常见坑。

## 🌐 在线访问

部署到 GitHub Pages 后即可在线浏览：**https://<你的用户名>.github.io/<repo 名>/**

## 📚 内容总览

- `index.html` — 入口卡片页（22 题概览 + 通用应试节奏）
- `01_*.html` ~ `22_*.html` — 每题独立深度展开
- `shared.css` — 共享样式

## 🏗 本地预览

```bash
git clone git@github.com:<你的用户名>/<repo 名>.git
cd <repo 名>
python3 -m http.server 8765
# 浏览器打开 http://localhost:8765
```

## 🚀 部署到 GitHub Pages

1. 在 GitHub 上**新建一个空 repo**（不要勾选 README/license）。
2. 在本目录初始化 git 并推送：
   ```bash
   cd /Users/bytedance/Desktop/google_interview/site
   git init -b main
   git add .
   git commit -m "Initial Google coding prep site"
   git remote add origin git@github.com:<你的用户名>/<repo 名>.git
   git push -u origin main
   ```
3. 打开 repo → **Settings → Pages**。
4. **Source** 选 "Deploy from a branch" → Branch 选 `main` / `/ (root)` → Save。
5. 等 1–2 分钟，回到 Pages 页面会显示部署好的 URL。

## 🔄 重新生成 HTML（如果你修改了 markdown 源）

源在 `../coding_questions.md`。改完跑：
```bash
cd ..
python3 generate_site.py
```
会重新生成 `site/*.html`。

## 📂 文件清单

| 文件 | 说明 |
|------|------|
| `index.html` | 入口卡片页 |
| `01_friend-logs.html` | 朋友圈与解除好友（LC 1101） |
| `02_necklace-split.html` | 项链切割平分 D/R |
| `03_dijkstra-via.html` | Dijkstra 经过指定点 |
| `04_min-cars.html` | 租车最少辆数（LC 253） |
| `05_text-editor.html` | Text Editor / Book Keeping |
| `06_huffman.html` | Huffman 编码树生成 |
| `07_place-flowers.html` | N×N 网格放花（N-Queens 变种） |
| `08_delete-directory.html` | 递归删除目录 |
| `09_game-of-life.html` | Game of Life（LC 289） |
| `10_door-schedule.html` | 进出门时间表 |
| `11_max-edge-remove.html` | 删点后图中最大边权 |
| `12_circular-fence.html` | 环形 Paint Fence |
| `13_perfect-wake.html` | Perfect Wake Number 计数 |
| `14_longest-match-token.html` | 最长匹配分词 |
| `15_quick-select.html` | Quick Select（LC 215） |
| `16_tree-distance.html` | 树中两点距离 |
| `17_substr-prefix.html` | 以 target 为前缀的子串计数 |
| `18_elevator.html` | 电梯调控器 OOP 设计 |
| `19_expr-eval.html` | 嵌套表达式求值 |
| `20_detonate-bombs.html` | Detonate Maximum Bombs（LC 2101） |
| `21_word-search-graph.html` | Word Search 图变体（LC 79 变体） |
| `22_delete-bst.html` | Delete Node in BST（LC 450） |
| `shared.css` | 共享样式表 |

---

整理自一亩三分地 2026.4–5 Google 面经，仅供学习交流。
