# Simple-Message-Notification-Client
Welcome to Simple Message Notification(SMN)    
The java sdk client for Simple Message Notification

update smn.properties for user info

```
#socket connector timeout(ms)
socket.connector.timeout=10000
#socket read timeout(ms)
socket.read.timeout=10000

# user name from iam
iam.user.name=liuqiangqiang
# domain name from iam
iam.domain.name=liuqiangqiang
# user passwd from iam
iam.user.password=******
# iam.url 
iam.token.url=https://iam.cn-north-1.myhwclouds.com/v3/auth/tokens
# regionId 
region.id=cn-north-1
# smn.endpoint
smn.endpoint=https://smn.cn-north-1.myhwclouds.com

```

run com.smn.client.SmnClientTest to send a message   
