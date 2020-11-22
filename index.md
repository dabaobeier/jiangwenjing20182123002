### 用例名称：Download Code 
### 用例说明：管理员和User可以下载Github中的code
### 参与者：管理员，User
### 元素：Open with Desktop,Download ZIP
### 关系：管理员和User对于Download Code用例是关联关系；Download Code对于Open with Desktop 和Download ZIP 是扩展（extend）关系
### 建模思路
1.	在管理员和User登录Github后，可以对其进行搜索的内容进行Download Code（下载）功能的操作。
2.	在Download Code的功能下，管理员和User均有两种选择。一个是Open with Desktop，另外一个是Download ZIP。所以Open with Desktop和Download ZIP均是Download Code的扩展（extend）关系

### 用例名称	User Enter File
### 用例说明	
User可以对文件进行查看和修改；
User修改时要向管理员提出修改申请；
管理员接受User的申请并对其进行审核
### 参与者	User，管理员
### 元素	Find File ,Enter File ,Change Flie ,User requests ,User questions
### 关系	
User对于Enter File是关联关系；
管理员对于Change File是关联关系；
Change File对于Enter File是泛化关系；
Find File 对于Enter File是包含关系；
User requests和User questions对于Change File均是包含关系。
### 建模思路	
1.	在User登录Github后，可以进入搜索界面进行搜索（Find File），查看文件等操作；
2.	除了搜索查看等操作，User还可根据用户提出的要求（User requests）和问题(User questions)对文件进行修改。但是作为用户进行修改操作时，必须要向管理员提出申请，得到管理员的同意之后才可以对其进行修改。
