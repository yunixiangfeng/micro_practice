当前服务 名称为 Cart 类型 service 

创建初始化模版请使用

```
sudo docker run --rm -v $(pwd): $(pwd) -w  $(pwd) -e ICODE=xxxxxx cap1573/cap-micro new git.imooc.com/coding-447/cart
```

## 快速开始

- [配置信息](#配置信息)
- [使用](#使用)

## 配置信息

- 服务名称: go.micro.service.cart
- 类型: service
- 简称: cart

 

## 使用
根据 proto 自动生成
```
make proto
```

编译
```
make proto
```

构建镜像
```
make docker
```