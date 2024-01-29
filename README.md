# 求生网站的yml文件以及source
先按照tutorial安装好本地的库之后，再将此处的source与yml文件放进根目录中，覆盖其原本的文件即可  
#关于插件   
目前有  
    "hexo": "^7.0.0",  
    "hexo-deployer-git": "^4.0.0",  
    "hexo-generator-archive": "^2.0.0",    
    "hexo-generator-category": "^2.0.0",  
    "hexo-generator-index": "^3.0.0",  
    "hexo-generator-tag": "^2.0.0",  
    "hexo-renderer-ejs": "^2.0.0",  
    "hexo-renderer-marked": "^6.0.0",  
    "hexo-renderer-pug": "^3.0.0",  
    "hexo-renderer-stylus": "^3.0.1",  
    "hexo-server": "^3.0.0",  
    "hexo-theme-landscape": "^1.0.0"  

你可以打开你的文件夹内的package.json文件然后进行核对，缺少插件的话本地是运行不起来的，然后你要是上传后，网站估计也不能正常运行  
因为Hexo的一键部署是覆盖式的  
不过也不要担心，因为大家都采用本地编辑再部署的方式，所以肯定至少有一个同学手里捏着某个可以正常运行的版本啦~  
回溯一下老版本再改改还是很方便的  
