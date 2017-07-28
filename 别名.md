## 设置别名


1. 系统全部用户    
sudo git config --system alias.st status  
sudo git config --system alias.ci commit  
sudo git config --system alias.co checkout  
sudo git config --system alias.br branch  

可发现在/etc/gitconfig 系统级配置文件中增加了下面的配置   
[alias]   
	st = status   
	ci = commit   
	co = checkout   
	br = branch   

2. 当前用户    
sudo git config --global alias.st status  
sudo git config --global alias.ci commit  
sudo git config --global alias.co checkout  
sudo git config --global alias.br branch  
