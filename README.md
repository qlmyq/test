# test

这是一个测试仓库,用于验证 Claude 与 GitHub 的接入。

## 简介

一组单文件网页小项目,无需安装任何依赖,用浏览器直接打开即可:

- `index.html`:扫雷
- `sphere.html`:可拖动旋转的 3D 星球(程序生成的地表贴图和云层,带一颗环绕飞行的卫星)

## 扫雷玩法

- 左键翻开格子,右键插旗(手机上长按,或点“插旗模式”)
- 点击已翻开的数字,若周围旗数正确,会自动翻开剩余格子
- 第一次点击一定安全
- 三种难度:初级 9×9、中级 16×16、高级 30×16

## 开始使用

```bash
git clone https://github.com/qlmyq/test.git
cd test
# 用浏览器打开 index.html(扫雷)或 sphere.html(3D 球体)
```

## 目录结构

```
test/
├── index.html   # 扫雷
├── sphere.html  # 带贴图和卫星的 3D 星球
└── README.md
```

## 贡献

欢迎提交 Issue 和 Pull Request。

## 许可证

暂未指定。
