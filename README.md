# CICD-Study

![CI](https://github.com/Hitotsubashi/cicd-study/actions/workflows/ci.yml/badge.svg) ![CD](https://github.com/Hitotsubashi/cicd-study/actions/workflows/cd.yml/badge.svg) ![E2E Test](https://github.com/Hitotsubashi/cicd-study/actions/workflows/e2e-test.yml/badge.svg)

该项目用于给前端 er 们由浅入深地展示如何给一个项目添加`CICD`操作。说明文档请看：



## 每次提 pr 时要确保 package.json 中的 version 值有变化，不然 CD Workflow 会在 Create GitHub Release 的步骤里报已存在 Tag 的错误。
