# 运维管理后台网站  
## 功能设计  
### Grafana（一期需求）
- 嵌套Grafana页面  
- 设置Grafana仅允许运维管理网站访问  
- 设置Grafana不需要密码访问
### Prometheus （一期需求） 
#### 告警项  
- 显示每个项目的告警规则状态  
#### Targets  
- 显示每个项目监控的目标状态  
#### 规则配置  
- 查看和编辑Prometheus的Rule文件  
#### 系统管理  
- 重新加载配置文件  
- 删除数据  
- 立即生效  
### 持续交付  （二期需求）
#### 执行任务  
- 点击执行任务  
- 任务开始后，可以查看任务状态  
- 显示任务执行状态，执行成功为绿色，失败为红色  
- 同一个任务，在执行期间，不允许再次执行  
#### 任务管理  
- 添加、修改、删除任务  
### Ansible（一期需求）  
#### 命令  
- 执行Ansible命令行命令  
#### Playbook  
- 查看、编辑、删除、上传、执行Playbook  
#### 主机管理    
- 查看、添加、删除主机  
### Web SSH（二期需求）  
- 登录运维管理网站所在的服务器SSH  
### 访问控制（一期需求）  
#### 用户管理  
- 添加、删除、修改、禁用、启用、MFA管理
#### 角色管理  
- 添加、删除、修改、禁用、启用、权限管理   
## 结构图  
- 获取Prometheus状态  
![image](https://devops-public-bucket.s3-us-west-2.amazonaws.com/Github/images/get_data_from_prom.png)  
- 管理Prometheus  
![image](https://devops-public-bucket.s3-us-west-2.amazonaws.com/Github/images/manage_prom.png)  
