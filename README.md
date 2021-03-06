# xind-components

参考`element-ui`进行组件的封装

## 组件内容

- 基本
  - [x] 按钮`xButton`
  - [x] 图标`xicon x-`
  - [ ] 色彩
  - [ ] 样式
- 导航
  - [x] 标签选择器`xTags`/`xSelectTags`
  - [x] 回到顶部组件`backTop`（目前基于`element-ui`）
  - [ ] 底部工具栏
  - [ ] 导航菜单
  - [ ] 标签页
- 表单
  - [ ] 输入框
  - [ ] 单选框
  - [ ] 多选框
  - [ ] 开关
  - [ ] 计数器
  - [ ] 表格
  - [ ] 选择器
  - [ ] 滑块
  - [ ] 日期/时间选择器
- 图表
  - [x] 趋势组件
  - [x] 进度条组件
  - [x] 图片预览
  - [x] 通知图标
- 功能
  - [x] 锁屏
  - [ ] dialog
  - [x] 403
  - [x] 404
  - [x] 500
- 复合组件
  - [x] 登录`xLogin`/`xPhoneLogin`
  - [ ] 行内可编辑表格
  - [ ] 单元格可编辑表格

## 关键点

1. Vue的$set属性
   在标签选择器组件的制作中，由于从父组件只接收标签列表的数组，没有包含选择时的判断属性，利用$set可以直接给原数组的对象添加自定义属性；
2. 控制元素节点位置
   利用ref绑定元素，并使用$refs来操作dom元素，利用append方法来控制节点的位置；
3. 。。。
