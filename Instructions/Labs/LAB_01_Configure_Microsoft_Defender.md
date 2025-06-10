---
lab:
  title: |-
    <group id="content" extype="content"><group id="paragraph-101"><trans-unit id="p101" translate="no" xml:space="preserve" restype="x-metadata">
              <source>配置 Microsoft Defender</source>
            </trans-unit><group id="sentence-101"><trans-unit id="101" translate="yes" xml:space="preserve" restype="x-metadata">
              <source>配置 Microsoft Defender</source>
            </trans-unit></group></group><group id="paragraph-102"><trans-unit id="p102" translate="no" xml:space="preserve">
              <source>你是一名安全运营分析师，所供职公司正在实现 Microsoft Defender XDR。</source>
            </trans-unit><group id="sentence-102"><trans-unit id="102" translate="yes" xml:space="preserve">
              <source>你是一名安全运营分析师，所供职公司正在实现 Microsoft Defender XDR。</source>
            </trans-unit></group></group><group id="paragraph-103"><trans-unit id="p103" translate="no" xml:space="preserve">
              <source>你的职责是负责指导公司的 IT 团队使用 Microsoft Defender (XDR) 抵御威胁。</source>
            </trans-unit><group id="sentence-103"><trans-unit id="103" translate="yes" xml:space="preserve">
              <source>你的职责是负责指导公司的 IT 团队使用 Microsoft Defender (XDR) 抵御威胁。</source>
            </trans-unit></group></group><group id="paragraph-104"><trans-unit id="p104" translate="no" xml:space="preserve">
              <source>公司的高管非常重视所有准则是否都得到遵守，并且在其环境中完成活动时是否满足所有要求。</source>
            </trans-unit><group id="sentence-104"><trans-unit id="104" translate="yes" xml:space="preserve">
              <source>公司的高管非常重视所有准则是否都得到遵守，并且在其环境中完成活动时是否满足所有要求。</source>
            </trans-unit></group></group><group id="paragraph-105"><trans-unit id="p105" translate="no" xml:space="preserve">
              <source>配置 Microsoft Defender XDR 环境</source>
            </trans-unit><group id="sentence-105"><trans-unit id="105" translate="yes" xml:space="preserve">
              <source>配置 Microsoft Defender XDR 环境</source>
            </trans-unit></group></group><group id="paragraph-106"><trans-unit id="p106" translate="no" xml:space="preserve">
              <source>在本练习中，你将预配 Microsoft Defender XDR 环境，在 Defender for Endpoint 中载入客户端工作站，并在客户端工作站上执行模拟攻击方案。</source>
            </trans-unit><group id="sentence-106"><trans-unit id="106" translate="yes" xml:space="preserve">
              <source>在本练习中，你将预配 Microsoft Defender XDR 环境，在 Defender for Endpoint 中载入客户端工作站，并在客户端工作站上执行模拟攻击方案。</source>
            </trans-unit></group></group><group id="paragraph-107"><trans-unit id="p107" translate="no" xml:space="preserve">
              <source>完成此练习大约需要 <bpt id="p1">**</bpt>10 - 15<ept id="p1">**</ept> 分钟。</source>
            </trans-unit><group id="sentence-107"><trans-unit id="107" translate="yes" xml:space="preserve">
              <source>完成此练习大约需要 <bpt id="p1">**</bpt>10 - 15<ept id="p1">**</ept> 分钟。</source>
            </trans-unit></group></group><group id="paragraph-108"><trans-unit id="p108" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>重要说明：<ept id="p1">**</ept>你需要有权访问具有 Microsoft Defender for Endpoint P2 许可证的 Microsoft 365 E5 租户才能执行以下练习。</source>
            </trans-unit><group id="sentence-108"><trans-unit id="108" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>重要说明：<ept id="p1">**</ept>你需要有权访问具有 Microsoft Defender for Endpoint P2 许可证的 Microsoft 365 E5 租户才能执行以下练习。</source>
            </trans-unit></group></group><group id="paragraph-109"><trans-unit id="p109" translate="no" xml:space="preserve">
              <source>还需要拥有 Microsoft Windows 10 或 11 客户端工作站以载入并执行模拟攻击。</source>
            </trans-unit><group id="sentence-109"><trans-unit id="109" translate="yes" xml:space="preserve">
              <source>还需要拥有 Microsoft Windows 10 或 11 客户端工作站以载入并执行模拟攻击。</source>
            </trans-unit></group></group><group id="paragraph-110"><trans-unit id="p110" translate="no" xml:space="preserve">
              <source>任务 1 - 准备 Microsoft Defender XDR 工作区</source>
            </trans-unit><group id="sentence-110"><trans-unit id="110" translate="yes" xml:space="preserve">
              <source>任务 1 - 准备 Microsoft Defender XDR 工作区</source>
            </trans-unit></group></group><group id="paragraph-111"><trans-unit id="p111" translate="no" xml:space="preserve">
              <source>在 Microsoft Edge 浏览器中，转到 Microsoft Defender 门户，网址为(<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>)。</source>
            </trans-unit><group id="sentence-111"><trans-unit id="111" translate="yes" xml:space="preserve">
              <source>在 Microsoft Edge 浏览器中，转到 Microsoft Defender 门户，网址为(<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>)。</source>
            </trans-unit></group></group><group id="paragraph-112"><trans-unit id="p112" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> 门户的导航菜单中，从左侧选择<bpt id="p2">**</bpt>“主页”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-112"><trans-unit id="112" translate="yes" xml:space="preserve">
              <source>在 <bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> 门户的导航菜单中，从左侧选择<bpt id="p2">**</bpt>“主页”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-113"><trans-unit id="p113" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>可能需要一直滚动到菜单顶部。</source>
            </trans-unit><group id="sentence-113"><trans-unit id="113" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>可能需要一直滚动到菜单顶部。</source>
            </trans-unit></group></group><group id="paragraph-114"><trans-unit id="p114" translate="no" xml:space="preserve">
              <source>将菜单项向下滚动到<bpt id="p1">**</bpt>“资源”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“设备”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-114"><trans-unit id="114" translate="yes" xml:space="preserve">
              <source>将菜单项向下滚动到<bpt id="p1">**</bpt>“资源”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“设备”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-115"><trans-unit id="p115" translate="no" xml:space="preserve">
              <source>部署 Defender XDR 工作区的过程应已启动，你应该会看到页面顶部短暂显示<bpt id="p1">*</bpt>正在加载和初始化<ept id="p1">*</ept>消息，然后将看到一个咖啡杯的图像和一条消息，内容为：<bpt id="p2">**</bpt>等等！我们正在为数据准备新空间并为其建立连接。<ept id="p2">**</ept></source>
            </trans-unit><group id="sentence-115"><trans-unit id="115" translate="yes" xml:space="preserve">
              <source>部署 Defender XDR 工作区的过程应已启动，你应该会看到页面顶部短暂显示<bpt id="p1">*</bpt>正在加载和初始化<ept id="p1">*</ept>消息，然后将看到一个咖啡杯的图像和一条消息，内容为：<bpt id="p2">**</bpt>等等！我们正在为数据准备新空间并为其建立连接。<ept id="p2">**</ept></source>
            </trans-unit></group></group><group id="paragraph-116"><trans-unit id="p116" translate="no" xml:space="preserve">
              <source>完成此操作大约需要 5 分钟。</source>
            </trans-unit><group id="sentence-116"><trans-unit id="116" translate="yes" xml:space="preserve">
              <source>完成此操作大约需要 5 分钟。</source>
            </trans-unit></group></group><group id="paragraph-117"><trans-unit id="p117" translate="no" xml:space="preserve">
              <source><bpt id="p1">*</bpt>保持页面打开并确保其完成，因为下一个实验室需要使用。<ept id="p1">*</ept></source>
            </trans-unit><group id="sentence-117"><trans-unit id="117" translate="yes" xml:space="preserve">
              <source><bpt id="p1">*</bpt>保持页面打开并确保其完成，因为下一个实验室需要使用。<ept id="p1">*</ept></source>
            </trans-unit></group></group><group id="paragraph-118"><trans-unit id="p118" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>忽略显示<bpt id="p2">*</bpt>某些数据无法检索的弹出错误消息<ept id="p2">*</ept>。</source>
            </trans-unit><group id="sentence-118"><trans-unit id="118" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>忽略显示<bpt id="p2">*</bpt>某些数据无法检索的弹出错误消息<ept id="p2">*</ept>。</source>
            </trans-unit></group></group><group id="paragraph-119"><trans-unit id="p119" translate="no" xml:space="preserve">
              <source>如果出现消息“等等！</source>
            </trans-unit><group id="sentence-119"><trans-unit id="119" translate="yes" xml:space="preserve">
              <source>如果出现消息“等等！</source>
            </trans-unit></group></group><group id="paragraph-120"><trans-unit id="p120" translate="no" xml:space="preserve">
              <source>我们正在为数据准备新空间并为其建立连接“未显示，或者”设置&gt; Microsoft Defender XDR &gt;帐户“页打开，但显示消息<bpt id="p1">*</bpt>无法加载数据存储位置。请稍后再试<ept id="p1">*</ept>，在“常规”菜单中选择“提醒服务设置”。</source>
            </trans-unit><group id="sentence-120"><trans-unit id="120" translate="yes" xml:space="preserve">
              <source>我们正在为数据准备新空间并为其建立连接“未显示，或者”设置&gt; Microsoft Defender XDR &gt;帐户“页打开，但显示消息 <bpt id="p1">*</bpt>无法加载数据存储位置。请稍后再试<ept id="p1">*</ept>，在“常规”菜单中选择“提醒服务设置”。</source>
            </trans-unit></group></group><group id="paragraph-121"><trans-unit id="p121" translate="no" xml:space="preserve">
              <source>新工作区初始化成功完成后，<bpt id="p1">**</bpt>主页<ept id="p1">**</ept>门户页面将显示<bpt id="p2">**</bpt>“将 SIEM 和 XDR 集中在一个位置”<ept id="p2">**</ept>横幅。</source>
            </trans-unit><group id="sentence-121"><trans-unit id="121" translate="yes" xml:space="preserve">
              <source>新工作区初始化成功完成后，<bpt id="p1">**</bpt>主页<ept id="p1">**</ept>门户页面将显示<bpt id="p2">**</bpt>“将 SIEM 和 XDR 集中在一个位置”<ept id="p2">**</ept>横幅。</source>
            </trans-unit></group></group><group id="paragraph-122"><trans-unit id="p122" translate="no" xml:space="preserve">
              <source>此外，在<bpt id="p1">**</bpt>“设置”<ept id="p1">**</ept>，Microsoft Defender XDR 的帐户、电子邮件通知、<bpt id="p2">**</bpt>预览功能的常规设置<ept id="p2">**</ept>、警报服务设置、权限和角色以及流式处理 API 现已开启。</source>
            </trans-unit><group id="sentence-122"><trans-unit id="122" translate="yes" xml:space="preserve">
              <source>此外，在<bpt id="p1">**</bpt>“设置”<ept id="p1">**</ept>中，Microsoft Defender XDR 的帐户、电子邮件通知、<bpt id="p2">**</bpt>预览功能的常规设置<ept id="p2">**</ept>、警报服务设置、权限和角色以及流式处理 API 现已开启。</source>
            </trans-unit></group></group><group id="paragraph-123"><trans-unit id="p123" translate="no" xml:space="preserve">
              <source>任务 2：应用 Microsoft Defender for Office 365 预设安全策略</source>
            </trans-unit><group id="sentence-123"><trans-unit id="123" translate="yes" xml:space="preserve">
              <source>任务 2：应用 Microsoft Defender for Office 365 预设安全策略</source>
            </trans-unit></group></group><group id="paragraph-124"><trans-unit id="p124" translate="no" xml:space="preserve">
              <source>在此任务中，你将在 Microsoft 365 安全门户为 Exchange Online Protection (EOP) 和 Microsoft Defender for Office 365 分配预设安全策略。</source>
            </trans-unit><group id="sentence-124"><trans-unit id="124" translate="yes" xml:space="preserve">
              <source>在此任务中，你将在 Microsoft 365 安全门户为 Exchange Online Protection (EOP) 和 Microsoft Defender for Office 365 分配预设安全策略。</source>
            </trans-unit></group></group><group id="paragraph-125"><trans-unit id="p125" translate="no" xml:space="preserve">
              <source>使用密码：<bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept>以管理员身份登录 WIN1 虚拟机。</source>
            </trans-unit><group id="sentence-125"><trans-unit id="125" translate="yes" xml:space="preserve">
              <source>使用密码：<bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept>以管理员身份登录 WIN1 虚拟机。</source>
            </trans-unit></group></group><group id="paragraph-126"><trans-unit id="p126" translate="no" xml:space="preserve">
              <source>启动 Microsoft Edge 浏览器。</source>
            </trans-unit><group id="sentence-126"><trans-unit id="126" translate="yes" xml:space="preserve">
              <source>启动 Microsoft Edge 浏览器。</source>
            </trans-unit></group></group><group id="paragraph-127"><trans-unit id="p127" translate="no" xml:space="preserve">
              <source>在 Microsoft Edge 浏览器中，转到 Microsoft Defender XDR 门户，网址为：(<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>)。</source>
            </trans-unit><group id="sentence-127"><trans-unit id="127" translate="yes" xml:space="preserve">
              <source>在 Microsoft Edge 浏览器中，转到 Microsoft Defender XDR 门户，网址为：(<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>)。</source>
            </trans-unit></group></group><group id="paragraph-128"><trans-unit id="p128" translate="no" xml:space="preserve">
              <source>。在<bpt id="p1">**</bpt>“登录”<ept id="p1">**</ept>对话框中，复制并粘贴租户电子邮件帐户中实验室托管服务提供商提供的管理员用户名，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-128"><trans-unit id="128" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>“登录”<ept id="p1">**</ept>对话框中，复制并粘贴租户电子邮件帐户中实验室托管服务提供商提供的管理员用户名，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-129"><trans-unit id="p129" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>“输入密码”<ept id="p1">**</ept>对话框中，复制并粘贴实验室托管服务提供商提供的管理员租户密码，然后选择<bpt id="p2">**</bpt>“登录”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-129"><trans-unit id="129" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>“输入密码”<ept id="p1">**</ept>对话框中，复制并粘贴实验室托管服务提供商提供的管理员租户密码，然后选择<bpt id="p2">**</bpt>“登录”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-130"><trans-unit id="p130" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息：“无法完成此操作。</source>
            </trans-unit><group id="sentence-130"><trans-unit id="130" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息：“无法完成此操作。</source>
            </trans-unit></group></group><group id="paragraph-131"><trans-unit id="p131" translate="no" xml:space="preserve">
              <source>请稍后重试。</source>
            </trans-unit><group id="sentence-131"><trans-unit id="131" translate="yes" xml:space="preserve">
              <source>请稍后重试。</source>
            </trans-unit></group></group><group id="paragraph-132"><trans-unit id="p132" translate="no" xml:space="preserve">
              <source>如果问题仍然存在，请联系 Microsoft 支持部门。”</source>
            </trans-unit><group id="sentence-132"><trans-unit id="132" translate="yes" xml:space="preserve">
              <source>如果问题仍然存在，请联系 Microsoft 支持部门。”</source>
            </trans-unit></group></group><group id="paragraph-133"><trans-unit id="p133" translate="no" xml:space="preserve">
              <source>只需单击<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>即可继续。</source>
            </trans-unit><group id="sentence-133"><trans-unit id="133" translate="yes" xml:space="preserve">
              <source>只需单击<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>即可继续。</source>
            </trans-unit></group></group><group id="paragraph-134"><trans-unit id="p134" translate="no" xml:space="preserve">
              <source>如果显示 Microsoft Defender XDR 快速教程弹出窗口，请将其关闭。</source>
            </trans-unit><group id="sentence-134"><trans-unit id="134" translate="yes" xml:space="preserve">
              <source>如果显示 Microsoft Defender XDR 快速教程弹出窗口，请将其关闭。</source>
            </trans-unit></group></group><group id="paragraph-135"><trans-unit id="p135" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>在本实验室的后面部分，需要等到 Defender 工作区预配完毕，可以利用这段时间浏览引导教程，了解有关 Microsoft Defender XDR 的详细信息。</source>
            </trans-unit><group id="sentence-135"><trans-unit id="135" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>在本实验室的后面部分，需要等到 Defender 工作区预配完毕，可以利用这段时间浏览引导教程，了解有关 Microsoft Defender XDR 的详细信息。</source>
            </trans-unit></group></group><group id="paragraph-136"><trans-unit id="p136" translate="no" xml:space="preserve">
              <source>在导航菜单的<bpt id="p1">*</bpt>“电子邮件&amp;协作”<ept id="p1">*</ept>区域下，选择<bpt id="p2">**</bpt>“策略&amp;规则”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-136"><trans-unit id="136" translate="yes" xml:space="preserve">
              <source>在导航菜单的<bpt id="p1">*</bpt>“电子邮件&amp;协作”<ept id="p1">*</ept>区域下，选择<bpt id="p2">**</bpt>“策略&amp;规则”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-137"><trans-unit id="p137" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略&amp;规则”<ept id="p1">*</ept>仪表板上，选择<bpt id="p2">**</bpt>“威胁策略”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-137"><trans-unit id="137" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略&amp;规则”<ept id="p1">*</ept>仪表板上，选择<bpt id="p2">**</bpt>“威胁策略”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-138"><trans-unit id="p138" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“威胁策略”<ept id="p1">*</ept>仪表板上，选择<bpt id="p2">**</bpt>“预设安全策略”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-138"><trans-unit id="138" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“威胁策略”<ept id="p1">*</ept>仪表板上，选择<bpt id="p2">**</bpt>“预设安全策略”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-139"><trans-unit id="p139" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“客户端错误 – 获取 bip 规则时出错”<ept id="p2">*</ept>，选择<bpt id="p3">**</bpt>确定<ept id="p3">**</ept>以继续。</source>
            </trans-unit><group id="sentence-139"><trans-unit id="139" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“客户端错误 – 获取 bip 规则时出错”<ept id="p2">*</ept>选择<bpt id="p3">**</bpt>确定<ept id="p3">**</ept>以继续。</source>
            </trans-unit></group></group><group id="paragraph-140"><trans-unit id="p140" translate="no" xml:space="preserve">
              <source>该错误是由于 Office 365 中租户的冻结状态默认未启用造成的。</source>
            </trans-unit><group id="sentence-140"><trans-unit id="140" translate="yes" xml:space="preserve">
              <source>该错误是由于 Office 365 中租户的冻结状态默认未启用造成的。</source>
            </trans-unit></group></group><group id="paragraph-141"><trans-unit id="p141" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“客户端错误 - 检索预设安全策略时出错。请稍后再试。”<ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-141"><trans-unit id="141" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“客户端错误 - 检索预设安全策略时出错。请稍后再试。”<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-142"><trans-unit id="p142" translate="no" xml:space="preserve">
              <source>选择<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>以继续。</source>
            </trans-unit><group id="sentence-142"><trans-unit id="142" translate="yes" xml:space="preserve">
              <source>选择<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>以继续。</source>
            </trans-unit></group></group><group id="paragraph-143"><trans-unit id="p143" translate="no" xml:space="preserve">
              <source>使用 <bpt id="p1">**</bpt>Ctrl + F5<ept id="p1">**</ept>。</source>
            </trans-unit> 刷新浏览器<group id="sentence-143"><trans-unit id="143" translate="yes" xml:space="preserve">
              <source>使用 <bpt id="p1">**</bpt>Ctrl+F5<ept id="p1">**</ept> 刷新浏览器。</source>
            </trans-unit></group></group><group id="paragraph-144"><trans-unit id="p144" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>了解预设安全策略<ept id="p1">**</ept><bpt id="p2">*</bpt>弹出<ept id="p2">*</ept>页上，选择<bpt id="p3">**</bpt>“关闭”<ept id="p3">**</ept>。</source>
            </trans-unit><group id="sentence-144"><trans-unit id="144" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">**</bpt>“了解预设安全策略”<ept id="p1">**</ept><bpt id="p2">*</bpt>弹出<ept id="p2">*</ept>页上，选择<bpt id="p3">**</bpt>“关闭”<ept id="p3">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-145"><trans-unit id="p145" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“标准保护措施”<ept id="p1">*</ept>下，选择<bpt id="p2">**</bpt>“管理保护设置”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-145"><trans-unit id="145" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“标准保护措施”<ept id="p1">*</ept>下，选择<bpt id="p2">**</bpt>“管理保护设置”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-146"><trans-unit id="p146" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>如果看到此选项灰显，请使用 <bpt id="p2">**</bpt>Ctrl+F5<ept id="p2">**</ept> 刷新浏览器。</source>
            </trans-unit><group id="sentence-146"><trans-unit id="146" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>如果看到此选项灰显，请使用 <bpt id="p2">**</bpt>Ctrl+F5<ept id="p2">**</ept>刷新浏览器。</source>
            </trans-unit></group></group><group id="paragraph-147"><trans-unit id="p147" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Exchange Online 保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“特定接收人”<ept id="p2">**</ept>，然后在<bpt id="p3">**</bpt>“域”<ept id="p3">**</ept>下开始写入租户的域名，将其选中，然后选择<bpt id="p4">**</bpt>“下一步”<ept id="p4">**</ept>。</source>
            </trans-unit><group id="sentence-147"><trans-unit id="147" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Exchange Online 保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“特定接收人”<ept id="p2">**</ept>，然后在<bpt id="p3">**</bpt>“域”<ept id="p3">**</ept>下开始写入租户的域名，将其选中，然后选择<bpt id="p4">**</bpt>“下一步”<ept id="p4">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-148"><trans-unit id="p148" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>租户的域名与为管理员帐户设置的域名相同，可能类似于 <bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept>。</source>
            </trans-unit><group id="sentence-148"><trans-unit id="148" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept>租户的域名与为管理员帐户设置的域名相同，可能类似于 <bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept>。</source>
            </trans-unit></group></group><group id="paragraph-149"><trans-unit id="p149" translate="no" xml:space="preserve">
              <source>请注意，此配置将应用针对反垃圾邮件、出站垃圾邮件筛选器、防恶意软件、防网络钓鱼的策略。</source>
            </trans-unit><group id="sentence-149"><trans-unit id="149" translate="yes" xml:space="preserve">
              <source>请注意，此配置将应用针对反垃圾邮件、出站垃圾邮件筛选器、防恶意软件、防网络钓鱼的策略。</source>
            </trans-unit></group></group><group id="paragraph-150"><trans-unit id="p150" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Defender for Office 365 保护”<ept id="p1">*</ept>部分，应用与上一步相同的配置，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-150"><trans-unit id="150" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Defender for Office 365 保护”<ept id="p1">*</ept>部分，应用与上一步相同的配置，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-151"><trans-unit id="p151" translate="no" xml:space="preserve">
              <source>请注意，此配置应用针对防网络钓鱼、安全附件、安全链接的策略。</source>
            </trans-unit><group id="sentence-151"><trans-unit id="151" translate="yes" xml:space="preserve">
              <source>请注意，此配置应用针对防网络钓鱼、安全附件、安全链接的策略。</source>
            </trans-unit></group></group><group id="paragraph-152"><trans-unit id="p152" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“模拟保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>四次以继续。</source>
            </trans-unit><group id="sentence-152"><trans-unit id="152" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“模拟保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>四次以继续。</source>
            </trans-unit></group></group><group id="paragraph-153"><trans-unit id="p153" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略模式”<ept id="p1">*</ept>部分，确保<bpt id="p2">**</bpt>“完成后开启策略”<ept id="p2">**</ept>单选按钮已选中，然后选择<bpt id="p3">**</bpt>“下一步”<ept id="p3">**</ept>。</source>
            </trans-unit><group id="sentence-153"><trans-unit id="153" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略模式”<ept id="p1">*</ept>部分，确保<bpt id="p2">**</bpt>“完成后开启策略”<ept id="p2">**</ept>单选按钮已选中，然后选择<bpt id="p3">**</bpt>“下一步”<ept id="p3">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-154"><trans-unit id="p154" translate="no" xml:space="preserve">
              <source>阅读<bpt id="p1">*</bpt>查看并确认更改<ept id="p1">*</ept>下的内容 ，并选择<bpt id="p2">**</bpt>“确认”<ept id="p2">**</ept>应用更改，然后选择<bpt id="p3">**</bpt>“完成”<ept id="p3">**</ept>以完成操作。</source>
            </trans-unit><group id="sentence-154"><trans-unit id="154" translate="yes" xml:space="preserve">
              <source>阅读<bpt id="p1">*</bpt>查看并确认更改<ept id="p1">*</ept>下的内容 ，并选择<bpt id="p2">**</bpt>“确认”<ept id="p2">**</ept>应用更改，然后选择<bpt id="p3">**</bpt>“完成”<ept id="p3">**</ept>以完成操作。</source>
            </trans-unit></group></group><group id="paragraph-155"><trans-unit id="p155" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' 对 PUT 操作无效。URI 必须指向 PUT 操作的单个资源。”<ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-155"><trans-unit id="155" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>'对 PUT 操作无效。URI 必须指向 PUT 操作的单个资源。”<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-156"><trans-unit id="p156" translate="no" xml:space="preserve">
              <source>只需选择<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“取消”<ept id="p2">**</ept>返回主页。</source>
            </trans-unit><group id="sentence-156"><trans-unit id="156" translate="yes" xml:space="preserve">
              <source>j只需选择<bpt id="p1">**</bpt>“确定”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“取消”<ept id="p2">**</ept>返回主页。</source>
            </trans-unit></group></group><group id="paragraph-157"><trans-unit id="p157" translate="no" xml:space="preserve">
              <source>你将看到<bpt id="p1">*</bpt>“标准保护已开启”<ept id="p1">*</ept>选项已启用。</source>
            </trans-unit><group id="sentence-157"><trans-unit id="157" translate="yes" xml:space="preserve">
              <source>>你将看到<bpt id="p1">*</bpt>“标准保护已开启”<ept id="p1">*</ept>>选项已启用。</source>
            </trans-unit></group></group><group id="paragraph-158"><trans-unit id="p158" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“严格保护”<ept id="p1">*</ept>下，选择<bpt id="p2">**</bpt>“管理保护设置”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-158"><trans-unit id="158" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“严格保护”<ept id="p1">*</ept>下，选择<bpt id="p2">**</bpt>“管理保护设置”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-159"><trans-unit id="p159" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept><bpt id="p2">*</bpt>严格保护<ept id="p2">*</ept>位于“电子邮件&amp;协作 - 策略&amp;规则 - 威胁策略 - 预设安全策略”下。</source>
            </trans-unit><group id="sentence-159"><trans-unit id="159" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>提示：<ept id="p1">**</ept><bpt id="p2">*</bpt>严格保护<ept id="p2">*</ept>位于“电子邮件&amp;协作 - 策略&amp;规则 - 威胁策略 - 预设安全策略”下。</source>
            </trans-unit></group></group><group id="paragraph-160"><trans-unit id="p160" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Exchange Online 保护”<ept id="p1">*</ept>中，选择<bpt id="p2">**</bpt>“特定接收人”<ept id="p2">**</ept>，然后在<bpt id="p3">**</bpt>“组”<ept id="p3">**</ept>下，开始写入<bpt id="p4">**</bpt>“领导层”<ept id="p4">**</ept>，将其选中，然后选择<bpt id="p5">**</bpt>“下一步”<ept id="p5">**</ept>。</source>
            </trans-unit><group id="sentence-160"><trans-unit id="160" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Exchange Online 保护”<ept id="p1">*</ept>中，选择<bpt id="p2">**</bpt>“特定接收人”<ept id="p2">**</ept>，然后在<bpt id="p3">**</bpt>“组”<ept id="p3">**</ept>下，开始写入<bpt id="p4">**</bpt>“领导层”<ept id="p4">**</ept>，将其选中，然后选择<bpt id="p5">**</bpt>“下一步”<ept id="p5">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-161"><trans-unit id="p161" translate="no" xml:space="preserve">
              <source>请注意，此配置将应用针对反垃圾邮件、出站垃圾邮件筛选器、防恶意软件、防网络钓鱼的策略。</source>
            </trans-unit><group id="sentence-161"><trans-unit id="161" translate="yes" xml:space="preserve">
              <source>请注意，此配置将应用针对反垃圾邮件、出站垃圾邮件筛选器、防恶意软件、防网络钓鱼的策略。</source>
            </trans-unit></group></group><group id="paragraph-162"><trans-unit id="p162" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Defender for Office 365 保护”<ept id="p1">*</ept>部分，应用与上一步相同的配置，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit><group id="sentence-162"><trans-unit id="162" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“应用 Defender for Office 365 保护”<ept id="p1">*</ept>部分，应用与上一步相同的配置，然后选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-163"><trans-unit id="p163" translate="no" xml:space="preserve">
              <source>请注意，此配置应用针对防网络钓鱼、安全附件、安全链接的策略。</source>
            </trans-unit><group id="sentence-163"><trans-unit id="163" translate="yes" xml:space="preserve">
              <source>请注意，此配置应用针对防网络钓鱼、安全附件、安全链接的策略。</source>
            </trans-unit></group></group><group id="paragraph-164"><trans-unit id="p164" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“模拟保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>四次以继续。</source>
            </trans-unit><group id="sentence-164"><trans-unit id="164" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“模拟保护”<ept id="p1">*</ept>部分，选择<bpt id="p2">**</bpt>“下一步”<ept id="p2">**</ept>四次以继续。</source>
            </trans-unit></group></group><group id="paragraph-165"><trans-unit id="p165" translate="no" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略模式”<ept id="p1">*</ept>部分，确保<bpt id="p2">**</bpt>“完成后开启策略”<ept id="p2">**</ept>单选按钮已选中，然后选择<bpt id="p3">**</bpt>“下一步”<ept id="p3">**</ept>。</source>
            </trans-unit><group id="sentence-165"><trans-unit id="165" translate="yes" xml:space="preserve">
              <source>在<bpt id="p1">*</bpt>“策略模式”<ept id="p1">*</ept>部分，确保<bpt id="p2">**</bpt>“完成后开启策略”<ept id="p2">**</ept>单选按钮已选中，然后选择<bpt id="p3">**</bpt>“下一步”<ept id="p3">**</ept>。</source>
            </trans-unit></group></group><group id="paragraph-166"><trans-unit id="p166" translate="no" xml:space="preserve">
              <source>阅读<bpt id="p1">*</bpt>“查看并确认更改”<ept id="p1">*</ept>下的内容，然后选择<bpt id="p2">**</bpt>“确认”<ept id="p2">**</ept>以应用更改，然后选择<bpt id="p3">**</bpt>“完成”<ept id="p3">**</ept>以完成操作。</source>
            </trans-unit><group id="sentence-166"><trans-unit id="166" translate="yes" xml:space="preserve">
              <source>阅读<bpt id="p1">*</bpt>“查看并确认更改”<ept id="p1">*</ept>下的内容，然后选择<bpt id="p2">**</bpt>“确认”<ept id="p2">**</ept>以应用更改，然后选择<bpt id="p3">**</bpt>“完成”<ept id="p3">**</ept>以完成操作。</source>
            </trans-unit></group></group><group id="paragraph-167"><trans-unit id="p167" translate="no" xml:space="preserve">
              <source><bpt id="p1">**</bpt>备注：<ept id="p1">**</ept> 如果收到消息 <bpt id="p2">*</bpt>“URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' 对 PUT 操作无效。URI 必须指向 PUT 操作的单个资源。”<ept id="p2">*</ept></source>
            </trans-unit><group id="sentence-167"><trans-unit id="167" translate="yes" xml:space="preserve">
              <source><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept>如果收到消息<bpt id="p2">*</bpt>“URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>'对 PUT 操作无效。URI 必须指向 PUT 操作的单个资源。”<ept id="p2">*</ept></source>
            </trans-unit></group></group><group id="paragraph-168"><trans-unit id="p168" translate="no" xml:space="preserve">
              <source>只需选择<bpt id="p1">**</bpt>“确认”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“取消”<ept id="p2">**</ept>以返回主页。</source>
            </trans-unit><group id="sentence-168"><trans-unit id="168" translate="yes" xml:space="preserve">
              <source>只需选择<bpt id="p1">**</bpt>“确认”<ept id="p1">**</ept>然后选择<bpt id="p2">**</bpt>“取消”<ept id="p2">**</ept>以返回主页。</source>
            </trans-unit></group></group><group id="paragraph-169"><trans-unit id="p169" translate="no" xml:space="preserve">
              <source>你将看到<bpt id="p1">*</bpt>“严格保护已开启”<ept id="p1">*</ept>选项已启用。</source>
            </trans-unit><group id="sentence-169"><trans-unit id="169" translate="yes" xml:space="preserve">
              <source>你将看到<bpt id="p1">*</bpt>“严格保护已开启<ept id="p1">*</ept>选项已启用。</source>
            </trans-unit></group></group><group id="paragraph-170"><trans-unit id="p170" translate="no" xml:space="preserve">
              <source>你已完成实验室</source>
            </trans-unit><group id="sentence-170"><trans-unit id="170" translate="yes" xml:space="preserve">
              <source>你已完成实验室</source>
            </trans-unit></group></group></group>
  module: Configure the Microsoft Defender XDR environment
