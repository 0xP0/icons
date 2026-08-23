# icons

公开托管的静态资源。放在这里的唯一理由：Olares 的 `OlaresManifest.yaml` 要求
`metadata.icon` 是**可公网访问的 http(s) URL** —— `data:` URI 会被校验拒掉（实测），
而 `0xP0/olares-ai` 是私有仓库，`raw.githubusercontent` 取不到。

## olares-ai

Olares AI 应用的图标。深色圆角底 + 一个环（助手）连着三个方块（它操作的应用）。

- `olares-ai/icon-256.png` —— manifest 用这个（官方应用都用 png/webp，SVG 能否被桌面渲染未验证）
- `olares-ai/icon.svg` —— 源文件，改图标从它改起

引用地址：

```
https://raw.githubusercontent.com/0xP0/icons/main/olares-ai/icon-256.png
```
