##安全

##主要内容
- 认证
    - peer authentication | transport authencitcation|service to service authenticatoin
        认证的是客户端、服务端
    - origin authentication|end user authentication
        认证的是运行用户
- 加密
- 访问控制

##具体干什么
- 两种认证方式，服务端客户端做的是不是一样的？
- peer auth
    - 客户端
      检查服务端的服务身份、用户身份是否合法，是否允许运行该服务端
    - 服务端
      根据客户端的服务身份、用户身份进行访问控制
- origin auth
    - 

###概念
- identity
    身份，分为服务身份，k8s里即为service account。用户身份
- secure naming
    表示方式为K:V，含义为，K被授权运行服务V。这个信息保存在哪里？证书里。问题是我怎么知道对方是不是K？
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