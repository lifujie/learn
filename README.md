### 部署方式

- 两台机器

  - 第一台执行

    memberlist

  - 第二台执行（xx表示第一台的ip和端口号）

    memberlist --members=xxx.xxx.xxx.xxx:xxxx

  - 

- 执行命令

  ```go
  # add
  curl "http://localhost:4001/add?key=foo&val=bar"
  
  # get
  curl "http://另一台机器:4001/get?key=foo"
  
  # delete
  curl "http://localhost:4001/del?key=foo"
  ```

  

- http://kaiyuan.me/2015/07/08/Gossip/

- https://www.jianshu.com/p/e2173b44db65

- https://www.jianshu.com/p/5198b869374a

- https://blog.csdn.net/screscent/article/details/91984420

- https://mp.weixin.qq.com/s?__biz=MzU2NDUwMjU3Ng==&mid=2247484297&idx=1&sn=14acf4aca97adcda6bc7ee665e2b70c7&chksm=fc4b4ad6cb3cc3c0bd3936a558d9101684940b86835804a82ce1a521a12566f539c030ac07de&scene=21#wechat_redirect

- http://blog.gssxgss.me/gossip-based-membership-change-1/

- https://blog.csdn.net/u010278923/article/details/79710333

- https://prakhar.me/articles/swim/

- http://vearne.cc/archives/584