---
You're a Security Operations Analyst working at a company that is implementing Microsoft Defender XDR. Your role is to guide the company’s IT team in defending against threats with Microsoft Defender (XDR). The company’s executives are very concerned that all guidelines are followed and that all requirements are met when you complete the activities in their environment.

# Configure the Microsoft Defender XDR environment

In this exercise you will provision your Microsoft Defender XDR environment, onboard client workstations in Defender for Endpoint and perform a simulated attack scenario on a client workstation.

This exercise should take approximately <bpt id="p1">**</bpt>10 - 15<ept id="p1">**</ept> minutes to complete.

><bpt id="p1">**</bpt>Important:<ept id="p1">**</ept> You'll need to have access to a Microsoft 365 E5 Tenant with a Microsoft Defender for Endpoint P2 license to perform the following exercises. You will also need to have Microsoft Windows 10 or 11 client workstations to onboard and perform simulated attacks on.

## Task 1- Preparing the Microsoft Defender XDR workspace

1. In the Microsoft Edge browser, go to the Microsoft Defender portal at (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>).
1. On the <bpt id="p1">**</bpt>Microsoft Defender<ept id="p1">**</ept> portal, from the navigation menu, select <bpt id="p2">**</bpt>Home<ept id="p2">**</ept> from the left.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> You may need to scroll all the way to the menu top.

