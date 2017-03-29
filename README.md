# ps4ipark
##### Specification
- **Method** : POST
- **URL** : http(s)://:your\_server\_url/message
- **Content-Type** : application/json; charset=utf-8
- **Parameters**

curl -XPOST 'https://:your_server_url/message' -d '{ "user_key": "encryptedUserKey", "type": "text", "content": "차량번호등록" }'
