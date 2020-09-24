# TODO

## 不支持 （持续更新）
目前对标准JSON Schema不支持的部分包含可能不限于如下：
1. object additionalProperties 属性只支持配置false
1. object Dependencies 属性依赖和schema依赖都不支持
1. if else 新特性不支持
1. $ref 不支持跨文件调用

## Todo
- [x] anyOf 嵌套数组调整顺序的时候数据渲染异常问题修复
- [x] lib如果直接umd包导入，默认注册vue组件 类elementUi
- [x] 配置化所有调用外部组件的地方，方便后续扩展支持不同的ui库
- [x] enumNames 支持 ui-schema 配置
- [x] 对表单所有渲染节点打上唯一class类名，方便重置样式
- [x] 整理文档，逐步梳理 基本使用方法和个性化配置field、组件、错误信息处理、options配置等
- [x] 添加 ui:fieldProps 传递给自定义field的参数
- [x] 添加 d.ts 文件
- [x] ui:widget 支持在array级别传入
- [x] custom-rule 参数 支持
- [x] 逐步开源发布
- [x] 优化源码 不需要this的组件调整为 functional

- [ ] 数组 title 和 description支持配置 $index 通配符 渲染时替换为 1 2 3
- [ ] 数组渲染样式微调优化（控制条下间距，）
- [ ] 添加代码测试
- [ ] Ui配置，支持函数表达式配置，hidden title description placeholder等
- [ ] 对照react schema from适配更多规则支持
- [ ] 解耦elementUi 重新开发form 和formItem组件，通过配置化实现适配elementUi iView 等常用ui组件
