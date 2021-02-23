---
title: 你好，世界
---

Welcome to [Hexo](https://hexo.io/)! This is your very first post.




<!-- 引入 -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
 
<!-- 添加一个容器-->
<div id="gitalk-container"></div>
 
<!-- 生成 gitalk 插件-->
<script>
var gitalk = new Gitalk({
  clientID: 'f057bacc8823b2df5bf6', //Client ID
 
  clientSecret: 'd2c414884cc59d059bf37a522eaac540bdcc3fe0', //Client Secret
 
  repo: 'gitalk',//仓库名称
  owner: 'xiaozhu2007',//仓库拥有者
  admin: ['xiaozhu2007'],
  id: location.href,      // Ensure uniqueness and length less than 50
  distractionFreeMode: false  // Facebook-like distraction free mode
})
gitalk.render('gitalk-container')
</script>
