# 你需要知道的

> 原文：<https://hackr.io/blog/wordpress-javascript>

Javascript 是一种非常成熟的前端语言，用于在网页上添加动画效果和样式。它不运行在服务器上，而是实际运行在用户的浏览器上。Javascript 一直是 Wordpress 的一部分。wp-admin 和 wp-includes 中的 js 文件夹代表 Javascript，主要用于主题开发。现在，随着 Calypso 等新接口的出现，Javascript 的角色已经渗透得更深了。Javascript 有自己的生态系统。AngularJS、jQuery 和 Node.js 是与 Javascript 相关的三个标准术语。但是所有这三个实体彼此都非常不同。AngularJS 是一个 Javascript 框架，而 [JQuery](https://click.linksynergy.com/deeplink?id=jU79Zysihs4&mid=39197&murl=https://www.udemy.com/jquery-tutorial/) 是一个 Javascript 库，Node.js 是一个运行时环境。然而，相比 AngularJS，React 更受设计师的欢迎。

库和框架的选择应该基于需求。Wordpress 开发可以分为后端和前端。前端开发人员应该会发现使用 AngularJS、Backbone.js 或 React 就足够了。对于后端开发人员，最好是精通 PHP、Node.js 的开发人员。对于 Wordpress 开发人员来说，了解 Javascript 的所有知识并不是强制性的。Javascript 与 Wordpress 以众多的 Javascript 库[的形式捆绑在一起，比如 JSON、JQuery、Underscore.js 和 Backbone.js。它使得用 Javascript 编程变得更加容易。通过 Wordpress 的管理界面进行的每一次交互都是通过 Javascript 进行的。只有在单击发布、保存更改或更新按钮之后，PHP 才会开始工作，并且对数据库进行更改。](https://hackr.io/blog/top-javascript-libraries)

除了用于改变网站现有的 HTML 和 CSS 之外，Javascript 还可以用于:

*   事件执行。
*   验证输入值和表单提交。
*   第三方 API。
*   收集用户数据。
*   快速加载图像。
*   包括音频视频播放器
*   响应移动设备。

有几种方法可以将 Javascript 添加到 Wordpress。一个这样的过程被称为排队。这是一种向 Wordpress 网站添加脚本的 CMS 友好方式。它可以防止多次添加相同的脚本。它非常有效地管理脚本依赖。在这个上下文中需要注意的一点是，由于 JQuery 已经在 Wordpress 中排队，所以不需要再次排队。可以将所需的脚本排队，并将它们的依赖关系设置为 JQuery。

为了让脚本入队，需要使用函数 wp_enqueue_script()。它应该放在函数内部，然后挂接到 wp_enqueue_script 钩子。如果您需要将脚本加载到管理屏幕上，您可以使用相同的函数，但是您需要将该函数与 admin_enqueue_styles 挂钩。WP-REST API 使您能够与网站的数据库进行交互。这是使用 JSON 完成的。它使用 Javascript 读取、写入和编辑数据。

在主题允许的范围之外，总会偶尔需要添加额外的调整。有时候，直接在页面中添加代码并不容易。然后可以通过插件和主题添加 Javascript 效果。

几个插件可以用来在 Wordpress 网站上部署脚本。

这可以被认为是集成第三方 API 的最简单的方法之一。这不需要直接编辑现有的主题。其主要特点是:

1.  能够在页眉或页脚中插入代码。
2.  能够添加谷歌分析到任何主题
3.  一站式脚本编辑和插入
4.  插入脸书像素代码，添加谷歌分析代码到任何主题。
5.  向任何主题添加自定义 CSS。
6.  使用多种代码，包括 HTML、CSS 和 Javascript

#### 装置

1.  将插入的页眉和页脚目录上传到/wp-content/plugins/目录。
2.  通过 Wordpress 的插件菜单激活它。
3.  转到设置>插入页眉和页脚菜单，开始插入您需要的代码。

它配有一个仪表板，使您能够管理您所有的网站代码和片段。工作起来毫不费力。定制代码可以直接添加到唯一的 CJT 代码块中，并根据需要进行分配。码组短码提供了更高的放置精度。其主要特点是:

1.  能够将 CSS、Javascript、HTML 和 PHP 添加到页面、帖子、类别等。
2.  无需编辑主题文件即可添加前端样式的能力
3.  通过仪表板管理所有代码添加的能力避免了 FTP 的使用
4.  能够添加代码，而不需要调整核心文件。
5.  通过 GitHub、CodeCanyon 等支持代码嵌入
6.  能够添加广告、联盟脚本、访客跟踪、市场商店小部件和社交媒体渠道
7.  CJT 升级版提供了更多选项和工具。它允许添加 CJT 码块作为古腾堡块。
8.  通过 CJT 短码、CJT 元盒代码块和 CJT 边栏或页脚部件进行代码注入。
9.  美化代码优化选项以获得更好的可读性。
10.  压缩代码以提高性能的缩小选项
11.  代码自动完成功能
12.  一个快速分页下拉选择器来管理一个有数千个帖子的网站。

#### 装置

1.  将 css-javascript-toolbox 文件夹上传到/wp-content/plugins/目录。
2.  转到插件菜单并激活插件
3.  单击主导航栏中的 CSS & Javascript 工具箱链接。

### 3.方位脚本

这个插件可以直接添加自定义的 CSS 和 Javascript 到单独的页面和文章中。你的主题需要有相关的挂钩才能起作用。它没有任何输入验证。它具有以下特性:

1.  能够将类添加到 body 标签和 post 容器中。
2.  它提供了一个全局设置页面，您可以通过它为整个博客编写脚本和样式。
3.  能够将类添加到 TinyMCE 的“格式”下拉列表中，用户可以使用它直接将样式添加到页面中
4.  限制未授权访问的能力。

#### 装置

这个插件不需要任何独特的激活。它可以从 wordpress.org/extend 下载并像其他插件一样安装。

顾名思义，它将所有文本移动到页脚。这有助于减少加载时间，如果有太多的脚本，清理瓶颈。然而，应该记住，脚本页脚运行有一个插件，和 wp_enqueue_scripts 是正确使用的主题。其主要特点是:

1.  能够禁用特定页面上的特定功能。
2.  能够禁用特定归档页面上的插件，如博客页面、分类页面、搜索页面等。这是通过一个复选框来禁用这些页面上的插件。
3.  能够选择要包含在标题中的脚本

#### 装置

1.  将 scripts-to-footer.php 上传到/wp-content/plugins 目录。
2.  转到插件菜单>激活插件。

它有助于利用第三方 API。它的免费版本带有广告。购买专业版将删除广告，let 将提供优质选项。其特点包括:

1.  能够添加自定义脚本到单独的页面，页眉或页脚。
2.  使您能够添加谷歌再营销代码到整个网站
3.  支持网络商务
4.  能够添加脚本到有限的/选择性的页面或职位。
5.  兼容古腾堡。
6.  支持类别和术语页面。

#### 装置

1.  将插件上传到目录/wp-content/plugins/
2.  通过 Wordpress 的“插件”菜单激活插件。
3.  导航到自定义帖子类型、帖子或页面
4.  在页眉或页脚中粘贴代码。
5.  保存文章或页面。

### 6.纯自定义 CSS 和 JS

该插件的专业版在充分发挥其潜力时是最有效的。它主要关注网站外观的变化。其主要特点是:

1.  能够在不修改插件或主题的情况下添加自定义 CSS 和 Javascript。
2.  能够改变代码到特定的网址或网页
3.  在使元素生效之前对其进行测试
4.  带有语法高亮显示的文本编辑器。
5.  内联编码或维护单独的代码文件。
6.  能够在页眉或页脚中放置代码
7.  能够添加尽可能多的管理或前端所需的编码
8.  即使发生更改，更改也会被保存。

#### 装置

##### 方法 1

1.  从这个[链接](https://wordpress.org/plugins/custom-css-js/)下载插件并保存。压缩文件
2.  转到 WP 管理面板，点击插件>添加新的。
3.  单击上传并浏览至。您下载的 zip 文件。
4.  点击“安装”和“激活插件”

##### 方法 2

1.  从这个[链接](https://wordpress.org/plugins/custom-css-js/)下载插件并保存。压缩文件
2.  提取。压缩文件
3.  通过 cPanel 或 FTP 访问你的网站文件目录
4.  转到 WP-内容/插件目录
5.  将提取的文件夹上传到此位置。
6.  转到 WP 管理面板，点击插件>添加新的。
7.  进入 WP 管理面板>插件，点击激活简单的自定义 CSS 和 JS 插件。

##### 方法 3

1.  转到 WP 管理面板，点击插件>添加新的。
2.  在浏览器输入框中键入“简单自定义 CSS 和 JS”
3.  选择“简单定制 CSS 和 JS”插件，然后单击“安装”
4.  激活插件。

## 结论

有许多其他数不清的插件，可以根据当时的需要来使用。一个 Wordpress 网站最终会有许多不同的插件。所有的主题和插件必须使用标准的 Wordpress 方法来加载，以确保没有不兼容的问题。Javascript 的一个潜在缺点是，如果没有在用户的浏览器中启用，它就无法工作。虽然现代浏览器可以很好地处理 Javascript，但是如果用户关闭了浏览器中的 Javascript，那么什么都不能工作。因此，即使您添加了在大多数情况下运行良好的 javascript 代码，拥有服务器端回退也是明智的。

### 推荐 JavaScript 课程

【JavaScript 全教程 2023:从零到专家！

**人也在读:**