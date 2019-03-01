## 概述
本文档是对 Math Wallet 常用二维码格式说明

## 二维码格式：

转账
~~~
{
    "client": "MathWallet",
    "type": "EOS",
    "action": "transfer",
    "data": {
        "to": "bigbigbigbig",
        "amount": "1.0000 EOS",
        "precision": 4,
        "contract": "eosio.token"
    }
}
~~~
购买内存
~~~
{
    "client": "MathWallet",
    "type": "EOS",
    "action": "createAccount",
    "data": {
        "account_name": "bigbigbigbig",
        "owner": "EOS7n5Aufs8wzsDaNpgez4HUz9W4VU45sQMKm8tAYRrshy1q3twPD",
        "active": "EOS7n5Aufs8wzsDaNpgez4HUz9W4VU45sQMKm8tAYRrshy1q3twPD",
        "ram": 1024,
        "net": "0.3000 EOS",
        "cpu": "0.3000 EOS"
    }
}
~~~
