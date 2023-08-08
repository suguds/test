# mikecabana/express-ts-starter安全风险及SBOM


## 基础信息

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1688458881864192000.svg)](https://www.murphysec.com/console/report/1688458881469927425/1688458881864192000)

仓库描述：A super simple Express starter project using Typescript. Includes VSCode debug config and Dockerfile. ✨

仓库地址：[https://github.com/mikecabana/express-ts-starter](https://github.com/mikecabana/express-ts-starter)

| 星星：2                  | 关注：0              | 叉分：0             |
| ------------------------ | -------------------- | ------------------- |
| 所有者：用户             | 更新时间：2023-02-20 | 许可证：MIT License |
| 最近检测时间：2023-08-07 | 组件总数：242        | 漏洞总数：2         |



## 漏洞列表

| 漏洞名称             | 漏洞类型 | MPS编号                                                    | CVE编号        | 影响组件  |
| -------------------- | -------- | ---------------------------------------------------------- | -------------- | --------- |
| word-wrap 安全漏洞   | ReDoS    | [MPS-2023-5109](https://www.oscs1024.com/hd/MPS-2023-5109) | CVE-2023-26115 | word-wrap |
| node-semver 安全漏洞 | ReDoS    | [MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166) | CVE-2022-25883 | semver    |



## 缺陷组件

| 组件名称  | 版本  | 最小修复版本 | 依赖关系 | 修复建议 | 漏洞级别           |
| --------- | ----- | ------------ | -------- | -------- | ------------------ |
| word-wrap | 1.2.3 | 1.2.4        | 间接依赖 | 建议修复 | C:0\|H:1\|M:0\|L:0 |
| semver    | 7.3.7 | 7.5.2        | 间接依赖 | 可选修复 | C:0\|H:1\|M:0\|L:0 |



## 许可证风险

| 许可证类型 | 相关组件 | 许可证冲突 |
| ---------- | -------- | ---------- |
| ISC        | 22       | 无         |
| MIT        | 190      | 无         |
| Python-2.0 | 1        | 无         |



## SBOM清单

| 组件名称                             | 组件版本 | 是否直接依赖 | 仓库 |
| ------------------------------------ | -------- | ------------ | ---- |
| range-parser                         | 1.2.1    | 否           | npm  |
| binary-extensions                    | 2.2.0    | 否           | npm  |
| @jridgewell/sourcemap-codec          | 1.4.14   | 否           | npm  |
| once                                 | 1.4.0    | 否           | npm  |
| queue-microtask                      | 1.2.3    | 否           | npm  |
| punycode                             | 2.1.1    | 否           | npm  |
| nopt                                 | 1.0.10   | 否           | npm  |
| file-entry-cache                     | 6.0.1    | 否           | npm  |
| to-regex-range                       | 5.0.1    | 否           | npm  |
| mime-types                           | 2.1.35   | 否           | npm  |
| glob-parent                          | 5.1.2    | 否           | npm  |
| strip-bom                            | 3.0.0    | 否           | npm  |
| basic-auth                           | 2.0.1    | 否           | npm  |
| inflight                             | 1.0.6    | 否           | npm  |
| @typescript-eslint/type-utils        | 5.45.0   | 否           | npm  |
| proxy-addr                           | 2.0.7    | 否           | npm  |
| @types/color-name                    | 1.1.1    | 是           | npm  |
| fill-range                           | 7.0.1    | 否           | npm  |
| ipaddr.js                            | 1.9.1    | 否           | npm  |
| argparse                             | 2.0.1    | 否           | npm  |
| find-up                              | 5.0.0    | 否           | npm  |
| vary                                 | 1.1.2    | 否           | npm  |
| eslint                               | 8.28.0   | 是           | npm  |
| fs.realpath                          | 1.0.0    | 否           | npm  |
| @typescript-eslint/typescript-estree | 5.45.0   | 否           | npm  |
| statuses                             | 2.0.1    | 否           | npm  |
| destroy                              | 1.2.0    | 否           | npm  |
| @typescript-eslint/visitor-keys      | 5.45.0   | 否           | npm  |
| @jridgewell/trace-mapping            | 0.3.9    | 否           | npm  |
| type-is                              | 1.6.18   | 否           | npm  |
| flat-cache                           | 3.0.4    | 否           | npm  |
| uri-js                               | 4.4.1    | 否           | npm  |
| levn                                 | 0.4.1    | 否           | npm  |
| @nodelib/fs.scandir                  | 2.1.5    | 否           | npm  |
| debug                                | 2.6.9    | 否           | npm  |
| has-symbols                          | 1.0.3    | 否           | npm  |
| path-type                            | 4.0.0    | 否           | npm  |
| fast-levenshtein                     | 2.0.6    | 否           | npm  |
| has                                  | 1.0.3    | 否           | npm  |
| path-is-absolute                     | 1.0.1    | 否           | npm  |
| supports-color                       | 5.5.0    | 否           | npm  |
| diff                                 | 4.0.2    | 否           | npm  |
| js-yaml                              | 4.1.0    | 否           | npm  |
| tree-kill                            | 1.2.2    | 否           | npm  |
| fastq                                | 1.13.0   | 否           | npm  |
| globby                               | 11.1.0   | 否           | npm  |
| @humanwhocodes/module-importer       | 1.0.1    | 否           | npm  |
| natural-compare                      | 1.4.0    | 否           | npm  |
| xtend                                | 4.0.2    | 否           | npm  |
| safer-buffer                         | 2.1.2    | 否           | npm  |
| safe-buffer                          | 5.1.2    | 否           | npm  |
