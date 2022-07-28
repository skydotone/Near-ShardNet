



- [第一个任务](https://github.com/near/stakewars-iii/blob/main/challenges/001.md) 安装一些需要的命令行, 升级等等, 系统是Ubuntu, 正常跟着教程来即可 :apple:
- [第二个任务](https://github.com/near/stakewars-iii/blob/main/challenges/002.md) 开始跑节点, 也没有什么可以说的, 跟着教程一步步来就好 ❤️
- [第三个任务](https://github.com/near/stakewars-iii/blob/main/challenges/003.md) 开始建立质押池 `near call factory.shardnet.near create_staking_pool '{"staking_pool_id": "<pool id>", "owner_id": "<accountId>", "stake_public_key": "<public key>", "reward_fee_fraction": {"numerator": 5, "denominator": 100}, "code_hash":"DD428g9eqLL8fWUxv8QSpVFzyHi1Qd16P8ephYCTmMSZ"}' --accountId="<accountId>" --amount=30 --gas=300000000000000` 这个命令行的code_hash不用管, 其余的按照教程替换掉. 没毛病✔️
- [第四个任务](https://github.com/near/stakewars-iii/blob/main/challenges/004.md) 检查自己的节点, 同样 发送几个命令行看看结果即可

注意点

1. 关于Near的这个任务, RPC有的时候会挂掉, 影响 explorer, 
2. RPC也会影响near命令, 本地curl等等, 可以等RPC好了之后再去做一些Check的工作
