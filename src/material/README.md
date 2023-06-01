# 关于该目录
该目录为物料开发时存放物料的目录，做项目开发请删除该目录以及该目录下的物料

# 关于物料开发
物料分为组件、区块、页面三个类型 
命名规则： 
  * 页面以P-开始
  * 组件C-开始
  * 区块以B-开始

# npm包发布
``` shell
npm version patch // 如果是更新
npm publish --registry http://fmsnexus.paydev.com:8081/repository/npm-local/
```
# 直接发布到脚手架使用
直接提交到内网gitlab，后续可通过fms-cli添加