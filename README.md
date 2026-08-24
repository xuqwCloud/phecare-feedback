# PheCare Feedback

<div align="center">
  <img src="./assets/app-icon.png" width="128" alt="PheCare App 图标" />
  <br />
  <strong>简体中文</strong> | <a href="./README_EN.md">English</a>
</div>

> PheCare 用户支持、隐私政策、功能建议与 Bug 反馈仓库

PheCare 是一款面向 PKU 宝宝家长与照护者的 iPhone 饮食和健康记录工具。它帮助用户记录每日食物、特殊配方、血 Phe 检验结果及成长数据，并在设备本地完成换算和趋势整理。

本仓库**不包含 PheCare 源代码**，主要用于：

- 查看 PheCare 的产品介绍与隐私政策
- 反馈崩溃、数据显示异常或兼容性问题
- 提交功能建议和交互体验意见
- 查询已知问题及后续改进计划

> **重要说明**
>
> PheCare 是家庭记录与信息整理工具，不提供医学诊断、治疗方案或特殊配方用量建议。饮食目标、血值目标及治疗调整应以医生或专业营养师的个体化意见为准。

## 主要功能

- **每日饮食记录**：按餐次记录食物重量并汇总 Phe 摄入
- **特殊配方记录**：记录每次饮用克数和时间，支持历史补记、编辑与删除
- **食物资料库**：提供本土常用食物、用户自定义食品及可按需查询的 USDA 扩展数据
- **血值记录**：保存 Phe、Tyr、Phe/Tyr 比值、检测日期和备注
- **成长记录**：记录体重、身高等数据并查看变化趋势
- **离线数据管理**：支持本地数据全量导出、导入、食物分享包和恢复初始状态

## 产品界面

<table>
  <tr>
    <td align="center" valign="top" width="50%">
      <strong>轻松开始</strong><br />
      <sub>三步完成宝宝档案与饮食目标设置</sub><br /><br />
      <img src="./assets/onboarding.png" alt="PheCare 引导页" width="92%" />
    </td>
    <td align="center" valign="top" width="50%">
      <strong>今天</strong><br />
      <sub>集中查看每日 Phe、特殊配方与餐次记录</sub><br /><br />
      <img src="./assets/today.png" alt="PheCare 今日饮食记录" width="92%" />
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <strong>食物库</strong><br />
      <sub>搜索本土数据、自定义食品与扩展资料</sub><br /><br />
      <img src="./assets/food-library.png" alt="PheCare 食物库" width="92%" />
    </td>
    <td align="center" valign="top" width="50%">
      <strong>饮食历史</strong><br />
      <sub>按日回顾摄入趋势和特殊配方记录</sub><br /><br />
      <img src="./assets/diet-history.png" alt="PheCare 饮食历史" width="92%" />
    </td>
  </tr>
  <tr>
    <td align="center" valign="top" width="50%">
      <strong>血值记录</strong><br />
      <sub>整理 Phe、Tyr、比值与历次检验结果</sub><br /><br />
      <img src="./assets/blood-records.png" alt="PheCare 血值记录" width="92%" />
    </td>
    <td align="center" valign="top" width="50%">
      <strong>宝宝档案</strong><br />
      <sub>管理成长资料、饮食目标与离线数据</sub><br /><br />
      <img src="./assets/baby-profile.png" alt="PheCare 宝宝档案与数据管理" width="92%" />
    </td>
  </tr>
</table>

## 数据与隐私

PheCare 当前版本不要求注册账号，不接入广告、用户追踪或第三方分析服务，也不会把宝宝档案、饮食记录、血值或成长数据自动发送给开发者。

所有主要数据均保存在用户设备本地。数据导出和导入必须由用户主动操作。详细说明请阅读：

- [隐私政策（简体中文）](./PRIVACY-ZH.md)
- [Privacy Policy (English)](./PRIVACY-EN.md)

## 数据来源与准确性

食物资料会尽可能标注来源、食物状态和数据类型。部分基础营养数据来自 USDA FoodData Central；该数据以 CC0 1.0 方式发布。中国 PKU 相关参考信息会注明对应共识或资料来源。

食物品种、产地、加工状态、品牌配方和生产批次都可能影响实际营养值。App 中的估算值不能替代包装标签、厂家报告、医院检验结果或医生意见。

## 如何提交反馈

请在 [Issues](../../issues) 中选择相应模板：

1. **Bug 反馈**：闪退、记录无法保存、计算或数据显示异常
2. **功能建议**：希望增加的能力或现有流程优化
3. **通用意见**：界面、文案、操作体验和其他建议

提交前请注意：

- 请先搜索已有 Issue，避免重复反馈
- 请提供 iOS 版本、设备型号、PheCare 版本和复现步骤
- 可以上传不包含敏感信息的界面截图
- **不要上传宝宝姓名、出生日期、血值、医院信息、完整饮食记录或导出的备份文件**
- 本仓库不提供诊疗建议；紧急或个体化医疗问题请联系专业医务人员

## Bug 反馈建议包含

1. iPhone 型号和 iOS 版本
2. PheCare 版本号
3. 问题发生前的操作步骤
4. 预期结果与实际结果
5. 已脱敏的截图或错误提示

如果问题涉及计算，请使用虚构或脱敏示例说明，不要公开真实的儿童健康数据。

## 自由讨论

早期想法和非正式交流可前往 [Discussions](../../discussions)。

## 不接受的内容

- 真实个人或未成年人健康隐私数据
- 针对具体儿童的诊断、治疗或配方用量咨询
- 重复刷屏、广告或无关推广
- 盗版、破解及其他违法违规内容

## 赞赏支持

PheCare 会持续免费维护。如果它对你的家庭记录有所帮助，欢迎小额赞赏支持后续设备适配、数据维护与功能迭代。

### 中国大陆用户：微信赞赏

<div align="center">
  <img src="./assets/wechat-donate.png" width="320" alt="微信赞赏码" />
  <p>使用微信扫描赞赏码</p>
</div>

### 海外用户：PayPal

海外用户可以通过 [PayPal](https://www.paypal.com/) 向以下 PayPal 注册邮箱付款：

**xbeichenbei@gmail.com**

> 请在付款前仔细核对收款邮箱。赞赏金额随意，感谢你的支持 🙏

## 联系方式

技术支持、隐私问题和产品反馈请通过 [GitHub Issues](../../issues) 联系。

## License

本仓库中的说明文档及用户提交的反馈用于 PheCare 产品支持和迭代。仓库现有许可证见 [LICENSE](./LICENSE)。
