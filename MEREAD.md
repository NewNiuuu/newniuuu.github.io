 站点配置
   - _config.yml - 标题、描述、作者信息、社交链接等

   - 主页内容
     - _pages/about.md - 关于页面的主要内容（这是主页的主体）
     - _pages/ 下的其他 .md 文件 - 导航栏各页面（publications.md, talks.md, teaching.md 等）

     导航与显示
     - _data/navigation.yml - 导航栏配置
     - images/profile.png - 侧边栏头像

     内容集合
     - _publications/ - 发表的论文
     - _talks/ - 报告/演讲
     - _teaching/ - 教学经历
     - _portfolio/ - 作品集

     _config.yml 修改后需要重启 Jekyll 服务才能生效，其他文件修改后会自动刷新预览。