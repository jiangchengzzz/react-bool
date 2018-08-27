# 可用性与可访问性

## 什么是web标准、可用性、可访问性

### 一、web标准  
　　简单的说，就是HTML、CSS、JavaScript这三者分离。WEB标准不是某一个标准，而是一系列标准的集合。网页主要由三部分组成：结构（Structure）、表现（Presentation）和行为（Behavior）。对应的标准也分三方面：结构化标准语言主要包括XHTML和XML，表现标准语言主要包括CSS，行为标准主要包括对象模型（如 W3C DOM）、ECMAScript等。
<hr>

**web标准的优点**：
* 代码的效率：在HTML文件中使用最精简的代码，而把样式和页面布局信息包含进CSS文件中。则放在服务器上的文件越小，下载文件需要的时间就越短。
* 易于维护：页面的样式和布局信息保存在单独的CSS文件中，如果你想改变站点的外观时，仅需要在单独的CSS文件中做出更改即可。整站统一css则可带来巨大的便利。
* 可访问性：上网用户中那些视力受损的人，通过屏幕阅读器使用键盘命令将网页的内容读给他们听。以语义化的HTML（结构和表现相分离的HTML）编写的网页文件，就可以让此类用户更容易导航，且网页文件中的重要信息也更有可能被这些用户找到。
* 设备兼容性：纯HTML，无附加样式信息，可以针对具有不同特点（如屏幕尺寸等）的设备而被重新格式化，只需要引用一套另外的样式表即可。同时，CSS本身也可以让你为不同的呈现方式和媒体类型（如在屏幕上阅读网页，打印网页，在移动设备上阅读网页等）规定不同的样式表。
* 网络爬虫/搜索引擎：搜索引擎使用“爬虫”，解析你的网页。语义化的HTML能更准确更快速的被解析，从而知道哪些才是重要的内容，那么你的网页在搜索结果中的排名就会大受影响。

### 二、可用性、可访问性
   可访问性就是对所有人一视同仁，无论他们是否有残障。
  
* 网站的用户类型：
  1. 身体健康的用户；
  2. 盲人或严重视觉障碍者，他们使用屏幕阅读器来听取网站，或者通过点字显示器来感知网页；
  3. 近视者，需要将字体大小放大到200%；
  4. 患有运动性残疾，因此无法用手操作鼠标，而用点击棒来操作键盘，或通过视线点击器来操作网站的用户；
  5. 使用移动设备如常用的手机，或使用跟踪球等不常见的计算机控制设备的用户。

* 实现可用性、可访问性的方法
  1. 逐步强化你的网站功能，同时对支持性进行测试。运用“渐进增强”和“平稳退化”原则开发网站。
  2. 允许用户关闭有问题的增强功能。
  3. 提供相同内容或功能的替代版本。
  4. 就客户端需要支持的技术向你的客户提出建议，并举例说明哪些公司的产品支持这些技术。
* 可访问性良好网页的特征
  1. HTML语义化、结构化：HTML语义结构提供了网页的整体框架，提示他们在文件层级中所处的位置，还有他们可以如何与各种页面元素进行交互，以及在适当的地方对文本内容进行强调，帮助用户获得大量重要信息。

* 四个可访问性标准（WCAG 2.0）：
  1. 可感知：人们可以通过适合自己的媒体来获知网页内容。比如应当让盲人得以收听页面内容。例如，图像应该有文本对应体。
  2. 可操作：人们可以与 web 应用程序或内容进行交互。例如，用户应该可以不用鼠标也能与某个网站进行交互，并且可以通过屏幕阅读器来进行导航。
  3. 可理解：使用者可以弄懂页面内容和用户界面。例如，正文不应该比它需要的更加复杂，且网站应以可预测的方式来运行。
  4. 健壮性：所提供的一切服务都应当不受平台或操作系统的限制。这样就可以避免人们提供一些不太完善的服务，这些服务会因为硬件/软件的限制而导致大多数人都无法使用。例如，不同设备上的浏览器能够一起使用网站，且导航应该是一致的。
  5. 说明：网站并不是必须满足全部这些要求，要视网站用户类型而定，但为了实现可访问性，网站应当确保其页面可以用一般的屏幕阅读技术读取。
  6. 总结：可访问性是网站开发质量的一个衡量标准。如果你在开发网站的时候（以及开始开发前）顾及你的使用用户的话，你就能创建可用性、可访问性更好、更符合web标准的网页，并且享受它所带来的一切好处。