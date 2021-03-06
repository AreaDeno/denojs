#### denojs
deno开发的微服务库
<p><img src="https://github.com/AreaDeno/denojs/blob/master/public/logo.jpg" width="200" /></p>

[DenoJS](https://areadeno.github.io/denojs/ "DenoJS") 

#### 快速启动
deno run   --allow-net --allow-read main.ts

#### 答疑解惑
官方群：834548785

#### 基础学习
1. [deno官方](https://deno.land/ "Deno") 
2. [deno中文官方](https://denocn.org/ "Denocn") 

#### 已实现
1. 分布式服务（多端口，多IP启动）
2. Mysql数据库ORM的实现，只需继承model目录的Base类型即可操作数据库
3. 配置文件读取
4. deno依赖包deps.ts独立拉取，只需在项目的任意代码中引入即可调用 import {xxx} from "./deps.ts";

#### 计划功能
1. 缓存（redis,file）
2. 页面渲染
3. 消息队列
4. 计划任务
5. 更多...

#### 测试
nginx负载2个服务<br/>
在window系统下使用ab测试 <br/>
模拟1000个用户<br/>
每个用户10000次的请求<br/>
操作mysql数据库做分页查询，每次请求查询2次<br/>
得出的结论<br/>
<p><img src="https://github.com/AreaDeno/denojs/blob/master/public/test.png" width="500" /></p>