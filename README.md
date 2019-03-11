mail2

#### 使用
发送主题为 test 的邮件给当前邮箱
mail2 -s test -m mail_content -a /home/laily/aa.jpg aa@aa.com

mail2 -h 查看参数说明

#### TODO 
使用管道命令
echo “mail content”| mail2 -s test aa@aa.com
读取文件中的内容发送邮件
mail2 -s test aa@aa.com< file
给多个用户发送邮件
mail2 -s test -c admin@aispider.com  root@aispider.com< file

#### 其他
项目使用 govendor 管理依赖
