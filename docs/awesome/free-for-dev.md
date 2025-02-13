<div class="github-widget" data-repo="ripienaar/free-for-dev"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## free-for.dev

开发人员和开放源代码作者现在拥有大量提供免费层的服务，但是很难找到所有这些层来做出明智的决定.

这是软件（SaaS，PaaS，IaaS等）和为开发人员提供免费套餐的其他产品的列表.

该特定列表的范围仅限于基础架构开发人员（系统管理员，DevOps实践人员等）可能会有用的事物. 我们喜欢那里的所有免费服务，但是最好还是保留它. 有时候这是一条灰色的线，所以这有点自以为是. 如果我不接受您的捐款，请不要冒犯.

此列表是900多个人的请求请求，评论，想法和工作的结果. 您也可以通过发送帮助 [Pull Requests](https://github.com/ripienaar/free-for-dev) 添加更多服务或删除产品已更改或已淘汰的服务.

 *注意：*此列表仅适用于即服务产品，不适用于自托管软件. 为了使服务合格，它必须提供免费套餐，而不仅仅是免费试用. 如果免费套餐有时间限制，则必须至少保留一年. 我们还从安全角度考虑免费层，因此SSO很好，但我将不接受将TLS限制为仅付费层的服务.

目录
=================


## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine-每天28个前端实例小时，每天9个后端实例小时
    * Cloud Firestore-1GB存储，每天50,000次读取，20,000次写入，每天20,000次删除
    * Compute Engine-每月1个不可抢占的f1-micro，30GB硬盘，5GB快照存储（仅限某些地区），每月从北美到所有区域目的地（中国和澳大利亚除外）的1GB网络出口
    *云存储-5GB，1GB网络出口
     * Cloud Shell-具有5GB持久存储的基于Web的Linux Shell /基本IDE. 每周限制60小时
    *云发布/订阅-每月10GB的邮件
    *云功能-每月2百万次调用（包括后台和HTTP调用）
    *云运行-每月200万个请求，360,000 GB-秒的内存，180,000 vCPU-秒的计算时间，每月从北美流出1 GB的网络
     * Google Kubernetes Engine-一个区域集群不收取集群管理费. 每个用户节点均按标准Compute Engine定价收费
    * BigQuery-每月1 TB的查询量，每月10 GB的存储量
    *云构建-每天120分钟构建
    *云源存储库-最多5个用户，50 GB存储，50 GB出口
    *完整详细的列表-https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * Amazon DynamoDB-25GB NoSQL数据库
    * Amazon Lambda-每月100万次请求
    * Amazon SNS-每月发布100万次
    * Amazon Cloudwatch-10个自定义指标和10个警报
    * Amazon Glacier-10GB长期对象存储
    * Amazon SQS-一百万个消息传递队列请求
    * Amazon CodeBuild-每月构建时间为100分钟
    * Amazon Code Commit-每月5位活跃用户
    * Amazon Code Pipeline-每月1条活动管道
    *完整的详细列表-https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) -1个B1S Linux VM，1个B1S Windows VM
    * [App Service](https://azure.microsoft.com/services/app-service/) -10个Web，移动或API应用
    * [Functions](https://azure.microsoft.com/services/functions/) -每月一百万个请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) -支持快速，轻松，精益的开发测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) -500,000个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) -每月存储50,000个用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) -5个活跃用户，无限制的私人Git仓库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) —针对Linux，macOS和Windows的开源软件，有10个免费的并行作业，且无限制地运行分钟
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) -每天8,000条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) -1个免费的公共负载平衡IP（VIP）
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) -一百万个推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) -每月5GB的出站流量
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) -5GB的存储空间和400 RU的预配置吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) —使用免费的SSL，身份验证/授权和自定义域来构建，部署和托管静态应用和无服务器功能
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS File or Blob storage
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) -具有免费层级的AI / ML API（计算机视觉，翻译器，面部检测，机器人等），包括有限的交易
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) -基于AI的搜索和索引服务，可免费处理10,000个文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) -托管的Kubernetes服务，免费的集群管理
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) -每月10万次运营
    *详细清单- [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    *计算-2个VM.Standard.E2.1.Micro 1GB RAM
    *块卷-2个卷，总计100 GB（用于计算）
    *对象存储-10 GB
    *负载平衡器-1个实例的10 Mbps
    *数据库-2个DB，每个20 GB
    *监视-5亿个摄取数据点，10亿个检索数据点
    *带宽-每月10 TB出口，速度限制为5 Mbps
    *通知-每月有100万个传递选项，每月发送1000封电子邮件
    *完整的详细列表-https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    *云功能-每月执行500万次
    *对象存储-每月25GB
    * Cloudant数据库-1 GB数据存储
    * Db2数据库-100MB数据存储
    * API Connect-每月50,000次API调用
    *可用性监视-每月300万个数据点
    *日志分析-每日日志500MB
    *完整的详细列表-https://www.ibm.com/cloud/free/

## Source Code Repos

  * [bitbucket.org](https://bitbucket.org/) —带有CI / CD管道的多达5个用户的无限公共和私人Git存储库
  * [chiselapp.com](http://chiselapp.com/) -无限的公共和私人化石仓库
  * [codebasehq.com](https://www.codebasehq.com/) —一个具有100 MB空间和2个用户的免费项目
  * [codeberg.org](https://codeberg.org/) -无限的公共和私人Git仓库
  * [gitea.com](https://www.gitea.com/) -无限的公共和私人Git仓库
  * [GitGud](https://gitgud.io)  —无限的私有和公共存储库. 永远免费. 由GitLab和Sapphire提供支持. 未提供CI / CD.
  * [github.com](https://github.com/)  —无限的公共存储库和无限的私人存储库（具有无限的协作者）. 除此之外，还提供了其他一些免费服务（还有更多免费服务，但我们在这里列出了主要的免费服务）：
       - [CI/CD](https://github.com/features/actions)（公共回购免费，私人回购免费2000分钟/月） 
       - [Static Website Hosting](https://pages.github.com) （公共回购免费）  
       - [Package Hosting & Container Registry](https://github.com/features/packages) （对于公共仓库是免费的，CI / CD之外有500 MB的存储空间和1GB的带宽，对于私人仓库是免费的）
       -项目管理和问题跟踪.
  * [gitlab.com](https://about.gitlab.com/)  -无限的合作者，无限的公共和私人Git仓库. 还提供以下功能：
       - [CI/CD](https://about.gitlab.com/product/continuous-integration) （公共回购免费，私人回购每月400分钟）
       -具有的静态网站 [GitLab Pages](https://about.gitlab.com/product/pages).
       -容器注册表，每个回购限制为10 GB.
       -项目管理和问题跟踪.
  * [heptapod.net](https://foss.heptapod.net/) — Heptapod是GitLab社区版的友好分支，为Mercurial提供支持
  * [ionicframework.com](https://ionicframework.com/appflow) -回购和使用Ionic开发应用程序的工具，您也拥有离子回购
  * [NotABug](https://notabug.org) — NotABug.org是用于基于Git的免费许可项目的免费软件代码协作平台
  * [Pagure.io](https://pagure.io) — Pagure.io是一个免费的开源软件代码协作平台，用于基于Git的FOSS许可项目
  * [perforce.com](https://www.perforce.com/products/helix-teamhub) —免费的1GB Cloud and Git，Mercurial或SVN存储库.
  * [pijul.com](https://pijul.com/)  -无限的免费和开源分布式版本控制系统. 它的独特功能是建立在可靠的补丁理论基础上的，这使得它易于学习和使用，并且真正地分发. 解决了git / hg / svn / darcs的许多问题.
  * [plasticscm.com](https://plasticscm.com/) —对个人，OSS和非营利组织免费
  * [projectlocker.com](https://projectlocker.com) —一个免费的私人项目（Git和Subversion），具有50 MB的空间
  * [RocketGit](https://rocketgit.com)  —基于Git的存储库托管. 无限的公共和私人存储库.
  * [savannah.gnu.org](https://savannah.gnu.org/) -用作免费软件项目的协作软件开发管理系统（适用于GNU项目）
  * [savannah.nongnu.org](https://savannah.nongnu.org/) -用作免费软件项目的协作软件开发管理系统（适用于非GNU项目）

## APIs, Data and ML

  * [IP.City](https://ip.city) —每天100个免费IP地理位置请求
  * [Abstract API](https://www.abstractapi.com) —适用于各种用例的API套件，包括IP地理位置，性别检测甚至电子邮件验证.
  * [algorithmia.com](https://algorithmia.com/)  —免费的主机算法. 包括免费的每月津贴，用于运行算法. 现在具有CLI支持.
  * [Apify](https://www.apify.com/)  — Web抓取和自动化平台，可让您创建提取网站数据的API. 免费套餐，每月抓取1万次，数据保留7天.
  * [API Mocha](https://apimocha.com)  -完全免费的在线API模拟，用于测试和原型制作. 每天最多处理500个请求，完全可自定义API响应，将模拟规则下载为Postman集合.
  * [APITemplate.io](https://apitemplate.io)  -使用简单的API或Zapier＆Airtable等自动化工具自动生成图像和PDF文档. 无需CSS / HTML. 免费计划随附每月50张图片和3个模板.
  * [Atlas toolkit](https://atlastk.org/)  -轻量级库，用于开发可立即访问的单页Web应用程序. 适用于Java，Node.js，Perl，Python和Ruby.
  * [Beeceptor](https://beeceptor.com)  -在几秒钟内模拟其余的API，伪造的API响应等等. 每天免费50个请求，公共仪表板，开放的端点（任何链接到仪表板的人都可以查看请求和响应）.
  * [bigml.com](https://bigml.com/)  —托管的机器学习算法. 无限的免费任务可供开发，每个任务限制为16 MB数据.
  * [Calendarific](https://calendarific.com)  -适用于200多个国家/地区的企业级公共假日API服务. 免费计划包括每月1000次通话.
  * [Clarifai](https://www.clarifai.com)  —用于自定义面部识别和检测的图像API. 能够训练AI模型. 免费计划每月有5000个通话.
  * [Cloudmersive](https://cloudmersive.com/) — Utility API平台，可完全访问扩展的API库，包括文档转换，病毒扫描等，每月可调用800次.
  * [Colaboratory](https://colab.research.google.com) —带有Nvidia Tesla K80 GPU的免费基于Web的Python笔记本环境.
  * [Collect2](https://collect2.com)  —创建一个API端点以测试，自动化和连接Webhook. 免费计划允许两个数据集，2000条记录，1个转发器和1个警报.
  * [Conversion Tools](https://conversiontools.io/)  -用于文件，图像，视频，音频，电子书的在线文件转换器.  REST API可用. 适用于Node.js，PHP，Python的库. 支持文件最大为50 GB（用于付费计划）. 免费套餐受文件大小和每天的转换次数限制.
  * [CurlHub](https://curlhub.io)  —用于检查和调试API调用的代理服务. 免费计划包括每月10,000个请求.
  * [CurrencyScoop](https://currencyscoop.com)  -金融科技应用程序的实时货币数据API. 免费计划包括每月5000次通话.
  * [Datapane](https://datapane.com) -用于在Python中构建交互式报表以及将Python脚本和Jupyter Notebook作为自助工具部署的API.
  * [DB Designer](https://www.dbdesigner.net/) —基于云的数据库模式设计和建模工具，具有2个数据库模型和每个模型10个表的免费入门计划.
  * [Diggernaut](https://www.diggernaut.com/)  —基于云的Web抓取和数据提取平台，用于将任何网站转换为数据集或与API一起使用. 免费计划包括每月5K页面的请求.
  * [Disease.sh](https://disease.sh/) —一个免费的API，可提供准确的数据来构建Covid-19相关有用的应用程序.
  * [dominodatalab.com](https://www.dominodatalab.com) —数据科学，支持Python，R，Spark，Hadoop，MATLAB等.
  * [dreamfactory.com](https://dreamfactory.com/)  —适用于移动，Web和IoT应用程序的开源REST API后端. 连接任何SQL / NoSQL数据库，文件存储系统或外部服务，它会立即创建一个全面的REST API平台，其中包含实时文档，用户管理，...
  * [Efemarai](https://efemarai.com)  -用于ML模型和数据的测试和调试平台. 可视化任何计算图. 每月为开发人员提供30个调试会话.
  * [ETF Data API](https://etf-data.com/)  -每天更新的优质欧洲ETF，ETN和ETC数据.  API提供了完整的概述，包括行业，国家，因素，股息收益率和估值. 此外，还提供基本信息，例如住所，住所索引，资产类别，费用，货币，复制方法，分配类型和频率. 每天50次免费API调用.
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) -免费的基于Web的HTTP客户端发送HTTP请求.
  * [FraudLabs Pro](https://www.fraudlabspro.com)  —筛选用于信用卡付款欺诈的订单交易.  REST API将基于订单的输入参数检测所有可能的欺诈特征. 免费Micro计划每月有500笔交易.
  * [FreeGeoIP.app](https://freegeoip.app/)  -完全免费的地理IP信息（JSON，CSV，XML）. 无需注册，每小时15,000个查询的速率限制.
  * [GeoDataSource](https://www.geodatasource.com)  —通过纬度和经度坐标查找城市名称的位置搜索服务. 免费的API查询，每月最多可进行500次.
  * [Hookbin](https://hookbin.com/)  -创建唯一的（公共或私有）端点，以收集，解析和检查HTTP请求. 检查标题，正文，查询字符串，Cookie，上传的文件等.对于测试/检查Webhook非常有用. 类似于RequestBin和Webhook.site.
  * [Hoppscotch](https://hoppscotch.io) -一个免费，快速，美观的API请求构建器.
  * [Invantive Cloud](https://cloud.invantive.com/)  —使用Invantive SQL或OData4（通常是Power BI或Power Query）访问70多个（云）平台，例如Exact Online，Twinfield，ActiveCampaign或Visma. 包括数据复制和交换. 开发人员和实施顾问的免费计划. 对于数据量有限的特定平台免费.
  * [IP Geolocation](https://ipgeolocation.io/) — IP地理位置API-永久免费计划，适用于每月限制3万个请求（每天1k /天）的开发人员.
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) —抽象的IP地理位置API-广泛的免费计划，每月允许200,000个请求.
  * [IP2Location](https://www.ip2location.com)  — Freemium IP地理位置服务.  LITE数据库可免费下载. 将数据库导入服务器，并执行本地查询以确定城市，坐标和ISP信息.
  * [ipapi](https://ipapi.co/)  -由Kloudend，Inc提供的IP地址位置API-基于AWS的可靠地理定位API，受财富500强公司信任.免费套餐每月提供30k的查询，无需注册. 请与我们联系以获取更高限制的试用计划.
  * [IPinfo](https://ipinfo.io/)  —快速，准确，免费（每月最多10万个）IP地址数据API. 提供有关地理位置，公司，运营商，IP范围，域，滥用联系人等详细信息的API. 所有付费API均可免费试用.
  * [IPList](https://www.iplist.cc)  —有关任何IP地址的查询详细信息，例如Geo IP信息，tor地址，主机名和ASN详细信息. 个人和企业用户免费.
  * [BigDataCloud](https://www.bigdatacloud.com/) - Provides fast, accurate and free (Unlimited or up to 10K-50K/month) APIs for modern web like IP Geolocation, Reverse Geocoding, Networking Insights, Email and Phone Validation, Client Info and more.
  * [IPTrace](https://iptrace.io) —令人尴尬的简单API，可为您的业务提供可靠且有用的IP地理位置数据.
  * [JSON IP](https://getjsonip.com)  —返回请求其的客户端的公共IP地址. 免费套餐无需注册. 可以直接使用浏览器的客户端JS请求使用CORS数据. 对于监视客户端和服务器IP中的更改的服务很有用. 无限请求.
  * [konghq.com/](https://konghq.com/)  — API市场以及用于私有和公共API的强大工具. 使用免费套餐时，某些功能会受到限制，例如监视，警报和支持.
  * [Kreya](https://kreya.app)  —免费的gRPC GUI客户端来调用和测试gRPC API. 可以通过服务器反射导入gRPC API.
  * [MailboxValidator](https://www.mailboxvalidator.com)  —使用真实邮件服务器连接的电子邮件验证服务，以确认有效的电子邮件. 免费的API计划每月有300个验证.
  * [microlink.io](https://microlink.io/) – It turns any website into data such as metatags normalization, beauty link previews, scraping capabilities or screenshots as a service. 100 reqs/day every day free.
  * [monkeylearn.com](https://monkeylearn.com/) —带有机器学习的文本分析，每月免费300次查询.
  * [MockAPI](https://www.mockapi.io/)  — MockAPI是一个简单的工具，可让您轻松地模拟API，生成自定义数据并使用RESTful接口对其执行操作.  MockAPI旨在用作原型设计/测试/学习工具.  1个项目/每个项目50个免费资源.
  * [microenv.com](https://microenv.com) —为开发人员创建伪造的REST API，并有可能在Docker容器中生成代码和应用程​​序.
  * [News API](https://newsapi.org)  —使用代码在网络上搜索新闻，以获取JSON结果. 开发人员每月可免费获得3,000个查询.
  * [OCR.Space](https://ocr.space/)  —一个OCR API，用于解析图像和pdf文件，并以JSON格式返回文本结果. 每月免费提供25,000个请求.
  * [OpenAPI3 Designer](https://openapidesigner.com/) —可视地免费创建Open API 3定义.
  * [parsehub.com](https://parsehub.com/) —从动态网站提取数据，将动态网站转换为API，免费提供5个项目.
  * [Pixela](https://pixe.la/)  -免费的日流数据库服务. 所有操作均由API执行. 热图和折线图的可视化也是可能的.
  * [Postbacks](https://postbacks.io/)  -稍后请求HTTP回调. 注册时有8,000个免费请求.
  * [Postman](https://postman.com)  —通过Postman（用于API开发的协作平台）简化工作流程并更快地创建更好的API. 永久免费使用Postman App. 邮递员云功能也是永久免费的，有一定的限制.
  * [ProxyCrawl](https://proxycrawl.com/) — Crawl and scrape websites without the need of proxies, infrastructure or browsers. We solve captchas for you and prevent you being blocked. The first 1000 calls are free of charge.
  * [QuickMocker](https://quickmocker.com/)  —在您自己的子域下管理在线虚假API端点，将请求转发到localhost URL以进行Webhooks开发和测试，使用RegExp和多种HTTP方法进行URL路径，对端点进行优先级划分，使用100多个短代码（动态或虚假响应值）进行响应模板化，从JSON格式的OpenAPI（Swagger）规范导入，代理请求，通过IP地址和授权标头限制端点. 免费帐户提供1个随机子域，10个终结点，5个RegExp URL路径，每个终结点50个简码，每天100个请求，请求日志中的50条历史记录.
  * [RequestBin.com](https://requestbin.com)  —创建一个可以向其发送HTTP请求的免费端点. 发送到该端点的所有HTTP请求都将与相关的有效负载和标头一起记录，因此您可以观察来自Webhooks和其他服务的请求.
  * [restlet.com](https://restlet.com/products/apispark/) — APISpark使任何API，应用程序或数据所有者都可以通过直观的浏览器界面在几分钟之内成为API提供者.
  * [Roboflow](https://roboflow.com)  -创建和部署自定义计算机视觉模型，而无需事先的机器学习经验. 免费套餐包括多达1,000个免费源图像.
  * [ROBOHASH](https://robohash.org/) -Web服务，可从任何文本生成唯一的（很酷的：）图像.
  * [Scraper.AI](https://scraper.ai)  -SaaS，可将任何网站转变为可消耗的API，供您继续使用. 每月免费提供50次提取和10000次API调用.
  * [Scraper API](https://www.scraperapi.com/)  —基于云的Web抓取API处理代理，浏览器和验证码. 只需简单的API调用即可抓取任何网页. 每月开始1000次免费API调用.
  * [ScrapingAnt](https://scrapingant.com/)  —无头Chrome抓取API和免费的已检查代理服务.  Javascript渲染，高级旋转代理，避免使用CAPTCHA. 提供免费计划.
  * [ScraperBox](https://scraperbox.com/)  —使用真实的Chrome浏览器和代理轮播无法检测到Web抓取API. 使用简单的API调用即可抓取任何网页. 免费计划每月有1000个请求.
  * [ScrapingDog](https://scrapingdog.com/)  — Scrapingdog可处理数百万个代理，浏览器和验证码，以在单个API调用中为您提供任何网页的HTML. 它还提供了适用于Chrome和Firefox的Web抓取工具以及可即时满足抓取需求的软件. 提供免费计划.
  * [scrapinghub.com](https://scrapinghub.com)  —通过可视界面和插件进行数据抓取. 免费计划包括在共享服务器上无限刮取.
  * [ScrapingNinja](https://www.scrapingninja.co/)  -一站式处理JS渲染，Chrome无头，代理旋转和验证码. 前1000个是免费的，不需要信用卡.
  * [Sheetson](https://sheetson.com)  -立即将所有Google表格转换为RESTful API. 提供免费计划.
  * [shrtcode API](https://shrtco.de/docs) -未经授权且没有请求限制的免费URL缩短API.
  * [Similar Words API](https://word-simi.herokuapp.com/) —查找相似单词的API，词汇量约为400万个单词.
  * [Sofodata](https://www.sofodata.com/)  -从CSV文件创建安全的RESTful API. 上传CSV文件并通过其API立即访问数据，从而加快应用程序开发速度. 免费计划包括每月2个API和2500个API调用. 无需信用卡.
  * [tamber](https://tamber.com)  —在应用程序中添加基于深度学习的建议. 免费的5k每月活跃用户.
  * [Time Door](https://timedoor.io) -时间序列分析API.
  * [TinyMCE](https://www.tiny.cloud)  -富文本编辑API. 免费提供核心功能，可无限制使用.
  * [Unixtime](https://unixtime.co.za) -免费的API，可将Unixtime转换为DateTime，反之亦然.
  * [Vattly](https://vattly.com/)  -高可用性，快速和安全的VAT验证API，可提供完整的欧盟覆盖范围. 每天10次免费API调用.
  * [Webhook.site](https://webhook.site) -使用这个方便的工具，可以立即显示请求，轻松测试HTTP webhooks.
  * [wit.ai](https://wit.ai/) — NLP for developers.
  * [wolfram.com](http://wolfram.com/language/) —在云中内置基于知识的算法.
  * [wrapapi.com](https://wrapapi.com/)  —将任何网站转换为参数化的API. 每月30k API调用.
  * [Zenscrape](https://zenscrape.com/web-scraping-api)  —具有无头浏览器，住宅IP和简单定价的Web抓取API. 每月1000次免费API调用，为学生和非营利组织提供额外的免费信用.
  * [ip-api](https://ip-api.com) — IP Geolocation API，免费用于非商业用途，不需要API密钥，从免费计划的同一IP地址开始，限制为每分钟45 req /分钟.
  * [WebScraping.AI](https://webscraping.ai)  -带有内置解析，Chrome渲染和代理的简单Web Scraping API. 每月5000次免费API调用.
  * [Zipcodebase](https://zipcodebase.com)  -免费的邮政编码API，可访问全球邮政编码数据. 每月10000个免费请求.
  * [EVA](http://eva.pingutil.com/) -免费的电子邮件验证器API，可帮助您确定电子邮件是否为一次性邮件以及是否具有有效的MX记录.
  * [happi.dev](https://happi.dev)  -免费增值api服务集合（音乐，汇率，键值存储，语言检测，密码生成器，QRCode生成器，歌词）. 每月有8000次免费API调用.

## Artifact Repos

 * [central.sonatype.org](https://central.sonatype.org) — Apache Maven，SBT和其他构建系统的默认工件存储库.
 * [cloudrepo.io](https://cloudrepo.io)  -基于云的私有和公共Maven和PyPi存储库. 对于开源项目免费.
 * [cloudsmith.io](https://cloudsmith.io)  —适用于Java / Maven，RedHat，Debian，Python，Ruby，Vagrant +的简单，安全和集中的存储库服务. 免费套餐+免费开源.
 * [jitpack.io](https://jitpack.io/) — GitHub上的JVM和Android项目的Maven存储库，公共项目免费.
 * [packagecloud.io](https://packagecloud.io) —易于使用的存储库托管，用于：Maven，RPM，DEB，PyPi和RubyGem软件包（具有免费层）.
 * [repsy.io](https://repsy.io) — 1 GB的免费私有/公共Maven存储库.

## Tools for Teams and Collaboration

  * [3Cols](https://3cols.com/) -一个免费的基于云的代码片段管理器，用于个人和协作代码.
  * [Bitwarden](https://bitwarden.com) —个人，团队和业务组织存储，共享和同步敏感数据的最简单，最安全的方法.
  * [Braid](https://www.braidchat.com/)  —专为团队设计的聊天应用程序. 免费提供给公共访问组，无限的用户，历史记录和集成. 它还提供了可自我托管的开源版本.
  * [cally.com](https://cally.com/)  —找到会议的最佳时间和日期. 简单易用，非常适合小型和大型团体.
  * [Discord](https://discordapp.com/)  —与公共/私人房间聊天.  Markdown文本，语音，视频和屏幕共享功能. 无限用户免费.
  * [evernote.com](https://evernote.com/)  —用于组织信息的工具. 分享您的笔记并与他人一起工作
  * [featurepeek.com](https://featurepeek.com)  -内置团队协作工具的，与云提供商无关的前端功能环境. 与静态和Dockerized前端一起使用. 免费提供公共存储库.
  * [Fibery](https://fibery.io/)  —连接的工作区平台. 单用户免费，最多2 GB磁盘空间.
  * [Filestash](https://www.filestash.app) —类似于Dropbox的文件管理器，可连接到一系列协议和平台：S3，FTP，SFTP，Minio，Git，WebDAV，Backblaze，LDAP等.
  * [flock.com](https://flock.com)  —您的团队进行交流的更快方式. 免费的无限制消息，频道，用户，应用程序和集成
  * [flowdock.com](https://www.flowdock.com/) —聊天和收件箱，最多5个团队免费
  * [GitDuck](https://gitduck.com/)  —用于分布式团队的专用实时编码和远程配对编程. 开源工具
  * [gitter.im](https://gitter.im/)  —聊天，适用于GitHub. 无限的公共和私人房间，最多25人的团队免费
  * [hangouts.google.com](https://hangouts.google.com/) —一个地方可以免费使用Google帐户进行所有对话
  * [helplightning.com](https://www.helplightning.com/)  —通过增强现实技术帮助解决视频问题. 免费，无需分析，加密和支持
  * [ideascale.com](https://ideascale.com/) —允许客户提交想法和投票，一个社区中的25名成员免费
  * [Igloo](https://www.igloosoftware.com/) —用于共享文档，博客和日历等的内部门户.最多10个用户免费.
  * [Keybase](https://keybase.io/) — Keybase是Slack的一个很酷的FOSS替代品，它可以确保从家庭到社区到公司的每个人的聊天和文件安全.
  * [Google Meet](https://meet.google.com/)  —使用Google Meet满足您企业在线视频会议的需求.  Meet提供安全，易于加入的在线会议.
  * [meet.jit.si](https://meet.jit.si/) —一键式视频对话，屏幕共享，免费
  * [Microsoft Teams](https://products.office.com/microsoft-teams/free)  — Microsoft Teams是一个基于聊天的数字中心，可将一次对话，内容和应用程序集中到一个地方. 多达50万名用户免费.
  * [Miro](https://miro.com/)  -适用于分布式团队的可扩展，安全，跨设备和企业就绪的团队协作白板. 有免费增值计划.
  * [Notion](https://www.notion.so/)  -概念是一个记笔记和协作应用程序，具有降价支持，还集成了任务，Wiki和数据库. 该公司将该应用程序描述为一个多功能的工作空间，用于记笔记，项目管理和任务管理. 除了跨平台应用程序之外，还可以通过大多数Web浏览器进行访问.
  * [Nuclino](https://www.nuclino.com)  -一个轻量级的协作式Wiki，适用于您团队的所有知识，文档和注释. 免费计划，具有所有基本功能，最多50个项目，总存储空间为5GB.
  * [Pendulums](https://pendulums.io/) -Pendulums是一个免费的时间跟踪工具，可通过易于使用的界面和有用的统计信息帮助您更好地管理时间.
  * [Raindrop.io](https://raindrop.io)  -适用于macOS，Windows，Android，iOS和Web的私有安全书签应用程序. 免费的无限书签和协作.
  * [element.io](https://element.io/)  —基于Matrix的去中心化开放源代码通信工具. 群组聊天，直接消息传递，加密的文件传输，语音和视频聊天，以及与其他服务的轻松集成.
  * [Rocket.Chat](https://rocket.chat/) -团队共享的收件箱，安全，无限且开源.
  * [seafile.com](https://www.seafile.com/)  —私有或云存储，文件共享，同步，讨论. 私人版本已满. 云版本只有1 GB
  * [Slab](https://slab.com/)  —为团队提供的现代知识管理服务. 免费（最多10位用户）.
  * [slack.com](https://slack.com/) —具有某些功能限制的无限用户免费
  * [Spectrum](https://spectrum.chat/) -免费创建公共或私人社区.
  * [StatusPile](https://www.statuspile.com/)  -状态页的状态页. 跟踪上游提供商的状态页.
  * [talky.io](https://talky.io/)  —免费的小组视频聊天. 匿名的. 点对点. 无需插件，注册或付款
  * [Tefter](https://tefter.io)  -具有强大的Slack集成的书签应用程序. 开源团队免费.
  * [TeleType](https://teletype.oorja.io/) — share terminals, voice, code, whiteboard and more. no sign-in required, end-to-end encrypted collaboration for developers.
  * [Tree Schema](https://treeschema.com/)  —使用API​​的数据目录和元数据管理，以代码形式管理数据沿袭. 最多可容纳5位用户的团队免费.
  * [twist.com](https://twist.com)  —异步友好的团队交流应用程序，其中的对话保持井井有条，并保持在主题上. 提供免费和无限计划. 为符合条件的团队提供折扣.
  * [typetalk.com](https://www.typetalk.com/) -通过网络或手机上的即时消息与团队共享和讨论想法
  * [Tugboat](https://tugboat.qa)  -预览每个自动和按需的拉取请求. 所有人免费，非营利组织免费提供Nano层.
  * [whereby.com](https://whereby.com/) —免费的一键式视频对话（以前称为“ appear.in”）
  * [userforge.com](https://userforge.com/)  -互连的在线角色，用户故事和上下文映射. 帮助保持设计和开发同步，最多免费提供3个角色和2个协作者.
  * [wistia.com](https://wistia.com/) —使用查看器分析，高清视频交付和营销工具来托管视频，以帮助了解您的访客，25个视频和Wistia品牌播放器
  * [wormhol.org](https://www.wormhol.org/)  —简单明了的文件共享服务. 与您想共享的同级共享多达5GB的无限文件.
  * [zoom.us](https://zoom.us/)  —安全的视频和Web会议，可以使用附加组件. 免费限时40分钟
  * [shtab.app](https://shtab.app/) -项目管理服务，可在办公室进行协作，并通过基于AI的跟踪器实现远程透明.
  * [Zulip](https://zulip.com/)  —通过独特的类似电子邮件的线程模型进行实时聊天. 免费计划包括10,000条搜索历史记录消息和高达5 GB的文件存储空间. 它还提供了可自我托管的开源版本.

## CMS

  * [acquia.com](https://www.acquia.com/)  —托管Drupal网站. 开发人员的免费套餐. 还提供免费的开发工具（例如Acquia Dev Desktop）
  * [Contentful](https://www.contentful.com/)  —无头CMS. 云中的内容管理和交付API. 带有一个免费的社区空间，其中包括5个用户，25K记录，48种内容类型和2个语言环境.
  * [Cosmic](https://www.cosmicjs.com/) — Headless CMS and API toolkit. Free personal plans for developers.
  * [Crystallize](https://crystallize.com)  —具有电子商务支持的无头PIM. 内置GraphQL API. 免费版包括无限的用户，1000个目录项，每月5 GB的带宽和每月25k的API调用.
  * [Forestry.io/](https://forestry.io/)  —无头CMS. 给您的编辑人员Git的力量. 轻松创建和编辑基于Markdown的内容. 带有三个免费站点，其中包括3个编辑器，即时预览. 与Netlify / GitHubpages /上托管的博客集成
  * [kontent.ai](https://www.kontent.ai)  -内容即服务平台，可为您提供所有无用的CMS好处，同时为营销人员提供支持. 开发人员计划为2个用户提供了无限的项目，每个项目有2个环境，500个内容项，2种语言（带有交付和管理API）以及自定义元素支持. 可以提供更大的计划来满足您的需求.
  * [Prismic](https://www.prismic.io/)  —无头CMS. 具有完全托管的可扩展API的内容管理界面. 社区计划为1位用户提供了无限的API调用，文档，自定义类型，资产和语言环境. 下一个项目所需的一切. 适用于开放内容/开放源代码项目的更大的免费计划.
  * [sanity.io](https://www.sanity.io/)  –使用React构建的可定制的MIT许可编辑器托管结构化内容的后端. 无限的项目.  3个用户，2个数据集，500k API CDN请求，每个项目免费5GB资产
  * [sensenet](https://sensenet.com)  -API首创的无头CMS，可为各种规模的企业提供企业级解决方案. 开发人员计划提供3个用户，500个内容项，3个内置角色，25 + 5个内容类型，完全可访问的REST API，文档预览生成和Office Online编辑.
  * [GraphCMS](https://graphcms.com/)  -为小型项目提供免费套餐.  GraphQL第一个API. 从传统解决方案转移到GraphQL原生Headless CMS-并首先提供全渠道内容API.


## Code Quality

  * [beanstalkapp.com](https://beanstalkapp.com/) —完整的工作流，用于编写，查看和部署代码），1个用户的免费帐户和1个具有100 MB存储空间的存储库
  * [browserling.com](https://www.browserling.com/) —实时交互式跨浏览器测试，在1024 x 768分辨率下，在Vista下使用MS IE 9仅免费提供3分钟的会话
  * [codacy.com](https://www.codacy.com/) —针对PHP，Python，Ruby，Java，JavaScript，Scala，CSS和CoffeeScript的自动代码审查，免费提供无限制的公共和私有存储库
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev)  -用于DevOps的作为代码审查工具的自动化基础架构与GitHub，Bitbucket和GitLab（甚至是自托管）集成. 除了标准语言外，它还分析Ansible，Terraform，CloudFormation，Kubernetes等.  （免费开源）
  * [CodeBeat](https://codebeat.co)  —适用于多种语言的自动代码审查平台. 通过Slack和电子邮件集成，永久免费提供公共存储库.
  * [codeclimate.com](https://codeclimate.com/)  —自动化代码审查，免费提供给开源和不受组织限制的私人私有存储库（最多4个协作者）. 对学生和机构也免费.
  * [codecov.io](https://codecov.io/) —代码覆盖率工具（SaaS），免费提供给开源和1个免费的私有仓库
  * [CodeFactor](https://www.codefactor.io)  — Git的自动代码审查. 免费版包括无限的用户，无限的公共存储库和1个私人存储库.
  * [codescene.io](https://codescene.io/)  -CodeScene根据开发人员使用代码的方式对技术债务进行优先排序，并可视化团队耦合和系统精通等组织因素. 免费提供开源.
  * [coveralls.io](https://coveralls.io/) —显示测试覆盖率报告，免费提供给开源
  * [dareboost](https://dareboost.com) -每月提供5份关于网络性能，可访问性和安全性的免费分析报告
  * [deepcode.ai](https://www.deepcode.ai)  — DeepCode基于AI查找错误，安全漏洞，性能和API问题.  DeepCode的分析速度使我们能够实时分析您的代码，并在您单击IDE中的“保存”按钮时提供结果. 支持的语言是Java，C / C ++，JavaScript，Python和TypeScript. 与GitHub，BitBucket和Gitlab的集成. 免费提供开源和私有存储库，最多释放30位开发人员.
  * [deepscan.io](https://deepscan.io) —先进的静态分析，可自动发现JavaScript代码中的运行时错误，免费提供给开源
  * [DeepSource](https://deepsource.io/)  -DeepSource持续分析源代码更改，查找并修复在安全性，性能，反模式，错误风险，文档和样式下分类的问题. 与GitHub，GitLab和Bitbucket的本机集成.
  * [eversql.com](https://www.eversql.com/) — EverSQL - The #1 platform for database optimization. Gain critical insights into your database and SQL queries, auto-magically.
  * [gerrithub.io](https://review.gerrithub.io/) —可以免费查看GitHub存储库的Gerrit代码
  * [gocover.io](https://gocover.io/) —任何代码覆盖率 [Go](https://golang.org/) 包裹
  * [goreportcard.com](https://goreportcard.com/) — Go项目的代码质量，开源免费
  * [gtmetrix.com](https://gtmetrix.com/) -报告和详尽的建议，以优化网站
  * [holistic.dev](https://holistic.dev/) - The #1 static code analyzer for Postgresql optimization. Performance, security, and architect database issues automatic detection service
  * [houndci.com](https://houndci.com/) —对GitHub提交的有关代码质量的评论，免费提供给开源
  * [Imgbot](https://github.com/marketplace/imgbot)  — Imgbot是一个友好的机器人，可以优化您的图像并节省时间. 优化的图像意味着较小的文件大小而不会牺牲质量. 它是免费的开放源代码.
  * [Kritika](https://kritika.io/)  — Perl的静态代码分析，具有与GitHub集成的功能. 免费提供无限的公共存储库.
  * [resmush.it](https://resmush.it)  — reSmush.it是提供图像优化的免费API.  reSmush.it已在最常见的CMS（例如Wordpress，Drupal或Magento）上实现.  reSmush.it是最常用的图像优化API，已经处理了超过70亿张图像，并且仍然免费.
  * [insight.sensiolabs.com](https://insight.sensiolabs.com/) — PHP / Symfony项目的代码质量，开放源代码免费
  * [lgtm.com](https://lgtm.com) — Continuous security analysis for Java, Python, JavaScript, TypeScript, C#, C and C++, free for Open Source
  * [reviewable.io](https://reviewable.io/) — GitHub存储库的代码审查，免费提供给公共或个人仓库
  * [parsers.dev](https://parsers.dev/) -抽象语法树解析器和中间表示形式的编译器即服务
  * [scan.coverity.com](https://scan.coverity.com/) — Static code analysis for Java, C/C++, C# and JavaScript, free for Open Source
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) —连续检查平台，免费提供给开源
  * [shields.io](https://shields.io) —开源项目的质量元数据徽章
  * [Sider](https://sider.review)  -适用于多种语言的代码审查平台. 支持与GitHub集成. 对于拥有无限用户的公共存储库免费.
  * [sonarcloud.io](https://sonarcloud.io) — Automated source code analysis for Java, JavaScript, C/C++, C#, VB.NET, PHP, Objective-C, Swift, Python, Groovy and even more languages, free for Open Source
  * [SourceLevel](https://sourcelevel.io/)  —自动化的代码审查和团队分析. 免费提供给开放源代码和最多5个协作者的组织.
  * [Typo CI](https://github.com/marketplace/typo-ci) — Typo CI会检查您的请求请求和提交是否存在拼写错误，并且可免费使用开放源代码.
  * [webceo.com](https://www.webceo.com/) -SEO工具，但也具有代码验证和不同类型的建议
  * [zoompf.com](https://zoompf.com/) — Fix the performance of your web sites, detailed analysis

## Code Search and Browsing

  * [codota.com](https://www.codota.com/)  — Codota通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件. 插件可用.
  * [libraries.io](https://libraries.io/) —针对32个不同程序包管理器的搜索和依赖项更新通知，免费提供给开源
  * [Namae](https://namae.dev/) -搜索各种网站，如github，gitlab，heroku，netlify等，以获取您的项目名称的可用性.
  * [searchcode.com](https://searchcode.com/) —全面的基于文本的代码搜索，免费提供给开源
  * [sourcegraph.com](https://about.sourcegraph.com/) -Java，Go，Python，Node.js等，代码搜索/交叉引用，免费提供给开源
  * [tickgit.com](https://www.tickgit.com/) —显示“ TODO”注释（和其他标记）以标识值得返回以进行改进的代码区域.
  * [CodeKeep](https://codekeep.io)  -Google Keep代码段. 组织，发现和共享代码片段，具有功能强大的代码截图工具，预设模板和链接功能.

## CI and CD

  * [AccessLint](https://github.com/marketplace/accesslint)  — AccessLint将自动化的Web可访问性测试引入您的开发工作流程. 它是免费的，用于开源和教育目的.
  * [appcircle.io](https://appcircle.io)  —具有在线设备仿真器的iOS和Android自动化移动CI / CD / CT.  20分钟的构建超时（对于开放源代码为60分钟）是免费的，并且并发是免费的.
  * [appveyor.com](https://www.appveyor.com/) — Windows的CD服务，开源的免费
  * [bitrise.io](https://www.bitrise.io/)  —用于移动应用程序（本机或混合）的CI / CD. 每月有200次免费构建，构建时间为10分钟，有两名团队成员.  OSS项目的构建时间为45分钟，并发+1，团队规模无限制.
  * [buddy.works](https://buddy.works/) —具有5个免费项目和1个并发运行的CI / CD（每月执行120次）
  * [buddybuild.com](https://www.buddybuild.com/) —在一个无缝的迭代系统中为iOS和Android应用程序构建，部署和收集反馈
  * [circleci.com](https://circleci.com/) —一次并发构建免费
  * [cirrus-ci.org](https://cirrus-ci.org) -对于公共GitHub存储库免费
  * [codefresh.io](https://codefresh.io) —终身免费计划：1个构建，1个环境，共享服务器，无限制的公共存储库
  * [codemagic.io](https://codemagic.io/) -每月免费构建500分钟
  * [codeship.com](https://codeship.com/) -每月100个私人构建，5个私人项目，开源无限制
  * [Continuous PHP](https://continuousphp.com/)  — Continuousphp是第一个也是唯一一个以PHP为中心的平台，可以在同一工作流程中构建，打包，测试和部署应用程序. 对于社区项目（即OSS /公共/教育项目）免费.
  * [deployhq.com](https://www.deployhq.com/) — 1个项目，每天部署10个（每月构建30分钟）
  * [drone](https://cloud.drone.io/) -Drone Cloud使开发人员可以在一处跨多个架构（包括x86和Arm（32位和64位））运行持续交付管道
  * [LayerCI](https://layerci.com)  — CI，用于全堆栈项目.  1个具有5GB内存和3个CPU的完整堆栈预览环境.
  * [ligurio/awesome-ci](https://github.com/ligurio/awesome-ci) —持续集成服务比较
  * [Octopus Deploy](https://octopus.com)  -自动化的部署和发布管理. 免费提供&lt;= 10个部署目标.
  * [scalr.com](https://scalr.com/)  -Terraform的远程状态和操作后端，具有完整的CLI支持，与OPA的集成以及分层配置模型. 最多释放5个用户.
  * [semaphoreci.com](https://semaphoreci.com/) -开源免费，每月100个私有版本
  * [shippable.com](https://app.shippable.com/) —每月150个私人构建，免费使用1个构建容器，私人和公共存储库
  * [Squash Labs](https://www.squash.io/) —为每个分支创建一个VM，并通过唯一的URL（无限的公共和私有存储库）提供您的应用程序，最大2 GB VM大小.
  * [stackahoy.io](https://stackahoy.io)  — 100％免费. 无限的部署，分支和构建
  * [styleci.io](https://styleci.io/) -仅公共GitHub存储库
  * [travis-ci.org](https://travis-ci.org/) —对于公共GitHub存储库免费
  * [Mergify](https://mergify.io) — GitHub的工作流自动化和合并队列—公共GitHub存储库免费

## Testing

  * [Applitools.com](https://applitools.com/)  —针对Web，本地移动和桌面应用程序的智能视觉验证. 与几乎所有自动化解决方案（例如Selenium和Karma）和远程运行程序（Sauce Labs，Browser Stack）集成. 免费提供开放源代码. 每周检查点数量有限的单个用户的免费套餐.
  * [Appetize](https://appetize.io)  —直接在浏览器中在此基于云的Android手机/平板电脑模拟器和iPhone / iPad模拟器上测试您的Android和iOS应用程序. 免费套餐包括1个并发会话，每月使用100分钟. 应用程式大小无限制.
  * [Bird Eats Bug](https://www.birdeatsbug.com/)  —更快（更好）地报告错误. 使用Bird浏览器扩展程序记录您的屏幕，它将自动捕获工程师需要调试的技术数据. 适用于小型团队的免费套餐.
  * [browserstack.com](https://www.browserstack.com/) —手动和自动浏览器测试， [free for Open Source](https://www.browserstack.com/open-source?ref=pricing)
  * [checkbot.io](https://www.checkbot.io/)  —浏览器扩展程序，用于测试您的网站是否遵循50多个SEO，速度和安全性最佳做法. 小型网站的免费套餐.
  * [crossbrowsertesting.com](https://crossbrowsertesting.com) -在云端进行手动，可视和Selenium浏览器测试- [free for Open Source](https://crossbrowsertesting.com/open-source)
  * [cypress.io](https://www.cypress.io/)  -对浏览器中运行的所有内容进行快速，轻松和可靠的测试. 赛普拉斯Test Runner始终是免费且开源的，没有任何限制. 对于多达5个用户的开源项目，赛普拉斯仪表板是免费的.
  * [everystep-automation.com](https://www.everystep-automation.com/) —记录和重放在Web浏览器中执行的所有步骤并创建脚本，...免费，更少的选择
  * [Gremlin](https://www.gremlin.com/gremlin-free-software)  — Gremlin的Chaos Engineering工具使您可以安全，安全地简单地将故障注入系统中，以在弱点引起面向客户的问题之前发现它们.  Gremlin Free可以访问最多5个主机或容器上的Shutdown和CPU攻击.
  * [gridlastic.com](https://www.gridlastic.com/) —带有免费计划的Selenium Grid测试，最多可同时进行4个Selenium节点/ 10个网格启动/每月4,000个测试分钟
  * [loadmill.com](https://www.loadmill.com/)  -通过分析网络流量自动创建API和进行负载测试. 每月最多免费模拟多达50个并发用户，长达60分钟.
  * [percy.io](https://percy.io)  -将视觉测试添加到任何Web应用程序，静态网站，样式指南或组件库. 无限的团队成员，演示应用程序和无限的项目，每月5,000张快照.
  * [reflect.run](https://reflect.run)  -针对Web应用程序的无代码自动化测试. 可以在应用程序内安排测试，也可以通过CI / CD工具执行测试. 每次测试运行都包括完整的视频记录以及控制台和网络日志. 免费套餐包括无限数量的已保存测试，每月可进行25次测试运行，最多可容纳3位用户.
  * [saucelabs.com](https://saucelabs.com/) —跨浏览器测试，Selenium测试和移动测试， [free for Open Source](https://saucelabs.com/open-source)
  * [testingbot.com](https://testingbot.com/) — Selenium浏览器和设备测试， [free for Open Source](https://testingbot.com/open-source)
  * [tesults.com](https://www.tesults.com)  —测试结果报告和测试用例管理. 与流行的测试框架集成. 开源软件开发人员，个人，教育者和入门小团队可以要求提供除基本免费项目之外的折扣和免费产品.
  * [websitepulse.com](https://www.websitepulse.com/tools/) —各种免费的网络和服务器工具.
  * [qase.io](https://qase.io)  -开发和质量保证团队的测试管理系统. 管理测试用例，编写测试运行，执行测试运行，跟踪缺陷并评估影响. 免费套餐包括所有核心功能，其中500Mb可用于附件，最多可容纳3个用户.
  * [knapsackpro.com](https://knapsackpro.com)  -通过任何CI提供程序上的最佳测试套件并行化来加快测试速度. 拆分Ruby，JavaScript在并行CI节点上进行测试以节省时间. 免费计划（最多10分钟的测试文件）和免费无限计划（针对开源项目）.
  * [webhook.site](https://webhook.site)  -验证webhook，出站HTTP请求或带有自定义URL的电子邮件. 临时URL和电子邮件地址始终是免费的.
  * [Vaadin](https://vaadin.com)  —用Java或TypeScript构建可扩展的UI，并使用集成的工具，组件和设计系统来更快地迭代，更好地设计并简化开发过程.  5年免费维护的无限项目.

## Security and PKI

  * [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) —发现您网络中受感染的系统
  * [atomist.com](https://atomist.com/)  —一种更快，更方便的方式来自动化各种开发任务. 现在处于测试阶段.
  * [auth0.com](https://auth0.com/)  —免费托管用于开发SSO. 最多2个社交身份提供者用于封闭源项目.
  * [Authress](https://authress.io/)  —身份验证登录和访问控制，任何项目的身份提供者不受限制.  Facebook，Google，Twitter等. 前1000个API调用是免费的.
  * [Authy](https://authy.com)  -具有备份功能的多个设备上的两因素身份验证（2FA）.  Google Authenticator的直接替代品. 免费获得多达100个成功的身份验证.
  * [bitninja.io](https://bitninja.io/) —通过黑名单，免费计划进行的僵尸网络保护仅报告有关每次攻击的有限信息
  * [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services（AWS）安全性和合规性审核和监控
  * [Cmd](https://cmd.com/) —安全平台可为您的云或数据中心中的每个Linux实例提供实时访问控制和动态策略实施
  * [CodeNotary.io](https://www.codenotary.io/) —带有不可磨灭的证明的公证平台，用于对代码，文件，目录或容器进行公证
  * [crypteron.com](https://www.crypteron.com/) —面向开发人员的云优先，对开发人员友好的安全平台可防止.NET和Java应用程序中的数据泄露
  * [Dependabot](https://dependabot.com/) 自动化的依赖项更新，适用于Ruby，JavaScript，Python，PHP，Elixir，Rust，Java（Maven和Gradle）、. NET，Go，Elm，Docker，Terraform，Git子模块和GitHub Actions.
  * [DJ Checkup](https://djcheckup.com)  —使用此免费的自动化检查工具在Django站点上扫描安全性缺陷. 从Pony Checkup网站派生.
  * [Doppler](https://doppler.com/)  —适用于应用程序秘密和配置的Universal Secrets Manager，支持同步到各种云提供商. 具有基本访问控制的无限用户免费.
  * [duo.com](https://duo.com/) — Two-factor authentication (2FA) for website or app. Free for 10 users, all authentication methods, unlimited, integrations, hardware tokens
  * [Firebase Auth](https://firebase.google.com/products/auth/) —免费的端到端身份解决方案，电子邮件和密码帐户，Google，Twitter，Facebook，GitHub登录，电话身份验证（每月最多10k）等.
  * [foxpass.com](https://www.foxpass.com/)  —托管的LDAP和RADIUS. 轻松地按用户登录服务器，VPN和无线网络.  10位用户免费
  * [globalsign.com](https://www.globalsign.com/en/ssl/ssl-open-source/) —开源的免费SSL证书
  * [Have I been pwned?](https://haveibeenpwned.com) — REST API，用于获取违规信息.
  * [Internet.nl](https://internet.nl) —测试现代互联网标准，例如IPv6，DNSSEC，HTTPS，DMARC，STARTTLS和DANE
  * [Jumpcloud](https://jumpcloud.com/)  —提供类似于Azure AD，用户管理，单点登录和RADIUS身份验证的目录即服务. 免费（最多10位用户）.
  * [keychest.net](https://keychest.net) -SSL到期管理和带有集成CT数据库的证书购买
  * [letsencrypt.org](https://letsencrypt.org/) —具有所有主要浏览器都信任的证书的免费SSL证书颁发机构
  * [LoginRadius](https://www.loginradius.com/)  —免费的托管用户身份验证服务. 电子邮件注册和3个社交服务提供商.
  * [logintc.com](https://www.logintc.com/) —通过推送通知的两要素身份验证（2FA），可免费使用10个用户，VPN，网站和SSH
  * [meterian.io](https://www.meterian.io/)  -监视Java，Javascript，.NET，Scala，Ruby和NodeJS项目中依赖项中的安全漏洞. 一个私有项目免费，开放源代码无限个项目.
  * [Mozilla Observatory](https://observatory.mozilla.org/) —查找并修复站点中的安全漏洞.
  * [Okta](https://developer.okta.com/)  —用户管理，身份验证和授权. 免费，每月最多有1000位活跃用户.
  * [onelogin.com](https://www.onelogin.com/) —身份即服务（IDaaS），单一登录身份提供程序，Cloud SSO IdP，3个公司应用程序和5个个人应用程序，无限的用户
  * [opswat.com](https://www.opswat.com/) —计算机，设备，应用程序，配置，…的安全监视.免费25位用户和30天历史记录用户.
  * [pyup.io](https://pyup.io)  —监视Python依赖关系中的安全漏洞并自动更新它们. 一个私有项目免费，开放源代码无限个项目.
  * [qualys.com](https://www.qualys.com/community-edition) —查找Web应用程序漏洞，审核OWASP风险
  * [report-uri.io](https://report-uri.io/) -CSP和HPKP违规报告
  * [ringcaptcha.com](https://ringcaptcha.com/) —免费使用电话号码作为ID的工具
  * [Shieldfy](https://shieldfy.io) —针对开发人员的Web应用程序防火墙和漏洞检测，每月最多可免费计划10万个请求.
  * [snyk.io](https://snyk.io)  —可以在您的开源依赖项中找到并修复已知的安全漏洞. 开源项目的无限测试和修复. 每月最多只能为您的私人项目进行200次测试.
  * [Sqreen](https://www.sqreen.com/)  —针对Web应用程序和API的应用程序安全监视和保护（RASP，WAF等）. 免费提供1个应用程序和300万个请求.
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) —对任何SSL Web服务器的配置进行非常深入的分析
  * [StackHawk](https://www.stackhawk.com/) 在整个管道中自动进行应用程序扫描，以发现并修复安全漏洞，然后再将其投入生产. 单个应用程序的无限扫描和环境.
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) -免费的网站安全检查和恶意软件扫描程序
  * [Protectumus](https://protectumus.com) - Free website security check, site antivirus and server firewall (WAF) for PHP. Email notifications for registered users in free tier.
  * [TestTLS.com](https://testtls.com) -测试SSL / TLS服务的安全服务器配置，证书，链等.不限于HTTPS.
  * [threatconnect.com](https://threatconnect.com)  —威胁情报：它是为开始学习网络威胁情报的个人研究人员，分析人员和组织而设计的. 最多释放3位用户
  * [tinfoilsecurity.com](https://www.tinfoilsecurity.com/)  —漏洞自动扫描. 免费计划允许每周进行XSS扫描
  * [Ubiq Security](https://ubiqsecurity.com/)  —使用3行代码和自动密钥管理来加密和解密数据. 免费提供1个应用程序，每月最多1,000,000个加密.
  * [Virgil Security](https://virgilsecurity.com/)  —用于在数字解决方案中实施端到端加密，数据库保护，IoT安全等的工具和服务. 对于拥有250个用户的应用程序免费.
  * [Virushee](https://virushee.com/)  —由混合启发式和AI辅助引擎提供支持的面向隐私的文件/数据扫描. 可以使用内部动态沙箱分析. 每个文件上传限制为50MB

## Management System

  * [bitnami.com](https://bitnami.com/)  —在IaaS上部署准备好的应用程序. 免费管理1个AWS微型实例
  * [Esper](https://esper.io)  —适用于具有DevOps的Android设备的MDM和MAM. 带有1个用户许可证和25 MB应用程序存储的100台设备免费.
  * [jamf.com](https://www.jamf.com/) —适用于iPad，iPhone和Mac的设备管理，免费提供3台设备
  * [moss.sh](https://moss.sh)  -帮助开发人员部署和管理其Web应用程序和服务器. 每月最多释放25个git部署
  * [runcloud.io](https://runcloud.io/)  -服务器管理主要集中在PHP项目上. 最多可免费使用1台服务器.
  * [ploi.io](https://ploi.io/)  -服务器管理工​​具，可轻松管理和部署服务器和站点.  1台服务器免费.

## Messaging

  * [Ably](https://www.ably.com/)  -具有状态，持久性和有保证的传递的实时消息传递服务. 免费计划包括每月300万条消息，100个高峰连接和100个高峰通道.
  * [cloudamqp.com](https://www.cloudamqp.com/)  — RabbitMQ即服务. 小狐猴计划：每月最多100万条消息，最多20个并发连接，最多100个队列，最多10,000个排队的消息，不同可用区中的多个节点
  * [connectycube.com](https://connectycube.com)  -无限聊天消息，p2p语音和视频通话，文件附件和推送通知. 免费，适用于最高2万MAU的应用.
  * [courier.com](https://www.courier.com/)  —单一API，用于推送，应用内，电子邮件，聊天，SMS和其他带有模板管理和其他功能的消息通道. 免费计划包括每月10,000条消息.
  * [pusher.com](https://pusher.com/)  —实时消息服务. 免费，每天最多可连接100个连接和200,000条消息
  * [scaledrone.com](https://www.scaledrone.com/)  —实时消息服务. 免费，每天最多可进行20个同时连接和100,000个事件
  * [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 作为服务. 全局，AWS，GCP和Azure. 永久免费，每月提供4k msg大小，50个活动连接和5GB数据.
  * [cloudkarafka.com](https://www.cloudkarafka.com/) -免费共享的Kafka集群，最多5个主题，每个主题10MB数据，数据保留28天.
  * [pubnub.com](https://www.pubnub.com/)  -每月有100万笔交易的Swift，Kotlin和React消息传递. 事务可能包含多个消息.


## Log Management

  * [bugfender.com](https://bugfender.com/) —每天最多释放10万条日志行，并保留24小时
  * [humio.com](https://www.humio.com/) —每天最多释放2 GB，保留7天
  * [logdna.com](https://logdna.com) -单个用户免费，无保留，主机和来源不受限制
  * [logentries.com](https://logentries.com/) —每月最多释放5 GB，保留7天
  * [loggly.com](https://www.loggly.com/) —单个用户免费，请参阅lite选项
  * [logz.io](https://logz.io/) —每天最多释放3 GB，保留3天
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-log-management)  —由Manage Engine提供支持的日志管理服务.  Free Plan提供50 GB的存储空间，保留1个月.
  * [papertrailapp.com](https://papertrailapp.com/) — 48小时搜索，7天存档，100 MB /月
  * [sematext.com](https://sematext.com/logsene) —每天释放高达500 MB的空间，保留7天
  * [sumologic.com](https://www.sumologic.com/) —每天释放高达500 MB的空间，保留7天

## Translation Management

  * [crowdin.com](https://crowdin.com/) —开源的无限项目，无限字符串和合作者
  * [lingohub.com](https://lingohub.com/) —最多释放3个用户，对于开源始终免费
  * [localazy.com](https://localazy.com) -免费提供1000种源语言字符串，无限语言，无限贡献者，启动和开源交易
  * [localizely.com](https://localizely.com/) —开源免费
  * [Loco](https://localise.biz/) —免费提供多达2000种翻译，无限制的翻译人员，10种语言/项目，1000种可翻译资产/项目
  * [oneskyapp.com](https://www.oneskyapp.com/) —有限的免费版本，最多可容纳5个用户，免费提供给开源
  * [POEditor](https://poeditor.com/) —最多释放1000个字符串
  * [SimpleLocalize](https://simplelocalize.io/) -释放多达100个翻译键，无限的字符串，无限的语言，启动交易
  * [transifex.com](https://www.transifex.com/) —开源免费
  * [Translation.io](https://translation.io) -开源免费
  * [webtranslateit.com](https://webtranslateit.com/) —最多释放500个字符串
  * [weblate.org](https://weblate.org/) —对于免费项目，免费项目最多可免费获得10,000个字符串源（免费层），以及本地无限制自托管.

## Monitoring

  * [Pingmeter.com](https://pingmeter.com/)  -5个正常运行时间的监视器，间隔10分钟. 监视SSH，HTTP，HTTPS和任何自定义TCP端口.
  * [amixr.io](https://amixr.io/)  -出色的Slack集成，API和Terraform，对开发人员友好的警报和通话管理. 免费电话，短信，电报，Slack和电子邮件包.
  * [apimetrics.io](https://apimetrics.io/)  —自动化的API性能监控，测试和分析. 免费计划，手动进行API调用并从其西海岸服务器运行
  * [appdynamics.com](https://www.appdynamics.com/) —免费提供24小时指标，应用程序性能管理代理限于一种Java，一种.NET，一种PHP和一种Node.js
  * [appneta.com](https://www.appneta.com/) — 1小时数据保留免费
  * [assertible.com](https://assertible.com)  —自动化的API测试和监视. 为团队和个人提供免费计划.
  * [bearer.sh](https://www.bearer.sh)  -自动监视API请求，跟踪性能，检测异常并解决关键API使用情况方面的问题. 使用1行代码免费安装Bearer Agent.
  * [blackfire.io](https://blackfire.io/)  — Blackfire是SaaS交付的应用程序性能解决方案. 免费的黑客计划（仅限PHP）
  * [checklyhq.com](https://checklyhq.com)  -面向开发人员的开源E2E /综合监控和深度API监控.  5位用户和50k +支票运行的免费计划.
  * [circonus.com](https://www.circonus.com/) —免费获得20个指标
  * [cloudsploit.com](https://cloudsploit.com)  — AWS安全性和配置监视. 免费：无限按需扫描，无限用户，无限存储帐户. 订阅：自动扫描，API访问等.
  * [datadoghq.com](https://www.datadoghq.com/) —最多免费提供5个节点
  * [deadmanssnitch.com](https://deadmanssnitch.com/)  —监视cron作业.  1个免费告密者（显示器），如果您推荐其他人进行注册，则更多
  * [elastic.co](https://www.elastic.co/solutions/apm)  — JS开发人员的即时性能见解. 免费提供24小时数据保留
  * [freeboard.io](https://freeboard.io/)  —公共项目免费. 物联网（IoT）项目的仪表板
  * [freshworks.com](https://www.freshworks.com/website-monitoring/) —每隔1分钟监控50个URL，并免费提供10个全局位置和5个公共状态页面
  * [ghostinspector.com](https://ghostinspector.com/)  —免费的网站和Web应用程序监视. 单用户，每月100次测试运行
  * [gitential.com](https://gitential.com)  —软件开发分析平台. 免费：无限的公共存储库，无限的用户，私人存储库的免费试用. 适用于企业的本地版本.
  * [Grafana Cloud](https://grafana.com/products/cloud/)  -Grafana Cloud是可组合的可观察性平台，将指标和日志与Grafana集成在一起. 免费：3个用户，10个仪表板，100个警报，Prometheus和Graphite中的指标存储（10,000系列，保留14天），Loki中的日志存储（50 GB日志，保留14天）
  * [healthchecks.io](https://healthchecks.io)  —监视您的cron作业和后台任务. 免费，最多20张支票.
  * [inspector.dev](https://www.inspector.dev) -不到一分钟的时间，一个完整的实时监控仪表板，并且永久免费.
  * [instrumentalapp.com](https://instrumentalapp.com) -精美且易于使用的应用程序和服务器监控，可免费提供多达500个指标和3个小时的数据可见性
  * [keychest.net/speedtest](https://keychest.net/speedtest) -针对Digital Ocean的独立速度测试和TLS握手延迟测试
  * [letsmonitor.org](https://letsmonitor.org) -SSL监控，最多可提供5台监控器
  * [loader.io](https://loader.io/) —有限制的免费负载测试工具
  * [newrelic.com](https://www.newrelic.com)  —建立了新的Relic可观察性平台，以帮助工程师创建更完善的软件. 从整体到无服务器，您可以检测所有内容，然后进行分析，故障排除和优化整个软件堆栈. 免费套餐提供每月100GB的免费数据摄取，1个免费的完全访问用户和无限的免费基本用户.
  * [nixstats.com](https://nixstats.com)  -一台服务器免费. 电子邮件通知，公共状态页面，60秒间隔等.
  * [nodequery.com](https://nodequery.com/) —免费的基本服务器监控多达10台服务器
  * [opsgenie.com](https://www.opsgenie.com/) — Powerful alerting and on-call management for operating always-on services. Free up to 5 users.
  * [paessler.com](https://www.paessler.com/)  —强大的基础架构和网络监控解决方案，包括警报，强大的可视化功能和基本报告. 释放多达100个传感器.
  * [pagertree.com](https://pagertree.com/)  -简单的警报和通话管理界面. 最多释放5个用户.
  * [pingbreak.com](https://pingbreak.com/)  —现代的正常运行时间监控服务. 检查无限的URL，并通过Discord，Slack或电子邮件获取停机通知.
  * [sematext.com](https://sematext.com/) —免费提供24小时指标，无限数量的服务器，10个自定义指标，500,000个自定义指标数据点，无限的仪表板，用户等.
  * [sitemonki.com](https://sitemonki.com/) -网站，域，Cron和SSL监控，每个类别中免费提供5个监控器
  * [skylight.io](https://www.skylight.io/) —前100,000个请求免费（仅适用于Rails）
  * [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — Performance Monitoring API，检查Ping，DNS等.
  * [stathat.com](https://www.stathat.com/) —免费获得10个统计信息，无过期
  * [statuscake.com](https://www.statuscake.com/) -网站监控，无限制的无限制测试
  * [statusgator.com](https://statusgator.com/) —状态页监控，免费提供3个监控器
  * [thousandeyes.com](https://www.thousandeyes.com/)  —网络和用户体验监视. 免费提供主要Web服务的3个位置和20个数据供稿
  * [thundra.io/apm](https://www.thundra.io/apm)  —应用程序监视和调试. 具有免费层，每月最多调用25万次.
  * [uptimerobot.com](https://uptimerobot.com/) -网站监控，免费提供50个监控器
  * [uptimetoolbox.com](https://uptimetoolbox.com/) —免费监视5个网站，间隔60秒，公共状态页.
  * [zenduty.com](https://www.zenduty.com/)  —用于网络运营，站点可靠性工程和DevOps团队的端到端事件管理，警报，呼叫管理和响应协调平台. 最多5位用户免费.

## Crash and Exception Handling

  * [CatchJS.com](https://catchjs.com/)  -带有屏幕截图和点击痕迹的JavaScript错误跟踪. 对于开源项目免费.
  * [bugsnag.com](https://www.bugsnag.com/) -初次试用后每月最多可免费提供2,000个错误
  * [exceptionless](https://exceptionless.com)  —实时错误，功能，日志报告等. 每月3k活动免费（/ 1位用户）. 开源且易于自我托管，可无限使用.
  * [GlitchTip](https://glitchtip.com/)  —简单的开源错误跟踪. 与开源Sentry SDK兼容. 每月免费提供1000个事件，或者可以无限制地自行托管
  * [honeybadger.io](https://www.honeybadger.io)  -异常，正常运行时间和cron监视. 小型团队和开源项目免费（每月12,000个错误）.
  * [rollbar.com](https://rollbar.com/) —异常和错误监控，每月有5,000个错误的免费计划，无限用户，保留30天
  * [sentry.io](https://sentry.io/)  -Sentry实时跟踪应用程序异常，有一个小的免费计划. 每月免费提供5k错误/ 1个用户，如果是自托管，则可以不受限制地使用

## Search

  * [algolia.com](https://www.algolia.com/)  —托管的按需输入（即时）. 免费的黑客计划最多10,000个文档和100,000个操作. 更大的免费计划可用于社区/开源项目
  * [bonsai.io](https://bonsai.io/) —释放1 GB内存和1 GB存储空间
  * [searchly.com](http://www.searchly.com/) —免费的2个索引和20 MB的存储空间
  * [pagedart.com](https://pagedart.com/)  -AI搜索即服务的免费层包括1000个文档，50000个搜索. 对于有价值的项目，可以使用更大的免费套餐.

## Email

  * [10minutemail](https://10minutemail.com) -免费的临时电子邮件进行测试.
  * [AnonAddy](https://anonaddy.com) -开源匿名电子邮件转发，免费创建无限的电子邮件别名
  * [biz.mail.ru](https://biz.mail.ru/) — 5,000个邮箱，每个自定义域每个25 GB，带有DNS托管
  * [Bump](https://bump.email/) -免费的10个Bump电子邮件地址，1个自定义域
  * [Burnermail](https://burnermail.io/) –免费的5个Burner电子邮件地址，1个邮箱，7天的邮箱历史记录
  * [Buttondown](https://buttondown.email/)  —通讯服务. 多达1,000个免费订阅者
  * [CloudMailin](https://www.cloudmailin.com/) -通过HTTP POST和事务出站接收电子邮件-每月10,000封免费电子邮件
  * [cloudmersive.com](https://www.cloudmersive.com/email-verification-api) —针对开发人员的电子邮件验证和验证API，每月2,000个免费API请求
  * [Contact.do](https://contact.do/) —链接中的联系表格（有点联系表格）-完全免费！
  * [debugmail.io](https://debugmail.io/) -开发人员易于使用的测试邮件服务器
  * [elasticemail.com](https://elasticemail.com)  —每天100封免费电子邮件.  1,000封电子邮件，每API的价格为$ 0.09（即付即用）.
  * [forwardemail.net](https://forwardemail.net)  —针对自定义域的免费电子邮件转发. 使用您的域名创建和转发不限数量的电子邮件地址（**注**：如果您使用.casa，.cf，.click，.email，.fit，.ga，.gdn，.gq， .loan，.london，.men，.ml，.pl，.rest，.ru，.tk，.top，.work TLD（由于垃圾邮件））
  * [ImprovMX](https://improvmx.com) –免费的电子邮件转发
  * [inumbo.com](http://inumbo.com/) —基于SMTP的垃圾邮件过滤器，可供10位用户免费使用
  * [kickbox.io](https://kickbox.io/) —验证100封电子邮件的免费，实时API是否可用
  * [mailazy.com](https://mailazy.com/) —每天免费发送250封电子邮件
  * [mail-tester.com](https://www.mail-tester.com) —测试电子邮件的dns / spf / dkim / dmarc设置是否正确，每月20个免费
  * [mailboxlayer.com](https://mailboxlayer.com/)  —用于开发人员的电子邮件验证和验证JSON API. 每月1,000个免费API请求
  * [mailcatcher.me](https://mailcatcher.me/) —捕获邮件并通过Web界面进行投放
  * [mailchimp.com](https://mailchimp.com/) —每月有2,000个订阅者和12,000封电子邮件免费
  * [MailerLite.com](https://www.mailerlite.com) —每月1,000个订阅者，每月12,000个电子邮件免费
  * [mailinator.com](https://www.mailinator.com/) —免费的公共电子邮件系统，您可以在其中使用所需的任何收件箱
  * [mailjet.com](https://www.mailjet.com/) —每月6,000封电子邮件免费（每天发送200封电子邮件）
  * [mailkitchen](https://www.mailkitchen.com/) —终身免费，无承诺，每月10,000封电子邮件，每天1,000封电子邮件
  * [Mailnesia](https://mailnesia.com) -免费的临时/一次性电子邮件，其中包含自动访问注册链接.
  * [mailsac.com](https://mailsac.com) -用于临时电子邮件测试的免费API，免费的公共电子邮件托管，出站捕获，电子邮件转松弛/ websocket / webhook（每月1,500个API限制）
  * [mailtrap.io](https://mailtrap.io/) -用于开发的伪造SMTP服务器，免费计划，包含1个收件箱，50条消息，无团队成员，2封电子邮件/秒，无转发规则
  * [mail7.io](https://www.mail7.io/)  —适用于质量检查开发人员的免费临时电子邮件地址. 使用Web Interface或API立即创建电子邮件地址
  * [mohmal.com](https://www.mohmal.com/en) —一次性临时电子邮件
  * [moosend.com](https://moosend.com/)  —邮件列表管理服务. 初创企业6个月的免费帐户
  * [Outlook.com](https://outlook.live.com/owa/) -免费的个人电子邮件和日历
  * [pepipost.com](https://pepipost.com) —首个月免费提供3万封电子邮件，然后每天免费提供前100封电子邮件
  * [phplist.com](https://phplist.com/) —托管版本允许每月免费发送300封电子邮件
  * [postmarkapp.com](https://postmarkapp.com/) -每月免费100封电子邮件，无限制的DMARC每周摘要
  * [Sender](https://www.sender.net) 每月多达15000封电子邮件-多达2500个订阅者
  * [sendgrid.com](https://sendgrid.com/) —每天100封电子邮件，免费2,000个联系人
  * [sendinblue.com](https://www.sendinblue.com/) —每月免费发送9,000封电子邮件
  * [sendpulse.com](https://sendpulse.com) —每小时免费50封电子邮件，每月免费前12,000封电子邮件
  * [socketlabs.com](https://www.socketlabs.com) -首月免费提供4万封电子邮件，然后每月免费提供前2000封电子邮件
  * [sparkpost.com](https://www.sparkpost.com/) —每月免费发送前500封电子邮件
  * [Substack](https://substack.com)  —无限的免费新闻通讯服务. 收费后开始付款.
  * [temp-mail.io](https://temp-mail.io) —免费的一次性临时电子邮件服务，一次可发送多封电子邮件并转发
  * [testmail.app](https://testmail.app/)  -使用无限的邮箱和GraphQL API自动化端到端电子邮件测试. 每月永久免费发送100封电子邮件，开源免费无限制.
  * [tinyletter.com](https://tinyletter.com/) — 5,000个订阅者/月免费
  * [trashmail.com](https://www.trashmail.com) -免费的一次性电子邮件地址，具有转发和自动地址过期
  * [Validator.Pizza](https://www.validator.pizza/) —免费的API可检测一次性电子邮件
  * [Verifalia](https://verifalia.com/email-verification-api)  —具有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证API； 每天25次免费电子邮件验证.
  * [verimail.io](https://verimail.io/)  —批量和API电子邮件验证服务. 每月100次免费验证
  * [Yandex.Connect](https://connect.yandex.com/pdd/) —最多可容纳1,000位用户的免费电子邮件和DNS托管
  * [yopmail.fr](http://www.yopmail.fr/en/) —一次性电子邮件地址
  * [Zoho](https://www.zoho.com)  —最初是作为电子邮件提供商，但现在提供了一套服务，其中一些服务有免费计划. 有免费计划的服务清单：
     - [Email](https://zoho.com/mail)  5位用户免费.  5GB /用户和25 MB的附件限制，1个域.
     - [Sprints](https://zoho.com/sprints) 5位用户免费，5个项目和500MB存储空间.
     - [Docs](https://zoho.com/docs)  -5位用户免费，上传限制为1 GB，存储空间为5GB.  Zoho Office Suite（书写，演示和演示）随附在其中.
     - [Projects](https://zoho.com/projects)  —免费提供给3个用户，2个项目和10 MB的附件限制. 相同的计划适用于 [Bugtracker](https://zoho.com/bugtracker).
     - [Connect](https://zoho.com/connect) — 25位用户免费的团队协作，包括3个小组，3个自定义应用程序，3个开发板，3个手册，10个集成以及渠道，活动和论坛.
     - [Meeting](https://zoho.com/meeting) —最多3位会议参与者和10位网络研讨会参与者的会议.
     - [Vault](https://zoho.com/vault) —个人免费密码管理.
     - [Showtime](https://zoho.com/showtime) —另一个会议软件，用于培训最多5位与会者的远程会议.
     - [Notebook](https://zoho.com/notebook) -Evernote的免费替代品.
     - [Wiki](https://zoho.com/wiki) — 3位用户免费使用，具有50 MB的存储空间，无限制的页面，zip备份，RSS和Atom提要，访问控制和可自定义的CSS.
     - [Subscriptions](https://zoho.com/subscriptions)  -20位客户/订阅和1位用户免费进行定期计费管理，所有付款托管工作均由Zoho自己完成. 最后40个订阅指标已存储 
     - [Checkout](https://zoho.com/checkout) —具有3页和最多50个付款的产品账单管理.
     - [Desk](https://zoho.com/desk)  —具有3个代理和私人知识库，电子邮件票证的客户支持管理. 与整合 [Assist](https://zoho.com/assist) 1个远程技术人员和5台无人值守的计算机.
     - [Cliq](https://zoho.com/cliq) —团队聊天软件，具有100 GB的存储空间，无限的用户，每个频道和SSO 100个用户.
     - [Campaigns](https://zoho.com/campaigns)
     - [Forms](https://zoho.com/forms)
     - [Sign](https:/zoho.com/sign)
     - [Surveys](https://zoho.com/surveys)
     - [Bookings](https://zoho.com/bookings)
     - [Analytics](https://zoho.com/analytics)
  * [SimpleLogin](https://simplelogin.io/)  –开源，可自行托管的电子邮件别名/转发解决方案. 免费提供5种别名，无限带宽，无限答复/发送. 教育人员（学生，研究人员等）免费.

## Font

  * [dafont](https://www.dafont.com/) - The fonts presented on this website are their authors' property, and are either freeware, shareware, demo versions or public domain.
  * [Everything Fonts](https://everythingfonts.com/)  -提供多种工具；  @ font-face，单位转换器，字体插入器和字体提交器.
  * [Font Squirrel](https://www.fontsquirrel.com/)  -获许可用于商业用途的免费软件字体. 手工选择这些字体，并以易于使用的格式显示它们.
  * [Google Fonts](https://fonts.google.com/) -许多免费字体，可以通过下载或指向Google CDN的链接轻松快捷地安装在网站上.
  * [FontGet](https://www.fontget.com/) -有多种字体可供下载，并与标签整齐地排序.

## Forms

  * [99inbound.com](https://www.99inbound.com/)  -建立表格并在线共享. 获取每个提交的电子邮件或Slack消息. 免费计划有2种形式，每月100个条目，基本电子邮件和Slack.
  * [Form.taxi](https://form.taxi/)  — HTML表单提交的端点. 通过通知，垃圾邮件阻止程序和符合GDPR的数据处理. 免费使用基本使用方案.
  * [Formcake.com](https://formcake.com)  -开发人员的表单后端，免费计划允许无限制表单，100个提交，Zapier集成. 无需库或依赖项.
  * [Formcarry.com](https://formcarry.com) -HTTP POST表单端点，免费计划每月允许100次提交.
  * [formingo.co](https://www.formingo.co/) -用于静态网站的简单HTML表单，无需注册即可免费开始使用. 免费计划允许每月500次提交，可自定义回复电子邮件地址.
  * [formlets.com](https://formlets.com/) —在线表单，每月无限制单页表单，每月100次提交，电子邮件通知.
  * [formspark.io](https://formspark.io/) -表单到电子邮件服务，免费计划允许无限制表单，每月250次提交，并获得客户支持团队的支持.
  * [Formspree.io](https://formspree.io/)  —使用HTTP POST请求发送电子邮件. 免费套餐限制为每个表格每月50个提交.
  * [getform.io](https://getform.io/) -面向设计人员和开发人员的表单后端平台，1个表单，50个提交，单个文件上传，100MB文件存储.
  * [Kwes.io](https://kwes.io/)  -功能丰富的表单端点. 非常适合静态网站. 免费计划包括最多1个网站，每月最多50个提交.
  * [Qualtrics Survey](https://qualtrics.com/free-account)  -使用此一流的工具创建专业表格并进行调查.  50多个由专家设计的调查模板. 免费帐户的限制是1个有效调查，100个响应/调查和8种响应类型.
  * [Pageclip](https://pageclip.co/) -免费计划允许一个网站，一个表格，每月提交1,000个文件.
  * [smartforms.dev](https://smartforms.dev/) -适用于您网站的强大而简单的表单后端，永久免费计划允许每月50次提交，250MB文件存储，Zapier集成，CSV / JSON导出，自定义重定向，自定义响应页面，Telegram＆Slack bot，单个电子邮件通知.
  * [staticforms.xyz](https://www.staticforms.xyz/)  -无需任何服务器端代码即可轻松轻松地集成HTML表单. 用户提交表单后，会将包含表单内容的电子邮件发送到您的注册地址.
  * [Typeform.com](https://www.typeform.com/)  —在网站上包括设计精美的表格. 免费计划每个表格仅允许10个字段，每月只允许100个回复.
  * [WaiverStevie.com](https://waiverstevie.com)  -具有REST API的电子签名平台. 接收带有Webhooks的通知. 免费计划水印签名文档，但允许无限制的信封+签名.
  * [Wufoo](https://www.wufoo.com/)  -在网站上使用的快速表格. 免费计划每个月最多只能提交100份.
  * [Web3Forms](https://web3forms.com)  -静态和JAMStack网站的联系表格，而无需编写后端代码. 免费计划允许每月无限制表格，无限制域和250项提交.

## CDN and Protection

  * [Arvan Cloud](https://arvancloud.com/)  —提供与云相关的服务（CDN，Cloud DNS，PaaS，安全性等）. 免费计划优惠：
     -带有免费SSL的CDN.  50 GB流量+ 1百万个HTTP（S）请求.
    -无限站点的免费Cloud DNS.
    -具有基本DDoS保护+ 5防火墙规则的免费云安全性.
    -具有10 GB存储+ 50 GB流量的免费VoD（视频点播）平台.
  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) — CDN，用于引导程序，bootswatch和fontawesome.io
  * [cdnjs.com](https://cdnjs.com/) — CDN，用于JavaScript库，CSS库，SWF，图像等.
  * [Cloudflare](https://www.cloudflare.com/)
    * CDN以及免费的SSL
    *免费DNS，无限数量的域
    *防火墙规则和页面规则
    *分析
    * [TryCloudflare](https://developers.cloudflare.com/argo-tunnel/trycloudflare) —通过Argo隧道将本地HTTP服务器公开.
  * [ddos-guard.net](https://ddos-guard.net/store/web) —免费的CDN，DDoS保护和SSL证书
  * [developers.google.com](https://developers.google.com/speed/libraries/) — Google Hosted Libraries是最流行的开源JavaScript库的内容分发网络
  * [jare.io](http://www.jare.io)  — CDN用于图像. 使用AWS CloudFront
  * [jsdelivr.com](https://www.jsdelivr.com/) —适用于开发人员和网站管理员的OSS CDN（JS，CSS，字体），接受PR来添加更多内容
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN托管流行的第三方JavaScript库（例如jQuery），使您可以轻松地将它们添加到Web应用程序中
  * [netdepot.com](https://www.netdepot.com/cdn/) —每月前100 GB可用空间
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) —免费的DDoS保护和SSL证书
  * [PageCDN.com](https://pagecdn.com/) -为所有人提供免费的公共CDN，并为开源/公益组织提供免费的私人CDN.
  * [Skypack](https://www.skypack.dev/)  — 100％本机ES模块JavaScript CDN. 每个域每月免费提供一百万个请求.
  * [raw.githack.com](https://raw.githack.com/) —现代化的** rawgit.com **替代品，它仅使用Cloudflare托管文件
  * [section.io](https://www.section.io/)  —启动和管理完整的Varnish Cache解决方案的简单方法. 据说一个站点永远免费
  * [speeder.io](https://speeder.io/)  —使用KeyCDN. 自动图像优化和免费的CDN增强功能. 免费，不需要任何服务器更改
  * [staticaly.com](https://staticaly.com/) — CDN for Git repos (GitHub, GitLab, Bitbucket), WordPress-related assets and images
  * [toranproxy.com](https://toranproxy.com/)  — Packagist和GitHub的代理. 永不让CD失败. 免费供个人使用，1个开发人员，不支持
  * [unpkg.com](https://unpkg.com/) -CDN上npm的所有内容
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) —免费的DDoS保护

## PaaS

  * [anvil.works](https://anvil.works)  -仅使用Python即可进行的Web应用程序开发. 免费套餐，无限制的应用程序.
  * [appharbor.com](https://appharbor.com/) —一个提供1个免费工作人员的.Net PaaS
  * [configure.it](https://www.configure.it/) —移动应用开发平台，可免费使用2个项目，功能有限，但没有资源限制
  * [codenameone.com](https://www.codenameone.com/)  —适用于Java / Kotlin开发人员的开源，跨平台，移动应用程序开发工具链. 免费用于商业用途，项目数量不受限制
  * [Deta](https://www.deta.sh)  –每月可免费部署多达数量的Node.js和Python应用，数量多达5万个请求. 包括免费的数据库，身份验证和电子邮件.
  * [dronahq.com](https://www.dronahq.com/)  —没有用于企业直观地开发应用程序，与现有系统集成以快速构建内部应用程序，流程和表单的代码应用程序开发平台. 免费计划每月提供200个任务，无限的草稿应用程序和1个已发布的应用程序
  * [encore.dev](https://encore.dev/)  —使用静态分析的后端框架可提供自动基础结构，免费样板代码等. 包括针对爱好项目的免费云托管.
  * [firebase.google.com](https://firebase.google.com) —构建实时应用程序，免费计划具有100个最大连接，10 GB数据传输，1 GB数据存储，1 GB主机存储和10 GB主机传输
  * [gearhost.com](https://www.gearhost.com/pricing)  — .NET和PHP应用程序的平台. 在资源有限的共享服务器上免费提供256 MB RAM
  * [gigalixir.com](https://gigalixir.com/) -Gigalixir为Elixir / Phoenix应用程序提供了1个永不休眠的免费实例，以及免费的PostgreSQL数据库限制为2个连接，10、000行且无备份.
  * [glitch.com](https://glitch.com/)  —具有代码共享和实时协作等功能的免费公共/私人托管. 免费计划的每月限制为1000小时.
  * [heroku.com](https://www.heroku.com/) —将您的应用程序托管在云中，单进程应用程序免费
  * [Krucible](https://usekrucible.com)  — Krucible是用于创建Kubernetes集群以进行测试和开发的平台. 免费套餐帐户每月有25个群集小时.
  * [ZARVIS](https://zarvis.ai)  -开源Github项目的免费托管Kubernetes命名空间. 释放1GB内存和1个vCPU.
  * [Mendix](https://www.mendix.com/)  —适用于企业的快速应用程序开发，支持无限制用户的无限数量的免费沙箱环境，每个应用0.5 GB的存储和1 GB的RAM.  Studio和Studio Pro IDE也可以免费使用.
  * [m3o.com](https://m3o.com)  -用于API服务开发的云平台.  M3O是完全托管的微服务即服务产品，专注于在云中进行Go微服务开发. 免费套餐可提供足以运行5项服务并与其他人协作的服务.
  * [Okteto Cloud](https://okteto.com)  -专为远程开发而设计的托管Kubernetes服务. 免费的开发人员帐户带有8GB的RAM，4个CPU和5GB的磁盘空间. 闲置24小时后，应用程序进入睡眠状态.
  * [opeNode](https://openode.io)  —用于开源项目的免费Node.js托管.  100 GB带宽/月，具有100 MB内存和1000 MB存储空间. 使用CLI或现有的Git存储库进行部署.
  * [outsystems.com](https://www.outsystems.com/) —用于本地或云的企业Web开发PaaS，免费的“个人环境”产品允许无限的代码和高达1 GB的数据库
  * [pipedream.com](https://pipedream.com)  -为开发人员构建的集成平台. 根据任何触发器开发任何工作流程. 工作流是代码，您可以运行 [for free](https://docs.pipedream.com/pricing/) . 无需管理服务器或云资源.
  * [pythonanywhere.com](https://www.pythonanywhere.com/)  — Cloud Python应用程序托管. 初学者帐户免费，在your-username.pythonanywhere.com域中有1个Python Web应用程序，512 MB私有文件存储，1个MySQL数据库
  * [scn.sap.com](https://scn.sap.com/docs/DOC-56411)  — SAP提供的内存中平台即服务产品. 免费的开发人员帐户具有1 GB的结构化，1 GB的非结构化，1 GB的Git数据，并允许您运行HTML5，Java和HANA XS应用程序
  * [staroid.com](https://staroid.com) - Managed Kubernetes namespace service designed to fund open source developers. Free 8 CPUs and 16GB of RAM namespace to test branches and pull requests of public repository. Free test namespace shutdown every 30 minutes. Maximum 2 concurrent test namespaces.
  * [SUSE Developer Program](https://developer.suse.com)  —免费体验云原生生产力. 通过您自己的开发人员沙盒获得SUSE Cloud Application Platform的动手能力.  1个免费应用程序. 提供免费的子域以及用于CLI的API.  1 GB的存储和内存配额.
  * [workers.dev](https://workers.dev)  -在Cloudflare的全球网络上免费部署无服务器代码. 每天使用worker.dev子域的100,000个免费请求.
  * [Platform9](https://platform9.com/)  -专为开发人员设计的托管Kubernetes服务. 免费的开发人员帐户最多包含3个群集和20个节点群集.
  * [fly.io](https://fly.io/)  -Fly是一个需要全局运行的应用程序的平台. 它可以在靠近用户的地方运行您的代码，并在您的应用最繁忙的城市中扩展计算. 编写您的代码，将其打包到Docker映像中，将其部署到Fly的平台上，然后执行所有工作以使您的应用程序保持活泼. 附带项目免费，每月10美元的服务信用可自动应用于任何付费服务. 而且，如果您运行的是非常小的虚拟机，那么信誉将大有帮助.
  * [appfleet.com](https://appfleet.com/)  -appfleet是一个边缘平台，允许其用户同时将容器全局部署到多个区域. 它提供了一个易于使用的UI，同时自动化了诸如智能路由，集群，故障转移，监视等所有复杂性. 它对开源项目是免费的，所有用户都会自动获得10美元来托管他们想要的任何东西.
  * [Divio](https://www.divio.com/)  -一个仅使用Docker管理云应用程序部署的平台. 可免费订阅开发项目.

## BaaS

  * [ably.com](https://www.ably.com)  -用于实时消息传递，推送通知和事件驱动的API创建的API. 免费计划每月有300万条消息，100个并发连接，100个并发通道.
  * [back4app.com](https://www.back4app.com) -Back4App是基于Parse Platform的易于使用，灵活且可扩展的后端.
  * [backendless.com](https://backendless.com/) —移动和Web Baas，具有1 GB的可用文件存储空间，每月推送通知50000，表中有1000个数据对象.
  * [blockspring.com](https://www.blockspring.com/)  —云功能. 每月免费运行500万次
  * [BMC Developer Program](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp)  — BMC开发人员计划提供了用于为您的企业构建和部署数字创新的文档和资源. 访问全面的个人沙箱，其中包括平台，SDK和可用于构建和定制应用程序的组件库.
  * [darklang.com](https://darklang.com/) - Hosted language combined with editor and infrastructure. Free during the beta, generous free tier planned after beta.
  * [getstream.io](https://getstream.io/) —在数小时而不是数周的时间内构建可扩展的新闻提要和活动流，每月免费更新300万个提要
  * [hasura.io](https://hasura.io/) —快速构建和部署应用程序后端的平台，单节点集群免费.
  * [iron.io](https://www.iron.io/) —具有免费套餐和1个月免费试用的异步任务处理（如AWS Lambda）
  * [netlicensing.io](https://netlicensing.io)  -从台式机到物联网和SaaS的任何平台上针对您的软件的经济高效且集成的许可即服务（LaaS）解决方案. 当您是学生时，*免费*的基本计划.
  * [onesignal.com](https://onesignal.com/) -无限的免费推送通知
  * [paraio.com](https://paraio.com)  —具有灵活身份验证，全文搜索和缓存的后端服务API. 免费提供1个应用，1GB应用数据.
  * [posthook.io](https://posthook.io/)  —作业计划服务. 允许您安排特定时间的请求. 每月免费提供500个预定的请求.
  * [progress.com](https://www.progress.com/kinvey)  —移动后端入门计划每秒可无限制请求，并具有1 GB的数据存储空间. 企业应用程序支持
  * [pubnub.com](https://www.pubnub.com/) —免费推送通知，每月最多可发送一百万条消息，每天可使用100台设备
  * [pushbots.com](https://pushbots.com/)  —推送通知服务. 每月免费进行150万次推送
  * [pushcrew.com](https://pushcrew.com/)  —推送通知服务. 无限通知，最多2000个订户
  * [pusher.com](https://pusher.com/beams)  —每月有2000名活跃用户的免费无限制推送通知. 适用于iOS和Android设备的单个API.
  * [pushtechnology.com](https://www.pushtechnology.com/)  —用于浏览器，智能手机和所有人的实时消息传递.  100个并发连接. 每月免费10 GB数据
  * [quickblox.com](https://quickblox.com/) —用于即时消息传递，视频和语音呼叫以及推送通知的通信后端
  * [restspace.io](https://restspace.io/) -为服务器配置身份验证，数据，文件，电子邮件API，模板等服务，然后组成管道并转换数据.
  * [Salesforce Developer Program](https://developer.salesforce.com/signup)  —使用拖放工具快速构建应用程序Lightning. 通过点击自定义您的数据模型. 使用Apex代码进一步了解. 使用功能强大的API与任何东西集成. 保持企业级安全性. 使用点击或任何先进的Web框架自定义UI. 免费开发人员计划可访问完整的Lightining平台.
  * [ServiceNow Developer Program](https://developer.servicenow.com/)  —快速构建，测试和部署使您的组织更好地工作的应用程序. 免费实例和访问早期预览.
  * [simperium.com](https://simperium.com/)  —即时，自动，多平台，无限制地发送和存储结构化数据，最大程度地移动数据.  2500个用户/月
  * [stackstorm.com](https://stackstorm.com/) —由事件驱动的应用程序，服务和工作流自动化，无流量，访问控制，LDAP等的免费提供.
  * [streamdata.io](https://streamdata.io/)  —将任何REST API转换为事件驱动的流API. 免费计划多达一百万条消息和10个并发连接
  * [tyk.io](https://tyk.io/)  —具有身份验证，配额，监控和分析的API管理. 免费云产品
  * [zapier.com](https://zapier.com/)  —连接您使用的应用程序，以自动执行任务. 每15分钟5个zaps，每月执行100个任务
  * [LeanCloud](https://leancloud.app/)  —移动后端.  1GB的数据存储空间，256MB实例，每天3K API请求，每天10K推送是免费的.  （API与解析平台非常相似）
  * [Liteflow](https://liteflow.com/) -旨在帮助您专注于应用程序真正价值的低代码开发工具包.

## Web Hosting

  * [000WebHost](https://www.000webhost.com/) —零成本的网站托管，其中包含Apache，PHP，MySQL，cPanel，且每页底部都有广告！
  * [20i](https://www.20i.com/)  —与付费计划在同一平台上的免费网络托管，无广告. 包括免费的CDN，100个电子邮件地址，SSL和80多个一键安装.
  * [Alwaysdata](https://www.alwaysdata.com/)  — 100 MB免费虚拟主机，支持MySQL，PostgreSQL，CouchDB，MongoDB，PHP，Python，Ruby，Node.js，Elixir，Java，Deno，自定义Web服务器，可通过FTP，WebDAV和SSH访问； 包括邮箱，邮件列表和应用安装程序.
  * [Awardspace.com](https://www.awardspace.com) —免费的虚拟主机+免费的短域名，PHP，MySQL，应用安装程序，电子邮件发送和无广告.
  * [Bubble](https://bubble.io/) —可视化编程，无需代码即可构建Web和移动应用程序，而Bubble品牌则免费提供.
  * [Byet](https://byet.host) — Byet为您提供了大量免费且无广告的负载平衡免费虚拟主机服务，包括PHP，MySQL，FTP，Vistapanel等！
  * [cloudno.de](https://cloudno.de/) —用于Node.js应用程序的免费云托管.
  * [Drive To Web](https://drv.tw)  —从Google云端硬盘和OneDrive直接托管到网络. 仅静态站点. 永远免费. 每个Google / Microsoft帐户一个站点.
  * [Endless Hosting](https://theendlessweb.com/)  — 30​​0 MB的存储空间，免费的SSL，PHP，MySQL，FTP，免费的子域，电子邮件，DNS，漂亮的面板UI. 最好的之一！
  * [Fenix Web Server](https://preview.fenixwebserver.com)  -开发人员桌面应用程序，用于在本地托管网站并公开共享（实时）. 使用其漂亮的用户界面，API和/或CLI，可以按自己喜欢的方式工作.
  * [Free Hosting](http://freehostingnoads.net/) —使用PHP 5，Perl，CGI，MySQL，FTP，文件管理器，POP电子邮件，免费子域，免费域托管，DNS区域编辑器，网站统计信息，免费在线支持以及许多其他功能所没有的免费托管其他免费主机.
  * [Freehostia](https://www.freehostia.com)  — FreeHostia提供免费的托管服务，包括. 业界最佳的控制面板和一键安装50多种免费应用程序. 即时设置. 没有强制广告.
  * [heliohost.org](https://www.heliohost.org) -社区为每个人免费托管.
  * [hostman.com](https://hostman.com) —从您的GitHub存储库中免费部署多达3个静态站点.
  * [InfinityFree](https://infinityfree.net/) -使用MySQL，cPanel和免费广告的免费PHP网站托管.
  * [neocities.org](https://neocities.org) —静态，1 GB可用存储空间和200 GB带宽.
  * [netlify.com](https://www.netlify.com/) — Builds, deploy and hosts static site/app free for, 100 GB data and 100 GB/month bandwidth.
  * [commons.host](https://commons.host/)  -静态网络托管和CDN.100％免费和开源软件（FOSS）. 通过商业上可持续的软件即服务（SaaS）为研发提供资金.
  * [pantheon.io](https://pantheon.io/)  — Drupal和WordPress托管，自动化的DevOps和可扩展的基础架构. 开发人员和代理机构免费
  * [pony.icu](https://pony.icu/)  —来自PonyICU的具有无限磁盘空间，无限带宽和无限网站的免费虚拟主机. 包括PHP和MySQL.
  * [readthedocs.org](https://readthedocs.org/) —免费文档托管，包括版本控制，PDF生成等
  * [render.com](https://render.com) —一个统一的平台，用于构建和运行所有应用程序和Web应用程序，其中包括免费的SSL，全局CDN，专用网络和来自Git的自动部署，对于静态网页免费.
  * [sourceforge.net](https://sourceforge.net/) —免费查找，创建和发布开源软件
  * [surge.sh](https://surge.sh/)  —面向前端开发人员的静态Web发布. 具有自定义域支持的无限站点
  * [tilda.cc](https://tilda.cc/) —一个站点，50个页面，50 MB的存储空间，只有170多个可用的主要预定义块，没有字体，没有网站图标，也没有自定义域
  * [txti.es](https://txti.es/) —使用降价快速创建网页.
  * [Vercel](https://vercel.com/)  —每次“ git push”时，使用免费的SSL，全局CDN和唯一的预览URL来构建，部署和托管Web应用程序. 非常适合Next.js和其他静态站点生成器.
  * [Versoly](https://versoly.com/)  —专注于SaaS的网站构建器-无限的网站，70多个块，5个模板，自定义CSS，网站图标，SEO和表单. 没有自定义域.
  * [Qovery](https://www.qovery.com)  — Qovery是在AWS，GCP和Azure上部署全栈应用程序的最简单方法. 对于具有数据库，SSL，全局CDN以及从Git自动部署的开发人员而言，它是免费的虚拟主机.
  * [0hi.me](https://0hi.me/)  —为您的小型项目提供免费的PHP和MySQL虚拟主机.  SSL / TLS和CDN也免费提供.

## DNS

  * [1984.is](https://www.1984.is/product/freedns/) —带有API的免费DNS服务，包括许多其他免费DNS功能.
  * [biz.mail.ru](https://biz.mail.ru) —最多可容纳5,000个用户的免费电子邮件和DNS托管
  * [cloudns.net](https://www.cloudns.net/) —免费DNS托管多达1个具有50条记录的域
  * [dns.he.net](https://dns.he.net/) —具有动态DNS支持的免费DNS托管服务
  * [dnspod.com](https://www.dnspod.com/) — Free DNS hosting.
  * [duckdns.org](https://www.duckdns.org/)  —免费DDNS，在免费层上最多包含5个域. 带有各种设置的配置指南.
  * [dynu.com](https://www.dynu.com/) —免费的动态DNS服务
  * [fosshost.org](https://fosshost.org/) -免费的开源托管VPS，Web，存储和镜像托管
  * [freedns.afraid.org](https://freedns.afraid.org/)  —免费的DNS托管. 还提供基于众多公共用户的免费子域 [contributed domains](https://freedns.afraid.org/domain/registry/) . 注册后，可从“子域”菜单中获得免费的子域.
  * [freenom.com](https://freenom.com/)  —免费域名提供商. 免费获取FQDN.
  * [luadns.com](https://www.luadns.com/) —免费DNS托管，3个域，所有功能都有合理的限制
  * [namecheap.com](https://www.namecheap.com/domains/freedns/)  —免费DNS. 域名数量无限制
  * [noip](https://www.noip.com/) —动态dns服务，每30天最多可免费提供3个主机名并进行确认
  * [ns1.com](https://ns1.com/) —数据驱动DNS，自动流量管理，500k免费查询
  * [pointhq.com](https://pointhq.com/developer) -Heroku上的免费DNS托管.
  * [selectel.com](https://selectel.com/services/dns/) —免费DNS托管，任意播
  * [web.gratisdns.dk](https://web.gratisdns.dk/domaener/dns/) — Free DNS hosting.
  * [Yandex.Connect](https://connect.yandex.com/pdd/) —最多可容纳1,000位用户的免费电子邮件和DNS托管
  * [zilore.com](https://zilore.com/en/dns) — Free DNS hosting.
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) —具有动态DNS支持的免费DNS托管.
  * [zonewatcher.com](https://zonewatcher.com)  —自动备份和DNS更改监视.  1个域名免费
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) –华为免费DNS托管
  * [Hetzner](https://www.hetzner.com/dns-console) – Hetzner提供的具有API支持的免费DNS托管
  * [Glauca](https://docs.glauca.digital/hexdns/) –多达3个域的免费DNS托管和DNSSEC支持
  * [F5](https://www.f5.com/products/ways-to-deploy/cloud-services/dns-cloud-service)  –免费的主要区域的Anycast DNS托管. 对于二级区域（每月最多1个域）和300万个请求，免费.

## IaaS

  * [backblaze.com](https://www.backblaze.com/b2/)  — Backblaze B2云存储. 免费10 GB（类似于Amazon S3）对象存储，不受时间限制
  * [scaleway.com](https://www.scaleway.com/en/object-storage/)  — S3兼容的对象存储.  75 GB的免费存储空间和外部传出流量
  * [terraform.io](https://www.terraform.io/)  —地形云. 免费的远程状态管理和团队协作，最多可容纳5个用户.

## DBaaS

   * [airtable.com](https://airtable.com/) —看起来像电子表格，但它是一个关系数据库，无限制的基础，1,200行/基础和每月1,000个API请求
   * [Astra](https://astra.datastax.com/register) —具有5GB免费套餐的Cloud Native Cassandra即服务
   * [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ即服务，每月最多1M消息和20个免费连接
   * [elephantsql.com](https://www.elephantsql.com/) — PostgreSQL即服务，免费20 MB
   * [FaunaDB](https://fauna.com/) —无服务器云数据库，具有本地GraphQL，多模型访问和每日免费层达100 MB
   * [graphenedb.com](https://www.graphenedb.com/) — Neo4j即服务，最多可支持1,000个节点和10,000个关系
   * [heroku.com](https://www.heroku.com/) — PostgreSQL即服务，最多10,000行和20个免费连接（作为“附件”提供，但可以附加到原本为空的应用程序中并从外部访问）
   * [Upstash](https://upstash.com/) —无服务器Redis，具有每天最多10,000个请求的免费层，最大256MB数据库大小和20个并发连接
   * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) —免费套餐提供512 MB
   * [redsmin.com](https://www.redsmin.com/) — Redis的在线实时监视和管理服务，可免费监视1个Redis实例
   * [redislabs](https://redislabs.com/try-free/) -免费的30Mb Redis实例
   * [MemCachier](https://www.memcachier.com/)  —托管的Memcache服务. 免费，最大25MB，1个代理服务器和基本分析
   * [scalingo.com](https://scalingo.com/) —主要是PaaS，但提供了128MB至192MB的MySQL，PostgreSQL或MongoDB免费层
   * [SeaTable](https://seatable.io/)  —由Seafile团队构建的，类似于电子表格的灵活数据库. 无限的表格，2,000行，1个月的版本控制，最多25位团队成员.
   * [skyvia.com](https://skyvia.com/) — Cloud Data Platform，提供免费套餐，并且处于Beta版时，所有计划都是完全免费
   * [StackBy](https://stackby.com/)  —一种工具，可将电子表格的灵活性，数据库的功能以及与您喜欢的业务应用程序的内置集成结合在一起. 免费计划包括无限用户，10个堆栈，每个堆栈2GB附件.
   * [remotemysql.com](https://remotemysql.com) —远程MySQL数据库托管，设置是即时的，并使用phpMyAdmin进行管理，免费提供100Mb数据，免费备份，无查询限制和99％正常运行时间.
   * [InfluxDB](https://www.influxdata.com/) —时间序列数据库，最多可提供3MB / 5分钟的写入，30MB / 5分钟的读取和10,000个基数序列
   * [Quickmetrics](https://www.quickmetrics.io/) —包含带有仪表板的时间序列数据库，每天最多可释放10,000个事件，并且总共提供5个指标.
   * [restdb.io](https://restdb.io/)  -快速，简单的NoSQL云数据库服务. 使用restdb.io，您可以获得架构，关系，自动REST API（带有类似MongoDB的查询）以及用于处理数据的高效多用户管理UI. 免费计划允许每秒3个用户，2500条记录和1个API请求.
   * [Unbounded](https://www.unbounded.cloud/)  -使用Javascript作为查询语言的NoSQL DBaaS. 免费套餐永久允许每月每月50,000次读写.
   * [Freedb](https://freedb.tech)  -免费的MySQL云数据库，可通过PhpMyAdmin进行远程访问. 免费套餐允许数据库存储高达100Mb.  **如果超过100Mb的数据库将被删除，而不会发出任何警告.**

## STUN, WebRTC, Web Socket Servers and Other Routers

   * [conveyor.cloud](https://conveyor.cloud/) — Visual Studio扩展，用于将IIS Express公开到本地网络，或通过通往公共URL的隧道公开.
   * [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi是一项托管VPN服务，可让您通过免费计划将类似于LAN的网络安全地扩展到分布式团队，并允许最多5人的无限网络
   * [Radmin VPN](https://www.radmin-vpn.com/)  -通过支持LAN状网络的VPN将多台计算机连接在一起. 无限的同行.  （Hamachi替代）
   * [localhost.run](https://localhost.run/)  —立即共享您的本地主机环境！ 无需下载. 在端口8080上运行您的应用程序，然后运行此命令并共享URL.
   * [ngrok.com](https://ngrok.com/) —通过隧道将本地运行的服务器公开到公共URL.
   * [segment.com](https://segment.com/) — Hub to translate and route events to other third-party services. 100,000 events/month free
   * [https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp](https://github.com/ripienaar/free-for-dev/blob/master/stun:global.stun.twilio.com:3478?transport=udp) — Twilio STUN
   * [https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302](https://github.com/ripienaar/free-for-dev/blob/master/stun:stun.l.google.com:19302) — Google STUN
   * [webhookrelay.com](https://webhookrelay.com)  —管理，调试，扇出并将所有Webhook代理到公共或内部（即localhost）目标. 另外，通过获取公共HTTP终结点（`https://yoursubdomain.webrelay.io &lt;----&gt; http：// localhost：8080），公开通过隧道在私有网络中运行的服务器.
   * [Xirsys](https://www.xirsys.com) —具有免费层级的STUN / TURN服务器的全球网络.
   * [ZeroTier](https://www.zerotier.com)  — FOSS管理的虚拟以太网即服务. 免费计划的100个客户端的无限端到端加密网络. 台式机/手机/ NA的客户端；  Web界面，用于配置自定义路由规则并批准专用网络上的新客户端节点.

## Issue Tracking and Project Management

   * [acunote.com](https://www.acunote.com/) —免费的项目管理和SCRUM软件，最多可容纳5个团队成员
   * [AppFlux](https://appflux.io)  —具有日志管理和问题的项目管理工具. 让您的团队加入其中，并通过电子邮件忘记管理.
   * [asana.com](https://asana.com/) —与合作者一起私人项目免费
   * [Basecamp](https://basecamp.com/personal)  -待办事项列表，里程碑管理，类似论坛的消息传递，文件共享和时间跟踪. 最多3个项目，20个用户和1GB的存储空间.
   * [bitrix24.com](https://www.bitrix24.com/) —免费的内部网和项目管理工具
   * [cacoo.com](https://cacoo.com/)  —实时在线图：流程图，UML，网络. 最高免费 15位使用者/图表，25张
   * [clickup.com](https://clickup.com/)  - 项目管理. 具有云存储功能的免费高级版本. 提供移动应用程序和Git集成
   * [Cloudcraft](https://cloudcraft.co/) —使用Cloudcraft可视化设计器在几分钟内设计出专业的架构图，该设计器还通过同时显示实时数据的智能组件针对AWS进行了优化.
   * [Clubhouse](https://clubhouse.io/)  -项目管理平台. 永久免费，最多可容纳10个用户
   * [Codegiant](https://codegiant.io)  —通过存储库托管和CI / CD进行项目管理. 免费计划与5位团队成员一起提供无限的存储库，项目和文档. 每月500 CI / CD分钟. 每月30000次无服务器代码运行分钟.1GB的存储库.
   * [Confluence](https://www.atlassian.com/software/confluence)  -Atlassian的内容协作工具，用于帮助团队高效地协作和共享知识. 免费计划，最多10位用户.
   * [contriber.com](https://www.contriber.com/) —可定制的项目管理平台，免费的入门计划，5个工作区
   * [draw.io](https://www.draw.io/)  —本地存储在Google云端硬盘，OneDrive或Dropbox中的在线图表. 免费提供所有功能和存储级别
   * [easyretro.io](https://www.easyretro.io/) —免费的简单直观的sprint追溯工具
   * [gleek.io](https://www.gleek.io)  —针对开发人员的免费图表描述工具. 使用您的关键字创建非正式的UML类，对象或实体关系图.
   * [gliffy.com](https://www.gliffy.com/)  —在线图：流程图，UML，线框，...也是Jira和Confluence的插件.  5张图和2 MB可用空间
   * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector)  -GraphQL检查器输出两个GraphQL模式之间的更改列表. 每次更改都经过精确解释，并标记为中断，不中断或危险.
   * [huboard.com](https://huboard.com/) —针对您的GitHub问题的即时项目管理，免费提供给开源
   * [Instabug](https://instabug.com)  —适用于移动应用程序的全面的错误报告和应用程序内反馈SDK. 免费计划，最多1个应用程序和1个成员.
   * [Ilograph](https://www.ilograph.com/)   —交互式图表，使用户可以从多个角度和细节级别查看其基础结构. 图可以用代码表示. 免费套餐拥有无限的私人图表，最多可容纳3个查看者.
   * [Issue Embed](https://issueembed.dev/)  -一个错误报告工具，网站可以直接进入您的Github问题. 免费的个人存储库计划，每月最多500个问题，每月最多10,000个页面浏览量.
   * [Jira](https://www.atlassian.com/software/jira)  —在许多公司环境中使用的高级软件开发项目管理工具. 免费计划，最多10位用户.
   * [kanbanflow.com](https://kanbanflow.com/)  -基于董事会的项目管理. 免费的高级版本，有更多选择
   * [kanbantool.com](https://kanbantool.com/)  -基于看板的项目管理. 免费的付费计划，更多选择
   * [Kitemaker.co](https://kitemaker.co)  -在产品开发过程的所有阶段进行协作，并跟踪Slack，Discord，Figma和Github上的工作. 无限的用户，无限的空间. 免费计划多达250个工作项目.
   * [kanrails.com](https://kanrails.com/)  -基于看板的项目管理. 免费供3个合作者，2个项目和5个曲目使用. 付费计划适用于无限的合作者，项目和轨道.
   * [Kumu.io](https://kumu.io/)   —带有动画，装饰，过滤器，聚类，电子表格导入等的关系图. 免费套餐允许无限的公共项目. 图形大小不受限制. 免费的学生私人项目. 如果您不希望文件公开在线（上载，编辑，下载，丢弃），则可以使用沙盒模式.
   * [LeanBoard](https://www.leanboard.io) —带有便笺的协作白板，用于解决GitHub问题（对于示例映射和其他技术很有用）
   * [Linear](https://linear.app/)  —具有简化界面的问题跟踪器. 免费提供给无限成员，最大上传文件大小为10MB，250个问题（不包括存档）
   * [MeisterTask](https://www.meistertask.com/)  —团队的在线任务管理. 最多释放3个项目，无限的项目成员.
   * [MeuScrum](https://www.meuscrum.com/en) -带看板的免费在线Scrum工具
   * [Ora](https://ora.pm/)  -敏捷的任务管理和团队协作. 最多可供3个用户免费使用，并且文件大小限制为10 MB.
   * [pivotaltracker.com](https://www.pivotaltracker.com/) —免费提供给无限的公共项目和两个私人项目，这些私人项目共有3个活跃用户（读写）和无限个被动用户（只读）.
   * [plan.io](https://plan.io/)  —具有存储库托管和更多选项的项目管理.  2位拥有10位客户和500MB存储空间的用户免费
   * [planitpoker.com](https://www.planitpoker.com/) —免费的在线计划扑克（估算工具）
   * [senseitool.com](https://www.senseitool.com/) —敏捷的回顾工具-免费.
   * [SpeedBoard](https://speedboard.app) -敏捷和Scrum回顾委员会-免费.
   * [Tadum](https://tadum.app) -专为定期会议而设计的会议议程和会议记录应用，免费供10人以下的团队使用
   * [taiga.io](https://taiga.io/) —适用于初创企业和敏捷开发人员的项目管理平台，免费提供给开源
   * [Tara AI](https://tara.ai/)  —简单的冲刺管理服务. 免费计划具有无限的任务，冲刺和工作空间，没有用户限制.
   * [targetprocess.com](https://www.targetprocess.com/)  —可视项目管理，从看板和Scrum到几乎所有运营过程. 无限用户免费使用，最多1000个数据实体{[more details](https://www.targetprocess.com/pricing/)}
   * [taskade.com](https://www.taskade.com/) —团队的实时协作任务列表和大纲
   * [taskulu.com](https://taskulu.com/)  -基于角色的项目管理. 最多释放5个用户. 与GitHub / Trello / Dropbox / Google Drive集成
   * [teamwork.com](https://teamwork.com/)  —项目管理和团队聊天.  5个用户和2个项目免费. 提供高级计划.
   * [testlio.com](https://testlio.com/)  —问题跟踪，测试管理和Beta测试平台. 免费供私人使用
   * [terrastruct.com](https://terrastruct.com/)  —专用于软件体系结构的在线图制作工具. 每个图最多可有4层免费层.
   * [todoist.com](https://todoist.com/)  —协作和个人任务管理. 提供免费，高级和团队计划. 为符合条件的用户提供折扣.
   * [trello.com](https://trello.com/)  -基于董事会的项目管理. 无限个人董事会，10个团队董事会.
   * [Tweek](https://tweek.so/) —简单的每周待办事项日历和任务管理.
   * [ubertesters.com](https://ubertesters.com/) —测试平台，集成和人群测试人员，2个项目，5个成员
   * [vabotu](https://vabotu.com/)  -用于项目管理的协作工具. 提供免费和其他计划.  Freelance计划适用于10个用户，包括消息传递，任务板，5GB在线存储，工作区，导出数据.
   * [vivifyscrum.com](https://www.vivifyscrum.com/)  —用于敏捷项目管理的免费工具.  Scrum兼容
   * [Yodiz](https://www.yodiz.com/)  —敏捷开发和问题跟踪. 最多释放3个用户，无限的项目.
   * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud)  —针对FOSS项目，私人项目免费托管的YouTrack（InCloud）（3个用户免费）. 包括时间跟踪和敏捷板
   * [zenhub.com](https://www.zenhub.com)  — GitHub内唯一的项目管理解决方案. 公共回购，OSS和非营利组织免费
   * [zepel.io](https://zepel.io/)  -项目管理工具，可让您规划功能，跨学科协作以及一起构建软件. 最多释放5名成员. 没有功能限制.
   * [zenkit.com](https://zenkit.com)  —项目管理和协作工具. 免费，最多5位成员，5 GB附件.
   * [Zube](https://zube.io)  —可免费为4个项目和4个用户提供免费计划的项目管理.  GitHub集成可用.

## Storage and Media Processing

   * [borgbase.com](https://www.borgbase.com/)  —用于Borg Backup的简单，安全的异地备份托管.  10 GB的可用备份空间和2个存储库.
   * [sirv.com](https://sirv.com/)  —具有动态图像优化和大小调整功能的Smart Image CDN. 免费套餐包括500 MB的存储空间和2 GB的带宽.
   * [image4.io](https://image4.io/)  —通过SDK，集成和迁移工具，可以为网站和应用程序进行图像上传，强大的处理，存储和交付. 免费套餐包括25个积分.  1个信用额度等于1 GB的CDN使用量，1GB的存储量或1000个映像转换.
   * [cloudimage.com](https://cloudimage.com/)  —全面的图像优化和CDN服务，在全球拥有1500多个在线点. 多种图像尺寸调整，压缩，水印功能. 用于响应图像，360图像制作和图像编辑的开源插件.  25GB CDN流量，25GB高速缓存存储和无限制转换的免费月租计划.
   * [cloudinary.com](https://cloudinary.com/)  —使用Ruby，Python，Java，PHP，Objective-C等库，可以为网站和应用程序进行图像上载，功能强大的操作，存储和交付. 免费套餐包括25个每月积分.  1个积分等于1,000个图像转换，1 GB的存储空间或1 GB的CDN使用率.
   * [easyDB.io](https://easydb.io/)  —一键式托管数据库提供程序. 它们为开发目的提供了您选择的编程语言的数据库. 该数据库是临时数据库，将在24或72小时后在免费层上删除.
   * [embed.ly](https://embed.ly/)  —提供用于将媒体嵌入网页，响应式图像缩放，从网页中提取元素的API. 免费，每月最多5,000个URL，每秒15个请求
   * [filestack.com](https://www.filestack.com/) —文件选择器，转换和交付，可免费使用250个文件，500个转换和3 GB带宽
   * [gumlet.com](https://www.gumlet.com/)  —图像调整服务. 它还可以优化图像并通过CDN进行传送. 免费套餐包括1 GB带宽，并且在1年中每月都有不限数量的图像处理.
   * [image-charts.com](https://www.image-charts.com/) —带有水印的无限图像图表生成
   * [jsonbin.io](https://jsonbin.io/) —免费的JSON数据存储服务，非常适合小型Web应用程序，网站，移动应用程序.
   * [kraken.io](https://kraken.io/) —用于网站性能即服务的图像优化，免费计划最大1 MB文件大小
   * [npoint.io](https://www.npoint.io/) —具有协作模式编辑的JSON存储
   * [otixo.com](https://www.otixo.com/)  —从一个位置加密，共享，复制和移动所有云存储文件. 基本计划提供最大250 MB的无限文件传输. 文件大小，并允许5个加密文件
   * [packagecloud.io](https://packagecloud.io/)  —托管YUM，APT，RubyGem和PyPI的软件包存储库. 有限的免费计划，可根据要求提供开源计划
   * [piio.co](https://piio.co/)  —为每个网站进行响应式图像优化和交付. 针对开发人员和个人网站的免费计划. 包括免费CDN，WebP和延迟加载.
   * [Pinata IPFS](https://pinata.cloud)  — Pinata是在IPFS上上传和管理文件的最简单方法. 我们友好的用户界面与IPFS API相结合，使Pinata成为针对平台，创建者和收集者的最简单的IPFS固定服务.  1 GB的免费存储空间以及对API的访问权限.
   * [placeholder.com](https://placeholder.com/) —快速简单的图像占位符服务
   * [placekitten.com](https://placekitten.com/) —一种快速简单的服务，用于获取小猫的图片以用作占位符
   * [plot.ly](https://plot.ly/)  —图形化并共享您的数据. 免费套餐包括无限的公共文件和10个私人文件
   * [podio.com](https://podio.com/) —您可以与多达五个人的团队一起使用Podio，并尝试基本计划的功能，但用户管理除外
   * [QuickChart](https://quickchart.io) —生成可嵌入的图像图表，图形和QR码
   * [redbooth.com](https://redbooth.com) — P2P文件同步，最多2个用户免费
   * [shrinkray.io](https://shrinkray.io/) — GitHub存储库的免费图像优化
   * [tinypng.com](https://tinypng.com/) —压缩和调整PNG和JPEG图像大小的API，每月免费提供500次压缩
   * [transloadit.com](https://transloadit.com/)  —处理文件上传以及视频，音频，图像，文档的编码. 通过GitHub Student Developer Pack为开源，慈善机构和学生免费. 商业应用程序可免费获得2 GB的测试驱动器
   * [uploadcare.com](https://uploadcare.com/hub/developers/)  — Uploadcare为媒体管道提供了基于尖端算法的终极工具包. 开发人员可以绝对免费使用所有功能：文件上传API和UI，图像CDN和原始服务，自适应传递和智能压缩.
   * [imagekit.io](https://imagekit.io)  –具有自动优化，实时转换和存储功能的Image CDN，您可以在几分钟之内将其与现有设置集成. 免费计划包括每月高达20GB的带宽.

## Design and UI

  * [Adobe XD](https://www.adobe.com/products/xd.html)  -与草图类似的线框和原型制作工具. 免费计划涵盖：1个有效的共享设计规范，Adobe Fonts Free（有限字体集），2GB的云存储.
  * [Mockplus iDoc](https://www.mockplus.com/idoc)  -Mockplus iDoc是功能强大的设计协作和移交工具. 免费计划包括3个用户和5个具有所有可用功能的项目.
  * [AllTheFreeStock](https://allthefreestock.com) -精选的免费图片，音频和视频列表.
  * [BoxySVG](https://boxy-svg.com/app) —一个免费的可安装Web应用程序，用于绘制SVG并以svg，png，jpeg其他格式导出.
  * [clevebrush.com](https://www.cleverbrush.com/) —免费的图形设计/照片拼贴应用程序，他们还提供付费集成作为组件.
  * [cloudconvert.com](https://cloudconvert.com/)  —将任何东西转换为任何东西.  208种支持的格式，包括视频到gif.
  * [CodeMyUI](https://codemyui.com) -精选的Web设计和带有代码段的UI灵感.
  * [designer.io](https://www.designer.io/)  —用于UI，插图等的设计工具. 有一个本机应用程序. 自由.
  * [figma.com](https://www.figma.com)  —用于团队的在线协作设计工具； 免费套餐包括无限的文件和查看器，最多2个编辑器和3个项目.
  * [Icons8](https://icons8.com)  —图标，插图，照片，音乐和设计工具. 免费计划以较低的分辨率提供有限的格式. 使用我们的资产时，链接到Icons8.
  * [imagebin.ca](https://imagebin.ca/) —用于图像的Pastebin.
  * [Invision App](https://www.invisionapp.com)  -UI设计和原型制作工具. 提供桌面和webapp. 可免费使用1个活动原型.
  * [landen.co](https://www.landen.co)  —为您的启动生成，编辑和发布漂亮的网站和登录页面. 全部没有代码. 免费套餐允许您拥有一个完全可自定义的网站，并可以在网络上发布.
  * [lensdump.com](https://lensdump.com/) -免费的云图像托管.
  * [Lorem Picsum](https://picsum.photos/)  -免费工具，易于使用的时尚占位符. 只需在我们的URL后添加所需的图像大小（宽度和高度），您将获得随机图像.
  * [marvelapp.com](https://marvelapp.com/) —设计，原型制作和协作，免费计划仅限于一个用户和一个项目.
  * [Mindmup.com](https://www.mindmup.com/)  —免费提供无限的思维导图，并将其存储在云中. 您的思维导图可随时随地在任何设备上随处使用.
  * [mockupmark.com](https://mockupmark.com/create/free) -为社交媒体和电子商务创建逼真的T恤和服装模型，免费提供40个模型.
  * [Octopus.do](https://octopus.do)  —视觉站点地图生成器. 实时构建您的网站结构并快速共享它，以与您的团队或客户进行协作.
  * [Pencil](https://github.com/evolus/pencil) -使用Electron的开源设计工具.
  * [Penpot](https://penpot.app)  -基于Web的开源设计和原型制作工具. 支持SVG. 完全免费.
  * [pexels.com](https://www.pexels.com/)  -免费的商业照片. 有免费的API，可让您按关键字搜索照片.
  * [photopea.com](https://www.photopea.com) —具有Adobe Photoshop UI的免费，高级在线设计编辑器，支持PSD，XCF和Sketch格式（Adobe Photoshop，Gimp和Sketch App）.
  * [pixlr.com](https://pixlr.com/) —在商业级别上免费的在线浏览器编辑器.
  * [Plasmic](https://www.plasmic.app/)  -快速，易于使用，功能强大的Web设计工具和页面构建器，已集成到您的代码库中. 建立响应式页面或复杂的组件； 可选地扩展代码； 并发布到生产站点和应用.
  * [Proto.io](https://www.proto.io)  -创建完全交互式的UI原型，而无需编写代码. 免费试用期结束后提供免费套餐. 免费套餐包括：1个用户，1个项目，5个原型，100MB在线存储和proto.io应用程序中的预览.
  * [resizeappicon.com](https://resizeappicon.com/) —一项简单的服务，用于调整和管理您的应用程序图标.
  * [Rive](https://rive.app)  -创建精美的动画并将其发送到任何平台. 个人永久免费. 该服务是一个编辑器，还可以在其服务器上托管所有图形. 它们还为许多平台提供运行时，以运行使用Rive制作的图形.
  * [smartmockups.com](https://smartmockups.com/) -创建产品模型，200个免费模型. 
  * [unDraw](https://undraw.co/) -不断更新的美丽svg图像集合，您可以完全免费使用，而无需注明出处.
  * [unsplash.com](https://unsplash.com/) -用于商业和非商业目的的免费库存照片（随心所欲许可）.
  * [vectr.com](https://vectr.com/) —适用于Web +桌面的免费设计应用程序.
  * [walkme.com](https://www.walkme.com/) —企业级指导和参与平台，免费计划3次穿越，最多5步/步行.
  * [Webflow](https://webflow.com)  -具有动画和网站托管的所见即所得网站生成器.  2个项目免费.
  * [Updrafts.app](https://updrafts.app)  -所见即所得的网站构建器，用于基于tailwindcss的设计. 免费用于非商业用途.
  * [whimsical.com](https://whimsical.com/)  -协作流程图，线框，便签和思维导图. 最多创建4个免费板.
  * [Zeplin](https://zeplin.io/)  —设计师和开发人员协作平台. 显示设计，资产和样式指南.  1个项目免费.
  * [Pixelixe](https://pixelixe.com/) —在线创建和编辑引人入胜的独特图形和图像.
  * [Responsively App](https://responsively.app) -一个免费的开发工具，可进行更快，更准确的响应式Web应用程序开发.
  * [SceneLab](https://scenelab.io) -在线样机图形编辑器，带有不断扩展的免费设计模板集合
  * [xLayers](https://xlayers.dev) -预览草图设计文件并将其转换为Angular，React，Vue，LitElement，Stencil，Xamarin等（https://github.com/xlayers/xlayers免费和开源）
  * [Grapedrop](https://grapedrop.com/)  —基于GrapesJS Framework的响应式，功能强大，经过SEO优化的网页构建器. 前5页免费，无限制的自定义域，所有功能和简单用法.

## Data Visualization on Maps

   * [IP Geolocation](https://ipgeolocation.io/) —每月可提供3万个请求的免费DEVELOPER计划.
   * [carto.com](https://carto.com/) —根据您的数据和公共数据创建地图和地理空间API.
   * [datamaps.world](https://datamaps.world/) —简单但功能强大的平台，可为您提供工具以免费层可视化地理空间数据.
   * [developers.arcgis.com](https://developers.arcgis.com)  —用于Web，台式机和移动设备上的地图，地理空间数据存储，分析，地理编码，路由等的API和SDK.  2,000,000个免费底图图块，20,000个未存储的地理代码，20,000个简单路线，5,000个行驶时间计算，每月5GB的免费图块+数据存储.
   * [Foursquare](https://developer.foursquare.com/) -通过Places API和Pilgrim SDK获得位置发现，场所搜索和上下文相关内容.
   * [geocod.io](https://www.geocod.io/)  —通过API或CSV上传进行地理编码. 每天2500个免费查询.
   * [geocodify.com](https://geocodify.com/)  —通过API或CSV上传进行地理编码和地理解析. 每月免费查询1万次.
   * [giscloud.com](https://www.giscloud.com/) —在线可视化，分析和共享地理数据.
   * [gogeo.io](https://gogeo.io/) —具有易于使用的API和对大数据的支持的地图和地理空间服务.
   * [graphhopper.com](https://www.graphhopper.com/) 为开发人员提供了免费的软件包，用于路由，路线优化，距离矩阵，地理编码，地图匹配.
   * [here](https://developer.here.com/)  —用于地图和可识别位置的应用程序的API和SDK. 每月免费进行25万笔交易.
   * [mapbox.com](https://www.mapbox.com/) —地图，地理空间服务和用于显示地图数据的SDK.
   * [maptiler.com](https://www.maptiler.com/cloud/)  —图库矢量图片矢量地图，地图服务和用于可视化的sdk. 具有每周更新和四种地图样式的免费矢量瓷砖.
   * [opencagedata.com](https://opencagedata.com)  —汇总OpenStreetMap和其他开放地理资源的地理编码API. 每天2500个免费查询.
   * [osmnames](https://osmnames.org/) —地理编码，搜索结果按相关维基百科页面的受欢迎程度排名.
   * [positionstack](https://positionstack.com/)  -全球位置和坐标的免费地理编码. 每月有25.000个个人使用请求.
   * [stadiamaps.com](https://stadiamaps.com/)  —地图图块，路线，导航和其他地理空间API. 每天有2,500幅免费地图视图和API请求，用于非商业用途和测试.
   * [GeocodeAPI](https://geocodeapi.io)  -Geocode API：基于Pelias的地址到坐标的转换和地理解析. 通过CSV批量地理编码. 每月350000个免费请求.

## Package Build System

   * [build.opensuse.org](https://build.opensuse.org/) —用于多个发行版（SUSE，EL，Fedora，Debian等）的软件包构建服务.
   * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) —针对Fedora和EL的基于模拟的RPM构建服务.
   * [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu和Debian构建服务.

## IDE and Code Editing

   * [3v4l](https://3v4l.org/) -免费的在线PHP Shell和摘要共享站点，可在300多个PHP版本中运行您的代码
   * [Android Studio](https://d.android.com/studio)  — Android Studio提供了用于在每种类型的Android设备上构建应用程序的最快工具. 开源IDE，对所有人免费，是开发Android应用程序的最佳人选. 适用于Windows，Mac，Linux甚至ChromeOS！
   * [Apache Netbeans](https://netbeans.apache.org/) —开发环境，工具平台和应用程序框架.
   * [apiary.io](https://apiary.io/) —带有即时API模拟和生成的文档的协作设计API（免费提供无限的API蓝图和具有一个管理员帐户和托管文档的无限用户）.
   * [Atom](https://atom.io/) -Atom是一个基于Electron的可入侵文本编辑器.
   * [Bootify.io](https://bootify.io/) -具有自定义数据库和REST API的Spring Boot应用程序生成器.
   * [cacher.io](https://www.cacher.io) —带有标签的代码片段组织器，并支持100多种编程语言.
   * [Code::Blocks](https://codeblocks.org)  —免费的Fortran和C / C ++ IDE. 开源，可在Windows，macOS和Linux上运行.
   * [codesnip.com.br](https://codesnip.com.br)  —具有类别，搜索和标签的简单代码段管理器. 自由和无限.
   * [cocalc.com](https://cocalc.com/)  —（以前是位于cloud.sagemath.com的SageMathCloud）—在云中进行协作计算. 浏览器可访问具有内置协作功能的完整Ubuntu和许多用于数学，科学，数据科学的免费软件，并且预装了以下软件：Python，LaTeX，Jupyter Notebooks，SageMath，scikitlearn等.
   * [ide.cs50.io](https://ide.cs50.io/) -由哈佛大学AWS Cloud9提供支持的免费IDE.
   * [codepen.io](https://codepen.io/) — CodePen是Web前端侧的游乐场.
   * [codesandbox.io](https://codesandbox.io/) —用于React，Vue，Angular，Preact等的在线游乐场.
   * [Eclipse Che](https://www.eclipse.org/che/)  -基于Web和Kubernetes-Native IDE的开发人员团队，具有多语言支持. 开源和社区驱动. 由Red Hat托管的在线实例可在以下位置获得： [workspaces.openshift.com](https://workspaces.openshift.com/).
   * [fakejson.com](https://fakejson.com/)  — FakeJSON可帮助您使用其API快速生成伪造数据. 发出一个API请求，描述您想要的东西和想要的方式.  API以JSON返回所有内容. 加快进入市场的过程，寻找创意，并加以伪造，直到实现为止.
   * [gitpod.io](https://www.gitpod.io)  —适用于GitHub项目的即时，可编写代码的开发环境. 免费提供开源.
   * [ide.goorm.io](https://ide.goorm.io)  goormIDE是云上的完整IDE. 多语言支持，通过功能齐全的基于Web的终端通过基于Linux的容器，端口转发，自定义url，实时协作和聊天，共享链接，Git / Subversion支持. 还有更多功能（免费层包括每个容器1GB RAM和10GB存储空间，5个容器插槽）.
   * [JDoodle](https://www.jdoodle.com) —用于60多种编程语言的在线编译器和编辑器，并提供免费的REST API代码计划，每天最多可编译200学分.
   * [jetbrains.com](https://jetbrains.com/products.html) -生产力工具，IDE和部署工具（aka [IntelliJ IDEA](https://www.jetbrains.com/idea/), [PyCharm](https://www.jetbrains.com/pycharm/) ， ETC）. 为学生，教师，开放源代码和用户组提供免费许可证.
   * [jsbin.com](https://jsbin.com) — JS Bin是前端Web的另一个游乐场和代码共享站点（HTML，CSS和JavaScript.还支持Markdown，Jade和Sass）.
   * [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle是前端Web的游乐场和代码共享站点，也支持协作.
   * [JSONPlaceholder](http://jsonplaceholder.typicode.com/) 一些REST API端点以JSON格式返回一些虚假数据. 如果要在本地运行服务器，也可以使用源代码.
   * [Katacoda](https://katacoda.com) —用于软件工程师的交互式学习和培训平台，可帮助开发人员学习和公司提高采用率.
   * [micro-jaymock](https://micro-jaymock.now.sh/) -微小的API模拟微服务，用于生成伪造的JSON数据.
   * [mockable.io](https://www.mockable.io/)  — Mockable是一个简单的可配置服务，用于模拟RESTful API或SOAP Web服务. 此在线服务使您可以快速定义REST API或SOAP端点，并使它们返回JSON或XML数据.
   * [mockaroo](https://mockaroo.com/)  — Mockaroo使您可以生成CSV，JSON，SQL和Excel格式的真实测试数据. 您还可以为后端API创建模拟.
   * [Mocklets](https://mocklets.com) -基于HTTP的模拟API模拟器，可帮助您模拟API，以实现更快的并行开发和更全面的测试，并且终身免费使用.
   * [Prepros](https://prepros.io/)  -Prepros可以开箱即用地编译Sass，Less，Stylus，Pug / Jade，Haml，Slim，CoffeeScript和TypeScript，重新加载您的浏览器并使开发和测试您的网站变得非常容易，因此您可以专注于使其完美. 您还可以单击几下添加自己的工具.
   * [repl.it](https://repl.it/) —用于各种程序语言的云编码环境.
   * [SoloLearn](https://code.sololearn.com)  —非常适合运行代码段的云编程游乐场. 支持各种编程语言. 运行代码无需注册，但需要在其平台上保存代码时需要注册. 还为初学者和中级编码人员提供免费课程.
   * [stackblitz.com](https://stackblitz.com/) — Angular＆React在线VS Code IDE.
   * [Visual Studio Code](https://code.visualstudio.com/)  -重新定义和优化了代码编辑器，以构建和调试现代Web和云应用程序. 由Microsoft针对Windows，macOS和Linux开发.
   * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) — Fully-featured IDE with thousands of extensions, cross-platform app development (Microsoft extensions available for download for iOS and Android), desktop, web and cloud development, multi-language support (C#, C++, JavaScript, Python, PHP and more).
   * [VSCodium](https://vscodium.com/) -社区驱动，无需遥测/跟踪，并且免费许可Microsoft编辑器VSCode的二进制分发
   * [wakatime.com](https://wakatime.com/) —使用文本编辑器插件免费获得有关您编码活动的量化自我指标，有限的计划是免费的.

## Analytics, Events and Statistics

   * [AO Analytics](https://analytics.ao.gl/) —永久免费的客户分析服务，适用于您所有网站，每月无限制活动
   * [Avo](https://avo.app/)  —简化的分析发布工作流程. 真相单一跟踪计划，键入安全分析跟踪库，应用内调试器，数据可观察性以在发布前捕获所有数据问题. 免费提供2个工作区成员和1小时数据可观察性回溯.
   * [Clicky](https://clicky.com)  —网站分析平台.  1个网站的免费计划，具有3000次浏览量分析.
   * [indicative.com](https://indicative.com/)  —客户分析平台，用于优化客户参与度，提高转化率并提高保留率. 每月最多释放5000万个事件.
   * [Panelbear.com](https://panelbear.com/) —快速，私密的免费套餐每月包含5,000次网页浏览，可访问无限的网站
   * [Hitsteps.com](https://hitsteps.com/) — 1个网站每月2,000次网页浏览
   * [amplitude.com](https://amplitude.com/) —每月百万次活动，最多2个应用
   * [goatcounter.com](https://www.goatcounter.com/)  — GoatCounter是一个开源Web分析平台，可以作为托管服务（非商业用途免费）或自托管应用程序使用. 它旨在提供易于使用且有意义的隐私友好型Web分析，以替代Google Analytics（分析）或Matomo. 免费套餐适用于非商业用途，包括无限数量的网站，6个月的数据保留和每月10万次的网页浏览量.
   * [Google Analytics](https://analytics.google.com/) - 谷歌分析
   * [expensify.com](https://www.expensify.com/) —费用报告，免费的个人报告批准工作流程
   * [getinsights.io](https://getinsights.io) -注重隐私，无cookie的分析，每月最多可进行5k次活动.
   * [heap.io](https://heap.io)  —自动捕获iOS或Web应用程序中的每个用户操作. 免费，每月最多访问5,000次
   * [Hotjar](https://hotjar.com)  -网站分析和报告. 免费计划允许每天2000次网页浏览. 每天100张快照（最大容量：300张）.  3个快照热图，可以存储365天. 无限的团队成员.
   * [imprace.com](https://imprace.com/)  -着陆页分析，并提供提高跳出率的建议. 免费5个目标网页/域
   * [keen.io](https://keen.io/)  —用于数据收集，分析和可视化的自定义分析. 每月50,000个事件免费
   * [metrica.yandex.com](https://metrica.yandex.com/) -无限的免费分析
   * [mixpanel.com](https://mixpanel.com/) -每月有100,000个跟踪的用户，无限制的数据历史记录和席位，美国或欧盟的数据居住地
   * [Moesif](https://www.moesif.com)  — REST和GraphQL的API分析.  （每月最多免费提供500,000个API调用）
   * [Molasses](https://www.molasses.app)  -强大的功能标志和A / B测试. 释放多达3个环境，每个环境具有5个功能标志.
   * [optimizely.com](https://www.optimizely.com) — A / B测试解决方案，免费入门计划，1个网站，1个iOS和1个Android应用
   * [Microsoft PowerBI](https://powerbi.com)  — Microsoft的业务见解和分析. 免费计划仅提供100万个用户许可证，供有限使用.
   * [quantcast.com](https://www.quantcast.com/products/measure-audience-insights/) -无限的免费分析
   * [sematext.com](https://sematext.com/cloud/) —每月最多可进行5万次操作，1天数据保留，无限制的仪表板，用户等，免费.
   * [Similar Web](https://similarweb.com)  — Web和移动应用程序的分析. 免费计划按指标提供5个结果，1个月的移动应用数据和3个月的网站数据.
   * [StatCounter](https://statcounter.com/)  —网站查看器分析. 免费计划，可供500位最新访问者使用.
   * [Tableau Developer Program](https://www.tableau.com/developer)  —创新，创建Tableau，并使Tableau完全适合您的组织. 免费开发人员计划为Tableau Online提供了个人开发沙盒许可证. 该版本是最新的预发行版本，因此Data Devs可以测试此一流平台的每个功能.
   * [usabilityhub.com](https://usabilityhub.com/)  -在真实人物上测试设计和实体模型，跟踪访问者. 一位用户免费，无限制测试
   * [woopra.com](https://www.woopra.com/) —免费的用户分析平台，可进行50万次操作，90天的数据保留，30次以上的一键式集成.

## Visitor Session Recording

   * [Reactflow.com](https://www.reactflow.com/) —每个站点：每天1,000页浏览量，3个热图，3个小部件，免费的错误跟踪
   * [LogRocket.com](https://www.logrocket.com) -每月1,000次会话，保留30天，错误跟踪，实时模式
   * [FullStory.com](https://www.fullstory.com)  —每月1,000次会话，具有1个月的数据保留和3个用户席位. 更多信息 [here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition).
   * [hotjar.com](https://www.hotjar.com/) —每个站点：每天2,000页浏览量，3张热图，存储3个月的数据，...
   * [inspectlet.com](https://www.inspectlet.com/) — 1个网站每月免费提供100次会话
   * [livesession.io](https://livesession.io/) — 1个网站每月1,000次会话免费
   * [mouseflow.com](https://mouseflow.com/) — 1个网站每月免费提供100次会话
   * [mousestats.com](https://www.mousestats.com/) — 1个网站每月免费提供100次会话
   * [smartlook.com](https://www.smartlook.com/) —适用于Web和移动应用程序的免费软件包（每月1500个会话），3个热图，1个渠道，1个月的数据历史记录
   * [usersurge.com](https://www.usersurge.com/) —每月个人250K会话.
   * [howuku.com](https://howuku.com)  —跟踪用户的互动，参与和事件. 免费，每月最多访问5,000次

## International Mobile Number Verification API and SDK

  * [cognalys.com](https://cognalys.com/)  —与使用SMS网关相比，通过创新且可靠的方法来免费增值移动电话号码验证. 每天免费10次尝试和15次验证
  * [numverify.com](https://numverify.com/)  —全局电话号码验证和查找JSON API. 每月250个API请求
  * [veriphone.io](https://veriphone.io/)  —通过免费，快速，可靠的JSON API进行全球电话号码验证. 每月1000个请求

## Payment and Billing Integration

  * [CurrencyFreaks](https://currencyfreaks.com/)  —提供当前和历史货币汇率. 提供免费的DEVELOPER计划，每月提供1000个请求.
  * [currencyapi.net](https://currencyapi.net/)  —实物和加密货币的实时货币汇率，以JSON和XML表示. 免费套餐每月提供1,250个API请求.
  * [currencylayer.com](https://currencylayer.com/) —为您的企业提供可靠的汇率和货币换算，每月免费提供1,000个API请求
  * [currencystack.io](https://currencystack.io/) — 154种货币的生产就绪型实时汇率.
  * [exchangerate-api.com](https://www.exchangerate-api.com)  -易于使用的货币转换JSON API. 免费套餐，无请求限制.
  * [fraudlabspro.com](https://www.fraudlabspro.com)  —帮助商家防止付款欺诈和拒付. 每月提供500个查询的免费Micro Plan.
  * [mailpop.in](https://mailpop.in) -通过上下文信息充分利用您的Stripe通知.
  * [namiml.com](https://www.namiml.com/)  -完整的平台，可在iOS和Android上进行应用内购买和订阅，包括无代码付费专区，CRM和分析. 免费提供运行IAP业务的所有基本功能.
  * [revenuecat.com](https://www.revenuecat.com/)  —用于应用内购买和订阅（iOS和Android）的托管后端. 每月最多可获得$ 10,000的跟踪收入.
  * [vatlayer.com](https://vatlayer.com/) —即时增值税号验证和欧盟增值税税率API，每月免费100个API请求

## Docker Related

  * [canister.io](https://canister.io/) —为开发人员提供20个免费的私有存储库，为团队构建和存储Docker映像提供30个免费的私有存储库
  * [Container Registry Service](https://container-registry.com/)  -基于港口的集装箱管理解决方案. 免费套餐为私有存储库提供1 GB的存储空间.
  * [Docker Hub](https://hub.docker.com) —一个免费的私有存储库和无限的公共存储库，用于构建和存储Docker映像
  * [Play with Docker](https://labs.play-with-docker.com/) —一个简单，互动且有趣的游乐场，以学习Docker.
  * [quay.io](https://quay.io/) —使用无限的免费公共存储库构建和存储容器映像

## Vagrant Related

  * [app.vagrantup.com](https://app.vagrantup.com)  -HashiCorp无业游民云. 无家可归的盒子托管.
  * [vagrantbox.es](https://www.vagrantbox.es/) — An alternative public box index

## Dev Blogging Sites

  * [dev.to](https://dev.to/) -程序员共享思想并互相帮助的地方.
  * [hashnode.com](https://hashnode.com/) —面向开发人员的无忧博客软件！.
  * [medium.com](https://medium.com/) —变得更重要.

## Commenting Platforms
  * [Staticman](https://staticman.net/) -Staticman是一个Node.js应用程序，它接收用户生成的内容，并使用Pull Requests将其作为数据文件上传到GitHub和/或GitLab存储库.
  * [GraphComment](https://graphcomment.com/) -GraphComment是一个评论平台，可帮助您从网站的受众群体建立活跃的社区.
  * [Utterances](https://utteranc.es/)  -一个基于GitHub问题的轻量级注释小部件. 将GitHub问题用于博客评论，Wiki页面等！
  * [Disqus](https://disqus.com/) -Disqus是一个网络社区平台，网络上成千上万的站点都在使用它.


## Screenshot APIs

  * [24browser.com](https://www.24browser.com) –使用强大的API大规模捕获精美呈现的网站屏幕截图.
  * [ApiFlash](https://apiflash.com)  —基于Aws Lambda和Chrome的屏幕截图API. 处理整页，捕获时间，视口尺寸，...
  * [microlink.io](https://microlink.io/)  –它将任何网站转换为数据，例如元标记标准化，美容链接预览，抓取功能或屏幕截图即服务. 每天250请求/天，免费.
  * [ScreenshotAPI.net](https://screenshotapi.net/)  -屏幕截图API使用一个简单的API调用即可生成任何网站的屏幕截图. 构建规模并托管在Google Cloud上. 每月提供100张免费屏幕截图.
  * [screenshotlayer.com](https://screenshotlayer.com/)  —捕获任何网站的高度可定制的快照. 每月免费提供100张快照
  * [screenshotmachine.com](https://www.screenshotmachine.com/) —每月捕获100个快照，png，gif和jpg，包括全长捕获，而不仅仅是主页
  * [PhantomJsCloud](https://PhantomJsCloud.com)  —浏览器自动化和页面渲染. 免费套餐每天最多提供500页. 自2017年以来免费.
  * [Webshrinker.com](https://webshrinker.com)  — Web Shrinker提供网站截图和域智能API服务. 每月免费100个请求.

## Browser based hardware emulation written in Javascript

  * [JsLinux](https://bellard.org/jslinux) —能够运行Linux和Windows 2k的非常快速的x86虚拟机.
  * [Jor1k](http://s-macke.github.io/jor1k/demos/main.html) —能够运行具有网络支持的Linux的OpenRISC虚拟机.
  * [v86](https://copy.sh/v86) —能够直接在浏览器中运行Linux和其他操作系统的x86虚拟机.

## Miscellaneous

  * [Smartcar API](https://smartcar.com) -用于查找，获取油箱，电池电量，里程表，开锁/上锁车门等的API.
  * [Blynk](https://blynk.io)  —具有API的SaaS，用于控制，构建和评估IoT设备. 具有5台设备的免费开发人员计划，免费的云和数据存储. 移动应用程序也可用.
  * [Bricks Note Calculator](https://free.getbricks.app/) - a note-taking app (PWA) with a powerful built-in multiline calculator.
  * [Code Time](https://www.software.com/code-time) -扩展了VS Code，Atom，IntelliJ，Sublime Text等中的时间跟踪和编码指标.
  * [ConfigCat](https://configcat.com)  -跨平台功能标记服务. 适用于所有主要语言的SDK. 免费计划，每月最多10个标志，2个环境，1个产品和500万个请求. 无限的用户席位. 学生每月免费获得100面旗帜和1亿个请求.
  * [docsapp.io](https://www.docsapp.io/) —最简单的发布文档的方式，免费提供给开源
  * [Elementor](https://elementor.com)  — WordPress网站生成器.  40多个基本小工具可提供免费计划.
  * [Form2Channel](https://form2channel.com)  —在您的网站上放置静态html表单，并直接接收对Google表格，电子邮件，Slack，电报或Http的提交. 无需编码.
  * [FOSSA](https://fossa.com/) -可扩展的端到端管理，用于第三方代码，许可证合规性和漏洞.
  * [fullcontact.com](https://www.fullcontact.com/developer/pricing/)  —通过将社交资料添加到您的应用中，帮助您的用户更多地了解他们的联系人. 每月500次免费的人API匹配
  * [http2.pro](https://http2.pro) — HTTP / 2协议准备测试和客户端HTTP / 2支持检测API.
  * [JWT Decoder](https://jwt.ssotools.com/) —在线免费工具，用于解码JWT（JSON Web令牌）并验证其签名.
  * [Base64 decoder/encoder](https://devpal.xyz/base64-decode/) —用于解码和编码数据的在线免费工具.
  * [newreleases.io](https://newreleases.io/) -从GitHub，GitLab，Bitbucket，Python PyPI，Java Maven，Node.js NPM，Node.js Yarn，Ruby Gems，PHP Packagist，.NET NuGet， Rust Cargo和Docker Hub.
  * [PDFMonkey](https://www.pdfmonkey.io/)  —在仪表板中管理PDF模板，使用动态数据调用API，然后下载PDF. 每月提供1000个免费文档.
  * [readme.com](https://readme.com/) -精美的文档变得简单，免费提供给开源.
  * [redirection.io](https://redirection.io/) — SaaS工具，用于管理企业，市场营销和SEO的HTTP重定向.
  * [ReqBin](https://www.reqbin.com/)  —在线发布HTTP请求. 流行的请求方法包括GET，POST，PUT，DELETE和HEAD. 支持标题和令牌认证. 包括用于保存您的请求的基本登录系统.
  * [superfeedr.com](https://superfeedr.com/)  —实时兼容PubSubHubbub的提要，导出，分析. 免费，定制更少
  * [SurveyMonkey.com](https://www.surveymonkey.com)  —创建在线调查. 在线分析结果. 免费计划每次调查仅允许10个问题和100个答复.
  * [videoinu](https://videoinu.com) —在线创建和编辑屏幕录像和其他视频.
  * [RandomKeygen](https://randomkeygen.com/) -免费的移动友好型工具提供了各种随机生成的密钥和密码，可用于保护任何应用程序，服务或设备的安全.
  * [Cronhooks](https://cronhooks.io/)  -使用api和网络应用安排一次或重复性的网络挂钩. 免费计划允许1个webhook时间表.
  * [Hook Relay](https://www.hookrelay.dev/)  -为您的应用程序添加webhook支持，而无需麻烦：为您完成排队，带退避重试和日志记录. 免费计划每天有100笔交货，保留14天，还有3个挂钩端点.

## Other Free Resources

  * [education.github.com](https://education.github.com/pack)  —为学生提供免费服务. 需要注册
  * [Framacloud](https://degooglisons-internet.org/en/list/) —由法国非营利组织提供的免费/自由开源软件和SaaS列表 [Framasoft](https://framasoft.org/en/).
  * [getawesomeness](https://getawesomeness.herokuapp.com) —从GitHub检索所有令人惊叹的超赞功能……必看
  * [github.com — FOSS for Dev](https://github.com/tvvocold/FOSS-for-Dev) —供开发人员使用的免费和开源软件中心.
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program)  —获得为Microsoft 365平台构建解决方案所需的免费沙盒，工具和其他资源. 订阅为期90天 [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5) (Windows excluded) which is renewable. It is renewed if you're active in development(measured using telemetry data & algorithms).
  * [RedHat for Developers](https://developers.redhat.com)  —专为开发人员免费访问Red Hat产品，包括RHEL，OpenShift，CodeReady等. 仅个人计划. 还提供免费电子书供参考.
  * [smsreceivefree.com](https://smsreceivefree.com/) —提供免费的临时和一次性电话号码.
  * [simplebackups.io](https://simplebackups.io/)  —用于直接存储到云存储提供程序（AWS，DigitalOcean，Backblaze ...）中的服务器和数据库（MySQL，PostgreSQL，MongoDB）的备份自动化服务. 提供1个备份的免费计划.
  * [SnapShooter](https://snapshooter.io/)  —用于DigitalOcean，AWS，LightSail，Hetzner和Exoscale的备份解决方案，支持将数据库，文件系统和应用程序直接备份到基于s3的存储. 提供免费计划，其中包含一项资源的每日备份.
  * [Web.Dev](https://web.dev/measure/) —这是一个免费工具，可让您查看网站的性能并改进SEO，以在搜索引擎中获得更高的排名.
