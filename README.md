# print
Test only. https://api.example.org/v1 or https://example.org/api/v1

REST API: 

GET /docs # 获取文件列表.
GET /docs/12 # 查看某个具体的doc.
POST /docs # 新建一个doc.
PUT /docs/12 # 更新doc 12.
DELETE /docs/12 #删除doc 12.

GET /printers
GET /printers/id
PUT /printers/id/docs/id # Print a PDF



GET /collection：返回资源对象的列表（数组）
GET /collection/resource：返回单个资源对象
POST /collection：返回新生成的资源对象
PUT /collection/resource：返回完整的资源对象
PATCH /collection/resource：返回完整的资源对象
DELETE /collection/resource：返回一个空文档

API OAuth2.0
