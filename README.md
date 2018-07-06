# Sprint
第二十组（Group Undefined）产品待办列表，Sprint 待办列表。
* 产品（项目）名称: My Coin
* 项目负责人：毛凯

---
### product backlog

| PBI_ID | 优先级 | 功能性/非功能性 | Backlog类型 | 用户故事（产品Backlog条目描述）| 验收条件（满意条件）| Sprint | 状态 |
|-|-|-|-|-|-|-|-|
| PBI_01 | 60 | 功能性 | 新需求 | 作为用户，可以通过注册页面，输入自己邮箱，设置用户名，并设置一次密码，点击注册按钮，注册一个用于登录的账户 | 作为用户，打开 APP 注册页面，输入自己邮箱，设置用户名，并设置一次密码，点击注册按钮，预期结果显示「注册成功」并且直接进入首页---明细页面。作为用户，倘若输入先前已经被他人注册过的用户名，预期结果页面显示「改用户名已被占用，请更换用户名重新注册」| Sprint1 | - | 
| PBI_02 | 60 | 功能性 | 新需求 | 作为用户，可以通过登录页面，输入注册时设置的用户名和密码（登录不需要邮箱），登录该 APP | 作为用户，在登录页面输入注册时设置的用户名和密码，点击登录按钮，预期结果显示「登录成功」，并跳转到首页---明细页面 。作为用户，倘若输入错误的用户名或者密码，预期结果显示「您的用户名或者密码错误，请重新登录」| Sprint1 | - | 
| PBI_03 | 100 | 功能性 | 新需求 | 作为用户，登录之后进入首页---明细页面，设置当月预算，查看当月支出，查看报表，来了解截止到当月的消费情况 | 作为用户，登录之后进入首页---明细页面，点击左上角当月预算，预期结果进入当月预算，输入数字点击右上角确认图标，预期结果明细页面的当月预算被更新，显示刚刚用户输入的数字。作为用户在明细页面点击右上角报表，预期结果跳转到饼状图页面。作为用户在明细页面什么也不操作，预期结果默认显示最近三天的支出情况。 | Sprint1 | - | 
| PBI_04 | 95 | 功能性 | 新需求 | 作为用户，登录进入首页后，可以点击下方导航栏的记账按钮，记录当天的各个种类的支出 | 作为用户，登录后可以点击下方导航栏的记账按钮，选择消费种类，输入金额，点击右下角对勾，预期结果显示「记账成功」，首页明细页面同理被更新。作为用户，倘若没有选择消费种类直接输入金额，预期结果默认消费种类为第一项，即「饮食」 | Sprint1 | - | 
| PBI_05 | 95 | 功能性 | 新需求 | 作为用户，登录进入首页后，可以点击下方导航栏的记账按钮，进入记账页面，选择消费所属的六个种类（饮食，教育，娱乐，一般，出行，服装） | 作为用户，登录后点击下方导航栏的记账按钮，进入记账页面点击消费所属的六个种类（饮食，教育，娱乐，一般，出行，服装）其中之一，预期结果页面上左上角会显示刚刚用户选择的消费种类名称和其 icon。作为用户，没有选择消费种类，预期结果左上角显示六个消费种类的第一项，即「饮食」的名称和其 icon。 | Sprint1 | - | 
| PBI_06 | 70 | 功能性 | 新需求 | 作为用户，登录进入首页后，可以点击下方导航栏的个人中心，查看自己用户名，或者点击退出登录按钮来注销登录 | 作为用户，登录后点击下方导航栏的个人中心，预期结果可以查看到自己的用户名，点击退出登录按钮，预期结果显示「您已退出登录」，并且跳转到登录页面 | Sprint1 | - | 
| PBI_07 | 80 | 功能性 | 新需求 | 作为用户，登录进入首页后，点击首页明细页面右上方的报表icon，进入到消费报表页面里面的月末账单，页面显示饼状图，来查阅当月各种类型（六种）的消费的比例。饼状图下方有消费具体账额 | 作为用户，登录后点击首页明细页面右上方的报表和 icon，预期结果进入到消费报表页面里面的月末账单，页面显示彩色的饼状图，饼状图显示当月各种类型（六种）的消费的比例，饼状图下方有消费具体账额，例如「x月您已花费xx元，其中饮食花费最多，是xxx元……」| Sprint1 | - | 
| PBI_08 | 80 | 功能性 | 新需求 | 作为用户，登录进入首页后，点击首页明细页面右上方的报表icon，进入到消费报表页面里面的月末账单，点击屏幕左上方最近七天按钮，进入最近七天页面，页面显示曲线图，可以通过曲线图走向查看一周的消费总体情况。曲线图下方有文字，显示具体花费账额 | 作为用户，登录后点击首页明细页面右上方的报表和 icon，进入到消费报表页面里面的月末账单，点击屏幕左上方最近七天按钮，进入最近七天页面，预期结果页面显示曲线图，曲线图走向的依据为最近七天的花费金额，曲线图下方的文字显示具体花费账额，例如「最近七天您一共花费了x元，其中x月x日花费的最多……」 | Sprint1 | - | 
| PBI_09 | 20 | 非功能性 | 新需求 | 作为用户，需要填写用户名、密码、邮箱来注册，从邮箱接收验证码，通过验证后，才能注册成功。然而登录时候只需使用用户名和密码登录 | 作为用户，没有设置用户名或者密码以及邮箱，会被禁止注册。作为用户设置了邮箱之后点击发送验证码按钮，预期结果用户设置的邮箱会收到验证码，同时按钮会开始 60 秒的倒计时。作为用户，填写邮箱中收到的验证码，之后点击注册，预期结果页面显示「注册成功」，并跳转到首页---明细页面。作为用户，如果邮箱没有收到验证码或者验证码输入错误，预期结果用户需要等 60 秒倒计时结束后，点击发送验证码按钮，重新获取 | Sprint2 | - | 
| PBI_10 | 15 | 非功能性 | 新需求 | 作为用户，可以登录后进入个人中心，查看校园卡账单情况 | 作为用户，登录后点击下方导航栏个人中心，点击「我的校园卡账单」，预期结果跳转到校园卡账单页面，页面显示今日消费具体流水 | Sprint2 | - |
| PBI_11 | 10 | 非功能性 | 新需求 | 作为用户，想要保护自己的隐私（比如密码）| 后端运维，网络部分从 HTTP 改为 HTTPS，实现安全加密传输，保护用户隐私安全 | Sprint2 | - | 
| PBI_12 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_13 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_14 | - | 功能性 | 新需求 | - | - | - | - |
| PBI_15 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_16 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_17 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_18 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_19 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_20 | - | 功能性 | 新需求 | - | - | - | - | 
| PBI_21 | - | 功能性 | 新需求 | - | - | - | - | 





















