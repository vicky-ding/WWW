# React #
## 简介 ##
React是2014年由Facebook推出，是一个用于**构建UI的Javascript库**  
React的理念：**UI=render(data)**   
React的首要思想是通过**组件**（Component）来开发应用  
React被认为是MVC中的V  
[React官网](https://reactjs.org/ "React官网")
## React的出现 ##
**老式的多页网络应用：**本质为一堆简单页面的机械组合，开始的主页面，点击链接，浏览器再把其他页面加载。缺点：用户体验差，加载新页面时，浏览器需要跟服务器交互  
**单页面应用（SPA）：**浏览不同页面时，不需要不停地向服务器请求然后加载新的页面，而是把不同的页面视图展示在一个单一的页面中。
**单页面应用面临的挑战：**如何保持与数据同步变换，如何高效的操作DOM模型，HTML过于复杂。  
**React应势而生**：React解决上述问题，降低数据和界面整合的难度


## React核心概念 ##
- **虚拟DOM（Virtural DOM）**  
 React将DOM抽象为虚拟DON，即用一个对象来描述DOM，通过对比前后两个对象之间的差异，把变化的部分重新渲染，提高渲染的效率  
  1.用Javascript对象结构表示DOM树的结构，然后用这个树构建一个真正的DOM树插入到文档中；  
  2.当状态变更的时候，重新构造一颗新的对象树。然后新旧两棵树进行比较，记录差异；  
  3.把2所记录的差异应用到步骤1构建的真正的DOM树上，视图更新。
- **Diff算法**  
[diff算法文档](https://reactjs.org/docs/reconciliation.html "diff算法文档")
  

## React生命周期 ##

