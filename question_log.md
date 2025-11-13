# git question
 1. git push/pull 鉴权失败 @https://blog.csdn.net/qq_18479497/article/details/127269105
    - step1: 本人的联系，不是github用户名和邮箱,
      git config --global user.name "YOUR_NAME"
      git config --global user.email "YOUR_EMAIL"
    - step2: 检查配置信息
      git config --global --list
    - step3: 生成tokens
      github.com->Settings->Developer settings -> Persional access tokens(PAT) -> generate new token
    - step4: git push/pull时,username是注册时设置的用户名，password是tokens
    
 
