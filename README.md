# 介绍

一个文档模板/



<link rel="stylesheet" href="https://unpkg.com/gitalk/dist/gitalk.css">
<script src="https://unpkg.com/gitalk@latest/dist/gitalk.min.js"></script> 

<div id="gitalk-container"></div>
<script>
    var gitalk = new Gitalk({
        clientID: '{{ site.gittalk.clientID }}',
        clientSecret: '{{ site.gittalk.clientSecret }}',
        repo: '{{ site.gittalk.repo }}',
        owner: '{{ site.gittalk.owner }}',
        admin: ['{{ site.gittalk.admin }}'],
        id: '{{ site.gittalk.id }}',
        language: 'zh-CN',
    });
    gitalk.render('gitalk-container');
</script> 
