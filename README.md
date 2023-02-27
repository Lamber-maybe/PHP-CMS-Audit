## PHP框架代码审计记录
分析一些老古董框架，提升基础的代码审计能力

## 预期架构
* README.md
* CMS_name_dir
  * CMS_version_dir
    * README.md (框架的整体阐述，框架的重要功能点代码)
    * CVE_number
      * README.md（漏洞复现部分，以及代码分析部分）
      * docker-compose.yml（漏洞的docker环境）

## TODO
- [ ] 74CMS
- [ ] ThinkPHP
- [ ] Laravel
- [ ] Symfony
- [ ] Yii

## Doing
- [ ] MetInfo
  - [ ] MetInfo6.0.0
  - [ ] MetInfo7.0.0
  - [ ] MetInfo7.0.0beta
    
## Done
- [ ] MetInfo7.0.0beta
  - [x] CVE-2020-21131
  - [x] CVE-2019-17553

## 漏洞成因统计
### SQL注入
<details>
<summary>SQL语句select中条件变量无单引号保护（1次）</summary>

* CVE-2020-21131

</details>

<details>
<summary>框架自身的过滤函数与语言自身的过滤函数相互冲突（1次）</summary>

* CVE-2019-17553

</details>
