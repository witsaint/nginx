# nginx
nginx 的基础配置 https\负载均衡 等后期研究

当前是为了利用node作为中间层、nginx指向vue-cil打包好的dist中的index.html

然后将项目中配置的请求代理放在nginx中，这是1 V 1 的前端对接后端可以这么使用

但是假设前端服务器是很多项目并用的情况，需要用到pm2部署express，来达到从构建到部署的过程
