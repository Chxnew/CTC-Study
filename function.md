###Consumer Transaction Controls: How it Works
    Control rules include: global on/off, spending thresholds, domestic-only, in-store or e-commerce only,
    select merchant types, and alert thresholds.
    
###Decline All(block)
    当开启时，拒绝所有的主副卡消费或者取现。
    当开启时，不鼓励发行机构拒绝自动支付账单。

###Decline All(alert)
    警告信息。任何一笔拒绝的交易发生，都会发送拒绝警告。如果，一笔E-Commerce交易被E-Commerce规则控制拒绝，
    不会同时发送拒绝警告和E-Commerce警告。

###Threshold(block)
    单笔交易金额超过或等于阈值，交易会被拒绝。

###Threshold(alert)
    当笔交易金额超过或等于阈值，发送阈值警告。

###TimeRange
    如果为block及alert设置了时间段，那么只有发生在该时间段内的交易，才会触发block规则或alert规则。

###ATM Withdraw(block)
    阻止取现及返现交易。

###ATM Withdraw(alert)
    取现及返现交易均发送ATM Withdraw警告。

###Brick and Mortar(block)
    拒绝所有商户销售点的有卡交易，但是ATM取现不受影响。

###Brick and Mortar(alert)
    商户销售点的有卡交易会触发Brick and Mortar警告。

###E-Commerce(block)
    禁止所有经过电子商务，邮件订单及电话订单的无卡交易。

###E-Commerce(alert)
    E-commerce和MOTO(邮件订单和电话订单)的无卡交易均发送E-Commerce警告。

###Cross Border(block)
    禁止国际间的有卡交易。

###Cross Border(alert)
    国际间的有卡交易触发Cross Border警告。

###Auto Pay(block)
    禁止所有与此账户有关的自动支付账单（经常性交易），比如健身房会员或者订阅服务。

###Auto Pay(alert)
    自动支付账单警告。

###Contactless(block)
    禁止所有非接的近场通信（NFC）有卡交易。

###Contactless(alert)
    非接有卡交易警告。


    

---
####部分英文注释

#####Card-present transaction
    A card not present transaction (CNP, MO/TO, Mail Order / Telephone Order, MOTOEC) is a payment card 
    transaction made where the cardholder does not or cannot physically present the card for a merchant's 
    visual examination at the time that an order is given and payment effected, such as for mail-order 
    transactions by mail or fax, or over the telephone or Internet.



























