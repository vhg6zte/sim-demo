# 仿真 Demo

两段仿真运行录屏的展示页面，纯静态 HTML，无需构建。

## 内容

| 文件 | 说明 |
| --- | --- |
| `index.html` | 展示页面 |
| `demo-01.mp4` | 仿真演示一（1068 × 596，约 14 秒） |
| `demo-02.mp4` | 仿真演示二（1156 × 332，约 6 秒） |

## 本地查看

直接双击打开 `index.html`，或启动一个本地服务：

```bash
python3 -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 部署到 GitHub Pages

1. 打开仓库 **Settings → Pages**；
2. **Build and deployment → Source** 选择 `Deploy from a branch`；
3. 分支选择 `main`，目录选择 `/ (root)`，保存；
4. 稍等片刻，访问 <https://vhg6zte.github.io/sim-demo/>。
