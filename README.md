# custom-antd
#一、 what
单独 fork ant-design-2.7.0中的select组件

# custom-antd，来自ant-design 官网
# 因 无法fork ant-design 2.7.0版本，故上传从 https://github.com/ant-design/ant-design/releases?after=2.7.1 下载 2.7.0 版本，各位看友周知；
# 另外，可以参看 https://github.com/ant-design/ant-design/tree/2.7.0

# MySelect 既是对原生 /ant-design-2.7.0/components/select/index.tsx 的单独包装；

custom-antd.d.ts
# export { default as Select } from '../components/select';


#二、 how
# 打包 走 tsc，不走webpack；
# 在package.json 中更改对应的 版本号，然后 在工程根目录下 执行 npm tsc，最后再执行 npm publish 发布到 npmjs上；