# 🌱 Mendel & His Peas — Interactive Biology Lesson

> G9 Honor Biology · Lesson 3: Mendel and His Peas
> 孟德尔与他的豌豆 · 交互式遗传学课件（中英双语）

一个零依赖的单文件交互式网页课件，适合课堂投屏与学生自主探索。

A zero-dependency, single-file interactive lesson for classroom projection and student exploration.

---

## 🎯 模块内容 · What's Inside

1. **为什么是豌豆？** Why Peas? — Mendel（豌豆）与 Darwin（家鸽）对比：为什么孟德尔找到了遗传规律
2. **Perfect Flower 完全花结构** — 可点击 SVG 花结构图：雌蕊（柱头/花柱/子房）、雄蕊（花药/花丝/花粉）、花瓣、萼片；自花 vs 异花授粉演示
3. **P → F₁：第一次杂交** — 四步交互：①自交验证 true-breeding 纯种 → ②预测 F₁ 花色（混合遗传干扰项）→ ③去雄/授粉/结荚动画（人工异花授粉）→ ④种下 16 颗 F₁ 种子发现全部紫花，引出显性/隐性（dominant / recessive）与 Pp 因子解释
4. **3:1 比例探索** — F₁×F₁ 杂交动画 + 32 格"豌豆园"互动统计，学生亲手播种、实时计数，体验样本越大越接近 3:1；附孟德尔 1865 年七对性状真实数据
5. **Reader's Theater 采访孟德尔** — 全英文剧本《An Interview with Gregor Mendel》，字幕跟随朗读（Web Speech TTS，可 Play / Pause / Restart，点击任意台词跳转）；也适合课堂分角色朗读。台词上方附生物学关键词汇表
- **仿真花结构**：蝶形花冠（旗瓣/翼瓣/龙骨瓣）可点击；可"剖开龙骨瓣"查看内部 10 枚雄蕊（9 合 1 离）与雌蕊结构

---

## 🚀 GitHub Pages 部署（约 3 分钟 · 免费）

1. 注册/登录 GitHub：<https://github.com>
2. 右上角 **＋** → **New repository**
3. 仓库名填 `mendel-peas`（或任意名字），选 **Public**，点 **Create repository**
4. 点击 **uploading an existing file**，把本文件夹里的 **全部文件**（`index.html`、`.nojekyll`、`README.md`）拖进去
   - ⚠️ 注意：`.nojekyll` 是隐藏文件，Windows 上看不到的话，只需确保上传 `index.html` 即可，本页是纯 HTML 不依赖它也能运行
5. 点 **Commit changes**
6. 进入仓库 **Settings** → 左侧 **Pages**
7. **Source** 选择 `main` 分支，文件夹选 `/ (root)`，点 **Save**
8. 等待 1–2 分钟，页面上方会显示网址：
   `https://<你的用户名>.github.io/mendel-peas/`

把这个网址发给学生即可。剧本朗读（TTS）推荐使用 Chrome / Edge 浏览器。

---

## 📱 课堂使用建议 · Classroom Tips

- 投屏打开模块 ①② 做讲解；模块 ③ 可让学生分组比赛"谁的 32 颗豌豆最接近 3:1"
- 模块 ④ 适合 pair work：一人扮演记者，一人扮演孟德尔读稿，再用网页语音互动
- 网页可离线使用（无外部资源），但语音识别需要联网 + HTTPS
- 打印网页可得到不含交互按钮的学生学案（已内置打印样式）

## 📄 文件结构 · Files

| 文件 | 说明 |
|---|---|
| `index.html` | 课件本体（HTML+CSS+JS 全内联，单文件） |
| `.nojekyll` | 告诉 GitHub Pages 直接原样发布，不做转换 |
| `README.md` | 本说明文件 |

---


