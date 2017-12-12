## 订单领域模型

### 基础模型（BaseOrder）

商户订单号（orderCode）：由商户生成以标识唯一订单信息

订单金额（orderAmt）：标识该笔订单的实际金额

交易金额（txnAmt）：标识该笔订单的实际交易金额等于订单金额加上（减去）手续费金额

币种（currency）：默认156（人民币）

订单创建时间（orderTime）：标识生成该笔订单的时间（yyyyMMddHHmmss），由商户填充

订单超时时间（orderTimeOut）：标识该笔订单超时时间（yyyyMMddHHmmss）

折扣金额（discAmt）：标识该笔订单的折扣金额

订单描述（orderDesc）：

