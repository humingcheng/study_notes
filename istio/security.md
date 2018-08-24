##安全

##主要内容
- 身份检查（peer, origin）
- 加密
- 访问控制

##具体干什么
- 客户端
  检查服务端身份是否合法，服务端运行用户的身份是否合法。
- 服务端
  根据客户端身份进行访问控制

###概念
- identity
    身份，分为服务身份，k8s里即为service account。用户身份
- secure naming
- first-class service identity
- SPIFFIE
- PKI
- SVID
- SPIRE
- authencitation
    认证
- authorization
    授权
- auditing
    审计
- CSR