前端面试知识点汇总：
1、属性特性分两种：数据属性与访问器属性
   数据属性：[[Configurable]] [[Enumerable]] [[Writable]] [[Value]]
   注：一旦[[Configurable]]修改为不可配置的（false）就再不能将其变回可配置了
   调用Object.defineProperty()方法修改特性时，如果不指定，一般[[Configurable]] [[Enumerable]] [[Writable]]特性的默认值为false
   
   访问器属性：[[Configurable]] [[Enumerable]] [[Get]] [[Set]]
   
   修改
