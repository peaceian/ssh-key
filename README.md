# ssh-key
The ssh key create and access.<br>
記錄下來，浪費了大半時間的慘痛經驗。<br>
You can command the following after finish the ssh key Authentication.<br> 
$ git remote set-url origin git@github.com:{user_id}/{project_name}.git <br>
![image](https://github.com/peaceian/ssh-key/blob/main/githubsshkey.png)
![image](https://github.com/peaceian/ssh-key/blob/main/githubsshkeycmd.png)<br>
做完sla ssh key 之後，push才知道目前不使用這種key，白做工。<br>
![image](https://github.com/peaceian/ssh-key/blob/main/githubsshkeyfinish.png)
![image](https://github.com/peaceian/ssh-key/blob/main/sshkeyed25519.png)<br>
最後使用ed25519 ssh key ，push後成功。<br>
ref:<br>
'https://peterpowerfullife.com/blog/github-shut-down-password/'<br>
'https://www.maxlist.xyz/2022/12/22/github-ssh-setting/'<br>
'https://blog.csdn.net/lishuangquan1987/article/details/123588802'<br>
'https://kiiuo.com/archives/3347/github-%e4%bd%bf%e7%94%a8-git-push-%e4%bd%bf%e7%94%a8-ssh-key-%e5%85%8d%e5%b8%b3%e8%99%9f%e5%af%86%e7%a2%bc/'<br>