1. Scroll down the menu items to <bpt id="p1">**</bpt>Assets<ept id="p1">**</ept> and select <bpt id="p2">**</bpt>Devices<ept id="p2">**</ept>.

1. The process to deploy the Defender XDR workspace should start and you should see messages saying <bpt id="p1">*</bpt>loading and Initializing<ept id="p1">*</ept> briefly displayed at the top of the page, and then you're going to see an image of a coffee mug and a message that reads: <bpt id="p2">**</bpt>Hang on! We're preparing new spaces for your data and connecting them.<ept id="p2">**</ept> It takes approximately 5 minutes to finish. <bpt id="p1">*</bpt>Leave the page open and make sure it finishes since it's required for the next Lab.<ept id="p1">*</ept>

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> Disregard pop-up error messages saying <bpt id="p2">*</bpt>Some of your data cannot be retrieved<ept id="p2">*</ept>. If the message "Hang on! We're preparing new spaces for your data and connecting them" does not appear, or the "Settings &gt; Microsoft Defender XDR &gt; Account" page opens, but you see the message <bpt id="p1">*</bpt>Failed to load data storage location. Please try again later<ept id="p1">*</ept>, select "Alert service settings" from the "General" menu.

1. When the new workspace initialization completes successfully, the <bpt id="p1">**</bpt>Home<ept id="p1">**</ept> portal page will display a <bpt id="p2">**</bpt>Get your SIEM and XDR in one place<ept id="p2">**</ept> banner. And, in <bpt id="p1">**</bpt>Settings<ept id="p1">**</ept>, the Microsoft Defender XDR General settings for Account, Email notifications, <bpt id="p2">**</bpt>Preview Features<ept id="p2">**</ept>, Alert service settings, Permissions and roles and Streaming API are now turned on.

