# QuantumultX
 QuantumultX Script Repository
 
# 相关脚本

### 一：基础配置
- 资源解析器  
resource_parser_url=https://raw.githubusercontent.com/0xYGC/QuantumultX/main/scripts/resource-parser.js

### 模块以及解释
| 序号 | 模块名称 | 支持文件 | 解释 |
| --- | --- | --- | --- |
| 1 | [general]  | 比如 资源解析器 js文件后缀 | 用的设置参数项 |
| 2 | [dns] |  |  |
| 3 | [policy]  |  |  |
| 4 | [server_local]  |  |  |
| 5 | [server_remote]  |  |  |
| 6 | [filter_local]  |  |  |
| 7 | [filter_remote] |  |  |
| 8 | [rewrite_local]  |  |  |
| 9 | [rewrite_remote]  |  |  |
| 10 | [task_local]  |  |  |
| 11 | [http_backend]  |  |  |
| 12 | [mitm]  |  |  |

### 二：BoxJS组件
站点地址: https://chavyleung.gitbook.io/boxjs

通过 Rewrite 的方式访问 BoxJs 会导致无法删除备份, 建议改用 HTTP Backend
```aidl
# 安装路径:
​ 风车 > 工具&分析> HTTP Backend > 添加

# 标签: boxjs
# 处理请求的路径: ^/

# 脚本路径 (稳定版)
https://raw.githubusercontent.com/chavyleung/scripts/master/chavy.box.js


# 访问地址:
http://127.0.0.1:9999

# 注意事项
注意配置 HTTP Backend 的地址为 0.0.0.0 端口为 9999
配置完成后确保打开了 HTTP Backend 的开关
然后 全部更新 > 重启代理
```



# 参考资料 & 致谢
[1] [KOP-XIAO (Github)](https://github.com/KOP-XIAO)  
[2] [w37fhy (Github)](https://github.com/w37fhy)  
[2] [chavyleung BoxJS](https://chavyleung.gitbook.io/boxjs/)
