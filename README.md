# go-pipeline-demo
快速構建自動測試及打包推播 Docker 映象

終端機輸入:
go mod init v0
初始化專案(不確定是不是正錯的指令參數)

輸入:
go test
(回傳 FAIL - 字串內容不一樣，改一樣就回傳 PASS)

要去 Docker 建立 Token
[docker hub - security](https://hub.docker.com/settings/security)
![Token](https://i.imgur.com/SNQIdG3.png)
![GitHub Secrets](https://i.imgur.com/UXKBkGb.png)
把上面的 token 填到 DOCKER_USER_NAME 與 DOCKER_ACCESS_TOKEN

![檔案位置](https://i.imgur.com/130yOam.png)

---

![Action](https://i.imgur.com/gAOJxzp.png)
