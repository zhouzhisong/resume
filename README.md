# biographicalnotes

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve  nodejs版本问题，直接启动会报错 需添加以下代码：
```

"serve": "set NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve",

### 项目分析：

简历一般包括 头部，基础信息，教育经历，项目经历，工作经历，技能，自我评价 等等。。
将这些部分看成一个个的小模块进行组装，形成一份完整的简历

遇到的问题：
1.sass 通过 变量 设置颜色 并转存（color: var(--font-color)；）

vscode 好用的插件 :
Color Manager 颜色插件
gitLens

个人信息: XXX / XX 岁 / 北京 /

联系方式: XXXXX

个人主页: XXXX

教育经历: 2013-2017 XXX 大学（本科）XXX 系 ​

工作经历
2020-2022 XXX 科技公司，前端专家-xxx 负责人

2017-2019 XXX 科技公司，高级前端工程师

20215-2017 XXX 科技公司，前端工程师

个人优势
精通 XX（❌ 最好别写，容易激起面试官的逆反心理，除非你真的很精通，不怕问）
了解 XX（❌ 最好别写两条以上）
熟练掌握 Javascript（🔥 基础扎实）
熟练掌握 Vue/React，并研究过其内部实现（🔥 基础扎实）
熟练掌握工程化，主导并实现了团队的 XX 系统（🔥 基础扎实）
熟悉常见算法和设计模式，有较好的计算机素养
喜欢分享，并推动团队内部技术分享；⼯作认真负责注重效率
（❗ 切记不写自己不会不擅长的，面试的时候会让面试官觉得你很虚浮）
开源教程&⼯具
掘金 V6：XXX
项目经历
2021 年-2022 年 XX 项目

项目描述： ⼤型 XXX 平台，使⽤ react 全家桶 iframe、react-single-spa ,vite，rollup。
工作内容： 从零搭建项⽬到微前端改造，经历了整个项⽬的⽣命周期。负责技术选型，难点攻克。
难点⼀ ：业务系统过多需要制定接⼊规范并对业务系统问题分类、整理并进⾏能⼒输出；
难点⼆ ：项⽬经过多次微前端选型改造，需要针对不同选型做⼯程化定制⽅案；
难点三 ：antd 组件的性能问题，对⼤批量的组件渲染速度慢，包括下拉框，input 框，table 组件等等，1000 左右 dom 渲染速度达到 3-4 秒，⽤户体验很差。
成果展示： 重写了⼀系列的 antd 的组件，做到了渲染速度秒级渲染。以及开发了⼏⼗个公共和业务组件，提升了团队的开发效率，统⼀项⽬标准化。项⽬⾸⻚加载速度做到了秒级。注重团队成员培养，提升团队成员的技术能⼒，以及⼯作负责任的态度，直接带来了效率和质量的提升。
备注：P6+描述
XX 年-XX 年 XX 项目

带领三个小伙伴负责开发公司的 XX 系统，为了提高 XX，解决了 XX，最终 XX 效果提高了 30% （🔥 有理有据有数据，令人信服）
推动 XX 技术落地 XX 项目，引入 XX 后，XX 提高了 XX%
带领五人团队主导研发了 XX ，实现了 XX 功能，开源并且获得了 XX（独当一面的描述，就是 P6 级别的描述）
实现公司营销搭建系统，实现 XX 个组件，支持 XX 功能和 XX 功能，能够 XXX
备注：P6 描述
XX 年-XX 年 XX 项目

开发了 XX 项目 （❌ 流水账没意义）
参与 XX 项目开发，使用 Vue 其中 XX 模块和 XX 个页面代码 （实现 XX 功能，多少个功能都是）
参与 YY 项目开发，使用 React 开发其中 XX 模块和 XX 个页面代码 （同上)
备注：P5 描述
最后
（❌ 不要说自己非常能吃苦，和非常能吃对面试官来说区别不大）

（❌ 不要说自己抗压，善于团队合作，你去问问哪个来面试的不说自己能抗压）

（🔥）面试就像相亲，简历上要写亮点，不要写小学二年级拿过三好学生，要写亮点

（🔥）亮点不要胡说，没有亮点日常工作中就注意修炼亮点

（🔥）项目不要流水账，要介绍什么情景（Situation），你接到什么任务任务（Task），有了什么行动 （Action），拿到了什么结果（Result），也就是 STAR 原则

​
