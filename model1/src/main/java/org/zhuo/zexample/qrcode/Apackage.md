这个包放生成二维码的后端代码

思路是：
1.前端用户选择模板，将信息和模板编号作为参数传递过
2.后端选择模板  通过freemarker生成html字符串
3.后端将html作为路径参数拼接在解析服务器的请求路径上 封装这个url返回给前端
3.后端将html作为路径参数拼接在解析服务器的请求路径上 解析服务器返回一个特定的地址返回给前端

- 23.12.19解决中文乱码问题，新增前端调用示例代码