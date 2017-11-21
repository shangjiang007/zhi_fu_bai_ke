## 银行卡领域模型

### 基础模型（BaseBankCard）

银行编号（bankCode）：用于标识银行的唯一ID

银行卡BIN（bankCardBin）：银行标识代码

卡类型（bankCardType）：

借贷记标识（debitFlag）：0：不区分借贷记、1:借记卡、2:贷记卡、3:准贷记卡、4:预付卡

银行卡号（）：银行卡的卡号是标识发卡机构和持卡人信息的号码，由以下三部分组成：发卡行标识代码\(BIN号\)、发卡行自定义位、       校验码。

联行行号（UnitedBankNumber）：是一个地区银行的唯一识别标志，用于跨区域银行间的结算和资金清算

开户行行名（bankName）：

开户城市编码（cityNumber）：

开户省份编号（provNumber）：

