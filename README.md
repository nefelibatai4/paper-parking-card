# 叠纸停车牌 · A4 打印折叠的挪车号码牌模板

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![在线使用](https://img.shields.io/badge/在线使用-GitHub%20Pages-2ea44f)](https://nefelibatai4.github.io/paper-parking-card/)
[![单文件](https://img.shields.io/badge/单文件-零依赖-111)](index.html)

**输入手机号 → A4 打印 → 裁剪折叠，10 分钟做出一个立在仪表台上的临时停车牌 / 挪车号码牌。**

免费、开源、不用注册、不用装 App。一张 A4 出两个成品，成本不到一毛钱。

<img src="screenshots/app.png" width="100%" alt="界面截图">

## 在线使用（不用装任何东西）

**https://nefelibatai4.github.io/paper-parking-card/**

打开就能用。也可以把 `index.html` 存到本地双击打开——**没有任何外部依赖，断网也能用**，号码只留在你自己浏览器里。

> 需要 PDF 的话，在打印对话框里把目标打印机选成「另存为 PDF」，得到的是精确 A4 横向尺寸。

## 什么场景用得上

- 小区、商场临时停车，怕挡住别人挪车
- 固定车位被占，想让对方能联系上
- 借车、租车、试驾，临时需要留个电话
- 车内本来没有停车牌，或者旧牌的号码已经换号
- 想自己设计一个，而不是买千篇一律的塑料牌子

两刀裁剪、四次折叠，不需要胶水，**除了剪刀不需要任何工具**。

## 特点

- **尺寸照着市售停车牌做**：面宽 120mm、高 38mm（市售款实测约 120–128 × 34–36mm），放仪表台上不占地方
- **一页出两张**：A4 横向排两张，裁完就是两个成品，可以放两辆车
- **内外两面分开设置**：朝车窗那面印手机号，朝驾驶员那面**默认不印号码**——开车时用不着看自己的号，也可以写别的字或干脆留白
- **12 套主题**：极简白、警示黄黑、霓虹赛博、港风霓虹、终端绿、公路牌、老电影、黑金、波普粉、深空、血字、录像带
- **字体 / 边框 / 底色 / 字色都能换**：黑体、超黑、车牌、海报、等宽、宋体、手写
- **实时 3D 预览**：拖动旋转，折起来长什么样先看再打，不用打废纸
- **50mm 标尺**：印在纸角，印完拿尺子量一下就知道打印比例对不对
- **三种尺寸**：小 100×34、标准 120×38、大 145×42；底脚深度 20–40mm 可调

<img src="screenshots/3d.png" width="49%" alt="3D 预览"> <img src="screenshots/how.png" width="49%" alt="折法说明">

## 打印

| 设置 | 值 |
|---|---|
| 纸张 | A4 **横向** |
| 缩放 | **100%**（不要选「适合页面」/「适应纸张」） |
| 边距 | 无 |
| 背景图形 | **勾选**（深色主题不勾会印成白纸） |

Chrome / Edge / Safari / Firefox 都可以。没有打印机的话，把 PDF 发给打印店，备注「A4 横向、100% 不缩放」即可。

纸质建议 **200–250g 卡纸**（折起来挺括、站得稳）；普通 A4 也能做，但会软，建议内侧再贴一层硬纸板。深色主题很费墨，家用喷墨先试白底或黄底。

打印出来长这样（A4 整页，两个成品）：

<img src="screenshots/print.png" width="100%" alt="打印版面">

## 折叠

1. 沿裁切线裁下整块纸面
2. 中间那条横虚线对折，**印刷面朝外**翻成 Λ 形
3. 上下两条窄边分别向外折成「脚」，压在台面上
4. 立在仪表台上，**印号码那面朝挡风玻璃**

折叠线打在成品内侧，正面看不到。不用胶水。

> ⚠️ 平铺在纸上时，**上半张是倒着印的，这是故意的**——折起来之后两面才能正读。看到上半是倒的别以为打错了。

## 常见问题

**印出来多大？**
标准档单个面 120×38mm，和市售停车牌一个尺寸；整块纸面 120×126mm（含 25mm 底脚），一张 A4 正好排两张。

**为什么上半张文字是倒的？**
折线在中间、印刷面朝外时，两个面的字头都要朝向折线，所以平铺时上半张必须倒着印。折起来两面都是正的。

**没有打印机怎么办？**
页面上点「打印 / 存成 PDF」生成 PDF，发给打印店或便利店，备注 A4 横向、100% 不缩放。

**印出来尺寸不对 / 折不上？**
九成是缩放选成了「适合页面」。纸角印了 50mm 标尺，拿尺子量一下对不上就是缩放了。

**不想把手机号直接印出来？**
可以配合扫码挪车工具（见下方「相关项目」），或者只在外侧留一块贴二维码贴纸的位置。

**能只打一张吗？**
可以，把「每页」改成 1。默认排满是因为纸已经用了，多出来的可以备用或者送人。

**手机能打开吗？**
能看能预览，但打印建议用电脑——手机浏览器的打印排版控制有限。

**能改尺寸、改主题吗？**
页面上可以直接选三种尺寸和 12 套主题；想自己加主题改 `index.html` 顶部的 `THEMES`，加一条就是一套新主题。

**电话号码会被收集吗？**
不会。纯前端单文件，号码只在浏览器内存里，不联网、不上传。

## 自定义

日常使用直接在页面上改。想改结构的话，`index.html` 顶部：

```js
// 成品尺寸（毫米）：单个面的宽高
const LAYOUTS = {
  tent: { sizes:{ s:{w:100,h:34}, m:{w:120,h:38}, l:{w:145,h:42} } }
};

// 主题：加一条就是一个新主题
const THEMES = [
  { id:'plain', name:'极简白', bg:'#ffffff', fg:'#111111',
    pattern:'none', font:'hei', border:'thin' },
  ...
];
```

- 字号自动缩放到「面能容纳的最大值」，改尺寸不用手调字号
- `pattern` 填任意 CSS `background-image`，图案是矢量，打印不会糊
- 点阵类图案要另外设 `patternSize`，比如 `'4mm 4mm'`

## 几个踩过的坑

**1. 折叠方向**：折线在中间、印刷面朝外时，两个面的「字头」都要朝向中间那条折线。也就是说平铺时上半张必须倒着印。做反了折起来两面全倒。

**2. 字体粗细**：macOS 的 PingFang SC 最粗只到 Semibold，`font-weight:800` 和 600 渲染一模一样。数字想够黑得用 Helvetica Neue Bold 或 Arial Black；车牌感用 `DIN Condensed`（家族名不要加 Bold 后缀）。

**3. 3D 里不能量字号**：`getBoundingClientRect()` 返回的是变换后的投影尺寸，在 3D 场景里量出来会偏小。要先在屏幕外一个不带变换的容器里排版量好，再把节点搬进 3D。

**4. 3D 缩放不能按纸面宽度估**：转动后投影范围由「宽度 + 深度」共同决定，Λ 折叠转到俯视时进深会完全展开。改成先应用旋转、量一次真实投影包围盒，再缩放并居中。

**5. 打印不能依赖屏幕布局**：一屏布局给 `html,body` 加了 `height:100%; overflow:hidden`，这个约束会漏进打印把纸裁掉；改成 `overflow:visible` 又会因为纸面比页框高 0.1px 多出一页空白。最后是打印前把纸克隆到一个独立容器里，彻底和屏幕布局解耦。

## 尺寸调研

市售停车牌的实际规格：

| 产品 | 尺寸 | 来源 |
|---|---|---|
| XWH / 希万辉 XWH-HMP-017 | 128 × 34.5 × 17 mm | [震坤行](https://www.zkh360.com.cn/item/AF0333123.html) |
| ShopKimo BY1272 | 120 × 36 × 17 mm | [ShopKimo](https://www.shopkimo.com/product/product&product_id=2351) |

所以成品按 **120 × 38mm** 做（高度多留 2mm 给折叠后的视觉比例）。

## 现成样例

`samples/` 里是几张已经排好版的 PDF（占位号码 `138 0000 0000`），想先试打可以直接用：

| 文件 | 内容 |
|---|---|
| `samples/plain.pdf` | 白底，内侧「临时停车」、外侧号码 |
| `samples/hazard.pdf` | 黄底黑斜纹，Arial Black |
| `samples/neon.pdf` | 深紫底青字，Impact |
| `samples/both-sides.pdf` | 双面都印号码的对照版 |

## 相关项目

- [ryanshi1103/print-ready-nameplate-generator](https://github.com/ryanshi1103/print-ready-nameplate-generator) —— A4 可折叠三角姓名牌生成器，几何思路很值得参考
- [oozzbb/car-qrcode-notify](https://github.com/oozzbb/car-qrcode-notify) —— 不想把手机号明着印出来的话，可以考虑扫码挪车
- [nbbk/movecar](https://github.com/nbbk/movecar)、[bg7iae/CarAlert](https://github.com/bg7iae/CarAlert) —— 同类扫码挪车通知

## English

A free, single-file web tool that generates a **printable, foldable parking phone-number card** (临时停车牌 / 挪车号码牌) on A4 paper.

Type your phone number → print on A4 (landscape, 100% scale) → cut → fold into a Λ-shaped card that stands on the dashboard. The **outward-facing side shows your number; the driver-facing side shows nothing by default**. 12 themes, custom fonts and colors, live 3D preview, no install, no network, no data collection.

Live demo: https://nefelibatai4.github.io/paper-parking-card/

Keywords: parking card, parking sign, car phone number sign, printable template, foldable, A4, papercraft, DIY.

## License

[MIT](LICENSE)
