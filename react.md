### react node

* 快速构建 React 开发环境
```npm
cnpm install -g create-react-app   
create-react-app my-app  // 
cd my-app/
npm start 
```
* yarn 
> 可以使用yarn 管理依赖库
` brew install yarn `
> 如果出现下面的错误
```
error upath@1.0.4: The engine "node" is incompatible with this module. Expected version ">=4 <=9".
```
可以使用下面的命令
` yarn install --ignore-engines `
 
jsx 表达式需要写在`{}` 内;

不能使用返回 `false` 的方式阻止默认行为 ,必须明确的使用 `preventDefault`

传递给子组件的对象 `props` 为只读对象

