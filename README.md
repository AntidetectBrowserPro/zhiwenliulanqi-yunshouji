# 指纹浏览器和云手机怎么选？

如果值班只需要在手机上查网页订单，**「指纹浏览器」** 就是一个合适的起点。点选店铺的环境卡片，看清「当前」标记，再打开订单页。同一份值班清单里，如果还有一项是进入 Android App 从相册上传素材，就要另看能运行这个 App 的设备或云手机。[手机端操作说明](https://zwbrowser.com/help/mobile/start/)

![手机浏览器中访问网页的入口](https://zwbrowser.com/images/mobile-guide-active-light.webp)

| 日常任务 | 先试哪种方式 | 重点验证 |
| --- | --- | --- |
| 网页后台对账、下载表格 | 浏览器环境 | 登录状态、弹窗、文件保存 |
| 自有 Android App 的相册上传 | 可运行该 App 的 Android 设备或云手机 | 安装兼容性、相册权限、上传结果 |
| 验收移动网页布局 | 手机浏览器或桌面响应式测试，最后用真机复核 | 触控目标、软键盘、窄屏换行 |
| 同一业务同时覆盖网页和 App | 两套环境分别测试 | 两套结果是否能按同一工单对上 |

## 什么时候需要云手机？

Multilogin 将浏览器环境和云手机列为两种配置。前者服务网页任务，后者运行 Android App，并涉及云手机使用时长。它的帮助页还写明云手机接收短信或电话的限制；依赖这些能力的流程要提前核对。[Multilogin 官方对照](https://multilogin.com/help/choose-profile-type/)

![Multilogin产品展示](https://github.com/user-attachments/assets/4de9816f-bfc2-462d-badf-9206366f02e9)

做预算可以拆成「网页环境数」和「每天云手机运行分钟数」两项。只在审核移动素材时临时需要 App 的团队，与全天都在处理原生 App 任务的团队，成本结构会很不一样。
