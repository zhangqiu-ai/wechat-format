# 使用nginx官方镜像作为基础镜像
FROM nginx:alpine

# 将项目文件复制到nginx的html目录下
COPY ./ /usr/share/nginx/html/

# 声明容器运行时监听的端口号
EXPOSE 80

# 当容器启动时运行nginx
CMD ["nginx", "-g", "daemon off;"]
