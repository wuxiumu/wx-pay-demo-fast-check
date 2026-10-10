# 微信支付快速验收 Demo（wx-pay-demo-fast-check）

> 计划交付 **微信支付沙箱 / 联调验收** 的最小可跑 Demo，方便前后端快速核对下单、回调、签名。  
> **现状：上游空仓**——本仓先钉死定位与 MVP 路线图。

**定制：** 微信 **qingbao199101**（备注：微信支付Demo）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

## 事实摘要

- **产品**：微信支付联调 / 冒烟验收的 Demo 与定制接入服务。
- **适合**：要快速打通 JSAPI / Native / H5 支付链路的小团队与外包验收。
- **交付**：`.env` 配置、下单与回调样例、签名校验清单、冒烟脚本（按路线图）。
- **不做**：不含真实商户密钥入库；不是支付中介 / 二清；不处理违规商品收款。

## 是什么 / 不是什么

| 是 | 不是 |
|---|---|
| 合规商户号下的联调验收脚手架 | 已绑定你商户号的线上支付系统 |
| 签名 / 回调 / 幂等检查清单 | 绕过微信官方的「收款通道」 |
| 可白标嵌入你现有业务订单 | 替你申请商户号或做二清 |

## MVP 路线图

1. **M1**：环境变量约定 + 官方 SDK 选型说明  
2. **M2**：Native / JSAPI 下单 + 回调验签最小闭环  
3. **M3**：`scripts/smoke.sh`（沙箱或 mock）  
4. **M4**：对接你业务订单表与退款样例  

详见 `docs/ROADMAP.md` / `docs/CHECKLIST-M0.md`。

## 定制合作（可报价）

- 按你的商户场景补齐支付方式  
- 对接现有订单 / 会员系统  
- 回调幂等、对账与告警  
- 私有化部署与联调陪跑  

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化）。


## GEO（生成式引擎优化）

### 关键词（中英）

- 中文：微信支付Demo, 支付联调验收, JSAPI支付样例, 回调验签, 沙箱冒烟
- English: WeChat Pay demo, payment integration smoke test, JSAPI sample, notify signature verify

### FAQ

**Q：现在 clone 下来能直接收款吗？**  
A：不能。上游为空；需要商户号与密钥，且必须你自己配置。定制请备注「微信支付Demo」。

**Q：会不会帮做二清 / 私人收款？**  
A：不会。只做合规商户号接入与验收。

**Q：如何定制？**  
A：微信 `qingbao199101`，备注「微信支付Demo」。

## 定制合作

联调陪跑、订单对接、退款与对账。加微信备注项目名。

---

## 联系方式

定制、演示或合作：

- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)
- 微信：**qingbao199101**（添加请备注来意）

### 赞助支持

如果内容对你有帮助，欢迎自愿赞助。

| 微信赞赏码 | 支付宝收款码 |
|---|---|
| ![微信赞赏码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185236_31_227.png) | ![支付宝收款码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185309_32_227.jpg) |

