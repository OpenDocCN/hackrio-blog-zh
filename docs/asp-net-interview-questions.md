# 2023 年 ASP.Net 面试 50 强问答[更新]

> 原文：<https://hackr.io/blog/asp-net-interview-questions>

你是一名 ASP.NET 程序员…你的下一次工作面试就在眼前…你想得到那份工作…这意味着你需要做好准备，尽管你对该领域很了解。一般来说，在技术性工作面试中，面试官不仅会问复杂的问题，而且你甚至可能会面临一些非常基本和基本的问题，这些问题可能会决定你的胜算。

## ASP.Net 面试问答

你可能需要更多的问题来为面试做好充分准备。我们推荐您访问 [ASP。NET 教程和课程](https://hackr.io/tutorials/learn-asp-net?ref=blog-post)，在那里你可以找到更多的阅读材料，全面了解 ASP.NET。

#### 问:什么是 ASP.NET？

**答:**ASP.NET 是一个开源的服务器端应用框架，专为 web 开发人员设计，用于制作动态网页。NET 框架。它是由微软开发的，允许程序员建立动态网站、网络应用程序和网络服务。

#### **问题:什么是 ASP.NET MVC 框架？**

**答:**ASP.NET MVC 是一个面向。NET 平台，用于使用模型-视图-控制器模式构建全栈 web 应用程序。

#### 问:什么是 ASP.NET 网络应用编程接口框架？

**回答:**ASP.NET 网络应用编程接口纯粹用于构建后端网络应用编程接口，可以被一系列客户端使用，从网络到桌面到移动设备。它构成了 RESTful(表述性状态转移)架构中的服务器组件。

#### 问:ASP.NET MVC 和 ASP.NET Web API 哪个是合适的框架？

**回答:**如果想要构建一个可以被一系列客户端轻松使用的服务器组件，那么 ASP.NET Web API 是一个不错的选择。然而，如果这个项目纯粹是作为一个 web 应用程序来使用，那么 ASP.NET MVC 是一个更合适的选择。

#### **问题:web.config 文件是什么，有什么用途？**

**答:**web . config 文件至关重要，因为它包含了应用程序的配置设置。它将您的整个配置与您的代码分开，因此您可以轻松地更改设置，而无需更改代码。它还允许您对配置设置进行加密，以提高安全性。

#### 问:ASP.NET 使用的是哪种编译器？

**答案:** Roslyn 是使用的编译器的名字。NET 框架。

#### 问题:ASP.NET 是开源的。解释一下。

**回答:**微软正在提供完整的。NET 服务器栈，这意味着它是一个“免费”下载。这包括 ASP.NET。NET 编译器。NET 核心运行时、框架和库，使开发人员能够使用。NET 跨 Windows，Mac 或 Linux。

#### **问题:解释 ASP.NET MVC 框架中的请求流程。**

**答:**请求流处理来自客户端的请求，并将其传递给服务器。来自客户端的请求命中控制器。控制器扮演其角色并决定使用哪个模型来进一步服务请求，将该模型传递给视图，视图然后转换该模型并生成呈现给客户端的适当响应。

#### **问:解释一下 ASP.NET 会话状态的各种模式？**

**答:**存储会话状态有多种方式:

*   InProc:会话状态存储在 web 服务器的内存中。这是默认模式。
*   自定义模式:您可以指定自定义存储提供程序。
*   关闭模式:禁用会话状态。
*   OutProc:有两种方法来处理这种模式:
*   StateServer:会话状态存储在一个称为 ASP.net 状态服务的独立进程中。即使应用程序服务器重新启动，会话状态也会保留，并且可用于多个 Web 服务器。
*   SQLServer:会话状态存储在数据库中，因此即使 Web 应用程序重新启动，也会保留会话状态。一个 Web 场中的多个 Web 服务器可以访问会话状态。

#### **问题:解释 GridView 和 DataGrid 的区别？**

**答案:**

| **GridView** | **数据网格** |
| 使用 PagerSettings 属性对分页、排序和就地编辑的内置支持。 | 需要自定义代码进行分页、排序和编辑。 |
| 使用数据源控件的排序、更新、删除和分页选项。 | 默认情况下，仅支持数据选择。更新和删除需要自定义代码。 |
| 支持额外的列类型，如超链接字段，按钮字段等。 | 仅支持有限的列类型。 |
| 支持术前和术后事件。 | 为操作引发单个事件。 |

#### 问题:你如何解释 ListView 和 Repeater 之间的区别？

**答案:**

| **中继器** | **ListView** |
| 中引入的灵活布局。NET 1.0。 | 引入了灵活的布局和轻松的自定义。净 3.5 |
| 没有内置支持，应该为数据分组和分页编写自定义代码。 | 为数据分组和分页提供内置支持。 |
| 不支持更新、插入、删除和排序操作。 | 支持所有操作。 |
| 提供更好的性能。 | 与中继器相比，性能较慢。 |

#### **问题:解释本地资源和全球资源？**

**答案:**

| **本地资源** | **全球资源** |
| 本地资源只能由创建它的页面访问。 | 所有页面均可访问。 |
| 当网站有大量本地化内容时很难维护，因为每个页面都需要每种语言的资源文件。 | 每种语言只需要一个文件。 |
| 存储在 App_LocalResources 文件夹中。 | 存储在 App_GlobalResources 文件夹中。 |

#### **问题:简单描述一下全球化和本地化？**

**回答:**全球化是业务在国界之外的增长。它涉及到了解各个国家的法律法规，以营造商业环境。全球化包括国际化和本土化。

本地化是一个过程，通过使产品对当地社区有吸引力，使产品可用于当地市场。它包括本地偏好、文化和区域方面，而不仅仅是将网页翻译成本地语言。

对于一个稳定的全球业务来说，你既需要全球化(通过全球化你可以扩大你的业务范围),也需要本地化(你可以根据当地偏好和其他方面展示定制内容)。

这些有助于有效的目标市场营销和连贯的全球战略。

#### **问题:用户控件和自定义控件有什么不同？**

**答案:**

| **用户控制** | **自定义控件** |
| 存储为。ascx 扩展。 | 它是一个. dll 扩展名。 |
| 他们有一个可视化的界面。 | 这些控件没有可视化界面。 |
| 不出现在工具箱中，并且没有设计支持；在运行时加载。 | 可以添加到工具箱中，并在各种应用程序中使用，而无需重新编译。 |
| 如果我们需要特定于网站的控件，用户控件是一个很好的选择。 | 可以创建自定义控件以在各种应用程序中使用。 |

#### 问:解释一下 ASP.NET 的服务器控制？

**答:**服务器控制是 ASP.NET 中的主要控制，分为以下几类:

*   验证控件:这些控件通过运行客户端脚本来验证用户输入
*   数据源控件:这些控件用于为多个数据源提供数据绑定。
*   数据视图控件:这些控件用于查看/显示从数据源获取的列表和表格数据
*   登录和安全控制:用于用户验证
*   母版页:用于为整个应用程序提供一致的界面和布局
*   丰富的控件:这些控件用于实现特殊的功能，如文件上传、日历控件、AdRotator 等。
*   导航控件:帮助导航菜单、树形视图等
*   个性化控件:用于基于用户信息和首选项的页面个性化

**问题:解释 ASP.NET 的各种页面事件？**

**回答:**ASP.NET 的各种页面事件有:

| **事件** | **描述** |
| 页面请求 | 此事件发生在生命周期开始之前。每当用户请求一个页面，ASP.NET 就解析并编译这个页面。 |
| 开始 | 像请求和响应这样的属性被设置，请求类型通过这个事件来确定 |
| 初始化 | 此事件设置每个控件的 UniqueID 属性，并将母版页应用于该页。 |
| 翻译 | 在这种情况下，将为每个控件调用“Render”方法。文本编写器将输出(视图状态)写入页面响应属性的 OutputStream 对象 |
| 负荷 | 如果页面请求是回发，则控件属性加载信息， |
| 回发事件处理 | 如果页面请求是回发，则通过此事件调用事件处理程序。然后，调用所有验证器控件的 Validate 方法 |
| 倾销 | 此事件在请求的页面完全呈现并准备停止后发生。卸载所有属性，并完成清理。 |

#### **问题:在 Web.config 文件中定义一个连接字符串？**

**答:**连接字符串包含了关于数据源以及如何连接到数据源的信息。

连接字符串添加如下:

```
<configuration>  
  <connectionStrings>  
    <add name="myConnection" connectionString="server=localhost;database=mydatabase;" />
  </connectionStrings>
</configuration>
```

#### **问题:解释一下 Web.config 和 Machine.config 文件的区别？**

**答案:**

| **web.config** | **machine.config** |
| 存储特定 web 应用程序的配置设置。 | 指定 web 服务器上托管的所有网站的配置设置。 |
| 位于应用程序的根目录中。 | 位于$WINDOWSDIR$\Microsoft。Net \ Framework \版本\配置 |
| 重写 machine.config 文件中的设置。 | 它是一个主文件，提供可以被覆盖的默认设置。 |

#### **问题:解释 Global.asax 文件？**

**答:**可选文件，也称为 ASP.NET 申请文件。它包含响应由 HTTP 模块或 ASP.NET 引发的会话级和应用程序级事件的代码。

#### **问题:简述网站和 Web 应用程序的区别？**

**答案:**

| **网站** | **网络应用** |
| 包含对所有访问者公开的静态内容。 | 动态和互动的内容。 |
| 内容对所有人都是可读的，但是不能被改变或操纵。 | 最终用户可以读取和操作受限数据。 |
| 这些大多是信息网站，因此认证不是强制性的。 | 需要身份验证，因为它们为用户提供了更多的功能和选项。 |
| 它很容易创建，因为只需加载和更新信息。 | 因为与最终用户有交互，所以 web 应用程序很复杂，并且执行更多的功能。 |
| 网站是一个完整的产品，可以通过浏览器访问。 | 这是整个网站的一部分。不能直接访问它。 |
| 不需要预编译，只需要刷新 HTML 代码。 | 部署前需要进行预编译。 |

**问题:解释视图状态？以及它的优缺点。**

**答:**假设用户提交了一个表单，出现了验证错误或者用户在页面上输入大量信息后页面刷新。在这种情况下，用户已经写入的信息将会丢失，他/她必须重新填写所有内容。为了避免这种情况发生，ASP.NET 使用了视图状态，它保留了用户已经输入的值。它是一种内置的状态管理技术，用于保存表单数据。

**优点:**

*   由于数据以加密格式存储，确保了安全性。
*   没有使用服务器资源。
*   可以很容易地启用或禁用视图状态属性。
*   开发人员可以根据需要在页面级或控件级开发。

**缺点:**

*   如果存储了大量数据，加载页面所需的时间可能会比需要的时间长。
*   数据不会从一页传输到另一页(页面之间)。

#### 问题:解释一下 ASP.NET 的饼干？

**答:**cookie 是存储用户特定数据的文本的一部分。浏览器将 Cookies 存储在用户的硬盘中，每当用户请求某个特定页面时就会使用。Cookies 有助于改善用户体验，并根据作为数据一部分存储的日期和时间信息更快地加载页面。在 ASP 中，可以创建和检索 cookies。ASP 中有两种类型的 cookies 持久的和非持久的。

#### 问:解释网络服务在 ASP.NET 的目的？

**回答:**ASP.NET 可以创建 web 服务，它只不过是使用 XML 通过常用的互联网协议与其他软件程序交换数据的程序。我们可以使用 web 服务与互联网上的任何对象进行通信。

Web 服务是语言独立、平台独立、协议独立、自描述和可编程的。

#### **问题:举例说明 ASP.NET 的应用领域概念。**

**回答:**ASP.NET 的 App domain 或者说 application domain 是一个轻量级的进程，有自己的一套代码、配置和数据设置。它是一个逻辑边界，将一个应用程序与访问或干扰其他应用程序分隔开来。应用程序域通过使用更少的进程来执行不同的应用程序，有助于更好地利用资源。例如，ASP.NET 是一个运行时宿主，它为访问网站的每个用户创建不同的应用程序域。这些可以为需要隔离代码或动态加载扩展的应用程序创建和设置。

#### **问题:ASP 中的查询字符串是什么？以及它的优缺点是什么？**

**答:**查询字符串是一种使用浏览器 URL 将数据从一个页面传输到另一个页面的方法。它使用问号符号(？).例如，【http://xyz.com】T2？userid = 12334&pwd = RF 5 r5 JM 3 smq

优点:易于使用，不需要服务器资源，受所有浏览器支持，包含在 URL 的 HTTP 请求中

缺点:URL 长度不能大于 255 个字符；危及安全的每个人都可以直接看到数据。

#### 问题:什么是追踪？网？

**回答:**描摹中。net 使人们能够跟踪页面的执行路径，调试应用程序并在运行时显示诊断信息。可以从代码中访问和操作跟踪消息，从而允许更好地控制添加更多的细节。ASP.NET 将追踪数据组织成一组表格。

#### **问题:为什么我们在。网？**

**答:**复选框用于获取用户的多个输入。用户可以从给定的选项中选择多个选项。在代码中，它被设置为是/否或真/假选项，当它被选中时，复选框的值为真，否则为假。

#### 问题:解释一下 ASP.NET 的 HTML 服务器控件？

**答:** HTML 服务器控件提供自动状态和服务器端事件管理。这些 HTML 元素具有属性 runat=server。HTML 服务器控件属性和输出与其等效的 HTML 标记相同。这些控件是在编译 ASP.NET 应用程序时编译的。

#### **问:简述国家管理在 ASP.NET 的应用？补充例子。**

**回答:** HTTP 是无状态的，即不记得用户的状态，例如，他以前访问过的网站、请求和 URL。但是，对于某些请求，我们需要保持应用状态直到结束，ASP.NET 有两种相同的方法:

*   客户端状态管理:在这种方法中，状态信息直接存储在客户机上。每当有用户请求时，所需的信息就会来回传递以满足请求和响应——例如，cookies、查询字符串。
*   服务器端状态管理:在这种方法中，状态信息存储在用户内存中。与客户端相比，服务器端有更多的安全域。应用程序状态和会话状态受服务器端状态管理，包括进程内、状态服务器和 SQL server。

#### **问题:描述 ASP 中的登录控件？此外，添加源代码和示例。**

**答:** Login control 提供了一个安全的登录解决方案，它具有用户界面和属性，可定制显示文本字段、消息以及忘记密码的链接和其他页面。

我们可以修改现有的 LoginControl 并选择格式。登录控件属性可以用 HTML 编写，如下所示:

```
<form id="form1" runat="server">  
 <div>  
 <asp:Login ID="Login1" runat="server" BackColor="#FFFFFF" BorderColor="#CDCC99" BorderStyle="Solid" BorderWidth="1px" Font-Names="Times New Roman" Font-Size="10pt">  
 <TitleTextStyle BackColor="#6B6B6B" Font-Bold="True" ForeColor="#E9967A" />  
 </asp:Login>  
 </div>  
</form>  
These can be set in CSS file too:
.LoginControl    
{    
      background-color:#FFFFFF;    
      border-color:#CDCC99;    
      border-style:solid;    
      border-width:1px;    
      font-family:Times New Roman;    
      font-size:10px;    
}
```

我们可以使用 CssClass 属性将 CSS 应用于控件:

```
<asp:Login ID="Login1" runat="server" CssClass="LoginControl">  
```

#### 问题:在 ASP.NET，“回发”是什么意思？

**答:**当用户采取某种动作(比如提交表单)将信息从页面通过 POST 方法发送到服务器进行处理时，就会发生回发。

#### 问题:简单解释一下 ASP.NET 页面的生命周期。

**回答:**ASP.NET 在每个页面的生命周期中都要经历一系列的阶段。

*   页面请求。用户请求一个页面。ASP.NET 决定是编译它还是从缓存中提供它。
*   页面开始。请求和响应对象被创建。
*   页面初始化。初始化所有页面控件，并应用所有主题。
*   页面加载。ASP.NET 使用视图状态和控件状态属性来设置控件属性。默认值在控件中设置。
*   回发事件处理。如果再次加载同一页面，将触发此事件。
*   渲染。ASP.NET 保存页面的视图状态，并将呈现的输出写入输出流。它发生在整个网页发送给用户之前。
*   卸载。呈现的页面被发送到客户端。ASP.NET 卸载页面属性并执行清理。所有不需要的对象都从内存中删除。

#### 问题:ASP.NET 的视图状态是什么？

**答:**视图状态是回发事件处理过程中，数据用来保存网页表单的页面值和控件值的地方。数据可以作为隐藏字段存储在客户端网页上。

#### **问题:自定义控件和用户控件有什么区别？**

**答案:**自定义控件基本都是编译好的代码，也就是 dll。这些可以很容易地添加到工具箱中，因此可以通过拖放的方式很容易地在多个项目中使用。这些控件相对来说很难创建。但是用户控件(。ascx)就像页面(。aspx)。这些相对容易创建，但是在用户界面和代码方面紧密耦合。

#### 问:ASP.NET 有哪些不同的验票员？

**答:**ASP.NET 验证控件定义了验证用户输入数据的重要角色。无论用户何时输入，在跨应用程序的不同层发送之前，都必须进行验证。ASP 中有两种类型的验证。网络:

*   客户端验证
*   服务器端验证

**客户端验证:**在客户端浏览器上进行验证时，称为客户端验证。您可以使用 JavaScript 来进行客户端验证。

**服务器端验证:**当验证发生在服务器上时，则称为服务器端验证。服务器端验证是一种安全的验证形式。服务器端验证的主要优点是，如果用户绕过了客户端验证，就可以在服务器端发现问题。

下面是 ASP 中的验证控件。网络:

*   RequiredFieldValidator 控件
*   比较验证器控制
*   RangeValidator 控件
*   正则表达式验证器控件
*   CustomFieldValidator 控件
*   验证摘要

#### 问:方法 Finalize 在 ASP.NET 有什么作用？

**答:**Finalize 方法用于对对象持有的非托管资源进行清理操作。它将一个对象放入终结队列。然后，该对象将被垃圾收集器收集起来，准备进行清理。

#### 问题:在 ASP.Net 什么是永久重定向？

**回答:** RedirectPermanent 执行从请求的 URL 到指定 URL 的永久重定向。重定向完成后，它还会向浏览器返回 http 301 状态代码。

#### **问题:LoginStatus 控件的作用是什么？**

**答:** LoginStatus 控件用于根据当前用户的登录/授权状态显示登录/注销链接。如果用户成功登录，将显示注销链接。

#### **问题:什么是 Repeater 控件，Repeater 支持哪些模板？**

**答:**中继器是数据绑定控件。数据绑定控件是容器控件。它在数据源和表示 UI 之间创建一个链接来显示数据。repeater 控件用于显示重复的项目列表。中继器有五个内联模板来格式化它:

*   显示数据源集合的标题文本，并对标题文本应用不同的样式。
*   更改数据源集合中交替项的背景色或样式。
*   它定义了如何从数据源集合中呈现每一项。
*   它将确定分隔项集合中每个项的分隔符元素。它可以是一个
    或

    * * *

    HTML 元素。
*   显示数据源集合的页脚元素。

#### 问:ASP.NET 有哪些不同的会话状态管理选项？

**答:**进程内和进程外是两种会话状态管理选项。

*   进程内将会话存储在 web 服务器的内存中。
*   进程外会话状态管理将数据存储在外部服务器中。存储在会话中的所有对象都需要是可序列化的。

#### **问题:服务器有什么区别。转移和响应。重定向？**

**回答:**服务器。Transfer 将信息从一个 web 请求发送到另一个 web 请求，所有这些都在服务器端。不会向浏览器发送响应。另一方面，[回应。Redirect](https://stackoverflow.com/questions/224569/server-transfer-vs-response-redirect) 向浏览器发送 HTTP 302 消息，并在浏览器中引起重定向。

#### **问题:什么是碎片缓存？**

**答:**片段缓存是指在一个 Web 表单内缓存单个用户控件。每个用户控件都可以有独立的缓存持续时间以及如何应用缓存行为的实现。当您只需要缓存页面的子集时，片段缓存非常有用。

#### 问:ASP.NET 的网络控制是什么？

**答:** Web 控件是。NET 框架。这些控件具有服务器可以理解的特殊标签。它们是在服务器上创建的，需要 run at="server "属性才能执行。它们生成 HTML 代码并发送回浏览器。

#### 问题:给出一些 web 控件的例子。

**答案:**

*   纽扣
*   日历
*   复选框列表
*   DropDownList
*   单选按钮列表

#### 问题:什么是 web 服务？

**答:**一个 Web 服务，在。NET 是一个驻留在 Web 服务器上的组件，它使用标准的 Web 协议(如 HTTP 和简单对象访问协议(SOAP ))向其他网络应用程序提供信息和服务。

#### **问题:会话和应用对象有什么区别？**

**答:**会话和应用对象的区别在于，所有用户共享一个应用对象，对于会话，每个用户有一个会话对象。存储在应用程序对象中的数据可以由应用程序的所有会话共享。应用程序对象将数据存储在键值对中。会话对象存储特定于会话的信息，这些信息仅在会话中可见。ASP.NET 为应用程序的每个会话创建唯一的 SessionId。根据应用程序配置设置中的设置，SessionIDs 由 HTTP cookie 或修改后的 URL 维护。默认情况下，SessionID 值存储在 cookies 中。

#### **问题:什么是缓存，使用缓存有什么好处？**

**答:**缓存是一种通过将数据存储在内存中以加快访问速度来提高应用程序性能的机制。当应用程序从缓存(即内存中)访问数据，而不是从原始数据存储(可能是数据库)获取数据时，它肯定会提高性能。但是缓存的好处不仅限于性能；它还提高了应用程序的可伸缩性和可用性。

#### 问:ASP.NET 有哪些认证类型？

**答:**ASP 中有三种认证方式。网络:

*   Windows 身份验证:这种身份验证方法使用内置的 Windows 安全功能对用户进行身份验证。
*   表单身份验证:根据自定义的用户列表或数据库中的用户进行身份验证。
*   Passport 身份验证:根据 Microsoft Passport 服务进行验证，这基本上是一种集中的身份验证服务。

#### 问题:什么是 ASP.NET 阿贾克斯？

**回答:**微软已经提供了一个名为 ASP.NET AJAX 的 AJAX 功能实现。AJAX 代表异步 JavaScript 和 XML。这是一种跨平台技术，可以加快响应时间，减少客户端和服务器之间的流量。ASP.NET AJAX 是 ASP.NET 的一组扩展，带有可重用的 AJAX 控件。

#### **问题:什么是 REST 架构？**

**答:**REST(representative State Transfer)是一种用于设计应用程序的架构风格，它规定使用 HTTP 进行通信调用，而不是像 CORBA、RPC 或 SOAP 这样的复杂机制。REST 架构风格有几个相关的原则:

*   一切都是资源，如文件、图像、视频、网页等。
*   每个资源都由唯一的标识符来标识。
*   使用简单统一的界面。
*   一切都是通过表示完成的(从客户机向服务器发送请求，从服务器向客户机接收响应)。
*   无状态——每个请求都应该是独立的请求。

#### **问题:ASP.NET 是跨平台解释。**

**回答:**ASP.NET 应用程序可以在任何操作系统上开发和运行，如 Windows、Linux、macOS 和 Docker。因此，它被称为跨平台框架。

#### **问题:剃刀在 ASP.NET 是什么东西**

**回答:** Razor 是一种标记语法，可以让你将基于服务器的代码(Visual Basic 和 C#)嵌入到网页中。当网页被写入浏览器时，基于服务器的代码可以动态地创建动态网页内容。当调用网页时，服务器在将页面返回给浏览器之前执行页面内基于服务器的代码。通过在服务器上运行，代码可以执行复杂的任务，比如访问数据库。Razor 基于 ASP.NET，为创建[网络应用](https://hackr.io/blog/web-application-architecture-definition-models-types-and-more)而设计。它具有传统 ASP.NET 标记的功能，但更容易使用和学习。

#### 问题:什么是 ASP.NET 核心？

**回答:** ASP **。** NET Core 是 ASP.NET 的开源跨平台版本。ASP.NET 的纯 Windows 版本，在 ASP.NET 核心之前就存在，通常被称为 ASP.NET。

在这里你可以下载[ASP.net 面试问题 PDF](https://hackr.io/blog/media/asp.pdf) 。

想在面试前复习一下你的 ASP.NET 吗？这个最好的 udemy 课程可以成为你准备 asset 面试的巨大财富:[完整的 ASP.NET MVC 5 课程](https://click.linksynergy.com/deeplink?id=jU79Zysihs4&mid=39197&murl=https://www.udemy.com/course/the-complete-aspnet-mvc-5-course/)。

通用编程问题是任何[编程面试](https://hackr.io/blog/programming-interview-questions)所固有的。这里有一本很棒的书，里面有顶级的编码和编程问答:[破解编码面试:189 个编程问答](https://geni.us/MmRP)。

**人也在读:**