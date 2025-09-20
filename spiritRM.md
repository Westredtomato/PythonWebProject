### 响应式布局项目

```
spirit/
├── index.html          # 主页面文件
└── assets/             # 资源文件夹
    ├── css/            # 样式文件
    │   ├── bootstrap.min.css    # Bootstrap框架
    │   ├── animate.min.css      # 动画库
    │   ├── reset.less          # 重置样式
    │   └── index.less          # 主要样式文件
    ├── js/             # JavaScript文件
    │   ├── jquery.min.js       # jQuery库
    │   ├── bootstrap.min.js    # Bootstrap脚本
    │   ├── less.min.js         # LESS编译器
    │   └── wow.min.js          # 动画触发库
    ├── fonts/          # 字体文件
    └── images/         # 图片资源
```

### 技术栈选择

- HTML5 - 页面结构
- Less - CSS 预处理器（比原生 CSS 更强大）
- Bootstrap - 响应式框架
- jQuery - JavaScript 库
- Animate.css - 动画库
- WOW.js - 滚动动画触发器

重要注意事项：

- CSS 引入顺序很关键 ：框架样式 → 第三方库 → 重置样式 → 自定义样式
- 后引入的样式会覆盖前面的样式（CSS 层叠性）
- type="text/less" 表示这是 Less 文件，需要 Less 编译器处理

