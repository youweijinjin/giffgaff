# 2025年最新 Vultr VPS 注册与购买教程：支持支付宝与微信支付


在 Vultr 官方网站，大部分内容为英文，仅部分页面为中文。许多新手用户面对这样的界面可能不知所措。因此，本教程将为大家详细讲解 Vultr 的注册与购买流程，让您轻松上手，快速开启服务器。

---

### **WildCard 优惠推荐**
一分钟注册，轻松订阅海外线上服务：[立即开通](https://bit.ly/bewildcard)  
**微信、支付宝均可使用，支持开通各类海外平台：ChatGPT、Claude、Google Play、Apple Store、OpenAI、Twitter、Patreon、MidJourney 等。**  
使用邀请码：**ACCPAY**，立享消费 0 手续费并减免开卡费用！

---

## 一、注册账户

点击 [Vultr 官方注册链接]后，进入如下页面：  
1. 填写 **注册邮箱** 和 **注册密码**（需包含小写字母、大写字母、数字和特殊字符中的三项，长度至少 10 位）。  
2. 点击 `Create account` 创建账户。

> **提示：**请务必仔细核对注册邮箱是否正确，否则后续操作可能受阻。

![注册账户](https://www.vultrcn.com/wp-content/uploads/2020/01/register01-2020.png)

---

## 二、验证邮箱

完成注册后，您将收到一封名为 “Welcome to Vultr.com” 的验证邮件。  
打开邮件，点击 `Verify Your E-mail` 即可完成邮箱验证。

> **注意：**如果未收到邮件，请检查垃圾箱或更换其他邮箱重新注册。

![邮箱验证](https://www.vultrcn.com/wp-content/uploads/2020/01/register02-2020.png)

---

## 三、充值账户余额

验证邮箱后，系统会提示账户余额为 $0。为了使用服务，需要先充值。以下为充值步骤：  
1. 选择支付方式为 **支付宝（Alipay）**，填写以下信息：
   - **姓名拼音**（如 Zhang SanFeng）  
   - **所在区/县拼音**（如 Chaoyang Qu）  
   - **所在市拼音**（如 Beijing）  
   - **邮政编码**（如 100000）  
   - **国家选择 China（中国）**  
2. 选择充值金额（如 $10），勾选 `I Agree to the Terms of Service`，然后点击 `Pay with Alipay`。

![账户充值](https://www.vultrcn.com/wp-content/uploads/2020/01/register03-2020.png)

完成以上操作后，通过支付宝 App 扫码支付，或使用支付宝账户登录进行支付。

> **温馨提示：**部分用户首次充值可能会需要 24 小时的账户验证期，请耐心等待。

---

## 四、创建服务器

充值成功后，您可以开始创建服务器。以下为步骤详解：

### 1. 选择服务器类型
推荐选择 **Cloud Compute**，价格最低，适合个人及小型项目使用。

![选择服务器类型](https://www.vultrcn.com/wp-content/uploads/2022/01/choose-server-202207.png)

### 2. 选择 CPU 和存储技术
推荐选择 **Regular Performance**，性价比高，适合大多数用户需求。

![CPU 和存储技术](https://www.vultrcn.com/wp-content/uploads/2022/01/cpu-and-storage-technology-202207.png)

### 3. 选择服务器位置
根据需求选择服务器机房位置，或使用 [Ping 测试脚本](https://www.vultrcn.com/9.html) 测试延迟后选择。

![选择服务器位置](https://www.vultrcn.com/wp-content/uploads/2022/01/server-location-202207.png)

### 4. 选择系统镜像
一般选择 **Debian** 或 **Ubuntu** 系统，如 Debian 11 x64 或 Ubuntu 22.04 x64。

![选择系统镜像](https://www.vultrcn.com/wp-content/uploads/2022/01/server-image-202207.png)

### 5. 选择服务器套餐
推荐选择 $5/月套餐。若有更便宜的套餐如 $3.5/月，也可根据需求选择。

![选择服务器套餐](https://www.vultrcn.com/wp-content/uploads/2022/01/server-size-202207.png)

### 6. 自动备份设置
自动备份默认开启，如无重要数据可关闭以节省费用。

![自动备份设置](https://www.vultrcn.com/wp-content/uploads/2022/01/add-auto-backups-202207.png)

### 7. 其他设置
若无额外需求，保持 Additional Features、SSH Keys、Server Hostname & Label 等默认设置即可。

![其他设置](https://www.vultrcn.com/wp-content/uploads/2022/01/additional-feature-ssh-keys-server-hostname-and-label-202207.png)

### 8. 确认并创建服务器
确认配置无误后，点击 `Deploy Now` 即可创建服务器。

![确认并创建服务器](https://www.vultrcn.com/wp-content/uploads/2022/01/servers-qty-and-summary-202207.png)

---

## 五、查看服务器信息

服务器创建完成后，可进入管理面板查看服务器状态。  
红色 `Installing` 表示正在初始化，几分钟后会变为绿色 `Running`。

![服务器运行状态](https://www.vultrcn.com/wp-content/uploads/2022/01/server-running-202207.png)

在服务器详情页面，您可以获取：
- **服务器 IP 地址、用户名及密码**（用于 SSH 登录）。  
- **服务器当前流量及费用信息**。  
- **系统版本信息**。

![服务器详情](https://www.vultrcn.com/wp-content/uploads/2022/01/server-information-202207.png)

---

## 六、检测服务器 IP 是否正常

为了确保服务器可以正常使用，建议检测服务器 IP 状态。  
访问 [IP112.cn](https://ip112.cn)，输入服务器 **IP 地址** 和 **端口号（22）**，点击 `开始检查`。  
若国内和国外的 TCP 检查均为正常，即表示 IP 可正常使用。

![检测服务器 IP](https://www.vultrcn.com/wp-content/uploads/2022/01/vultr-ip-check-by-ip112.cn-202207.png)

---

## 总结

通过以上步骤，您已成功完成 Vultr 服务器的注册、充值与部署。  
更多使用教程请参考本站 [新手教程]，了解更多 Vultr 的功能与操作技巧。
