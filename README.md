<h1 align="center"> SE2022 文档 </h1>
<div align="center">

[![](https://img.shields.io/badge/backend-Django-96d6d1)](https://www.djangoproject.com/) [![](https://img.shields.io/badge/frontend-Vue.js-7B8ED0)](https://vuejs.org/) [![](https://img.shields.io/badge/framework-uniapp-4E9645)](https://uniapp.dcloud.net.cn/) [![](https://img.shields.io/badge/license-MIT-9cf)](./LICENSE)
</div>

## 项目简介

**面向企业技术需求的专家对接服务平台**

在现有论文解读科研社交平台基础上进行二次开发，建立完整的企业与专家对接流程，以及专业化的对接链路等，利用Al针对性地促成企业与专家合作。

- 名称：`PaperDaily`
- 成员：[@oyk](https://github.com/Mike-Smith-rem), [@lzz](https://github.com/cpfy), [@xgl](https://github.com/xgl010607), [@lpx](https://github.com/lpx-single), [@xcc](https://github.com/MrXcc0), [@gmm](https://github.com/imingx)
- 编号：O2E-TU-2

## 成果

- [项目文档](./Document)
- [周报和汇报](./Weekly)

|         | 🌈 REPO                                                       | 🍿DEPLOY                                        | 🧙URL  |
| ------- | ---- | ------- | ------- |
| uni-app |   [repo](https://github.com/SE-mcdb/SE2022_Frontend_App)   |   [App](https://github.com/SE-mcdb/App)   |- [`apk`](https://github.com/SE-mcdb/SE2022_Frontend_App/releases)<br/>- [`spoc.uno`](http://spoc.uno) |
| web     | [repo](https://github.com/SE-mcdb/SE2022_Frontend_Web)     | [Web](https://github.com/SE-mcdb/Web) | [`w.spoc.uno`](http://w.spoc.uno) |
| manager | [repo](https://github.com/SE-mcdb/SE2022_Frontend_Manager) | [Manager](https://github.com/SE-mcdb/Manager) | [`m.spoc.uno`](http://m.spoc.uno) |

## 进度安排

- [开会记录](./Meeting.md)、[评价指导](./Comments.md)、[TODO](./Todo.md)
- `3.22` 周报初稿、汇报进度
- `3.29` 团队作业需求汇报评审，提交**需求文档**、周报
- `4.5` ，`4.12`，`4.19`，`4.26` 提交周报、汇报进度
- `5.5` Alpha版本评审，提交周报、概要设计文档

## 每周安排

- 周二：课上汇报
- 周二下午：开会，制定初步分工计划
- 周三至周日：群内细化分工，完成开发任务。
- 周一：开会，讨论下周计划。
- 周一晚：提交周报

## 平台工具

- 周报、需求等文档：[金山文档](https://www.kdocs.cn/group/1730778455)
- 文档归档：[SE2022_doc](https://github.com/SE-mcdb/SE2022_doc)
- 资源归档：[SE2022_source](https://github.com/SE-mcdb/SE2022_source)
- 源代码： 
  - 后端：[SE2022_Backend](https://github.com/SE-mcdb/SE2022_Backend)
  - 管理端：[SE2022_Frontend_Manager](https://github.com/SE-mcdb/SE2022_Frontend_Manager)
  - 用户端：[SE2022_Frontend_Web](https://github.com/SE-mcdb/SE2022_Frontend_Web)
  - APP端：[SE2022_Frontend_App](https://github.com/SE-mcdb/SE2022_Frontend_App)
- API协作：[Apifox](https://www.apifox.cn/web/project/843519)
- 通知公告：微信群

## 账号

<details><summary>数据库</summary>

```
'HOST': 'rm-2zeu3f7e1n5yt10v0co.mysql.rds.aliyuncs.com',
'NAME': 'se2022',
'USER': 'root',
'PASSWORD': 'myja&*$4X579cKr',
'PORT': '3306'
```
</details>

<details><summary>云服务</summary>

#### 华为云（课程）

```
CentOS

'HOST': 122.9.14.73

// 普通用户
'USER': admin
'PASSWORD': se-mcdb-o2e

// 根用户
'USER': root
'PASSWORD': se-mcdb-o2e

建议使用普通用户登录
```

#### 阿里云

```
CentOS

'HOST': 47.94.7.26

// 普通用户
'USER': admin
'PASSWORD': se-mcdb-o2e

// 根用户
'USER': root
'PASSWORD': se-mcdb-o2e

建议使用普通用户登录
开放端口：8000-20000
```

</details>

## 资料

### 组员整理：

- [项目文档初稿归档](./Archive)

- [知兔接口整理(lzz, lpx)](./Archive/知兔接口详细整理.md)
- [项目相关文件](https://github.com/SE-mcdb/SE2022_source/tree/main/%E9%A1%B9%E7%9B%AE%E7%9B%B8%E5%85%B3)

### 其他参考：

- 参见：[SOURCE](https://github.com/SE-mcdb/SE2022_source)

## License

[MIT](./LICENSE)

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
