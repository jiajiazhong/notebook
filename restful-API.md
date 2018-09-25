#restful API
定义了资源的通用访问格式
1. REST请求仍然是标准的HTTP请求，但是，除了GET请求外，POST、PUT等请求的body是JSON数据格式，请求的Content-Type为application/json；
2. REST响应返回的结果是JSON数据格式，因此，响应的Content-Type也是application/json。