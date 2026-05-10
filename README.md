# PastimeReading

[中文说明](#中文) | [English](#english)

---

<a id="english"></a>
## English

A reading mod for The Long Dark. Read custom books/texts in-game to pass time during blizzards and long nights.

### Installation

**Prerequisite: MelonLoader (net6) installed**

1. Place `PastimeReading.dll` into your game's `Mods/` folder
2. Place the `pastimeReading/` folder into your game's root directory (next to `Mods/`)

```
TheLongDark/
├── Mods/
│   └── PastimeReading.dll
└── pastimeReading/
    ├── book.txt
    ├── pastimeReadingAssets.ass
    ├── textures/
    │   └── (cover textures)
    └── handtex
```

### Adding Books

1. Create a `.txt` file in UTF-8 encoding
2. First line = book title
3. Second line = author name
4. Everything below = book content
5. Place the file in the `pastimeReading/` folder

If you see squares instead of special characters, convert your text file to UTF-8.

### Cover Textures

Custom cover textures are in `pastimeReading/textures/`. Do not rename them. The bottom-left 2 pixels of each texture control title (T) and author (A) font color.

---

<a id="中文"></a>
## 中文

漫漫长夜看书 mod。在暴风雪和漫漫长夜中阅读自定义书籍/文本来消磨时间。

### 安装

**前提：已安装 MelonLoader (net6)**

1. 将 `PastimeReading.dll` 放入游戏的 `Mods/` 文件夹
2. 将 `pastimeReading/` 文件夹放入游戏根目录（和 `Mods/` 同级）

```
TheLongDark/
├── Mods/
│   └── PastimeReading.dll
└── pastimeReading/
    ├── book.txt
    ├── pastimeReadingAssets.ass
    ├── textures/
    │   └── (封面贴图)
    └── handtex
```

### 添加书籍

1. 创建一个 UTF-8 编码的 `.txt` 文件
2. 第一行 = 书名
3. 第二行 = 作者
4. 下面的内容 = 书的正文
5. 把文件放在 `pastimeReading/` 文件夹里

如果看到方块字符，请将文本文件转换为 UTF-8 编码。

### 封面贴图

自定义封面贴图在 `pastimeReading/textures/` 里。不要重命名文件。每张贴图左下角的 2 个像素分别控制标题 (T) 和作者 (A) 的字体颜色。
