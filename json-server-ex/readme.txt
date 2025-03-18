npm install -g json-server

폴더 생성 : javascript-project
폴더 생성 : json-server

javascript-project 내 json-server 내 db.json

db.json 파일로 만든다. 
{
    "posts": [{ "id": 1, "title": "json-server", "author": "typicode" }],
    "comments": [{ "id": 1, "body": "some comment", "postId": 1 }],
    "profile": {"name": "typicode"}
}

json-server 폴더 내에서

json-server --watch db.json
