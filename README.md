## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

- Auto Sign-in run successful on Mon May  5 09:02:10 UTC 2025
- Auto Sign-in run successful on Tue May  6 01:11:33 UTC 2025
- Auto Sign-in run successful on Wed May  7 01:12:03 UTC 2025
- Auto Sign-in run successful on Thu May  8 01:12:29 UTC 2025
- Auto Sign-in run successful on Fri May  9 01:11:49 UTC 2025
- Auto Sign-in run successful on Sat May 10 01:09:23 UTC 2025
- Auto Sign-in run successful on Sun May 11 01:16:29 UTC 2025
- Auto Sign-in run successful on Mon May 12 01:14:41 UTC 2025
- Auto Sign-in run successful on Tue May 13 01:13:12 UTC 2025
- Auto Sign-in run successful on Wed May 14 01:12:00 UTC 2025
- Auto Sign-in run successful on Thu May 15 01:09:56 UTC 2025
- Auto Sign-in run successful on Fri May 16 01:13:03 UTC 2025