### Task 2: Apply Microsoft Defender for Office 365 preset security policies

In this task, you'll assign preset security policies for Exchange Online Protection (EOP) and Microsoft Defender for Office 365 in the Microsoft 365 security portal.

1. Log in to WIN1 virtual machine as Admin with the password: <bpt id="p1">**</bpt>Pa55w.rd<ept id="p1">**</ept>.  

1. Start the Microsoft Edge browser.

1. In the Microsoft Edge browser, go to the Microsoft Defender XDR portal at (<ph id="ph1">&lt;https://security.microsoft.com&gt;</ph>).

1. In the <bpt id="p1">**</bpt>Sign in<ept id="p1">**</ept> dialog box, copy, and paste in the tenant Email account for the admin username provided by your lab hosting provider and then select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>.

1. In the <bpt id="p1">**</bpt>Enter password<ept id="p1">**</ept> dialog box, copy, and paste in the admin's tenant password provided by your lab hosting provider and then select <bpt id="p2">**</bpt>Sign in<ept id="p2">**</ept>.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive a message "The operation could not be completed. Please try again later. If the problem persists, contact Microsoft support." just click <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> to continue.  

1. If shown, close the Microsoft Defender XDR quick tour pop-up window. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> Later in this lab, you'll need to wait until the Defender workspace is provisioned, you can take this time to navigate through the guided tours to learn more about Microsoft Defender XDR.

1. From the navigation menu, under <bpt id="p1">*</bpt>Email &amp; Collaboration<ept id="p1">*</ept> area, select <bpt id="p2">**</bpt>Policies &amp; rules<ept id="p2">**</ept>.

1. On the <bpt id="p1">*</bpt>Policy &amp; rules<ept id="p1">*</ept> dashboard, select <bpt id="p2">**</bpt>Threat policies<ept id="p2">**</ept>.

1. On the <bpt id="p1">*</bpt>Threat policies<ept id="p1">*</ept> dashboard, select <bpt id="p2">**</bpt>Preset Security Policies<ept id="p2">**</ept>.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"Client Error - Error when getting bip rule"<ept id="p2">*</ept> select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept> to continue. The error is due to the hydration status of your tenant at Office 365 which is not enabled by default.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"Client Error - An error occurred when retrieving preset security policies. Please try again later."<ept id="p2">*</ept> select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> to continue. Refresh your browser using <bpt id="p1">**</bpt>Ctrl+F5<ept id="p1">**</ept>.

1. On the <bpt id="p1">**</bpt>Learn about preset security policies<ept id="p1">**</ept> <bpt id="p2">*</bpt>pop-out<ept id="p2">*</ept> page, select <bpt id="p3">**</bpt>Close<ept id="p3">**</ept>.

1. Under <bpt id="p1">*</bpt>Standard protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Manage protection settings<ept id="p2">**</ept>. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> If you see this option grayed out, refresh your browser using <bpt id="p2">**</bpt>Ctrl+F5<ept id="p2">**</ept>.

1. In the <bpt id="p1">*</bpt>Apply Exchange Online Protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Specific recipients<ept id="p2">**</ept> and under <bpt id="p3">**</bpt>Domains<ept id="p3">**</ept> start writing your tenant's domain name, select it, and then select <bpt id="p4">**</bpt>Next<ept id="p4">**</ept>.

    ><bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> Your tenant's domain name is the same name that you have for your admin account, it might be something like <bpt id="p2">*</bpt>WWLx######.onmicrosoft.com<ept id="p2">*</ept>. Notice that this configuration applies policies for anti-spam, outbound spam filter, anti-malware, anti-phishing.

1. In the <bpt id="p1">*</bpt>Apply Defender for Office 365 protection<ept id="p1">*</ept> section, apply the same configuration as the previous step and select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>. Notice that this configuration applies policies for anti-phishing, Safe Attachments, Safe Links.

1. In the <bpt id="p1">*</bpt>Impersonation protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept> four times (4x) to continue.

1. In the <bpt id="p1">*</bpt>Policy mode<ept id="p1">*</ept> section, make sure the <bpt id="p2">**</bpt>Turn on the policy when finished<ept id="p2">**</ept> radio button is selected, and then select <bpt id="p3">**</bpt>Next<ept id="p3">**</ept>.

1. Read the content under <bpt id="p1">*</bpt>Review and confirm your changes<ept id="p1">*</ept> and select <bpt id="p2">**</bpt>Confirm<ept id="p2">**</ept> to apply the changes and then select <bpt id="p3">**</bpt>Done<ept id="p3">**</ept> to finish.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"The URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' is not valid for PUT operation. The URI must point to a single resource for PUT operations."<ept id="p2">*</ept> just select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> and then select <bpt id="p2">**</bpt>Cancel<ept id="p2">**</ept> to return to the main page. You will see that <bpt id="p1">*</bpt>Standard protection is on<ept id="p1">*</ept> option enabled.

1. Under <bpt id="p1">*</bpt>Strict protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Manage protection settings<ept id="p2">**</ept>. <bpt id="p1">**</bpt>Hint:<ept id="p1">**</ept> <bpt id="p2">*</bpt>Strict protection<ept id="p2">*</ept> is found under "Email &amp; Collaboration - Policies &amp; rules - Threat policies - Preset security policies".

1. In the <bpt id="p1">*</bpt>Apply Exchange Online Protection<ept id="p1">*</ept>, select <bpt id="p2">**</bpt>Specific recipients<ept id="p2">**</ept> and under <bpt id="p3">**</bpt>Groups<ept id="p3">**</ept> start writing <bpt id="p4">**</bpt>Leadership<ept id="p4">**</ept>, select it, and then select <bpt id="p5">**</bpt>Next<ept id="p5">**</ept>. Notice that this configuration applies policies for anti-spam, outbound spam filter, anti-malware, anti-phishing.

1. In the <bpt id="p1">*</bpt>Apply Defender for Office 365 protection<ept id="p1">*</ept> section, apply the same configuration as the previous step and select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept>. Notice that this configuration applies policies for anti-phishing, Safe Attachments, Safe Links.

1. In the <bpt id="p1">*</bpt>Impersonation protection<ept id="p1">*</ept> section, select <bpt id="p2">**</bpt>Next<ept id="p2">**</ept> four times (4x) to continue.

1. In the <bpt id="p1">*</bpt>Policy mode<ept id="p1">*</ept> section, make sure the <bpt id="p2">**</bpt>Turn on the policy when finished<ept id="p2">**</ept> radio button is selected, and then select <bpt id="p3">**</bpt>Next<ept id="p3">**</ept>.

1. Read the content under <bpt id="p1">*</bpt>Review and confirm your changes<ept id="p1">*</ept> and select <bpt id="p2">**</bpt>Confirm<ept id="p2">**</ept> to apply the changes and then select <bpt id="p3">**</bpt>Done<ept id="p3">**</ept> to finish.

    ><bpt id="p1">**</bpt>Note:<ept id="p1">**</ept> If you receive the message <bpt id="p2">*</bpt>"The URI '<ph id="ph1">&lt;https://outlook.office365.com/psws/service.svc/AntiPhishPolicy&gt;</ph>' is not valid for PUT operation. The URI must point to a single resource for PUT operations."<ept id="p2">*</ept> just select <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> and then select <bpt id="p2">**</bpt>Cancel<ept id="p2">**</ept> to return to the main page. You will see the <bpt id="p1">*</bpt>Strict protection is on<ept id="p1">*</ept> option enabled.

## You have completed the lab
