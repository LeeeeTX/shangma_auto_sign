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
- Auto Sign-in run successful on Sat May 17 01:11:18 UTC 2025
- Auto Sign-in run successful on Sun May 18 01:17:26 UTC 2025
- Auto Sign-in run successful on Mon May 19 01:15:58 UTC 2025
- Auto Sign-in run successful on Tue May 20 01:13:53 UTC 2025
- Auto Sign-in run successful on Wed May 21 01:13:25 UTC 2025
- Auto Sign-in run successful on Thu May 22 01:12:52 UTC 2025
- Auto Sign-in run successful on Fri May 23 01:12:41 UTC 2025
- Auto Sign-in run successful on Sat May 24 01:09:57 UTC 2025
- Auto Sign-in run successful on Sun May 25 01:19:19 UTC 2025
- Auto Sign-in run successful on Mon May 26 01:14:50 UTC 2025
- Auto Sign-in run successful on Tue May 27 01:12:11 UTC 2025
- Auto Sign-in run successful on Wed May 28 01:13:52 UTC 2025
- Auto Sign-in run successful on Thu May 29 01:13:26 UTC 2025
- Auto Sign-in run successful on Fri May 30 01:11:31 UTC 2025
- Auto Sign-in run successful on Sat May 31 01:11:36 UTC 2025
- Auto Sign-in run successful on Sun Jun  1 01:26:35 UTC 2025
- Auto Sign-in run successful on Mon Jun  2 01:16:33 UTC 2025
- Auto Sign-in run successful on Tue Jun  3 01:14:37 UTC 2025
- Auto Sign-in run successful on Wed Jun  4 01:14:33 UTC 2025
- Auto Sign-in run successful on Thu Jun  5 01:13:39 UTC 2025
- Auto Sign-in run successful on Fri Jun  6 01:13:39 UTC 2025
- Auto Sign-in run successful on Sat Jun  7 01:13:07 UTC 2025
- Auto Sign-in run successful on Sun Jun  8 01:20:41 UTC 2025
- Auto Sign-in run successful on Mon Jun  9 01:17:57 UTC 2025
- Auto Sign-in run successful on Tue Jun 10 01:15:11 UTC 2025
- Auto Sign-in run successful on Wed Jun 11 01:14:52 UTC 2025
- Auto Sign-in run successful on Thu Jun 12 01:13:46 UTC 2025
- Auto Sign-in run successful on Fri Jun 13 01:14:55 UTC 2025
